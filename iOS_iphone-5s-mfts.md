#### Test 1459176191a53731_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1459176191a53731/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/4C4A45A9-3222-4110-A1E9-EB1E7D9C1A35/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/4C4A45A9-3222-4110-A1E9-EB1E7D9C1A35/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1459176191a53731/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1459176191a53731/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52450"
,(lldb)     command script import "/tmp/4C4A45A9-3222-4110-A1E9-EB1E7D9C1A35/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,JXcore engine is started
,2017-10-12 14:07:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:07:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:07:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:07:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:07:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:07:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:07:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "772BFDA7-D121-4C22-BB1F-020CAA38F444", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:772BFDA7-D121-4C22-BB1F-020CAA38F444
Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisement,s
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AD5A8D31-A3C5-4ADF-B87D-F46D8D5C4701
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] ,BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:27787109-E6D8-4358-97AD-826683862703
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5BE38927-DAD6-4A09-BF39-36ADCD9C2271", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5BE38927-DAD6-4A09-BF39-36ADCD9C2271
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BE38927-DAD6-4A09-BF39-36ADCD9C2271:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BE38927-DAD6-4A09-BF39-36ADCD9C2271", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-10-12 14:07:33 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.516897141933441
,2017-10-12 14:07:33 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-10-12 14:07:33 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5BE38927-DAD6-4A09-BF39-36ADCD9C2271:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5BE38927-DAD6-4A09-BF39-36ADCD9C2271", generation: 0)
,2017-10-12 14:07:36 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-10-12 14:07:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-10-12 14:07:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-10-12 14:07:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-10-12 14:07:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-10-12 14:07:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-10-12 14:07:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-10-12 14:07:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-10-12 14:07:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-10-12 14:07:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-10-12 14:07:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-10-12 14:07:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-10-12 14:07:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-10-12 14:07:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-10-12 14:07:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-10-12 14:07:40 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-10-12 14:07:41 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-10-12 14:07:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:08:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:08:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:08:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:08:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:08:25 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-10-12 14:08:25 - DEBUG CoordinatedClient: 'connected to the test server'
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
,ok 3 Got the right error
# teardown
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
ok 5 should be equal
,ok 6 should be equal
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
,2017-10-12 14:08:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-10-12 14:08:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-10-12 14:08:54 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-10-12 14:08:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:08:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0E49FB6F-B4F1-4C1B-8842-3B0C26FAC000
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
2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0235C4D0-099B-4557-9685-6221F0F1205A
,[ThaliCore] Browser.startListening
,2017-10-12 14:09:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:09:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:09:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-10-12 14:09:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:09:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:09:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6FBB03E9-D173-417E-B970-F46475F56A33", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6FBB03E9-D173-417E-B970-F46475F56A33
2017-10-12 1,4:09:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6FBB03E9-D173-417E-B970-F46475F56A33
,2017-10-12 14:09:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0BC8026F-5DCF-4922-9A8A-A372F7BCA555", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0BC8026F-5DCF-4922-9A8A-A372F7BCA555
2017-10-12 1,4:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0BC8026F-5DCF-4922-9A8A-A372F7BCA555", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:0BC8026F-5DCF-4922-9A8A-A372F7BCA555
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:09:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0BC8026F-5DCF-4922-9A8A-A372F7BCA555
[ThaliCore] Advertiser.stopAdvertising() peerID:0BC8026F-5DCF-4922-9A8A-A372F7BCA555,
2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e,).'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
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
2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7CE7BB6E-C82C-4C8F-B9DB-C90F6B8C394F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7CE7BB6E-C82C-4C8F-B9DB-C90F6B8C394F
2017-10-12 1,4:09:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:628D1FF1-F36B-4DE1-ABF1-9EF51700AC53
[Thali,C,ore] Browser.startListening
,2017-10-12 14:09:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:09:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-10-12 14:09:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3806CC5D-8F7F-45C0-B357-1E5F3C9E873D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3806CC5D-8F7F-45C0-B357-1E5F3C9E873D", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A4FF9A1-67A7-4775-8320-CFA8061C113C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A4FF9A1-67A7-4775-8320-CFA8061C113C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CE7BB6E-C82C-4C8F-B9DB-C90F6B8C394F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CE7BB6E-C82C-4C8F-B9DB-C90F6B8C394F", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:09:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:09:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7CE7BB6E-C82C-,4C8F-B9DB-C90F6B8C394F
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdat,e (was in stopped state).'
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to nati,v,e'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:AF5469F9-24AD-4DE5-8938-C5288B08F245
2017-10-12 1,4:09:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:70A7F325-6D8D-4559-BC64-A9F5A71AB0FA
[ThaliCore] Browser.startListe,ning
2017-10-12 14:09:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:09:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:09:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
2017-10-12 14:09:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1E35A50E-3E8B-4739-963D-88DB705300A6","generation":0}'
2017-10-12 14:09:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1E35A50E-3E8B-4739-963D-88DB705300A6, (syncValue: 1O2zeI6ojj6JBnog4TJTFN0guK1hpVRz)'
,2017-10-12 14:09:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:44955EBC-6F63-44A4-8959-38ED685B534C
[ThaliCore] Advertiser: session connected Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:44955EBC-6F63-44A4-8959-38ED685B534C state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
2017-10-12 14:09:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7A795224-AA94-44DF-BB33-0C1B76A830D2","generation":0}'
2017-10-12 14:09:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:09:25 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57017
,2017-10-12 14:09:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1O2zeI6ojj6JBnog4TJTFN0guK1hpVRz","error":null,"portNumber":57017}'
,2017-10-12 14:09:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1O2zeI6ojj6JBnog4TJTFN0guK1hpVRz', error: 'null', listeningPort: '57017''
,2017-10-12 14:09:27 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:44955EBC-6F63-44A4-8959-38ED685B534C
,[ThaliCore] Session.session(_:peer:didChange:) peer:44955EBC-6F63-44A4-8959-38ED685B534C state: connecting -> connected
,2017-10-12 14:09:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:AF5469F9-24AD-4DE5-8938-C5288B08F245
2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14,:,09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1E35A50E-3E8B-4739-963D-88DB705300A6
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57017
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1O2zeI6ojj6JBnog4TJTFN0guK1hpVRz","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:44955EBC-6F63-44A4-8959-38ED685B534C state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:44955EBC-6F63-44A4-8959-38ED685B534C
[ThaliCore] AdvertiserRelay.deinit
,# Can shift data
,[ThaliCore] Session.deinit peer:44955EBC-6F63-44A4-8959-38ED685B534C
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:780BD97C-6130-4480-B34B-311832BCA220
2017-10-12 1,4:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3347533E-2456-4380-92DD-7C9D11C4A7E5
,[ThaliCore] Browser.startListening
2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:09:32 - INFO thaliMobile: 'Received state ({"discoveryActive,":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:32 - INFO thaliMobile: 'F,iltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
2017-10-12 14:09:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7A795224-AA94-44DF-BB33-0C1B76A830D2","generation":0}'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7A795224-AA94-44DF-BB33-0C1B76A830D2, (syncValue: UjuF66w2xmTzeILnje1DwQ3VcEEcs4jJ)'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A,830D2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"1E35A50E-3E8B-4739-963D-88DB705300A6","generation":0}'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
,2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4","generation":0}'
,2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:27902114-8768-484E-9050-1BAE80B6CED9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "27902114-8768-484E-9050-1BAE80B6CED9", generation: 0)
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"27902114-8768-484E-9050-1BAE80B6CED9","generation":0}'
2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7A,795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7A,795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F64D23A4-BF51-4897-BCF6-DAEC3A2B3C1F
[ThaliCore] Advertiser: session connected Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F64D23A4-BF51-4897-BCF6-DAEC3A2B3C1F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7A,795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7A795224-AA94-44DF-BB33-0C1B76A830D2 error: max retries exceeded
2017-10-12 14:09:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UjuF66w2xmTzeILnje1DwQ3VcEEcs4jJ","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UjuF66w2xmTzeILnje1DwQ3VcEEcs4jJ', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:09:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4 (syncValue: 8jobm71,R1fm8FboyBrDHqfiqQVJXwPF1)'
2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "92,6E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CDC4C3D7-011E-4441-AA4D-651A44459395
[ThaliCore] Advertiser: session connected Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CDC4C3D7-011E-4441-AA4D-651A44459395 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F64D23A4-BF51-4897-BCF6-DAEC3A2B3C1F
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CDC4C3D7-011E-4441-AA4D-651A44459395
,[ThaliCore] Session.session(_:peer:didChange:) peer:CDC4C3D7-011E-4441-AA4D-651A44459395 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CDC4C3D7-011E-4441-AA4D-651A44459395
[ThaliCore] Session.startOutputStream(with:) peer:CDC4C3D7-011E-4441-AA4D-651A44459395
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:1
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:1
,[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57025
,2017-10-12 14:09:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8jobm71R1fm8FboyBrDHqfiqQVJXwPF1","error":null,"portNumber":57025}'
,2017-10-12 14:09:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8jobm71R1fm8FboyBrDHqfiqQVJXwPF1', error: 'null', listeningPort: '57025''
,Connecting to the localhost:57025
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
Connected to the localhost:57025
2017-10-12 14:09:47 - DE,BUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:2
[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:2
,ok 88 got the same data back
,# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] T,CPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
,[ThaliCore] Session.session(_:peer:didChange:) peer:F64D23A4-BF51-4897-BCF6-DAEC3A2B3C1F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F64D23A4-BF51-4897-BCF6-DAEC3A2B3C1F
,[ThaliCore] Session.startOutputStream(with:) peer:F64D23A4-BF51-4897-BCF6-DAEC3A2B3C1F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:3
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:3
[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:3
2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:3
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-12 14:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 ,14:09:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
,2017-10-12 14:09:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:780BD97C-6130-4480-B34B-311832BCA220
2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57025
[ThaliCore] Session.disconnect() p,eer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F64D23A4-BF51-4897-BCF6-DAEC3A2B3C1F state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:CDC4C3D7-011E-4441-AA4D-651A44459395
,[ThaliCore] Session.deinit peer:CDC4C3D7-011E-4441-AA4D-651A44459395
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
,[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4D5CF258-9502-47E8-8BC3-9388881E8557
2017-10-12 1,4:09:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:885202F4-6DBB-483D-B99D-63BD61F1ECE1
[ThaliCore] Browser.startListening
2017-10-12 14:09:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-10-12 14:09:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
2017-10-12 14:09:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4","generation":0}'
2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4, (syncValue: ftIyAm7XHkhdFWNmzqhSnqatDLrlwUWe)'
2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96,DA5C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:27902114-8768-484E-9050-1BAE80B6CED9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "27902114-8768-484E-9050-1BAE80B6CED9", generation: 0)
2017-10-12 14:09:49, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"27902114-8768-484E-9050-1BAE80B6CED9","generation":0}'
2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:09:49 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
,2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5425ADD4-4917-4D69-B6C4-BE1BB3866CFD","generation":0}'
2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
,2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BBF9DB54-27C0-4C93-909E-CE62E7FD08F3","generation":0}'
2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-,12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:92,6E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,26E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "926E3705-DB20-4BD,E-A6DB-E3E0E96DA5C4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "92,6E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:92,6E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,26E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:92,6E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:926E3705,-DB20-4BDE-A6DB-E3E0E96DA5C4 error: max retries exceeded
2017-10-12 14:10:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ftIyAm7XHkhdFWNmzqhSnqatDLrlwUWe","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ftIyAm7XHkhdFWNmzqhSnqatDLrlwUWe', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:10:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 27902114-8768-484E-9050-1BAE80B6CED9 (syncValue: MDWEigT,j9mDtAdeoDsEmJfBlwYXGOO5N)'
2017-10-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "27902114-8768-484E-9050-1BAE80B6CED9", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "27902114-8768-484E-9050-1BAE80B6CED9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:27902114-8768,-484E-9050-1BAE80B6CED9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:27902114-8768-484E-9050-1BAE80B6CED9:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "27902114-8768-484E-9050-1BAE80B6CED9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:27902114-8768-484E-9050-1BAE80B6CED9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:27,902114-8768-484E-9050-1BAE80B6CED9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "27902114-8768-484E-9050-1BAE80B6CED9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,7902114-8768-484E-9050-1BAE80B6CED9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "27902114-8768-484E-9050-1BAE80B6CED9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:10:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MDWEigTj9mDtAdeoDsEmJfBlwYXGOO5N","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:10:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MDWEigTj9mDtAdeoDsEmJfBlwYXGOO5N', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:10:03 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:10:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5425ADD4-4917-4D69-B6C4-BE1BB3866CFD (syncValue: dQtit37PzGQCi0zYTJzFRGX,8pkFMaFKm)'
2017-10-12 14:10:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5425ADD4-4917-4D69-B6C4-BE1BB,3866CFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:10:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:27902114-8768-484E-9050-1BAE80B6CED9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57044
2017-10-12 14:10:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dQtit37PzGQCi0zYTJzFRGX8pkFMaFKm",,"error":null,"portNumber":57044}'
2017-10-12 14:10:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dQtit37PzGQCi0zYTJzFRGX8pkFMaFKm', error: 'null', listeningPort: '57044''
,Connecting to the localhost:57044
Connecting to the localhost:57044
,Connecting to the localhost:57044
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
Connected to the localhost:57044
[ThaliCore] Session.startOutputStream(with:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] TCPListener.,socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.cr,eateVirtualSocket(with:)
Connected to the localhost:57044
[ThaliCore] Session.startOutputStream(with:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
,Connected to the localhost:57044
,ok 91 correct string length
,2017-10-12 14:10:07 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-10-12 14:10:07 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-10-12 14:10:07 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-10-12 14:10:07 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-10-12 14:10:07 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-10-12 14:10:07 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:4
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:4
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:5
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:5
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:6
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:6
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 3244 vsID:4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 94 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams,() vsID:4
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6]
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:5
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 95 got the same data b,ack
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:5 [6]
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 96 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:6 []
,# teardown
,2017-10-12 14:10:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 ,14:10:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4D5CF258-9502-47E8-8BC3-9,388881E8557
2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57044
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
,[ThaliCore] Session.deinit peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:67A7E480-106F-41FD-ADAD-2706A37CB77E
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:10:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2566884B-FC74-48AA-8975-4EAD52289E05
[ThaliCore] Browser.startListening
2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
2017-10-12 14:10:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5425ADD4-4917-4D69-B6C4-BE1BB3866CFD","generation":0}'
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5425ADD4-4917-4D69-B6C4-BE1BB3866CFD, (syncValue: OsVakfdymNTZemrXXEISLTk0QjoslO5d)'
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB38,66CFD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
2017-10-12 14:10:10, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BBF9DB54-27C0-4C93-909E-CE62E7FD08F3","generation":0}'
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE","generation":0}'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3","generation":0}'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,25ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,25ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,25ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,25ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5425ADD4,-4917-4D69-B6C4-BE1BB3866CFD error: max retries exceeded
2017-10-12 14:10:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OsVakfdymNTZemrXXEISLTk0QjoslO5d","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OsVakfdymNTZemrXXEISLTk0QjoslO5d', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:10:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BBF9DB54-27C0-4C93-909E-CE62E7FD08F3 (syncValue: Rf0Enif,jW2ExiKR81Ia6X2AVR6VQcQ5Q)'
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BBF9DB54-27C0,-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B26A740F-A322-41AA-AC9A-48619D26B2DE
[ThaliCore] Advertiser: session connected Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B26A740F-A322-41AA-AC9A-48619D26B2DE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,F9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,BF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B26A740F-A322-41AA-AC9A-48619D26B2DE
,[ThaliCore] Session.session(_:peer:didChange:) peer:B26A740F-A322-41AA-AC9A-48619D26B2DE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B26A740F-A322-41AA-AC9A-48619D26B2DE
[ThaliCore] Session.startOutputStream(with:) peer:B26A740F-A322-41AA-AC9A-48619D26B2DE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7, [7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:7
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:75 count:1 vsID:7
[ThaliCore] VirtualSocket.writePendingData() to write:75 written:75 count:0 vsID:7
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 177 vsID:7
,Server received psk id: psk-id
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:7
,[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:7
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 69 vsID:7
,2017-10-12 14:10:24 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-10-12 14:10:24 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-10-12 14:10:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:69 count:1 vsID:7
[ThaliCore] VirtualSocket.writePendingData() to write:69 written:69 count:0 vsID:7
2017-10-12 14:10:24 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:53 count:1 vsID:7
2017-10-12 14:10:24 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
[ThaliCore] VirtualSocket.writePendingData() to write:53 written:53 count:0 vsID:7
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,F9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,BF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,F9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,BF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:10:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Rf0EnifjW2ExiKR81Ia6X2AVR6VQcQ5Q","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:10:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Rf0EnifjW2ExiKR81Ia6X2AVR6VQcQ5Q', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:10:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:10:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE (syncValue: c1jSnXuuapbjnrKTol8kozq,xWqjgAY6c)'
2017-10-12 14:10:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70,814FCCE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:10:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57069
2017-10-12 14:10:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"c1jSnXuuapbjnrKTol8kozqxWqjgAY6c","error":null,"portN,umber":57069}'
,2017-10-12 14:10:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'c1jSnXuuapbjnrKTol8kozqxWqjgAY6c', error: 'null', listeningPort: '57069''
,Connecting to the localhost:57069
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [7, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:8
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:8
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 75 vsID:8
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:177 count:1 vsID:8
,[ThaliCore] VirtualSocket.writePendingData() to write:177 written:177 count:0 vsID:8
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:8
,Connected to the localhost:57069
,2017-10-12 14:10:32 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:69 count:1 vsID:8
,[ThaliCore] VirtualSocket.writePendingData() to write:69 written:69 count:0 vsID:8
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
,2017-10-12 14:10:32 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 69 vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 53 vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:8
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [7]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,ok 99 got the same data back
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# teardown
,2017-10-12 14:10:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:10:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:67A7E480-106F-41FD-ADAD-2706A37CB77E
,[ThaliCore] Session.session(_:peer:didChange:) peer:B26A740F-A322-41AA-AC9A-48619D26B2DE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B26A740F-A322-41AA-AC9A-48619D26B2DE
[ThaliCore] Advert,iserRelay.deinit
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57069
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:B26A740F-A322-41AA-AC9A-48619D26B2DE
,# setup
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"c1jSnXuuapbjnrKTol8kozqxWqjgAY6c","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC
,2017-10-12 14:10:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:10:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:10:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1668740B-0A4B-4BA8-BEC2-08E068BAA78A
,[ThaliCore] Browser.startListening
,2017-10-12 14:10:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:10:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:10:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
2017-10-12 14:10:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3","generation":0}'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3, (syncValue: gHylRtghAAVcUOqS15yDaCKanBSjgEqg)'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E,03CD3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE",, generation: 0)
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE","generation":0}'
,2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
2017-10-12 14:10:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"95033898-78DB-4672-A53C-705177BC68F9","generation":0}'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:34 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F732965-3C77-46D7-A946-F17E3B7CC083:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F732965-3C77-46D7-A946-F17E3B7CC083", generation: 0)
2017-10-12 14:10:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F732965-3C77-46D7-A946-F17E3B7CC083","generation":0}'
2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:35 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:DDC5D80E,-EA98-4BE1-BC6C-FFDB05E03CD3 error: max retries exceeded
2017-10-12 14:10:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gHylRtghAAVcUOqS15yDaCKanBSjgEqg","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gHylRtghAAVcUOqS15yDaCKanBSjgEqg', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:10:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE (syncValue: 0BJrij0,7BGqSZILusDmHC5EkNOvoSEDc)'
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E8D1D4C-9C9E,-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t!'
,2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0E,8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0E,8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0E,8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0E,8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:0E8D1D4C,-9C9E-44E1-8D15-EBE70814FCCE error: max retries exceeded
2017-10-12 14:10:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0BJrij07BGqSZILusDmHC5EkNOvoSEDc","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:10:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0BJrij07BGqSZILusDmHC5EkNOvoSEDc', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:10:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:10:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95033898-78DB-4672-A53C-705177BC68F9 (syncValue: Q5oQj66,OctmKSN057AnaqhxrDCUYpyMC)'
2017-10-12 14:10:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95033898-78DB,-4672-A53C-705177BC68F9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:10:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:95033898-78DB-4672-A53C-705177BC68F9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:95033898-78DB-4672-A53C-705177BC68F9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:95033898-78DB-4672-A53C-705177BC68F9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57093
2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Q5oQj66OctmKSN057AnaqhxrDCUYpyMC",,"error":null,"portNumber":57093}'
2017-10-12 14:10:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Q5oQj66OctmKSN057AnaqhxrDCUYpyMC', error: 'null', listeningPort: '57093''
,Connecting to the localhost:57093
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:95033898-78DB-4672-A53C-705177BC68F9:0
,Connected to the localhost:57093
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [7, 9]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:9
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-10-12 14:10:59 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-10-12 14:10:59 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:65536 count:1 vsID:9
,[ThaliCore] VirtualSocket.writePendingData() to write:65536 written:65536 count:0 vsID:9
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:9
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 102 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [7]
,# teardown
,2017-10-12 14:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:10:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:10:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:10:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:95033898-78DB-4672-A53C-705177BC68F9
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57093
[ThaliCore] Session.disconnect() p,eer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:95033898-78DB-4672-A53C-705177BC68F9:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:10:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Q5oQj66OctmKSN057AnaqhxrDCUYpyMC","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] BrowserRelay.deinit
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:721ED235-F9B7-43A8-BF5D-421DED7D61A6
[ThaliCore] Browser.startListening
2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:10:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:10:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397
2017-10-12 1,4:11:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:11:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:248F322F-C94D-4AF2-82E0-F19CBC6314FE:0
2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0E8D1D4C-9C9E-44E1-8D,15-EBE70814FCCE","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "248F322F-C94D-4AF2-82E0-F19CBC6314FE", generation: 0)
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE","generation":0}'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397:0
[Thali,Core] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397", generation: 0)
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95033898-78DB-4672-A53C-705177BC68F9","generation":0}]'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95033898-78DB-4672-A53C-705177BC68F9","generation":0}'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"248F322F-C94D-4AF2-82E0-F19CBC6314FE","generation":0}]'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"248F322F-C94D-4AF2-82E0-F19CBC6314FE","generation":0}'
,2017-10-12 14:11:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
2017-10-12 14:11:02 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"95033898-78DB-4672-A53C-705177BC68F9","generation":0}]'
2017-10-12 14:11:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"95033898-78DB-4672-A53C-705177BC68F9","generation":0}'
2017-10-12 14:11:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
2017-10-12 14:11:05 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3","generation":0}]'
2017-10-12 14:11:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3","generation":0}'
2017-10-12 14:11:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A03F322A-AAF9-44C3-94C0-5BEFCC62078A
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "48806E87-4B5F-453D-A574-BD091B04051E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:48806E87-4B5F-453D-A574-BD091B04051E
ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:48806E87-4B5F-453D-A574-BD091B04051E
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
,2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
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
2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-10-12 14:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-10-12 14:11:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:c57bc265-458e-495d-8d37-a76122588099 error: startListeningNotActive
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"kL0ztdSjtynNDm6JAkAjkisfhHOFjfEj","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort ,is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:09 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:08C69801-6F69-4E5A-BBB5-F04E5D7B3D62
[ThaliCore] Browser.startListening
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
,ok 132 Got null as expected
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"L4nttqqEQfMDKvyd0s3mCgLjwABlHU2t","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
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
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0FDD870D-DE65-4945-BA25-93A21BC2C20C
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
[ThaliCore] AdvertiserManager.stopAdvertising()
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
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:d0b55c79-a968-4243-a986-6d8d8bfb71a2
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B3666918-5171-4C9E-8643-662288950CC7
2017-10-12 1,4:11:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7982BFFA-C4E0-4084-AC2C-25EBE2BE4891
[Tha,liCore] Browser.startListening
2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:11:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
2017-10-12 14:11:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3","generation":0}'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3 (syncValue: SnfKytE4t2EDKxbKH0ykW1NJH7E7r4xk)'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE","generation":0}'
2017-10-12 14:11:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
2017-10-12 14:11:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7563EA47-7507-4979-92D8-1508550C9D7E","generation":0}'
2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471","generation":0}'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E2756A13-EE78-4729-B144-17173EA110AF
[ThaliCore] Advertiser: session connected Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E2756A13-EE78-4729-B144-17173EA110AF state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9D95AC40-480D-470C-AFB8-670885D43507
[ThaliCore] Advertiser: session connected Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9D95AC40-480D-470C-AFB8-670885D43507 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E2756A13-EE78-4729-B144-17173EA110AF
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2756A13-EE78-4729-B144-17173EA110AF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2756A13-EE78-4729-B144-17173EA110AF
[ThaliCore] Session.startOutputStream(with:) peer:E2756A13-EE78-4729-B144-17173EA110AF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [7, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:10
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9D95AC40-480D-470C-AFB8-670885D43507
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D95AC40-480D-470C-AFB8-670885D43507 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D95AC40-480D-470C-AFB8-670885D43507
[ThaliCore] Session.startOutputStream(with:) peer:9D95AC40-480D-470C-AFB8-670885D43507
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [7, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:11
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:DDC5D80E,-EA98-4BE1-BC6C-FFDB05E03CD3 error: max retries exceeded
2017-10-12 14:11:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SnfKytE4t2EDKxbKH0ykW1NJH7E7r4xk","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:11:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SnfKytE4t2EDKxbKH0ykW1NJH7E7r4xk', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:11:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:11:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7563EA47-7507-4979-92D8-1508550C9D7E (syncValue: OxXl4Nr,rGrCDzIFTZ5ltQfJ28fIUDTHj)'
2017-10-12 14:11:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7563EA47-7507,-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:11:22 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-10-12 14:11:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57111
,2017-10-12 14:11:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OxXl4NrrGrCDzIFTZ5ltQfJ28fIUDTHj","error":null,"portNumber":57111}'
,2017-10-12 14:11:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OxXl4NrrGrCDzIFTZ5ltQfJ28fIUDTHj', error: 'null', listeningPort: '57111''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0) found active relay
,2017-10-12 14:11:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2k5xZ0jusJCzGDUAnieXG9g5KNrM8Rxt","error":null,"portNumber":57111}'
,ok 144 No error
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
ok 145 Ports equal
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [7, 10, 11, 12]
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:12
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0) found active relay
,2017-10-12 14:11:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9AsnPi3VgKtZmgZLO3ZgiyAWuU86yjsL","error":null,"portNumber":57111}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,2017-10-12 14:11:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [7, 11, 12]
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket.deinit vsID:11 [7, 12]
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:11:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:11:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B3666918-5171-4C9E-8643-662288950CC7
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:7563EA47-7507-4979-92D8-1508550C9D7E
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57111
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:12 [7]
,[ThaliCore] Session.disconnect() peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
,[ThaliCore] Session.deinit peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D95AC40-480D-470C-AFB8-670885D43507 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9D95AC40-480D-470C-AFB8-670885D43507
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:9D95AC40-480D-470C-AFB8-670885D43507
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2756A13-EE78-4729-B144-17173EA110AF state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
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
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
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
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:30 - DEBUG createNativeListener: 'listening 57114'
ok 149 Should throw
,# teardown
,2017-10-12 14:11:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:30 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'listening 57116'
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'listening 57119'
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
2017-10-12 14:11:31 - DEBUG createNativeListener: 'listening 57123'
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
2017-10-12 14:11:32 - DEBUG createNativeListener: 'listening 57128'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'listening 57132'
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
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'listening 57136'
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
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'listening 57140'
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
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'listening 57144'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-10-12 14:11:37 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:37 - DEBUG createNativeListener: 'listening 57196'
,2017-10-12 14:11:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-10-12 14:11:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-10-12 14:11:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:37 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-10-12 14:11:37 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-10-12 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'listening 57200'
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
ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'listening 57203'
,ok 196 port must be in range
,# teardown
,2017-10-12 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'listening 57204'
,ok 197 second start should return same port
,# teardown
,2017-10-12 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'listening 57206'
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
,listening on 57208
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DFD51C65-E602-49DB-BA9A-26A7B16A95DB
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4DA2D295-F6F0-4264-8E65-79653B414127
,[ThaliCore] Browser.startListening
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:11:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-10-12 14:11:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
2017-10-12 14:11:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471","generation":0}'
,2017-10-12 14:11:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471 (syncValue: YbTfM3pf6aGE0SXkJV38DkF2fa6oCe4f)'
2017-10-12 14:11:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6F,C9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:11:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3014F9AF-1D13-40A2-81E5-517A999AD0EE","generation":0}'
,2017-10-12 14:11:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
2017-10-12 14:11:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"766863A9-E14B-4B2C-AC66-EEF3271F0561","generation":0}'
2017-10-12 14:11:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:11:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6F,C9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:11:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YbTfM3pf6aGE0SXkJV38DkF2fa6oCe4f","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:11:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YbTfM3pf6aGE0SXkJV38DkF2fa6oCe4f', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:11:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-10-12 14:11:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3014F9AF-1D13-40A2-81E5-517A999AD0EE (syncValue: ZcJU9Clmdns5dgvViOhzV1v23HEkOY1B)'
,2017-10-12 14:11:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:11:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57216
2017-10-12 14:11:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZcJU9Clmdns5dgvViOhzV1v23HEkOY1B",,"error":null,"portNumber":57216}'
2017-10-12 14:11:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZcJU9Clmdns5dgvViOhzV1v23HEkOY1B', error: 'null', listeningPort: '57216''
,ok 210 should be equal
,2017-10-12 14:11:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 766863A9-E14B-4B2C-AC66-EEF3271F0561 (syncValue: AV1qFKrhYRM1QfA48oCQmPlUy1oE22dD)'
,2017-10-12 14:11:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:32744408-508E-49AB-B150-13D7858EDCA4
[ThaliCore] Advertiser: session connected Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:32744408-508E-49AB-B150-13D7858EDCA4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5
[ThaliCore] Advertiser: session connected Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57220
2017-10-12 14:11:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AV1qFKrhYRM1QfA48oCQmPlUy1oE22dD",,"error":null,"portNumber":57220}'
2017-10-12 14:11:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AV1qFKrhYRM1QfA48oCQmPlUy1oE22dD', error: 'null', listeningPort: '57220''
,ok 211 should be equal
# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:32744408-508E-49AB-B150-13D7858EDCA4
,[ThaliCore] Session.session(_:peer:didChange:) peer:32744408-508E-49AB-B150-13D7858EDCA4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5
,[ThaliCore] Session.session(_:peer:didChange:) peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 ,14:11:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-12 14:11:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DFD51C65-E602-49DB-BA9A-2,6A7B16A95DB
2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57216
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:766863A9-E14B-4B2C-AC66-EEF3271F0561
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57220
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:32744408-508E-49AB-B150-13D7858EDCA4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5
,[ThaliCore] Session.session(_:peer:didChange:) peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:11:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZcJU9Clmdns5dgvViOhzV1v23HEkOY1B","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
,[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 57222
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:11:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12, 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F53D4835-021E-4B75-99AB-2901B2A6C2E5
2017-10-12 1,4:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F
[ThaliCore] Browser.startListening
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
2017-10-12 14:11:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"766863A9-E14B-4B2C-AC66-EEF3271F0561","generation":0}'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 766863A9-E14B-4B2C-AC66-EEF3271F0561, (syncValue: e4cTQU7A9j2hMqWDSILiyFVr9RRemMaf)'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271,F0561", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3014F9AF-1D13-40A2-81E5-517A999AD0EE","generation":0}'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
2017-10-12 14:11:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:76,6863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,66863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:76,6863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,66863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22114238-337B-4DEA-B3CE-8BD17D02606B
[ThaliCore] Advertiser: session connected Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:22114238-337B-4DEA-B3CE-8BD17D02606B state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:76,6863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,66863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:76,6863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:766863A9,-E14B-4B2C-AC66-EEF3271F0561 error: max retries exceeded
2017-10-12 14:12:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"e4cTQU7A9j2hMqWDSILiyFVr9RRemMaf","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:12:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'e4cTQU7A9j2hMqWDSILiyFVr9RRemMaf', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:12:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:12:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A40386E-2B01-46CD-87DA-781E0DD5ECDD (syncValue: NzYzYhY,1DQLpRiJmB4I3aqYd8q59GofL)'
2017-10-12 14:12:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A40386E-2B01,-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:12:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:12:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:22114238-337B-4DEA-B3CE-8BD17D02606B
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:22114238-337B-4DEA-B3CE-8BD17D02606B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57240
2017-10-12 14:12:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NzYzYhY1DQLpRiJmB4I3aqYd8q59GofL",,"error":null,"portNumber":57240}'
2017-10-12 14:12:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NzYzYhY1DQLpRiJmB4I3aqYd8q59GofL', error: 'null', listeningPort: '57240''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-10-12 14:12:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 899195D7-975F-4830-8A7A-ABF48513F94C (syncValue: fAYFzavuwzKf3TwSQ9uvg8XDuACyO1hv)'
,2017-10-12 14:12:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:12:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57246
,2017-10-12 14:12:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fAYFzavuwzKf3TwSQ9uvg8XDuACyO1hv","error":null,"portNumber":57246}'
,2017-10-12 14:12:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fAYFzavuwzKf3TwSQ9uvg8XDuACyO1hv', error: 'null', listeningPort: '57246''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33
[ThaliCore] Advertiser: session connected Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33
,[ThaliCore] Session.session(_:peer:didChange:) peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 ,14:12:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-12 14:12:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F53D4835-021E-4B75-99AB-2,901B2A6C2E5
2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
[ThaliCore] BrowserManager.disconnect peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57240
[ThaliCore] Sess,ion.disconnect() peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:899195D7-975F-4830-8A7A-ABF48513F94C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57246
[ThaliCore] Session.disconnect() peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33 state: connected -> notConnected
[ThaliCore] Session.session(_:peer:didChange:) peer:22114238-337B-4DEA-B3CE-8BD17D02606B state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
,[ThaliCore] Session.deinit peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
,[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:12:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33
,# setup
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
,# should be able to call #stopListeningForAdvertisements many times
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'listening 57250'
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
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:12:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'listening 57251'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AFFEFD2E-6BFC-49D7-ACDD-968E0C04A756
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
2017-10-12 14:12:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}]'
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
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
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'listening 57252'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "62566230-F71D-4575-94EE-8BD7C281157A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:62566230-F71D-4575-94EE-8BD7C281157A
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "62566230-F71D-4575-94EE-8BD7C281157A", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:62566230-F71D-4575-94EE-8BD7C281157A
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:62566230-F71D-4575-94EE-8BD7C281157A
,[ThaliCore] Advertiser.stopAdvertising() peerID:62566230-F71D-4575-94EE-8BD7C281157A
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'listening 57255'
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
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,# all services are started when we call start
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'listening 57256'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E7E5FC7B-356D-4B8A-AB08-4C5BFD853996
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FA6F5780-8C9B-4F37-9B87-A1AC78035EDD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FA6F5780-8C9B-4F37-9B87-A1AC78035EDD
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:FA6F5780-8C9B-4F37-9B87-A1AC78035EDD
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
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
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'listening 57259'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7F70628B-07E6-4E77-9888-4A42CA178037
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D8BE341A-72FF-4C8B-B887-78FEACBBC4DE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D8BE341A-72FF-4C8B-B887-78FEACBBC4DE
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D8BE341A-72FF-4C8B-B887-78FEACBBC4DE
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'listening 57261'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BCB6A1BD-2F52-4533-920F-740444486D14
[ThaliCore] Browser.st,artListening
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "47DD2D16-F20F-4AF3-BA33-6C89EDF730FE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:47DD2D16-F20F-4AF3-BA33-6C89EDF730FE
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:47DD2D16-F20F-4AF3-BA33-6C89EDF730FE
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:12:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:12:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,# make sure bad PSK connections fail
,2017-10-12 14:12:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'listening 57264'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CC6E0B0A-EFA4-4ABC-9A57-CD81FE883532
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
ok 271 advertisingActive matches
,2017-10-12 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'listening 57265'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7159C115-93CF-4357-830F-E79E0406B77C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7159C115-93CF-4357-830F-E79E0406B77C
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7159C115-93CF-4357-830F-E79E0406B77C
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'listening 57267'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:12:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'listening 57268'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E10555B0-46AC-4CE5-8224-ACE27A08FD9D
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
[ThaliCore] AdvertiserManager,.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}]'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}]'
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}'
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:12:36 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:12:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'listening 57270'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:68753756-18AD-45B3-83C4-613448A34424
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:81780A6B-66B6-4FF1-8B15-F2911B9E5A76
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}'
2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Received peer, [ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
availability changed event with {"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}]'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 76CF7764-5163-4F9C-84F2-74BED114CDC9 (syncValue: pZbcZUp7iazW1nO7S4U3kYxfveVhxkdh)'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-10-12 14:12:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}]'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","generation":0}]'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","generation":0}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}]'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
2017-10-12 14:12:38 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}]'
2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}'
,2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-10-12 14:12:38 - ,DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:76,CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,6CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
,2017-10-12 14:12:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}]'
,2017-10-12 14:12:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}'
,2017-10-12 14:12:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-10-12 14:12:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:76,CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,6CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:12:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pZbcZUp7iazW1nO7S4U3kYxfveVhxkdh","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:12:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pZbcZUp7iazW1nO7S4U3kYxfveVhxkdh', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:12:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:12:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A40386E-2B01-46CD-87DA-781E0DD5ECDD (syncValue: CQOw8NXR2LijjquroPlJzeV,7RsTGeXPe)'
2017-10-12 14:12:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A40386E-2B01-46CD-87DA-781E0,DD5ECDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,2017-10-12 14:12:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
,2017-10-12 14:12:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
,2017-10-12 14:12:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
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
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
2017-10-12 14:12:51 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}]'
2017-10-12 14:12:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","generation":0}'
,2017-10-12 14:12:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:12:51 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"2A40386E-2B01-46CD-87DA-781E0DD5ECDD","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2A40386E,-2B01-46CD-87DA-781E0DD5ECDD error: max retries exceeded
2017-10-12 14:12:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CQOw8NXR2LijjquroPlJzeV7RsTGeXPe","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:12:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CQOw8NXR2LijjquroPlJzeV7RsTGeXPe', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:12:52 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:12:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F773DE60-18A4-400C-8204-9798A9B73E46 (syncValue: ey9RdE6,Wk06IJ6gRPsJdr3TK4woK4trV)'
2017-10-12 14:12:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F773DE60-18A4,-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57288
2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ey9RdE6Wk06IJ6gRPsJdr3TK4woK4trV",,"error":null,"portNumber":57288}'
2017-10-12 14:12:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ey9RdE6Wk06IJ6gRPsJdr3TK4woK4trV', error: 'null', listeningPort: '57288''
,2017-10-12 14:12:57 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [7, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:13
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:13
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:13
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 93 vsID:13
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:179 count:1 vsID:13
,[ThaliCore] VirtualSocket.writePendingData() to write:179 written:179 count:0 vsID:13
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:13
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:117 count:1 vsID:13
,[ThaliCore] VirtualSocket.writePendingData() to write:117 written:117 count:0 vsID:13
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 261 vsID:13
,2017-10-12 14:12:57 - DEBUG testUtils: 'Got response data'
,2017-10-12 14:12:57 - DEBUG testUtils: 'Got end'
,ok 279 response body should match testData
,ok 280 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:81780A6B-66B6-4FF1-8B15-F2911B9E5A76
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:F773DE60-18A4-400C-8204-9798A9B73E46
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57288
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:13 [7]
,[ThaliCore] Session.disconnect() peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
,[ThaliCore] Session.deinit peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
,[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'listening 57290'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:37518B26-8BF7-469C-B92D-28C8738C7E6A
[ThaliCore] Browser.st,artListening
2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:58 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:,D7CAB270-9BC0-4CDF-BD73-40FA14990958
2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:58 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
2017-10-12 14:12:59 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvai,l,able":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 899195D7-975F-4830-8A7A-ABF48513F94C (syncValue: wanEzHYoxkHQpZEWTDfs65V7zOCrqV41)'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}]'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}]'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
2017-10-12 14:13:00 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}]'
2017-10-12 14:13:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}'
,2017-10-12 14:13:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:13:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:13:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,9195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,99195D7-975F-4830-8A7A-ABF48513F94C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,9195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,99195D7-975F-4830-8A7A-ABF48513F94C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
2017-10-12 14:13:07 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
,2017-10-12 14:13:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
,2017-10-12 14:13:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-10-12 14:13:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,9195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:899195D7,-975F-4830-8A7A-ABF48513F94C error: max retries exceeded
2017-10-12 14:13:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wanEzHYoxkHQpZEWTDfs65V7zOCrqV41","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:13:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wanEzHYoxkHQpZEWTDfs65V7zOCrqV41', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:13:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:13:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ABD6CB4A-6271-425B-A46F-AF3661BD6BDF (syncValue: JTPSr2f,9Hpxu0ZObSfMsZWh0Nc48GRX1)'
2017-10-12 14:13:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ABD6CB4A-6271,-425B-A46F-AF3661BD6BDF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AB,D6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,BD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
,2017-10-12 14:13:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}]'
,2017-10-12 14:13:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","generation":0}'
,2017-10-12 14:13:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-10-12 14:13:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ABD6CB4A-6271-425B-A46F-AF3661BD6BDF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AB,D6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,BD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-10-12 14:13:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JTPSr2f9Hpxu0ZObSfMsZWh0Nc48GRX1","error":"Peer is unavailable","portNumber":null}'
2017-10-12 14:13:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolve,d -syncValue: 'JTPSr2f9Hpxu0ZObSfMsZWh0Nc48GRX1', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:13:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:13:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F4118EDF-60F4-42F0-BF43-5EB5C47044EE (syncValue: dPpgDs9b4EAgWolYjFF5aGR,9EUvZK7wM)'
2017-10-12 14:13:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4118EDF-60F4-42F0-BF43-5EB5C,47044EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E3E6800D-080B-4126-8D61-32FBECFAD95D
[ThaliCore] Advertiser: session connected Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E3E6800D-080B-4126-8D61-32FBECFAD95D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57306
2017-10-12 14:13:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dPpgDs9b4EAgWolYjFF5aGR9EUvZK7wM",,"error":null,"portNumber":57306}'
2017-10-12 14:13:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dPpgDs9b4EAgWolYjFF5aGR9EUvZK7wM', error: 'null', listeningPort: '57306''
,2017-10-12 14:13:18 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [7, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:14
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:14
[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:14
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 93 vsID:14
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:179 count:1 vsID:14
,[ThaliCore] VirtualSocket.writePendingData() to write:179 written:179 count:0 vsID:14
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:14
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:117 count:1 vsID:14
,[ThaliCore] VirtualSocket.writePendingData() to write:117 written:117 count:0 vsID:14
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:14
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 261 vsID:14
,2017-10-12 14:13:18 - DEBUG testUtils: 'Got response data'
,2017-10-12 14:13:18 - DEBUG testUtils: 'Got end'
,ok 282 response body should match testData
,ok 283 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CC84257A-D8B4-422A-93BC-E0349FBA3B0B
[ThaliCore] Advertiser: session connected Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CC84257A-D8B4-422A-93BC-E0349FBA3B0B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E3E6800D-080B-4126-8D61-32FBECFAD95D
,[ThaliCore] Session.session(_:peer:didChange:) peer:E3E6800D-080B-4126-8D61-32FBECFAD95D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E3E6800D-080B-4126-8D61-32FBECFAD95D
[ThaliCore] Session.startOutputStream(with:) peer:E3E6800D-080B-4126-8D61-32FBECFAD95D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,5 [7, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:15
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:15
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:93 count:1 vsID:15
[ThaliCore] VirtualSocket.writePendingData() to write:93 written:93 count:0 vsID:15
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:15
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 179 vsID:15
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:15
,[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:15
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:15
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 117 vsID:15
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:261 count:1 vsID:15
,[ThaliCore] VirtualSocket.writePendingData() to write:261 written:261 count:0 vsID:15
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:15
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CC84257A-D8B4-422A-93BC-E0349FBA3B0B
,[ThaliCore] Session.session(_:peer:didChange:) peer:CC84257A-D8B4-422A-93BC-E0349FBA3B0B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CC84257A-D8B4-422A-93BC-E0349FBA3B0B
[ThaliCore] Session.startOutputStream(with:) peer:CC84257A-D8B4-422A-93BC-E0349FBA3B0B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [7, 14, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:16
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:16
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:93 count:1 vsID:16
[ThaliCore] VirtualSocket.writePendingData() to write:93 written:93 count:0 vsID:16
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:16
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 179 vsID:16
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:16
[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:16
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:16
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 117 vsID:16
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:261 count:1 vsID:16
,[ThaliCore] VirtualSocket.writePendingData() to write:261 written:261 count:0 vsID:16
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:16
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D7CAB270-9BC0-4CDF-BD73-40FA14990958
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:13:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:13:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 284 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeS,treams() vsID:15
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer}),
[ThaliCore] BrowserManager.disconnect peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserR,elay.closeRelay() state:connected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57306
,[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:15 [7, 14, 16]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocket,DisconnectHandler
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [7, 14]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] Session.disconnect() peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:14 [7]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
,[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CC84257A-D8B4-422A-93BC-E0349FBA3B0B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:CC84257A-D8B4-422A-93BC-E0349FBA3B0B
[ThaliCore] Advert,iserRelay.deinit
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E3E6800D-080B-4126-8D61-32FBECFAD95D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
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
,[ThaliCore] Session.deinit peer:CC84257A-D8B4-422A-93BC-E0349FBA3B0B
,# test to coordinate connection cut
,# teardown
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'listening 57310'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AD16D2A5-CF05-4471-8954-790D54808257
,[ThaliCore] Browser.startListening
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:13:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:13:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FB421661-2DB1-4A56-B4CE-BFB2D97775BD
2017-10-12 1,4:13:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:13:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-10-12 14:13:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
2017-10-12 14:13:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}]'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54,BD9FA2","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 410E7270-6EDA-4ECB-8986-F94E54BD9FA2 (syncValue: xov7J5sU99UM9Mc,YAg0MhKRW4IzsIP1I)'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0) crea,ting a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:410E7270-6EDA-4ECB-8,986-F94E54BD9FA2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}]'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}]'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-10-12 14:13:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-10-12 14:13:24 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5C8287F-80CD-4EE0-B744-DD990FEE672B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5C8287F-80CD-4EE0-B744-DD990FEE672B", generation: 0)
2017-10-12 14:13:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D5C8287F-80CD-4EE0-B744-DD990FEE672B","generation":0}]'
2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D5C8287F-80CD-4EE0-B744-DD990FEE672B","generation":0}'
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D5C8287F-80CD-4EE0-B744-DD990FEE672B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:13:25 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D5C8287F-80CD-4EE0-B744-DD990FEE672B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-10-12 14:13:25 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"D5C8287F-80CD-4EE0-B744-DD990FEE672B","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F7B780B3-E5D5-4724-94CC-B034C67019CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7B780B3-E5D5-4724-94CC-B034C67019CD", generation: 0)
2017-10-12 14:13:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F7B780B3-E5D5-4724-94CC-B034C67019CD","generation":0}]'
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F7B780B3-E5D5-4724-94CC-B034C67019CD","generation":0}'
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F7B780B3-E5D5-4724-94CC-B034C67019CD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:13:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F7B780B3-E5D5-4724-94CC-B034C67019CD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F7B780B3-E5D5-4724-94CC-B034C67019CD","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:41,0E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,10E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:13:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xov7J5sU99UM9McYAg0MhKRW4IzsIP1I","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:13:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xov7J5sU99UM9McYAg0MhKRW4IzsIP1I', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:13:27 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-10-12 14:13:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F4118EDF-60F4-42F0-BF43-5EB5C47044EE (syncValue: 549jvc3vBkYWtQmy9jxDdUS6xUniwMDd)'
,2017-10-12 14:13:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:13:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:13:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D642EDF8-5839-47D5-B7F7-2922EAF29D6C
[ThaliCore] Advertiser: session connected Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D642EDF8-5839-47D5-B7F7-2922EAF29D6C state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ECD60A6A-D6F6-46A7-875A-934594B43C95
[ThaliCore] Advertiser: session connected Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ECD60A6A-D6F6-46A7-875A-934594B43C95 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:F4118EDF,-60F4-42F0-BF43-5EB5C47044EE error: max retries exceeded
2017-10-12 14:13:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"549jvc3vBkYWtQmy9jxDdUS6xUniwMDd","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:13:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '549jvc3vBkYWtQmy9jxDdUS6xUniwMDd', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:13:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:13:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D5C8287F-80CD-4EE0-B744-DD990FEE672B (syncValue: qJYa5KXJbfyHTRJnjSBjnhwnuw56rRSB)'
2017-10-12 14:13:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D5C8287F-80CD-4EE0-B744-DD990FEE672B", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D5C8287F-80CD-4EE0-B744-DD990FEE672B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D5C8287F-80CD,-4EE0-B744-DD990FEE672B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5C8287F-80CD-4EE0-B744-DD990FEE672B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D642EDF8-5839-47D5-B7F7-2922EAF29D6C
,[ThaliCore] Session.session(_:peer:didChange:) peer:D642EDF8-5839-47D5-B7F7-2922EAF29D6C state: connecting -> connected
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
,2017-10-12 14:13:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","generation":0}]'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D642EDF8-5839-47D5-B7F7-2922EAF29D6C
2017-10-12 14:13:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"F4118EDF-6,0F4-42F0-BF43-5EB5C47044EE","generation":0}'
[ThaliCore] Session.startOutputStream(with:) peer:D642EDF8-5839-47D5-B7F7-2922EAF29D6C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [7, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-10-12 14:13:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-10-12 14:13:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F4118EDF-60F4-42F0-BF43-5EB5C47044EE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] TCPClie,nt: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:17
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:93 count:1 vsID:17
[ThaliCore] VirtualSocket.writePendingData() to write:93 written:93 count:0 vsID:17
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 179 vsID:17
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:17
,[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:17
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 117 vsID:17
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:261 count:1 vsID:17
,[ThaliCore] VirtualSocket.writePendingData() to write:261 written:261 count:0 vsID:17
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,2017-10-12 14:13:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ECD60A6A-D6F6-46A7-875A-934594B43C95
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D5C8287F-80CD-4EE0-B744-DD990FEE672B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5C8287F-80CD-4EE0-B744-DD990FEE672B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D5C8287F-80CD-4EE0-B744-DD990FEE672B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57330
2017-10-12 14:13:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qJYa5KXJbfyHTRJnjSBjnhwnuw56rRSB","error":null,"portNumber":57330}'
,2017-10-12 14:13:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qJYa5KXJbfyHTRJnjSBjnhwnuw56rRSB', error: 'null', listeningPort: '57330''
,2017-10-12 14:13:41 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] Session.session(_:peer:didChange:) peer:ECD60A6A-D6F6-46A7-875A-934594B43C95 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D5C8287F-80CD-4EE0-B744-DD990FEE672B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D5C8287F-80CD-4EE0-B744-DD990FEE672B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [7, 17, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:18
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:18
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ECD60A6A-D6F6-46A7-875A-934594B43C95
[ThaliCore] Session.startOutputStream(with:) peer:ECD60A6A-D6F6-46A7-875A-934594B43C95
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [7, 17, 18, 19]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:19
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:93 count:1 vsID:19
[ThaliCore] VirtualSocket.writePendingData() to write:93 written:93 count:0 vsID:19
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 179 vsID:19
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 93 vsID:18
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:19
[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:19
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:179 count:1 vsID:18
[ThaliCore] VirtualSocket.writePendingData() to write:179 written:179 count:0 vsID:18
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 117 vsID:19
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:261 count:1 vsID:19
,[ThaliCore] VirtualSocket.writePendingData() to write:261 written:261 count:0 vsID:19
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:18
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:117 count:1 vsID:18
,[ThaliCore] VirtualSocket.writePendingData() to write:117 written:117 count:0 vsID:18
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 261 vsID:18
,2017-10-12 14:13:41 - DEBUG testUtils: 'Got response data'
,2017-10-12 14:13:41 - DEBUG testUtils: 'Got end'
,ok 287 response body should match testData
,ok 288 must be started
,# teardown
,2017-10-12 14:13:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - can do HTTP requests after connections are cut, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE,-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/bluebird/js/re,lease/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-10-12 14:14:41 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-10-12 14:14:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4,CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:01 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:350:16
$9@timers.js:120:1
''
,2017-10-12 14:17:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4,CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4,CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4,CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4,CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4,CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4,CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4,CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4,CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4,CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD,3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F6EB8D66-23DC-4CD3-BFEE-445E94F83C31/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
