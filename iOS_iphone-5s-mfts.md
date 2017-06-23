#### Test 127198710fdd070d_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/127198710fdd070d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CAA241D4-55E8-47AE-83F2-DD82D61F5994/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/CAA241D4-55E8-47AE-83F2-DD82D61F5994/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/127198710fdd070d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/127198710fdd070d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54807"
,(lldb)     command script import "/tmp/CAA241D4-55E8-47AE-83F2-DD82D61F5994/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
(lldb) ,Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-06-23 13:10:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-23 13:10:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-23 13:10:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-23 13:10:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-23 13:10:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-23 13:10:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-23 13:10:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
(lldb) ,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
,[ThaliCore] Advertiser.startAdvertising with peerID:65DC9556-904F-4E9A-8CB5-83105BBE5B09
Optional(true)
Optional(false)
(lldb) ,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.startListening
[ThaliCore] Advertiser.startAdvertising with peerID:68578D7A-0C3D-43DB-BD93-3E28C472FD95
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68578D7A-0C3D-43DB-BD93-3E28C472FD95:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68578D7A-0C3D-43DB-BD93-3E28C472FD95", generation: 0)
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-06-23 13:10:03 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.531105041503906
,2017-06-23 13:10:03 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
(lldb) ,2017-06-23 13:10:03 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:68578D7A-0C3D-43DB-BD93-3E28C472FD95:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "68578D7A-0C3D-43DB-BD93-3E28C472FD95", generation: 0)
(lldb) ,2017-06-23 13:10:07 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-23 13:10:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-23 13:10:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-23 13:10:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-23 13:10:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-23 13:10:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-06-23 13:10:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-06-23 13:10:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-06-23 13:10:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
(lldb) ,2017-06-23 13:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-06-23 13:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
(lldb) ,2017-06-23 13:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-06-23 13:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-06-23 13:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-06-23 13:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-06-23 13:10:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-06-23 13:10:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-06-23 13:10:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-06-23 13:10:11 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
(lldb) ,2017-06-23 13:10:11 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
,2017-06-23 13:10:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C(lldb) ,7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-23 13:10:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C(lldb) ,7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-23 13:10:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-23 13:10:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C(lldb) ,7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-23 13:10:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-23 13:10:39 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-06-23 13:10:39 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-06-23 13:11:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-06-23 13:11:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-06-23 13:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-06-23 13:11:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-06-23 13:11:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-06-23 13:11:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-06-23 13:12:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
(lldb) ,# teardown
,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-06-23 13:12:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
(lldb) ,ok 4 should be equal
,ok 5 should be equal
ok 6 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# test defaultAdapter
(lldb) ,ok 7 should be equal
,ok 8 should be equal
,ok 9 should be equal
(lldb) ,ok 10 should be equal
,ok 11 should be equal
(lldb) ,ok 12 should be equal
,ok 13 should be equal
(lldb) ,ok 14 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# enqueue and run in order
(lldb) ,ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
(lldb) ,ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
ok 23 thirdPromise testValue
,# teardown
(lldb) ,# setup
,# enqueueAtTop and run backwards
(lldb) ,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
(lldb) ,# teardown
,# setup
(lldb) ,# mix enqueue and enqueueAtTop
,ok 31 fourth
ok 32 fourth
ok 33 second
(lldb) ,ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
(lldb) ,# teardown
,# setup
(lldb) ,2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
(lldb) ,2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-06-23 13:14:41 - INFO Coord(lldb) ,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-06(lldb) ,-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGG,ER result: passed - enqueue and run in order'
2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and en(lldb) ,queueAtTop'
2017-06-23 13:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - queues handled independently, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79(lldb) ,410057A9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/releas(lldb) ,e,/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-06-23 13:14:41 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
(lldb) ,2017-06-23 13:17:10 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-06-23 13:17:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C,7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-23 13:17:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-23 13:17:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C(lldb) ,7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-23 13:17:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1322C739-9BBB-49C7-BA9B-6D79410057A9/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-23 13:18:00 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-06-23 13:18:00 - DEBUG CoordinatedClient: 'test client failed'
2017-06-23 13:18:00 - ERROR CoordinatedClient: 'reconnect_er(lldb) ,ror error: 'timeout', description: 'undefined', stack: 'undefined''
2017-06-23 13:18:00 - DEBUG CoordinatedClient: 'test client failed'
,2017-06-23 13:18:00 - DEBUG CoordinatedClient: '20000'
2017-06-23 13:18:00 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-06-23 13:18:00 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
```
