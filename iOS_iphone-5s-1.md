#### Test 11335185130e646f_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/F4F29965-9124-4742-9F0E-F081F9F45D3A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F4F29965-9124-4742-9F0E-F081F9F45D3A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51243"
,(lldb)     command script import "/tmp/F4F29965-9124-4742-9F0E-F081F9F45D3A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
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
,2017-07-27 09:38:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:38:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:38:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:38:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:38:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:38:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:38:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "26BC50EF-7F4D-4D46-BE4C-B10CEA2AEB55", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:26BC50EF-7F4D-4D46-BE4C-B10CEA2AEB55
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2C9CC13B-81D3-4A43-8027-00D746979BED
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:522A7007-,9BBC-43BD-923F-6D47602E241C
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "103CC0F5-FB5A-44D6-B17C-BA14FAFCE444", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:103CC0F5-FB5A-44D6-B17C-BA14FAFCE444
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:103CC0F5-FB5A-44D6-B17C-BA14FAFCE444:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "103CC0F5-FB5A-44D6-B17C-BA14FAFCE444", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-27 09:38:20 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.545911908149719
,2017-07-27 09:38:20 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-27 09:38:20 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:103CC0F5-FB5A-44D6-B17C-BA14FAFCE444:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "103CC0F5-FB5A-44D6-B17C-BA14FAFCE444", generation: 0)
,2017-07-27 09:38:24 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-27 09:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-27 09:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-27 09:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-27 09:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-27 09:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-27 09:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-27 09:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-27 09:38:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-27 09:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-27 09:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-27 09:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-27 09:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-27 09:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-27 09:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-27 09:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-27 09:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-27 09:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-27 09:38:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-27 09:38:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-27 09:38:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-27 09:38:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-27 09:38:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-27 09:38:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-27 09:38:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-27 09:38:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-27 09:38:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-27 09:38:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-27 09:38:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-27 09:38:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-27 09:38:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-27 09:38:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-27 09:38:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-27 09:38:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-27 09:38:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-27 09:38:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-27 09:38:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-27 09:38:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-27 09:38:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-27 09:38:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-27 09:38:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-27 09:38:28 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-27 09:38:28 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-27 09:38:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:38:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:38:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:44 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-27 09:38:44 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-27 09:38:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-27 09:38:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
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
,ok 16 firstPromise result
,ok 17 firstPromise testValue
,ok 18 secondPromise setTimeout
,ok 19 secondPromise result
,ok 20 secondPromise testValue
,ok 21 thirdPromise in promise
,ok 22 thirdPromise result
,ok 23 thirdPromise testValue
,# teardown
,# setup
,# enqueueAtTop and run backwards
,ok 24 thirdPromise - first to run
,ok 25 thirdPromise - in resolve
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
,2017-07-27 09:39:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-27 09:39:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-27 09:39:12 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 60 throws if usn has invalid generation
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
,2017-07-27 09:39:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:87278EEA-227C-4448-9615-B9C17BB96C7C
[ThaliCore] Browser.startListening
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:39:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7B1949F8-9275-43DF-9476-F645FD6B1C0B
[ThaliCore] Browser.startListening
2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-27 09:39:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:39:16 - INFO thaliMobile: 'Received state ({"discoveryAc,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:16 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BA2CF892-9766-4281-AFF3-4627D84ED413", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BA2CF892-9766-4281-AFF3-4627D84ED413
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:BA2CF892-9766-4281-AFF3-4627D84ED413
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD19E0C5-9FB5-40F0-9A91-6135F0585B13", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FD19E0C5-9FB5-40F0-9A91-6135F0585B13
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD19E0C5-9FB5-40F0-9A91-6135F0585B13", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:FD19E0C5-9FB5-40F0-9A91-6135F0585B13
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:FD19E0C5-9FB5-40F0-9A91-6135F0585B13
,[ThaliCore] Advertiser.stopAdvertising() peerID:FD19E0C5-9FB5-40F0-9A91-6135F0585B13
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "31037A71-18FB-4EDC-9425-AE037F466BC6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:31037A71-18FB-4EDC-9425-AE037F466BC6
2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:19, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-27 09:39:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:33683A87-237B-4847-891E-AB42DEEC94B5
[ThaliCore] Browser.startListening
2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advert,isingActive":true}'
,2017-07-27 09:39:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-27 09:39:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E915080D-D526-4FB8-80FE-E5B6C7288468:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E915080D-D526-4FB8-80FE-E5B6C7288468", generation: 0)
,ok 76 peers must be an array
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:980AB9B2-4046-43E4-8FB8-434566707B01:0
ok 77 peers must not be zero-length
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "980AB9B2-4046-43E,4-8FB8-434566707B01", generation: 0)
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31037A71-18FB-4EDC-9425-AE037F466BC6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31037A71-18FB-4EDC-9425-AE037F466BC6", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:39:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:31037A71-18FB-4EDC-9425-AE037F466BC6
2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCha,nged registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0
2017-07-27 0,9:39:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:39:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DDEF01BA-3E50-43A9-B6BB-4FE7CF7F0C7B
[ThaliCore] Browser.startListening
,2017-07-27 09:39:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:39:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:39:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] Session.init(sess,ion:identifier:connected:notConnected:) peer:94AA360F-CFB6-4D1F-9587-9D47B8A1E928
[ThaliCore] Advertiser: session connected Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] Session.,session(_:peer:didChange:) peer:94AA360F-CFB6-4D1F-9587-9D47B8A1E928 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FB74A961-CFB9-44EC-A7B,8-C64BFD36836A
[ThaliCore] Advertiser: session connected Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:p,eer:didChange:) peer:FB74A961-CFB9-44EC-A7B8-C64BFD36836A state: notConnected -> connecting
,2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6","generation":0}'
2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4D7B1B8,8-0FB5-4D2B-B0F3-0C19B3221DD6 (syncValue: 2NVrdWsWDeQ0vKkNLewJ3TghoooIQVrC)'
2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D,7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] Session.init(session:ident,ifier:connected:notConnected:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73A09F1E-56FB-45EF-99A3-14DCD6DE2211:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73A09F1E-56FB-45EF-99A3-14DCD6DE2211", generation: 0)
,2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"73A09F1E-56FB-45EF-99A3-14DCD6DE2211","generation":0}'
2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:94AA360F-CFB6-4D1F-9587-9D47B8A1E928
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:94AA360F-CFB6-4D1F-9587-9D47B8A1E928 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62838
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2NVrdWsWDeQ0vKkNLewJ3TghoooIQVrC","error":null,"portNumber":62838}'
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2NVrdWsWDeQ0vKkNLewJ3TghoooIQVrC', error: 'null', listeningPort: '62838''
,2017-07-27 09:39:40 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FB74A961-CFB9-44EC-A7B8-C64BFD36836A
,[ThaliCore] Session.session(_:peer:didChange:) peer:FB74A961-CFB9-44EC-A7B8-C64BFD36836A state: connecting -> connected
,2017-07-27 09:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:94AA360F-CFB6-4D1F-9587-9D47B8A1E928 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FB74A961-CFB9-44EC-A7B8-C64BFD36836A
,2017-07-27 09:39:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:39:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62838
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:FB74A961-CFB9-44EC-A7B8-C64BFD36836A
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.disconnect() peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2NVrdWsWDeQ0vKkNLewJ3TghoooIQVrC","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8
2017-07-27 0,9:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AEE928C1-5243-4F40-A3FD-C638BC70252B
[Thal,i,Core] Browser.startListening
2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:39:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:41 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
2017-07-27 09:39:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6","generation":0}'
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6, (syncValue: pYCo3LFA9SyCE8p0Ee6yP1NVLFsSlN1B)'
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B32,21DD6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
2017-07-27 09:39:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9","generation":0}'
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:39:42 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FE78BB24-6874-4581-AD57-0DC8832424B4","generation":0}'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserRelay.deinit
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
2017-07-27 09:39:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pYCo3LFA9SyCE8p0Ee6yP1NVLFsSlN1B","error":"Connection could not be established","portNumber":null}'
2017-0,7-27 09:39:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pYCo3LFA9SyCE8p0Ee6yP1NVLFsSlN1B', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:39:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-27 09:39:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9 (syncValue: XJ3WwQF,ZJPP0rHDkKHqcE1tBaHVWqQid)'
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
[ThaliCore] Browser: session connected to Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62845
2017-07-27 09:39:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XJ3WwQFZJPP0rHDkKHqcE1tBaHVWqQid",,"error":null,"portNumber":62845}'
2017-07-27 09:39:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XJ3WwQFZJPP0rHDkKHqcE1tBaHVWqQid', error: 'null', listeningPort: '62845''
,Connecting to the localhost:62845
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
Connected to the localh,ost:62845
,2017-07-27 09:39:56 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-27 09:39:56 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,2017-07-27 09:39:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8
2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62845
[ThaliCore] Session.disconnect() p,eer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A7A20DB4-FB47-4900-98BA-D663B3798342
2017-07-27 0,9:39:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CB210357-920A-4640-B8A5-52F6C1925C45
[ThaliCore] Browser.startListe,ning
2017-07-27 09:39:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:39:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisi,ngStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
2017-07-27 09:39:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9","generation":0}'
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9, (syncValue: GQMHt6hkeKUpNy8PzVab1FkrUXu2uzyh)'
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2,A7CD9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5284E402-404F-461B-A0AD-E6A5CA3CD24A", generation: 0)
2017-07-27 09:39:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5284E402-404F-461B-A0AD-E6A5CA3CD24A","generation":0}'
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:39:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", g,eneration: 0)
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5D887890-529C-4AA4-8B6E-27EF41303DBD","generation":0}'
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Already running ,t,est!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
,2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:64,B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:64B3EA7D,-E3EE-4014-B73C-A9EA8C2A7CD9 error: max retries exceeded
2017-07-27 09:40:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GQMHt6hkeKUpNy8PzVab1FkrUXu2uzyh","error":"Connection could not be established","portNumber":null}'
2017-0,7-27 09:40:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GQMHt6hkeKUpNy8PzVab1FkrUXu2uzyh', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:40:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-27 09:40:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5284E402-404F-461B-A0AD-E6A5CA3CD24A (syncValue: GhzEodO,mbZNPaokYdnSvwNlRpF4X2j6d)'
2017-07-27 09:40:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5284E402-404F-461B-A0AD-E6A5CA3CD24A", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5284E402-404F-461B-A0AD-E6A5CA3CD24A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5284E402-404F,-461B-A0AD-E6A5CA3CD24A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:40:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E
[ThaliCore] Advertiser: session connected Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
[ThaliCore] Advertiser: session connected Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "5284E402-404F-461B-A0AD-E6A5CA3CD24A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62860
,2017-07-27 09:40:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GhzEodOmbZNPaokYdnSvwNlRpF4X2j6d","error":null,"portNumber":62860}'
,2017-07-27 09:40:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GhzEodOmbZNPaokYdnSvwNlRpF4X2j6d', error: 'null', listeningPort: '62860''
,Connecting to the localhost:62860
,Connecting to the localhost:62860
Connecting to the localhost:62860
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5284E402,-404F-461B-A0AD-E6A5CA3CD24A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E
[ThaliCore] Session.startOutputStream(with:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E
Connected to the localhost:62860
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
Connected to the localhost:62860
,Connected to the localhost:62860
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E
[ThaliCore] Session.startOutputStream(with:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E
[ThaliCore] Session.startOutputStream(with:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 3, 4, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 3, 4, 5, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-27 09:40:13 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-27 09:40:13 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B state: connecting -> connected
,ok 93 correct string length
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [2, 3, 4, 5, 6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [2, 3, 4, 6]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
,[ThaliCore] Session.startOutputStream(with:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 3, 4, 6, 8]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
[ThaliCore] Session.startOutputStream(with:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [2, 3, 4, 6, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
[ThaliCore] Session.startOutputStream(with:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [2, 3, 4, 6, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4, 6, 8, 9, 10]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3,
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [4, 6, 8, 9, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:), client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [6, 8, 9, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cl,ient disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server data flushed'
,ok 96 got the same data back
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received all data: OBhBV6yiEZqRBYc1OHmtaCocltsjyCcE5w0XEn8VXiPWJCIUW1y0uQhL4JmlluIz2udluneD8Az2QvvVmuEUgqeR8Q7rwH4ghSCRSIM2fB8p3xDTK73RxPaV1ioPceslO2TIFJ14ifN8ZlhbrA7AkgkV5qGqh9X75JWpFGie6oXNwwZWud,5I3yZA8PO1paAhVG2r92gqC6AyuqimUn46rZ3XQLtVB1xUVTqUExynyUuF9jsrADsM5JDu4kJ0an3yzyg9BD0KodSOHLGVJHZ5LWVD1ouh76aXDv7w1UlpqGhonnAeiQZjg1DT8Uc3KH2ZiedOkzCCEhoJy7IQaBuLrVYrRlDoBiogdPMtI3jnJC29h5lYp5VFKvOcZJiaQSlYujTPdx08nxp8YPrA4N6DnAiP66cowAgTnfYXJhYIfkJ1zC3nTK,zSfUW1ircrDCcvnY3T7XNSxF1DH3nkysc6ughSkQYpQgHnE54tpFhpS3Kt6qWgX9TYHOOfS78HW0se76vDEfYRXQZuBtI3mPuYrLWnJga1MP0JKAi8tgjvRkapwfL1kQanX5jTfUS5CG1OarPxmUHTyroAsolk20F4iesqwbgfXjCcsx5X8y9dSje7x9g3wLBV6TMs2V7jYJ7BxFueUuKhUaQWzKS7BsVz89xLMKO29H5PCuyVM4sS3MfU7bkq9k,Imo6k1ydB3XgZRQSeCqolAb4olt7n0wGYt3lPd0qpOuUNMNBEL87l7ojMzWg5uWAvaxAZ14F3Ml5naOrdWwJ5FdNQoqdbFR5pLwWYKmPGafxfZiKNDxWjZvzv0iY4ECw1xvhMUcpcReY3tjNd9i4TDBD3MRLTnDIu9ATWGkwhnlQYVcNXxsaKRCEfMQhPgbJa7hxqGbeNSWsxK05FFkmW8eFBGtATR5OvZhNH6aHZKpn5JIS186iCSizIOOERIAH,iA8IDYJEA67kfosExUFg43dqKpkaXkJ24eZG4weL32r1Hn1aOLOgrneUY6vIchVTZ1Nk11rv6eWL0TQQGmQTh3R8XSXe8mfHhxklvhetsl7HhmbWGJN8yVqYJcoiJIUudWog44MCX38PM2CiMhQ0NAEVbr6DoGT1tQzsBQqKjasL1hbUePai08P8pg2QNiBEOtdzcRvJDMrnnwnqfMre2vxAAfcNVK0VKen2HbLXtvPGOWDdXrHTlTot9A8jivZU,UJuciwTp9GVZfcmnmswabdqng6RrytIDJ9XIK6HGNtFwY0ieMfqj68m4ql7CEOFlB12WUeGXuysoSAUPPoeTTLjHj9IRbnmYycrMhHAUbdLVmOSThS1KXuymQy7gmQMlkvSsaS5dOVeNinZxJ9zh27ewGLZ2H5jKW2IBWJV4AOiTRyCaqiIhTSEkQZ4W72c3WsOL03Ykw3EYd3vxSYSPnsMQ5c9UfjN2O7E5PMMqX0KypdUF9at2CkErq5VPOHjW,h9l0m5qevq7R8OJSAXHrVYzDh2c3hV9u1iwyuxUQp7jQwAfAkqFErjNiZejvqSKoczAZMtk135Kus1XA7sAieiiAg9CHCmIAr7GRCZrAyebM4sYr8EWU5vA4blUtj1fgmA8UolMsss8GAGu0zJW431htSou4lwojomvBrBpPhudIUzFin1aJ4uZ86IP6jttNGZ2nBlNeP96jPW3RGn6mMUEigGo25AX96mUcHKfD15iMnYlgclzyTVPanjlognNN,0urNdGh4jU2QkQ1taN5MvFd8S5OgqGGqd8Lf2DG83ZLKxu77l74ZmW1L2pIYdqdYq1mUNO7F6v3wbBlJtsGW75lfbhzbMS9p8OZBfv89ttLQksMLbDLFss74Td2DlSMN7Dot5mMEF17hdKUkPiPUZljpjUiP1w6t7zx4Tos0Tr99EKX2GkHvRyS8qhVBggKDkh0UdZElQsrziFJfnQoevYME9t6re7d3pXc3C2Y5TN9Iiublfcve6FJOopP3215Q,zvfYkE4dbESqF4Lhk6EyR99cy0iW77X2pDwFoYwHCogalxCMLjYvCPUWWREAJg0CNQECQHV4qH2BxFgK3i55L5EAnvpiH1TT3G80NS0jP9egLcVs2AJZ90TRnKoZydNtYuVbV5gCOc0DR4T9mtsK26p8RKMC7eitsnsUCOgfTIStaD4ZpThcpNmwAmewO2Xv6XUsYHGBV3JlsVBbtzlhTjicrivhrxBaAxdUXVXJXudIYtUPJvsK3PgGNXaekS9J,ZlBPgveO2uXObXer73bVfddgETaxtZeZISrgTS1qDU6K9UrZBCksRDs0hGPiIl3wONRJWOR59UaifV8Opybbn29l4gwPotGpucLF7uJDDjHUkXCkcmljYlTI4bnjOG5J2EkSPhjts4arqN6O2HT3ZomfyA52nS6v92jRF64k2P9uzZo7e2nxHSIJUZOQo2zkkqWzOa1GrccCao2UpDG6VH5WOGNCHYmAGCPynITw8fkyMpMjyc1eYCCnCBh6eVOh,wFgcAe5P1oM6GotzqdeBAzVXUgLblLYF8cyHAnqNc6cBHD0bYvaU3BQSmVcxR6m7672RZ8rLamjkQozmPrQmBZVIsRUwobPwLwAWOhdml1xcF6m1ujofbTOYtUdOvPlVJOFCou9qD4GTkx2Xyq6osNJRGOqqvbnNoXK8wNDXySrZtN0IeBL9QRZoE5i6TQqd7FZO2D1LlLE71UCmRsuJ7uj4ihrr76rqjCRK3N2S4urKWSxdJJIVYVhuWwyPS6Fd,8p3YuUEquJl4SgfzGmgV4xmEJx6fhUYtYuvBVHATqt36YqzRcll23ij7FBwyO7kWotSUl0jUYEBV99a71e3tZzJdTfuyOMGZhEQw4AyqmM9CqFemW6fpo62HmGuH76Gqo0UVCUYkluoKUMl3S7jeVDgTLKe2kfG3rqhiB0Mak6AJwvrULCo5XUDlPY2h3j8CwrEqyIIFaeHx2FzjimRUbSCarndMSfUxZmAyipMyUUMDiCDk9qk5RorRqM0OdAPo,yPgiaTLJjnYmYvIGkmuqQ8TymoQnN9EOswxwonq5TTf9HJXY8jHufYsgE3K9I0lcscURIPamUI1lvIXQ0PtgwjDTbNpmoR0AXYjYQUQtBWl01UEB8kp054GJH2yvz5ItmAC7lxa8iEsY3YGqa9LkyoSEU47bwZ9yRK6pMCpDPQz3GELLF8avDTSya4ERYFgMVC67mOOOKXKFzRXqRPDDGQID7yzb9A5hLt7UvXN2D1JpQLfIhpEvgU4poNGF2Uih,shMDawhqitquTick0Y8g93kaTUwVQ3zPkmDwXNZyUsRYTnPkB8HjQr8rYoAYArkJn4rAU9dr45IP0zbRantTtlLw1Hr8hAtukEMO89lxseorYbkiZT9z17lKuz1egdpHuLeq0hqgZHVhT2NS4QRTKVKCkk64RkNEAigxsl9xS76SvLCkhOW2Og7kTo7F5Vdsznyn8bNd5krmiqqc8CELjIuusZbDHKhupSc7Bya7oFTPny60I00Vo3qG83zy9AaN,YJeULrSLWQdHJ8iVm1wUW23VRcI6XNxVNNCqo4atO1AX2S9WLeTmcfNWPwLzb4zWwnb4hLv0BpB5HGR5JVCTBBjqdKqkCwA3SyKLSZClKcNzmxzqfFZGbuTJJJ1yk9aly3CxB6N3HQgDWMuNOa741Obwb6mg4nLkoFycTDSnSX2dqhdVCS3CWADpIip0S76SUyCArL6mo42OaRfk6iZLr7HkEL1e3YnqvSugFwyyVxqbLODHbrQsYksc3CZT5xEq,OtwgZS8vyZaVBEqJBtcM1vhr8o2NW54DrZu8AYuq1TAW7KvpNZph98Q1gsKCll2JUKZSZJI8Vjk6bu1tAz9sPTUr6wU0jqYrojfhZtFOKBh5U1ipCEK2NVGKt2bFrWPjCy6xD8MVvRYEJjDZibhmeINclS8g065iLiimlS9zmO2cZUcGLnNYlblUangvi7mci4YO5IUTOBXZNRE1Z5D3UhPETpWbaGdYsPEFTVyQROk4HSSIPkzkBGAw6UGCR1xa,QAmrbmcaUp3zRxIU98r1m07SuB0JjGUhpCuFPHu9Xvc0t6fRPUNJ4dYGzdxWwlW3W3aKliljva9cQj1FVBW9B68NFxizRlbrrc2zoP3yYDObp17Yfvk6Fb0ewRyTQNVhHiDrpvwPZFfkTtOFYWs6RUGL8e7YUIIfojoWgxvkx1mUMMtix4CALl2Xk3YC9RZ2uYthVBvg1HW7byeaog1OryP9j1hbkrsRayGZbTagtPh89JFOtAmjMxTpULabsppW,hfDGRYFJl5UE4VQKJklIbVg4e01m4NfbgZxDL4qftQnvya3PtEDWtcN2dOPMKl7YylzeY02cylkfGvJCVeLdmFt2gTXrD2SYZlyzgGb0xiztPAS6Y5yiVwqIt9OTMOxUPJYcP67HGlIcya0X8jgggmvOTxO2gKjwBTRxriRMRGQtbf6Az5Wp12sL0eSIgd9UeDvimWcXj5tYYYNfmuUUnBAh2dUAb8aPd99N9WhwP63icBChChdOZM45wvAbnV3l,5sUBtzRnaChYWLXJCTr63IbUlhQlauRm1gEwyiciO1pais7mJHLvE9XADpJTGCzvuMKgxrLjlt3eJjhSSPRJWVwr1fT2Jc9c7gPSbpVWD86HQ28ZOYMPoBzKb90QQHJ0kadwRHpdy2b5w79BlHbLhfl1c0cPMsOdC6RqNrAZRZhqFNb4hezCaFmpUw7K7cWEfG9d5xogMRh33N9fuD3XAP5VSEdCAdxj8P1WHaZSxucC3Bz8YajXrmhhOyUQo2le,hODCP3NFJ8Cmm17EiltGjyHGOS7HgsfdCq4X0tWYAFQSPAEE4km183f0m8g2duFCXQfWQiPkQdV8Q8rnxidoXLYd9JHtfqFVadkr20H1qkSVopvVQvPHspjgNEr1hyIQf8wrYMANSRnGUv0ssJnU0QkluCaMHnIccgds0DcgJNFu9huIx8mrr1rD73eGV741EpguwjPJMXm3ZmO4mOW5WOcNxwcVmvLw7kCX7hyvIb6SsjkINwtX3RLkhU4tG555,9pzzyEFicw5vhSY4FzC2luP29frJRKOKrhgzhABlXmSLdyslHzsi7i0RhvrBB7crFpzUUS62bFA1OBAqxOXsvHcwsoN0iaG26CUWMswpm9nKB0Dekb6GJBFSj8bMUykqXr53iVDV8BNH0A2g5djexISnBadGkbrAcJZvEYfTlxMRQcr47txbuq26mguyLYcq9rK8qG14KjYr6ekdHFCIuBZnj0SBqCQBYaxwRRIsMkNPg15Wp8zGbAHaUHJkqslM,hkuxyI2gDl1Dcij5AnYFGqNCEW2vmNKZqgLafUbtvbzjcjBI5JFTCeKpZlp0W0Mqy26LNqTq1GN8mX8ArZcLBKEuO6FazUPETONx1mKGT6zoKjmvVaL81wqBaMOJ6MlhUJrPUaB9sWEtGKctPeMRGe1PoDvD4l2aMfwuLlmyddq6jIy5UM1vNdNBNtEjLjxAHbpc5DKGje3ru4h7BSrrGbNB1fYv69Og6eUEuhQY7IfRltXjKU4OvK6L6Fa7aWJL,15OhGqpmJ9iLHkrbUZEQAMmsnh2pqEPAvwsmDOALntG16DwK2Vt64dXkDHXbG1lcbKIgcoZ5Wb1X3Df0iFM1kgsaaC14weLyw0Set1OSgTRDHAv4Zd7a9NfQfNBX8DxxJM2eDpw8a43tuVDNk0FuPWsCIKQ108N3jowy7qFGWGFx2yqs5kf0TQQJXjGgMknHt4EbnBE8myWLwvndNigEcsjeVdYuaHKHjln07mTxzKBm17hCECPv07Ho5n2IUVvZ,ZVUK3OLnwhWHFoPG8DRX5t82uLBeu7vN8XU762VcGO3P8QRlOu6JkQWxoByfHc1fZXFcm5DRzNQg0YniD5u30E7Lrh39zH0bISmaaFLdFHM8WJygjXswU7scQ4VD3i2A9UVViUsaK0l9GEiDQ9AQBLbdeIPeEnNLvIUQ8tOd6H86NRuD77tZb6uNDBwQTR0Nqf6pLlG0K5kQI6U6uIWxAmYqwA9Q0mzoWpl8Q9VPBQKD4KF92NHm8PduyJEAurpT,CfBLmFWTbuExJvMPWQDG69Vkahf9f7iBO2QASpvMSTYpGoyNjOTGXnZdK8Dxnu4jiL4WKzad2wVFFhE6JII55FaCO42vM4Skq0n8nA6IuNDs3xHiGg4Lf54Oi3citnFDfzUY9UfchCvdCbZdlCPkKRFai56K9A2UfaDs7g3Xs3MZJod3gzZXmqGzTeeYdUNomDKI1RcgqlLdkzmcMQUixVy21IBwDFzO4XSh02gRPqosc9hiDLA6IrWFdrqkCc8H,sAau8sthF19qctLAuXtFi4oYyk1yTp0JJ7hjV9X81hsM3DvJxYTzxueLACcpzbSEv7xJk2Rln6sy6kDQ4kyhBB90Wors34WddYvwEXBOVeDPTjSRTr4Nl7fKgrMbHGkBkmeWpTUkKGDOobRr5vsMIkDwQz6IoIwwN7Yr6ZugLA8hGEmkFA6CIEnF3vSle3JqrM5AoBUFPh4g2qEhx7y0bvfWBr23Yrbg9V7JAMEWA1rXeHRNLw4vaLM8iJK1lpyr,E7VoaLOQ7rEfVhBKJNOfLREDVJMDANZ7C3qBo3Dv1nZ3dFlObf3MOzpPuHHY4sYypi2fof3ghRiBYhndunJhOGzYPbAWjqoYxQj7ET4CyWg3QPRYxkM9RUwih8Ds9vHQQxU0hou7mh6UrEHrSoc2GNy3jpB0vI3QE2lvlc2L881JrMHlUICZTgLEjZa6EiSulgyDOSHysdsjDIrVuvVupd7TKT5FouO9caofqTEwosyNO6YngqVVJ2jgtGHAjpcQ,W47xJ5X5oXHxldDUPw8iErcaK0e4x7eHPMxnqj16B3U5a6I1CA32Vy4bMQwXUr55OjPdAWQl1nsz2D4SwOnR7gTQ1Lq3QAQIm4PfLUdN463IC6o2wJ8gIcFtf0ck84cMrnv9dONUpFKUTDovv6luRAzYCb4xuJSKlFd50SBJCJF1BpjmLx725BKJRroPbgCMq1mIU7W005H2yRB9TR7rMFvMtb4zajP7tqspQZXI0dwysBwJL9Pw3PR1nrVhKlag,KuXsaEO56H4V1JSVJVKAHLCbqaFG5TmGSVdKnQzOTEv1pTAJFkpzIR5z3UKMuAHsVTk0pFYohNg13F705NVjix7TOuUeUJXOx118awQ3dW4avJQA2P9m8NnH9eUNXrW452TZ7qyzZWDpFe4YEjyoHB7q2xlbQWdHnwhdFJ3dITzFrkTmQtjzDvax7wD0DXXjC5BdUFBrXNfXDk1IwFzZp3sX2L6ZEgvOffWfZBRmE4BlzT7A9aXInq7iy9KCOqrw,FzxbwA0z1XISNlVLqY2WHoCu28uUjhqtNsTMiUH2ACCybE7nR8u4tMcwuQZsZSbvCfoiDyoYNbTTVx7TtFqcQ5cMnaNSjA9z3MpXbs6vCRqDpOo6wQS47jzrxjWGk7yJkMhPtz5WLP1hTv9wW9EUyhf2ezN8jHWxI5IJfonndlgYlosNQnFKVH8fvDfTYnhxEcmavWTRiOs4SpeXqtyDh0RVPLve1wBEIaAjYbLUlfdGZTe23t06ETgchFVLynst,cBrjBgAlwsUnQiWNh0NTnxuaMEy98CwUUKmBe2OjPyJmdhyhyAkkL3VtaHPLjfUjVxYGePmpdmac8lxmIqIcOilXje8YoXZB3KqHRtaTyabDDfIrmHOBWDT2KTBhLXHPP5gY291dZVfAyE88DqbKJFl9xzFalgFUXwgUIa6YGaHW1LFPLfR7RJugCYyT5Tnt072GRif9vVm6TNEElxFBWvkvX9PechQ3MkHzYV0fSZnKvuwQ76X0NApnd2SymrbB,LzXNo1cGDH8X4ZPQLtgogCXDNlJOhDFFNCGze6xFXP1d8EDXomHTYvqZiDm0gtgCQ1C3pdbdRIeBsn32huz9aPjEh7riyM5pdyvBcqepLbijPyGAt9gqVXHsLOUzvIbfQsrv63hTqy1hQkq2HhbRQBRz2yflgD2Xjjm96ZKuj7YqXrOb8YAU3AYZ6CjuOgkDTT6hko3lRZPJVnbhOGmjYwidkb25ed3TUSDo2QXdcDSVhpZ7PgW7r2DHT2pzpIUx,zFzoUZoKHYMeDnXIsYAQxeSn6xD03zsicqxasDkwKhnFKFkZMNgDAc1iETXxA1ZfJQiINNFcT0IDRQqebr3rAJBFMmVr4Nc73Qml7CXeeLnhobcBhrAPF15y9pr5opEPAaaQRBhzuE2TXQ5xbS7HVGBMAFxVrBXyudkmw4dZqpIguLZ0eSagibZhGgJpT86D0nr7DuLMvjRlxQR00sXR54Yt096qQENR3KgxRuoSIOX2GMOXuqhStEp8pCOnyYf2,Z6JTNLjyran00Kdu89Gbbz8YbBIVYLcUKVpUEjQNZLa4l75cSiwf8CxlyNichxH9tGvCQyPaflNp9KNqFeTFy7HnFl5FuuLOnZaL6xDf0d3xRHJc3fPYBxeIZEkQIaFW3wOlIhQuprgRA3hHIqz3Gw1cyYigH5hPikZwUQqbnQHb0qVMl6B7RGvK2kJOyNBou7ZG3OBI70xzTxKJTQgtLKI8J5S2zJIEY8UQjb8jPlMy1rn4jxiUEo4Y8R4wYwf7,2NTgs3lCFHDBHc7iMgJNMvhRC9SKeU4eXX4h5cQf1TI75k1aXTqxFMWj2Ei4QMVG9kFArWIpcrp9D9RI7tIoYItEQG9LrZVf3d599ztgjFgF7QE7lwmWzv3LcT3vSZyHEueZUzcAhohoZyAqIXMK4oERVrYSgDPr46p4henw6Wr3urRt2usSeo7p7D2pfmN6kOw2xnRhFDtfUoKQGpGwkWJzWQNhZo4lb20S5iJQifhTuOBQcdyeRPg6RkNp2Ejp,j0HLRycXjh46KcJRoLtE2abNJDfodfwPfQJWY3xkHYY3RLPoUPpOqTNxJnhRBviswck8p4tDQGrkBfM80VSJ7zf0gC447LOOQBfnkAXSjQhB1sqLkT29jeiuZaQpZStGJPnMoVYcopgkEoNyYBF9xDuSACeELlRigEnjktKAz1Mw48JzMs9M4FWCXYxbQFcqdlL0B8FoGKkG3AZoxRJTKjgHstXZR9MWVTFGLltYWZJYhYHyP8GZuG2TXMHd13bx,6qT2CXzBLDxXc7FSuSx2FaiU4soiwh0JyZtQgwNSOiicCKLcRcilrCPHHIglIOS8HqQJ0MioSpVtuh3pnq6xIQgMliVRZKxo8QjKBDwgzKtyYDurzQwhLZl9lfNBnNRrqbCIw4wDmalbd5fN0A2e4UPB2wbEOdfsqcGWxfd2giGw2xus9okGJTA6RKhAeT1MVhQ2cL1XjowxJSFiK6HZrgPmTigNtQuKAIyRi35AgM1Mim24zmjY0jLq6EYpstdY,Qylbii9oXHQUxWBZS6U9tK5redC1wujkeitmKO5o0GGcFp7UXHLrm6CJwsxsP4eBFriII2np5uxp5lvIMGmrJA89XrxFM0vn5DmSz2c2xTXAZiOACOSZU9W2NTUk1JY29JGlTvlFVD1spnbsnkVE8qX24jk1VOngvqOnilWdjN0HCUbsKTZe2Kemg2kIRn9r10bL5w4PKdUxnNTKXnVqGH19xflB7XbswRAD2jn15fGOc5SzilT8VHoaHtfQ2aKN,RohkgqI6gevcmeOfXpVXBJC84PiIdlhySigUY1ZDuZyt3caZVCoC3svxMsmgfk5PHkm59bJWZhTrCkLZ1a9fewgCcskN1Xmudw2Kn02iFKNrnJsS9iE7plcfwjMpl7zv0OzSuID5rmSgyq8KCBCt0n8JvZPOakid1FzzmCNDunYkpU1bXARMfUfmGa9WH0uKtRRdGnNyaxlPalO9LMrAtW93C3n3yFG99Tze919ilb9KfKV1uSM8IAfpj0eYuUxc,KO82TQljCzBucyzu7XHaBJ38rCN6R8nKsaF2XxDy2SrflwFxGqOxyfiKSbB4zCh5wJWHIsW8LoBmjb34j3zxRLAdAmfOF1faLOnHukckJk57lJHKGW6Z9FaP6vs8wk9dXA9kQwhfyqVKMlHoaCCRcYzsGSgks44UMdcmtRmfx5zdxD4PRrOpy3zBGU50MiPVGUyJcO3vPHUTSAsP2yZiSYc19ZB2clVqr5r9NMD2stkzlDzszLFVjWOaGTJnVY7d,MBB82LTO9bnjjdmCGRVfisQFGBsHRrmdb8r2pqhDVFeaf9HvWQWAzfNloolqAECLYQcOSNYhlk3Kn6J1dobgr4jFFH30W0HnhACeRv2mAH7Wvb65MLIuYqz1ijzqgNxjxWZKYyGGZSAyEjI2GV7P4CorNtdCA2RRqFgDyhmmSzlqoVEx8Gripw0DwuYq1a1bYsRoTZBMOFzVDUBSaZjX5ATp10ev5X80yKswcICL4u7eMSI2PdoN5AjsXiyVK16j,vVmSO7hEarwpWfB7pibLbz3zZjLU86sOabgEgCkayMU9Ef1rDHHstuzLcK4xa5cFjfmMMyykzUhecXekhkPgWGrucO1jArxqeetAhz0noKvcCoChbAWHVvG9AnDRHSHyvAGZ1V61AGl4iTyKz7gYDOr4abQg927qWtDV5aLkIjpEnBnHdMvBiarAjlSlVbczUc2BO2ERAw5GQLQwH8bjVjyx5bP3b12ua8DJpFFvlbp1V7mRP50wF8rAG5Y888mL,Y2J2YTorUCYC4Z2OB3TfyKqZUrPmWiz0nMtiYgLWxwFQHFqTlc8GGOjHF7h7BpWOnk8lQUsviJAQ9j56qiKoW2XNWcwzCawCl6vrhppHvKY3Wc2mXu69AP3rbqW6tBWKSPC5QxzLDfi1ByIO0vTEETqmcJWWsNPFFyNpZhZAHE8n979Y4xqKGDszig8Gi6reTG0LY6iqNR5A4EC7ANQ7T6AnNiEqjEd2Cs5yXSy7i595GkZH3BumbQ9tu8mTAECA,xSWecff7Vogkp2YkKMfjEm5kKsjln6vB4F7YO1yrkKz0aKMJrLRtgBZL4MUrnk7h9oYIpH2Y7wao5IHrM2fP8fn0PRg2RRsgrY9NVtd8Hbe61nmQiys9hKomRRRlBqLfV2hj93Vx1MZJj9k0ekMZD5DFXraD8MPBApR45WKeDbsjAa0NPm8dpPBDPVncmwLPFQqTd0Mt8S3qCENO9XzdmEsJjin842q10IF63RTUPInWu0rXgHEhzL82PunXJkFr,qMLzu8j7OZb0SotvFFvaS8mKb4DFPhca5NobtxSEfEGbZ0fyVghAOFqX8ZDu8By9PpEh4ECZJVdsgrxMKyppKFoSeIP3PVU38J4x6pfcqOg6uVZYysL3ES8PCkRsoFCBN4HKV8RuSNBdBCTeGQMbejCKMSTBok9zEaOhX7xCp8hjjOr1XALKRdhKcSwdlYI2w56SlTUnQummv536gt9JzURD8FyaloAPT2lEtR2T5QilycBw9wzzt9akCHjbvzTy,5Xdj8EAVj7pLlXdEoSiWb0N2WOmzDMdWrwsCOO59w0c7BhepQOWe9NKb69bj2tWi0q4H3lYpDZZxW38laLZCfqY64S8TRXddVLqeQZUv3bWPCwND1r5kS3dFBCWOLmHLUUB4QDsLhzRoADj1PMBVocYeHhkiPPUye6H3bEIygr6RrDkR7NYiJGWIJR62nnoRkq7ynwpmf3UxcVXS19BVhceNYct1Vt8T8gjyECKpYb8OHqjoQHpnqec0Tr8opCEm,g85HX62KAicqlQGluXID5KWck5bEAHHJptTvEh6ZLNljeXgnVSj7LfsNraqjItUzHgzHPGNVuEX3LqKgrCVGLFGgKGbpldM0v6LhdlOWwKNw0WyFhisdmjKboMdvGgxGqYOVUhAEytxfsLlpwoqleDy76nWu7Dq5RIlpvcamsjgbllbxsVgbrzxpi1tuvoTfOcGMJz8PZsCqvosJBAxbDd57HGJXVmt9xmwxaLTuhPFD34LXNdnoLGSdW9JrXr1u,yZLQk000F577c6fs905hXcytbyiCT7Cy4PAGpvf08ZUZWFrOsNQ7gx35CgIoPy7XZcW1yvCBmsF68hWec5c1mI66PRxiaVpvQJtrrx1KUSEhZ8SS9qJTQD9QYW44E9KMhA9AC7UySfVjLEOP7oYcgGLq4wFwFGGnrRqijmg2yzbRKXNjgscRoOAAMzcEh9Jl165mxJP3HsaZS8VmsRpLWPzqyugnyXqQtJJU3AtCRrwQJzNinolakIm2kZ3HRISI,ZnXABJqgOzrpzWLwppLQ7siPiDEqyrG5pLTgNZrbiDdynsuixsWgTXFkvAK8ImyXJgATXI6ggmhy0GhUg08mX4dCx2caOhjj20fTrUforAhfq8yDU6n8Ze3UD4yZ0tCnH3XUHdhT9eCUCBDvu8DseAjNRqLNbi0U2NC0QhnhE5qbpR6gggIbSaeYt0Ffss3LwMEPmDGlkUCmI4L8HbBruuolC1GVMOQ4I0xTI7b1IHCQUBzWCof3PVjQaYuzNL7f,DhDB41EGs5R39Q3LhPLCZuqywpdx8ctk6ipd7iVi5gs1cXxE43njoANamKzligCs5BbLofPyOLuca1u8tiyfGuHJxL9sfBoEhmx458LsG214HFD751XLb1xz8273bUcbfteWFF8pOv18ZxA4kvNcdFevWu2oMuj1jFfkj2Rspgh2FaR6poeCfsEoUf24cjOJ9qDezwVWaHGCGmzc2YcIRAyXG23s3DQSsueQ8C0nUo2TExXg8Z0Chly5u6Xm92zH,HY7QB8Ml5DYFR7ZDzfzxSfGYFVF3Bri2TXcJrIfzbpUnnUaPSRyU9tgzRX9EabQCRcC2c4mbRFv7DWe4FVxrkLtTl73EcE7aTsiYcjDP2EPvXEbTUBb2JhlGMQZrasYy3gVtufipnWHDzsDPA1dFzeszRVTP6ihqBgLdZ3qm7hoikLJThR5O6Y4E7ibfDWySDNJHU0ysbUvuUHXUhyC5dYV37I9OxvbykP1AwC9wdK0jhPUa31FDlfwwkE1jKVa2,jCG9UTWtcRYS1ULxzcJLUaGiUV9DiOnjv0uCMUvtMm4ec4viZ8HwXfbkKW4roRa1bygFfPWIUk6ngSMgl1blMKL06YzSawt2f2XN4VgM3CwVz6a8k4porbtCl5Ur6yDsd2q34P4Ko88g2zUvE9I7VXqqEspXlxJfK4hH5RePoGmXoJIJPOxrDfDZBsC3jElHFw6nJwHN2Kzr0nfivzXHdBR8H8GsyfuXd2dDiMVHnd3j49r0Sw4LeffuW4me12MJ,RaGOw3NotfzMEUGmhDGMJKNbemsPj3JedrCUQnnTqJjpakpzp9Tk4tj19cUHRiJMQ2MZT6WqqQJ0Pgg7NI5vZe90xaDyZTcU4p6W2m1XavQXh8LkRfgUAEvICiY7c63TpnvcpKTtsFF1M82NcpL4Z0iZVncIToIvGBFXS2RjNVCcb1UrzsMjkHsxq2WvbWXwuhhoqbGg6LG0QW3Qjgtvj9u59fp9yonanhmv9NEEbWaMzxW6vuMAzGA3DypCd0um,YCTJZt155ZuJMkJhTf78YQYeXym8MtaL44Q7Qy6HRAMAGOeXxECkoQ9d11Jw3h1VonVrbqQZSUGTqYnjf8mUqh6Wc5cfgqH7TiupTWYHaT27x2GqvTXLWRO1I8iPX05bkgzKK269DVzx3MdgF70EmLMt90IjAntRJc4zdllnanrZIFbYzooRuba08t8Z4OFEGoEehG3sPi6uk0CObmWQ3ETk6K04AQ9GwHzkzaQC2D3hoP62JdYKCDpQc6S3EH65,qFfpYDqjGW5szCZxw8n44YOahxzUcwnpwU3BZm6rDwjRjXG79t9GFQfqDu2t5cIUxWzhH8dzD2k8Fh6OBQncPQMxeulnuEXmCiLYAZXmP1JfV2143OBx3QgAkA374kHQg1TpouomCMPvRC6MP9aSFNCMPZTr4s2vZxhnqqJwV6KAIH2K9mQHlPRPlwglNYaKY6VWHoUZ0IbMmx6Hld29cVTDzwFVPvue3w2COliEpDanAs3AA2ybZfUNMZj2x3Gd,ah4QfHQhWfU6A8AOyfavKF3NLznNn1o6S0c2N0YZB2Wwm31n0KZa4nlo6gb9ruPshWVEvN5rDodQ6k6JusZIURB3inThPVILOeb1oBcpt7TgrpEdoznLtSOqK2pJh5o9pvNvdFQHL6dD7WjfDtuZfdKgBuCdhC8BmO4tbKIxe0mjeC2MlmZ7Hk9Y4G81hem9xi9QE5vAQMwMjBaz0Q8fhP1NFfqyogY2KbZqQbFTgfVL6Rzjdr7LPXM6TcPsKrOv,EtAQD6EyVOYq8DlchcmdqN2P4syKCAe1YGu4J4wT4VABY74RTY8FDIxiwEPTzNUAQj6k3T2DysU2I8kRWn7oHQ8ITNeClqwGYiDrZvnWywm9PCI4A06Wl5Vt8P62qWF9uLWlHAdrmXE2L1E9ZW6P5SaNGv7yTxkzxoSZopqWwWEXwjj0FgCvKMKryy2s97bHdy0YymMUB9m4BC9rsDXcK1ioOBlufPLuPMVUHTMmTRCBhGBRtUcZgprBdM7sX0As,3c15JPognY7c3PgCY17RFQii9p5p4QptRvURYRADuAs3rgvRVHGjGcD2ByttjUTofkjBNVr73pbD67qP4ky99kEvO13Fy3hNIcC8sbR9uXYEPL0mdUmar7ninem4NNxQTx8R0Ri5ktA0hH9XAcgu37yPVJcErtPaQ2qlVXTI31T6CDlbIt9hb7xtEhoDISLmR3tXwxBqvlajMrUZc9H2JJegRv1I57V57grCp3m8f33Oezf5iRP3pBNVyVghYEW7,XZFZsFtHkmm0jmN85XYG0ahUHIKwyw0VnIEq6Y9lUElmLPgWyww0lvj6UUo38bUsG3QKtoQeGPg9cIOBjUIuPHkMzEJpP6TboppRU55DslL6LGU1RS96m0KFtIl44oDfTQUvnuNOWYgsRZtGsxsYnB7cwiYXf8d1axXAznE1jD2R5hlwHc1T5riR41BvrCwtXe43S3fjdvSuQY4GPVD6OikudV8UdBnRSwy5GnplaK7g65khn5ZHtiKiX6FyOaPw,4wXv9Bd5EPG3yPjDiEOvF977dnXoeEBjGOCwznTAVgmgFqpLkcdLi01K9IRSr5qyrUnEkQyBpjKCeznQj0tvE5QOPBNq0ixDpvUr80YW8DJOOcMCtilIVdmHSg0ssdIl8f2VCSokKlfA7ya9JBCPiSE8Huo6QZyyvfGlXtfzKL2St687QxMnTd5yOpSDZ1oGUCZhZgQAIKRLVOkQLlnlyLEf4dDSArAJfqH59QqS10ihysLOXnoTULv98vtxEQa6,SRDw5sWgtPUVWLqWK7xzfFRvEIdhwrnfusbz4jrGtkp58gBFnQ7UwLSXvhGzGRy96HbNMvJp9ImX4bCteBOmSXIRF1VHEsZHFS9jv6iYaXEfipBstR9e39VZRojCd5KEURoT04OLc1KmfSaxeBxgKEUWff6ushlyx0jVO0y7uPfuPHxkDCOqhV2NHZrIDJYZWIEWjzqs5sEtB7dfpBkovpK2JjBwgWXpDZfAIxYH7WQpwnxjZDo2OldzYX8NikS6,Nbo4zNL76AtndFdHgQr8gKwYn0WjvUW7qrAmRDGU47zGfnXCdeUo9aFjyFDd58SbHPfHNuaq10dxrf5wHlsxT5GOrPR4LRNldFmtgerZg1VQRAgN7QBXjzjHENZc9CA3gEx2j8GfiUO138tQ9vwaB6rnUrCl5oFd8y5lctKcqwPOek9yk21Q1Anirp3NKRyz6ddz187YbXcbRtervhyNE1T5vrCIR6ZiuAczTucZtEJX55LHA53PhLxnIanUpcij,QzZykLCOwgcXlerIy9cXSMZeiWjLJbXGMvpIE209bh7Fzb5yLOT8WVc1Kk3IZ3wEa5Yaul8DCPPbvguQHgYAruJ3OniAlVGblicNPc73Z4QBom9xXHzD0MpFRGmYAyHyswYCUwfLEBzESXuWMwfupYozxWjmNqs8zEctf8RzkO7nPSP232zdtUXcIREs6pkrWiD8wonBdFI1iliCduBcG8CdEWVVCKfr4ybyPZpwA4sCYbFXlAeyl62UqpFXHlWT,SaKHfhvzsBiPVFI0ioV0AmCyudMoaj1y5nH1OnmM0jiKrHZ33qBF6cyYhnmzaGlcZmyAkzWVNglrLDFhw1DoAz64dwvY9JkJcv917FFLYXeD2ELJuDZk6upJPaLsg4BtgHG5uAKlGsxpiozs3lko0C6uga04Slj6UiBSAIwtn6KrYFAq1vRhoRN14wqRdZmNM4gVXAEkzqRRFMfrn9QK5CZyIhiD6ZtyI1Jtq7TyWVcKNJ0pUI4HLhn9ejZlvhKn,39vepsHPPVa2KJ03kG8mz76sqOSpuK3xQUy13f2y11PqUhghrRZjVIjai2faK5P10eXFeKEkUi7JQK'
2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [6, 9, 10]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [6, 10]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,# teardown
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [6]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:40:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:40:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:A7A20DB4-FB47-4900-98BA-D663B3798342
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62860
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "5284E402-404F-461B-A0AD-E6A5CA3CD24A", generation: 0)
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GhzEodOmbZNPaokYdnSvwNlRpF4X2j6d","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C3F589B-2F89-4B10-812A-A7D414D9EF9E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "90F04B47-253B-44D4-BB34-B5C287986AB0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:90F04B47-253B-44D4-BB34-B5C287986AB0
,2017-07-27 09:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:40:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FABC8F34-5629-46DF-90BC-859367EC0792
[ThaliCore] Browser.startListening
,2017-07-27 09:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:40:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-27 09:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
[ThaliCore] Session.deinit peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
2017-07-27 09:40:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9","generation":0}'
2017-07-27 09:40:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9, (syncValue: CPe0tCsuFZ7eMhlaBbahW10SaUFxf6SO)'
2017-07-27 09:40:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2,A7CD9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90F04B47-253B-44D4-BB34-B5C287986AB0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90F04B47-253B-44D4-BB34-B5C287986AB0", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E27FBB5D-EE77-449F-841C-C5B2D7938662","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F597521-BA0A-4144-A2E4-1D226FF5B49F","generation":0}'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:64,B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:64B3EA7D,-E3EE-4014-B73C-A9EA8C2A7CD9 error: max retries exceeded
2017-07-27 09:40:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CPe0tCsuFZ7eMhlaBbahW10SaUFxf6SO","error":"Connection could not be established","portNumber":null}'
2017-0,7-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CPe0tCsuFZ7eMhlaBbahW10SaUFxf6SO', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:40:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E27FBB5D-EE77-449F-841C-C5B2D7938662 (syncValue: GxDpvOr,Us122zwQRq5mSm2ed04dVbgqR)'
2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E27FBB5D-EE77,-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62882
2017-07-27 09:40:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GxDpvOrUs122zwQRq5mSm2ed04dVbgqR",,"error":null,"portNumber":62882}'
2017-07-27 09:40:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GxDpvOrUs122zwQRq5mSm2ed04dVbgqR', error: 'null', listeningPort: '62882''
,Connecting to the localhost:62882
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [6, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:62882
,2017-07-27 09:40:29 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-27 09:40:29 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 99 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B0AE0244-121A-44D7-981A-7E0E70E76DA2
[ThaliCore] Advertiser: session connected Peer(uuid: "90F04B47-253B-44D4-BB34-B5C287986AB0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B0AE0244-121A-44D7-981A-7E0E70E76DA2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B0AE0244-121A-44D7-981A-7E0E70E76DA2
,[ThaliCore] Session.session(_:peer:didChange:) peer:B0AE0244-121A-44D7-981A-7E0E70E76DA2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B0AE0244-121A-44D7-981A-7E0E70E76DA2
[ThaliCore] Session.startOutputStream(with:) peer:B0AE0244-121A-44D7-981A-7E0E70E76DA2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,2 [6, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-27 09:40:37 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-27 09:40:37 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-27 09:40:37 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-27 09:40:37 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-27 09:40:37 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeS,treams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [6, 11]
,2017-07-27 09:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:40:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:90F04B47-253B-44D4-BB34-B5C287986AB0
2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:E27FBB5D-EE77-449F-841C-C5B2D7938662
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62882
[ThaliCore] Session.disconnect() p,eer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:B0AE0244-121A-44D7-981A-7E0E70E76DA2 state: connected -> notConnected
[ThaliCore] Adv,ertiser: session notConnected Peer(uuid: "90F04B47-253B-44D4-BB34-B5C287986AB0", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.dis,connectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B0AE0244-121A-44D7-981A-7E0E70E76DA2
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:B0AE0244-121A-44D7-981A-7E0E70E76DA2
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:61237622-BEF2-4351-A24C-AE880E588319
,2017-07-27 09:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6BC3BD79-DB14-472E-B488-45998FA9E58F
[ThaliCore] Browser.startListening
2017-07-27 09:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
2017-07-27 09:40:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E27FBB5D-EE77-449F-841C-C5B2D7938662","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E27FBB5D-EE77-449F-841C-C5B2D7938662 (syncValue: beF6fgkfqrVCNX1zdfQ0rv9vpw2W4JSA)'
2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2,7FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D028B2EF-4493-4F02-B3B2-E9956CFE8164","generation":0}'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61237622-BEF2-4351-A24C-AE880E588319:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D", generation: 0)
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D","generation":0}'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A15260A5-8C04-447A-AE83-D766D3C971EB
[ThaliCore] Advertiser: session connected Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A15260A5-8C04-447A-AE83-D766D3C971EB state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E2,7FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:40:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"beF6fgkfqrVCNX1zdfQ0rv9vpw2W4JSA","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:40:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'beF6fgkfqrVCNX1zdfQ0rv9vpw2W4JSA', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:40:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:40:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D028B2EF-4493-4F02-B3B2-E9956CFE8164 (syncValue: phyqza2lZ1GPqP68GGOHhrE,1TMbJyf6V)'
2017-07-27 09:40:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:40:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A15260A5-8C04-447A-AE83-D766D3C971EB
,[ThaliCore] Session.session(_:peer:didChange:) peer:A15260A5-8C04-447A-AE83-D766D3C971EB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A15260A5-8C04-447A-AE83-D766D3C971EB
,[ThaliCore] Session.startOutputStream(with:) peer:A15260A5-8C04-447A-AE83-D766D3C971EB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [6, 11, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (36935 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received (7796 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13,
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.soc,ketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [6, 11]
2017-07-27 09:40:47 - DEBUG ,testThaliMobileNative: 'Server data flushed'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62896
,2017-07-27 09:40:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"phyqza2lZ1GPqP68GGOHhrE1TMbJyf6V","error":null,"portNumber":62896}'
,2017-07-27 09:40:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'phyqza2lZ1GPqP68GGOHhrE1TMbJyf6V', error: 'null', listeningPort: '62896''
,Connecting to the localhost:62896
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [6, 11, 14]
,Connected to the localhost:62896
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 102 got the same data back
,# teardown
,2017-07-27 09:40:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 ,09:40:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-27 09:40:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:61237622-BEF2-4351-A24C-A,E880E588319
2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62896
[ThaliCore] Session.disconnect() p,eer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A15260A5-8C04-447A-AE83-D766D3C971EB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A15260A5-8C04-447A-AE83-D766D3C971EB
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:A15260A5-8C04-447A-AE83-D766D3C971EB
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F4EC8ABF-9651-4E51-A4EB-1008683F3A0E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F4EC8ABF-9651-4E51-A4EB-1008683F3A0E
2017-07-27 0,9:40:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:40:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:474D4190-FAB4-4D7E-905F-AE7F838269B1
[ThaliCore] Browser.startListening
2017-07,-,27 09:40:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:40:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F4EC8ABF-9651-4E51-A4EB-1008683F3A0E
,2017-07-27 09:40:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:40:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:40:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:40:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:40:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
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
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:40:57 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DB7875ED-9648-4088-B2F7-02BE8F60A834
[ThaliCore] Browser.startListening
ok 107 discoveryActive should be false
ok 108 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1D321AAA-D6B6-4306-A6F7-35BA2CAAC7D4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1D321AAA-D6B6-4306-A6F7-35BA,2CAAC7D4
ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1D321AAA-D6B6-4306-A6F7-35BA2CAAC7D4
ok 113 discoveryActive should be false
ok 114 advertisingActive should be true
,ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-27 09:41:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:00 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-27 09:41:01 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-27 09:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-27 09:41:01 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-27 09:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-27 09:41:02 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-27 09:41:03 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:41:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:41:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:41:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:b1c4d0fd-aa69-4844-9eb4-49d0d815198d error: startListeningNotActive
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"H2E1ovK1QQsmkluan0GAXRtF1Rm7hSwL","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 129 Should only get called after multiConnect returned
,ok 130 SyncValue matches
,ok 131 Got right error
,ok 132 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:06 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:31D1BF04-E235-478E-9896-581095372EC4
[ThaliCore] Browser.startListening
2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:41:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 No error on star,ting
ok 134 Got null as expected
2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"txKOwMcm2BqJPHl5R03TUZ3bZFJ70Gky","error":"Illegal peerID","portNumber":null}'
ok 135 Should only get called after multiConnect ,r,eturned
,ok 136 SyncValue matches
,ok 137 Got right error
,ok 138 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
# teardown
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"043B6E7B-5BF1-4D4E-A18A-4039818E34E6","generation":0}]'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"043B6E7B-5BF1-4D4E-A18A-4039818E34E6","generation":0}'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-27 09:41:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:41:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:08 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C15923E6-F7A2-44C9-92B8-A627F9CF1367
[ThaliCore] Browser.startListening
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on star,ting
,ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27, 09:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-27 09:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:10 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:367eb96e-53e4-4951-82a3-d40588bff115
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E4673876-CD79-4B66-A02B-FE40C77AED43
2017-07-27 0,9:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CEBD3BAD-7736-47D6-AA03-A37F3F1EE6F2
[ThaliCore] Browser.startListening
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
2017-07-27 09:41:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"043B6E7B-5BF1-4D4E-A18A-4039818E34E6","generation":0}'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 043B6E7B-5BF1-4D4E-A18A-4039818E34E6 (syncValue: nvb97cYCTiBdFjruZ5wJ2YUblscguhwV)'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68","generation":0}'
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E4673876-CD79-4B66-A02B-FE40C77AED43:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
2017-07-27 09:41:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8205ADF4-3323-4842-8B88-4588EAF9E8A1","generation":0}'
2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:41:12 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:04,3B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,43B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:41:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nvb97cYCTiBdFjruZ5wJ2YUblscguhwV","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:41:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nvb97cYCTiBdFjruZ5wJ2YUblscguhwV', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:41:14 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:41:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68 (syncValue: Zg3r1vGyNJHyGhofaGvLWDs,3CX3zK35u)'
2017-07-27 09:41:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A,6D73C68:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:41:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62905
2017-07-27 09:41:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Zg3r1vGyNJHyGhofaGvLWDs3CX3zK35u",,"error":null,"portNumber":62905}'
2017-07-27 09:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Zg3r1vGyNJHyGhofaGvLWDs3CX3zK35u', error: 'null', listeningPort: '62905''
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket,:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
,ok 145 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) found active relay
2017-07-27 09:41:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WP4IQFUvvrazDnT3uV7dkLQ4JT3O4bjG","error":null,"portNumber":62905}'
ok 146 No error
ok 147 Ports equal
,ok 148 Got null as expected
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [6, 11, 14, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) found active relay
,2017-07-27 09:41:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"clI4LduibEEBKCQe3HDrLNAoGFEnIsYD","error":null,"portNumber":62905}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4B01804B-5851-4C3A-B1D3-915D446925C1
[ThaliCore] Advertiser: session connected Peer(uuid: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4B01804B-5851-4C3A-B1D3-915D446925C1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4B01804B-5851-4C3A-B1D3-915D446925C1
,[ThaliCore] Session.session(_:peer:didChange:) peer:4B01804B-5851-4C3A-B1D3-915D446925C1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B01804B-5851-4C3A-B1D3-915D446925C1
[ThaliCore] Session.startOutputStream(with:) peer:4B01804B-5851-4C3A-B1D3-915D446925C1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [6, 11, 14, 15, 16]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-27 09:41:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:E4673876-CD79-4B66-A02B-FE40C77AED43
2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09,:[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCP,Client.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.close,Streams() vsID:16
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [6, 11, 14, 15]
41:26 - INFO thaliMobile: 'Filtered out disc,overyAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62905
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:15 [6, 11, 14]
,[ThaliCore] Session.disconnect() peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
,[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4B01804B-5851-4C3A-B1D3-915D446925C1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4B01804B-5851-4C3A-B1D3-915D446925C1
2017-07-27 09:41:2,6 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4B01804B-5851-4C3A-B1D3-915D446925C1
,# initial peer discovery
,2017-07-27 09:41:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-27 09:41:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-27 09:41:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-27 09:41:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'listening 62909'
,ok 151 Should throw
,# teardown
,2017-07-27 09:41:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:29 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'listening 62911'
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:30 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:30 - DEBUG createNativeListener: 'listening 62914'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'listening 62918'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
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
2017-07-27 09:41:31 - DEBUG createNativeListener: 'listening 62923'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
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
2017-07-27 09:41:31 - DEBUG createNativeListener: 'listening 62927'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'listening 62931'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'listening 62935'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'listening 62939'
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
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
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
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'listening 62991'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 181 we should not have gotten an error
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 183 server should be fine
,ok 184 server should be open
,ok 185 incoming has been removed
,ok 186 The mux object should be closed
,ok 187 The mux stream should be closed
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'listening 62995'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 195 serversManager must not be null
,ok 196 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 197 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:35 - DEBUG createNativeListener: 'listening 62998'
ok 198 port must be in range
,# teardown
,2017-07-27 09:41:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:35 - DEBUG createNativeListener: 'listening 62999'
,ok 199 second start should return same port
,# teardown
,2017-07-27 09:41:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'listening 63001'
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should be connected
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 now we are disconnected
,2017-07-27 09:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-27 09:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-27 09:41:36 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 202 Passed bogus id
,2017-07-27 09:41:36 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 203 Passed good id but bogus port
,2017-07-27 09:41:36 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 63003
,ok 209 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:36 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Me,thod peerAvailabilityChanged registered to native'
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F2620B9A-00C1-4B34-8AA8-6CE552013511
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824
,[ThaliCore] Browser.startListening
2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68","generation":0}'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68 (syncValue: MTnazdBMI8jei42YezjSzM7Bd1HHkTI7)'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8205ADF4-3323-4842-8B88-4588EAF9E8A1","generation":0}'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D","generation":0}'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6EA0C969-35BA-462D-8165-A0BABFC74371","generation":0}'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BC9BDDF8-215E-43EF-9BEA-8B22BA7ACE4C
[ThaliCore] Advertiser: session connected Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BC9BDDF8-215E-43EF-9BEA-8B22BA7ACE4C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,2ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BC9BDDF8-215E-43EF-9BEA-8B22BA7ACE4C
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC9BDDF8-215E-43EF-9BEA-8B22BA7ACE4C state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,2ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:878DACE9-3741-43AD-9FBE-AB693BD154B7
[ThaliCore] Advertiser: session connected Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:878DACE9-3741-43AD-9FBE-AB693BD154B7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
,[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68 error: ma,x retries exceeded
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:878DACE9-3741-43AD-9FBE-AB693BD154B7
,2017-07-27 09:41:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MTnazdBMI8jei42YezjSzM7Bd1HHkTI7","error":"Connection could not be established","portNumber":null}'
,2017-07-27 09:41:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MTnazdBMI8jei42YezjSzM7Bd1HHkTI7', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:41:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-27 09:41:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8205ADF4-3323-4842-8B88-4588EAF9E8A1 (syncValue: 14xJkrTuVGN03hYw8yYwjx5L26FCIZRm)'
,2017-07-27 09:41:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-27 09:41:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Session.session(_:peer:didChange:) peer:878DACE9-3741-43AD-9FBE-AB693BD154B7 state: connecting -> connected
2017-07-27 09:41:48 - DEBUG thaliMobileNativ,eTestUtils: 'Already running test!'
,2017-07-27 09:41:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:82,05ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:82,05ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:41:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14xJkrTuVGN03hYw8yYwjx5L26FCIZRm","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:41:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '14xJkrTuVGN03hYw8yYwjx5L26FCIZRm', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-27 09:41:53 - ERROR thaliMobileNativeTestUti,ls: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:41:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D (syncValue: zGscqeo1eWegNB4ps8Cvoftg5H6KBbVA)'
2017-07-27 09:41:53 - DEBUG thaliMobile,NativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sess,ionConnected:sessionNotConnected:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserRelay.init(session:ge,neration:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:41:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:41:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63022
2017-07-27 09:41:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zGscqeo1eWegNB4ps8Cvoftg5H6KBbVA",,"error":null,"portNumber":63022}'
2017-07-27 09:41:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zGscqeo1eWegNB4ps8Cvoftg5H6KBbVA', error: 'null', listeningPort: '63022''
,ok 212 should be equal
,2017-07-27 09:41:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6EA0C969-35BA-462D-8165-A0BABFC74371 (syncValue: oXNDzw6T52YAPiNZGYLLdjEDQTvFAmDm)'
,2017-07-27 09:41:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:41:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63026
2017-07-27 09:42:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oXNDzw6T52YAPiNZGYLLdjEDQTvFAmDm",,"error":null,"portNumber":63026}'
2017-07-27 09:42:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oXNDzw6T52YAPiNZGYLLdjEDQTvFAmDm', error: 'null', listeningPort: '63026''
,ok 213 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 ,09:42:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-27 09:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F2620B9A-00C1-4B34-8AA8-6CE552013511
,2017-07-27 09:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63022
[ThaliCore] Session.disconnect() peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC9BDDF8-215E-43EF-9BEA-8B22BA7ACE4C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:878DACE9-3741-43AD-9FBE-AB693BD154B7
,[ThaliCore] Session.deinit peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:6EA0C969-35BA-462D-8165-A0BABFC74371
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63026
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,2017-07-27 09:42:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:878DACE9-3741-43AD-9FBE-AB693BD154B7
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oXNDzw6T52YAPiNZGYLLdjEDQTvFAmDm","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 63028
,ok 214 should be equal
,ok 215 should be equal
,ok 216 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E0ECECFD-99D4-4837-84C7-C4E68676530E
2017-07-27 0,9:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:42:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1
[ThaliCore] Browser.startListening
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-27 09:42:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
2017-07-27 09:42:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6EA0C969-35BA-462D-8165-A0BABFC74371","generation":0}'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6EA0C969-35BA-462D-8165-A0BABFC74371, (syncValue: 1gUZrQIegLJ7OaH92gMcBjU6wdMsPBAX)'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC,74371", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo,:) found peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D","generation":0}'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
2017-07-27 09:42:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}'
2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:42:03 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
2017-07-27 09:42:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}'
2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:42:03 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,A0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:42:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1gUZrQIegLJ7OaH92gMcBjU6wdMsPBAX","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:42:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1gUZrQIegLJ7OaH92gMcBjU6wdMsPBAX', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:42:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:42:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D (syncValue: vCVfKZBMUAHaRmK2MsZ9uqv,lk4VgUhuC)'
2017-07-27 09:42:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00,E3CBC3D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:42:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:42:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A0,FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A0,FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FBE91978-6593-4C2C-80BD-6B5270525409
[ThaliCore] Advertiser: session connected Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FBE91978-6593-4C2C-80BD-6B5270525409 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FBE91978-6593-4C2C-80BD-6B5270525409
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FBE91978-6593-4C2C-80BD-6B5270525409 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A0,FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:A0FCD6E9,-33DE-4B08-AA31-5AA00E3CBC3D error: max retries exceeded
2017-07-27 09:42:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vCVfKZBMUAHaRmK2MsZ9uqvlk4VgUhuC","error":"Connection could not be established","portNumber":null}'
2017-0,7-27 09:42:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vCVfKZBMUAHaRmK2MsZ9uqvlk4VgUhuC', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:42:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-27 09:42:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E7703811-CCCA-4D64-BE3F-2CE0B9423AE0 (syncValue: XuP6EGX,FnG3Ir4XWRLRrlftcaDC54rMa)'
2017-07-27 09:42:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E7703811-CCCA,-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:42:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:42:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63048
2017-07-27 09:42:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XuP6EGXFnG3Ir4XWRLRrlftcaDC54rMa","error":null,"portN,umber":63048}'
,2017-07-27 09:42:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XuP6EGXFnG3Ir4XWRLRrlftcaDC54rMa', error: 'null', listeningPort: '63048''
,ok 219 should be equal
,ok 220 should be equal
,ok 221 should be equal
,2017-07-27 09:42:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F26BEBDA-8461-458A-80B4-5C81D72A6F32 (syncValue: BmdFJjudiyasenNa5nreUH1sVUhvRucm)'
,2017-07-27 09:42:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-27 09:42:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD
[ThaliCore] Advertiser: session connected Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63055
,2017-07-27 09:42:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BmdFJjudiyasenNa5nreUH1sVUhvRucm","error":null,"portNumber":63055}'
,2017-07-27 09:42:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BmdFJjudiyasenNa5nreUH1sVUhvRucm', error: 'null', listeningPort: '63055''
,ok 222 should be equal
,ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD
,[ThaliCore] Session.session(_:peer:didChange:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 ,09:42:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-27 09:42:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E0ECECFD-99D4-4837-84C7-C,4E68676530E
2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63048
[ThaliCore] Session.disconnect() p,eer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FBE91978-6593-4C2C-80BD-6B5270525409 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
,[ThaliCore] Session.deinit peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63055
[ThaliCore] Session.disconnect() peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD
,[ThaliCore] Session.deinit peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:42:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-27 09:42:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 229 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,# should be able to call #startListeningForAdvertisements many times
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'listening 63059'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:89347AD0-1386-42BB-84A4-B1746D1A4349
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:30 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-27 09:42:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'listening 63060'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9B6445C9-E30D-4473-AC73-EA85DCF7FA6F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9B6445C9-E30D-4473-AC73-EA85DCF7FA6F
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9B6445C9-E30D-4473-AC73-EA85DCF7FA6F", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:9B6445C9-E30D-4473-AC73-EA85DCF7FA6F
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:9B6445C9-E30D-4473-AC73-EA85DCF7FA6F
,[ThaliCore] Advertiser.stopAdvertising() peerID:9B6445C9-E30D-4473-AC73-EA85DCF7FA6F
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-27 09:42:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
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
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'listening 63063'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
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
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
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
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'listening 63064'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E88F20D3-F455-40A1-9B26-5338E68B3027
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B5430BC7-77BD-4B39-AA19-D9D60BA2814C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B5430BC7-77BD-4B39-AA19-D9D60BA2814C
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
[,ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
,ok 243 all connection succeed
,# teardown
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}]'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}]'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B5430BC7-77BD-4B39-AA19-D9D60BA2814C
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:32 - I,NFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":,null}})'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-27 09:42:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'listening 63067'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8F5749B9-561D-4D53-857D-068B108B0462
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F869D043-2B47-4712-9BC4-91B876D3D9CC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F869D043-2B47-4712-9BC4-91B876D3D9CC
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E7703811-CCCA-4D64-,BE3F-2CE0B9423AE0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}]'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F869D043-2B47-4712-9BC4-91B876D3D9CC
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
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
,# all services are stopped when we call stop
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'listening 63069'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FE88E28F-AB72-420C-9C4D-F4B0E634F293
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A9BFC631-DC0E-4BDC-ADCC-891B4465D30E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A9BFC631-DC0E-4BDC-ADCC-891B4465D30E
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:A9BFC631-DC0E-4BDC-ADCC-891B4465D30E
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
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
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:34 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
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
,# make sure terminateListener is properly hooked up
,2017-07-27 09:42:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
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
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
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
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:35 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-27 09:42:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
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
,ok 259 must be stopped
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
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-27 09:42:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
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
,ok 264 must be stopped
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
,# peer changes handled from a queue
,2017-07-27 09:42:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
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
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-27 09:42:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-27 09:42:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
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
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'listening 63072'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7A07B01C-81F6-4E7A-8B57-9066E7102F26
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-27 09:42:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'listening 63073'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4ED9C9F9-90B4-4628-BBCA-3E7742B211F5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4ED9C9F9-90B4-4628-BBCA-3E7742B211F5
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4ED9C9F9-90B4-4628-BBCA-3E7742B211F5
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'listening 63075'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
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
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'listening 63076'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:44FD94BE-B506-4DCB-BEFB-15ECF1E6BD1B
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "51E3490C-357,1-426B-910E-CC3E35165F7B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:51E3490C-3571-426B-910E-CC3E35165F7B
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
2017-07-27 09:42:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}]'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}]'
2017-07-27 09:42:40 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}]'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:51E3490C-3571-426B-910E-CC3E35165F7B
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-27 09:42:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
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
,# calls correct starts when network changes
,2017-07-27 09:42:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
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
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'listening 63078'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:73929F52-4D39-4C39-A307-4B21AE2B67D2
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6ECF630A-A1AB-4826-8FC0-E527CADCE577
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:42:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}]'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}]'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96 (syncValue: gnwT32c4sTzyjTOBAMo7PCjnqXNrO5jB)'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}]'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}]'
2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:59628830-82CA-4182-B076-3090507B3592
[ThaliCore] Advertiser: session connected Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:59628830-82CA-4182-B076-3090507B3592 state: notConnected -> connecting
2017-07-27 09:42:44 - DEBUG thaliMobileNativeWrapper: 'Received pee,rAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}]'
2017-07-27 09:42:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvaila,ble":true,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}'
,er {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-27 09:42:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-27 09:42:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-27 09:42:44 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:59628830-82CA-4182-B076-3090507B3592
,[ThaliCore] Session.session(_:peer:didChange:) peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97,FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:59628830-82CA-4182-B076-3090507B3592 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:59628830-82CA-4182-B076-3090507B3592
[ThaliCore] Session.startOutputStream(with:) peer:59628830-82CA-4182-B076-3090507B3592
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [6, 11, 14, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
2017-07-27 09:42:47 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}]'
2017-07-27 09:42:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","generation":0}'
,2017-07-27 09:42:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-27 09:42:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:42:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}]'
,2017-07-27 09:42:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}'
,2017-07-27 09:42:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-27 09:42:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gnwT32c4sTzyjTOBAMo7PCjnqXNrO5jB","error":"Peer is unavailable","portNumber":null}'
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gnwT32c4sTzyjTOBAMo7PCjnqXNrO5jB', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:42:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 327545E6-9804-4ADB-A8DA-5253B0B8EB0E (syncValue: oie532k1FF9ReyX2gQ4nuiXDaFA2Qc9A)'
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}]'
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","generation":0}'
,2017-07-27 09:42:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-27 09:42:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E7703811-CCCA-4D64-BE3F-2CE0B9423AE0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.deinit peer:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63085
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:273CA323-F42B-40C3-89D9-73B6D8E9BE06
[ThaliCore] A,dvertiser: session connected Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:273CA323,-F42B-40C3-89D9-73B6D8E9BE06 state: notConnected -> connecting
2017-07-27 09:42:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oie532k1FF9ReyX2gQ4nuiXDaFA2Qc9A","error":null,"portNumber":63085}'
2017-07-27 09:42:51 - DEBUG thal,iMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oie532k1FF9ReyX2gQ4nuiXDaFA2Qc9A', error: 'null', listeningPort: '63085''
,2017-07-27 09:42:51 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [6, 11, 14, 17, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:42:52 - DEBUG testUtils: 'Got response data'
2017-07-27 09:42:52 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:273CA323-F42B-40C3-89D9-73B6D8E9BE06
,[ThaliCore] Session.session(_:peer:didChange:) peer:273CA323-F42B-40C3-89D9-73B6D8E9BE06 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:273CA323-F42B-40C3-89D9-73B6D8E9BE06
,[ThaliCore] Session.startOutputStream(with:) peer:273CA323-F42B-40C3-89D9-73B6D8E9BE06
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [6, 11, 14, 17, 18, 19]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:6ECF630A-A1AB-4826-8FC0-E527CADCE577
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [6, 11, 14, 17, 19]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted, socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] Session.session(_:peer:didChange:) peer:273CA323-F42B-40C3-89D9-73B6D8E9BE06 state: connected -> notConnected
[ThaliCo,re] Advertiser: session notConnected Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [6, 11, 14, 17]
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:273CA323-F42B-40C3-89D9-73B6D8E9BE06
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:nil
[ThaliCore] TCPClient.deinit
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [6, 11, 14]
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63085
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
,[ThaliCore] Session.deinit peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:273CA323-F42B-40C3-89D9-73B6D8E9BE06
,[ThaliCore] Session.session(_:peer:didChange:) peer:59628830-82CA-4182-B076-3090507B3592 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-27 09:42:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:55 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-27 09:42:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-27 09:42:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:42:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:42:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'listening 63089'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'listening 63090'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EF9B8448-C153-4B2D-AB5A-6876EB40A0C8
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 306 error should be null
ok 307 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
,ok 309 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'listening 63091'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8B10439D-E1DF-4A59-A177-9412776E0AAD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8B10439D-E1DF-4A59-A177-9412776E0AAD
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8B10439D-E1DF-4A59-A177-9412776E0AAD", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:8B10439D-E1DF-4A59-A177-9412776E0AAD
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 315 error should be null
,ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8B10439D-E1DF-4A59-A177-9412776E0AAD
,[ThaliCore] Advertiser.stopAdvertising() peerID:8B10439D-E1DF-4A59-A177-9412776E0AAD
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'listening 63094'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
,ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-27 09:42:58 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
,ok 328 native router should be bad
,# teardown
,ok 329 error should be null
,ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-27 09:42:59 - DEBUG thaliMobileNativeWrapper: 'listening 63095'
ok 332 first call should succeed
ok 333 first call should succeed
,ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
,ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-27 09:42:59 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-27 09:42:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
,ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-27 09:42:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"347d9e23-0da6-41fe-8ba1-3b6cd405510c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
ok 345 should not have been called more than once
,# teardown
,2017-07-27 09:42:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"347d9e23-0da6-41fe-8ba1-3b6cd405510c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
,ok 347 error should be null
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
2017-07-27 09:43:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dc4663d3-1d3c-4286-b7da-0a7edc2b6a92","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 354 peer should be available
ok 355 cache contains native peer
2017-07-27 09:43:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dc4663d3-1d3c-4286-b7da-0a7edc2b6a92","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 356 peer should be unavailable
,ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"eae49b2c-7c93-4804-9de8-44ff1c7efa34","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 362 peer should be available
ok 363 cache contains wifi peer
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"eae49b2c-7c93-4804-9de8-44ff1c7efa34","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 364 peer should be unavailable
,ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
,ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d272b224-1445-4a01-b216-e8319fb7241d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"076bda62-1257-463e-88ff-1ce65e5be90d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d272b224-1445-4a01-b216-e8319fb7241d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"076bda62-1257-463e-88ff-1ce65e5be90d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2d3b386e-937a-4b4d-8808-f8cf38b7ddf3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 376 peer is available
,# teardown
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2d3b386e-937a-4b4d-8808-f8cf38b7ddf3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
,ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-27 09:43:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-27 09:43:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
,ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6ef74db2-cec5-4837-a3e6-e22afc59eb1c","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be ,available
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6ef74db2-cec5-4837-a3e6-e22afc59eb1c","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be ,available
ok 388 should store correct generation
,# teardown
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6ef74db2-cec5-4837-a3e6-e22afc59eb1c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
,ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-27 09:43:02 - DEBUG thaliMobileNativeWrapper: 'listening 63096'
2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5c7b682e-6484-4f34-9fa7-3b8bd2807fc6","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5c7b682e-6484-4f34-9fa7-3b8bd2807fc6","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5c7b682e-6484-4f34-9fa7-3b8bd2807fc6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'listening 63097'
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b59efc61-fc54-4f21-8d2b-c975cc5027fa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b59efc61-fc54-4f21-8d2b-c975cc5027fa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
,ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83465206-46d0-4d31-9e01-f3ee7f1a1096","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83465206-46d0-4d31-9e01-f3ee7f1a1096","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 405 peer should be unavailable
,ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'listening 63098'
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dfec477e-8c37-442c-8147-d1de5fee2852","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 first peer is expected to be available
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5a82d1ac-487c-412f-8fb5-a11e636eae76","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 411 second peer is expected to be available
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5a82d1ac-487c-412f-8fb5-a11e636eae76","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5a82d1ac-487c-412f-8fb5-a11e636eae76","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5a82d1ac-487c-412f-8fb5-a11e636eae76","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dfec477e-8c37-442c-8147-d1de5fee2852","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-27 09:43:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-27 09:43:04 - DEBUG thaliMobileNativeWrapper: 'listening 63099'
,2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4d5c36cd-23b3-4bb0-9698-deb5c3a3c731","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 424 first peer is expected to be available
,2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"12485bdf-0895-45b2-9886-6bafd25c78e3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 425 second peer is expected to be available
,2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4d5c36cd-23b3-4bb0-9698-deb5c3a3c731","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"12485bdf-0895-45b2-9886-6bafd25c78e3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-27 09:43:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
,ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-27 09:43:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec6acee1-9912-46fe-ba27-ab204aebf398","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 437 peer discovered ,first time does not have new address
2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec6acee1-9912-46fe-ba27-ab204aebf398","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 438 address has not been changed
2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec6acee1-9912-46fe-ba27-ab204aebf398","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 439 new port handled correctly
,2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec6acee1-9912-46fe-ba27-ab204aebf398","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 440 new host handled, correctly
2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec6acee1-9912-46fe-ba27-ab204aebf398","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 441 new,AddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-27 09:43:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 445 error should be null
,ok 446 error should be null
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
,2017-07-27 09:43:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
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
,2017-07-27 09:43:06 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
,ok 463 the same hostAddress
,ok 464 the same portNumber
,# teardown
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
,ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
,ok 469 the same hostAddress
,ok 470 the same portNumber
,# teardown
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-27 09:43:07 - DEBUG thaliMobileNativeWrapper: 'listening 63100'
2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"27f84a58-437f-4c53-acb5-2433fa040a75","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 474 Got specific error message
,# teardown
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"27f84a58-437f-4c53-acb5-2433fa040a75","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'listening 63101'
,2017-07-27 09:43:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"59788601-6f5d-4978-b7b7-bfe39a7b4243","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:59788601-6f5d-4978-b7b7-bfe39a7b4243
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-27 09:43:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"59788601-6f5d-4978-b7b7-bfe39a7b4243","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-27 09:43:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-27 09:43:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
,ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
,ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
,ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-27 09:43:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'listening 63102'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:40E460E8-D438-4931-9F37-8C11F045F138
,[ThaliCore] Browser.startListening
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cd8ab33a-802f-493f-8502-2fa23d948c49","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9d663527-f69a-4f64-a861-5876a3123201","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cd8ab33a-802f-493f-8502-2fa23d948c49","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9d663527-f69a-4f64-a861-5876a3123201","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-27 09:43:11 - DEBUG thaliMobileNativeWrapper: 'listening 63103'
2017-07-27 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bae6d33b-d626-4850-b3e3-f2657f252d3e","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 512 1
ok 513 2
,2017-07-27 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fdc9e99a-157a-4829-bc53-fce190f2507f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-27 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bae6d33b-d626-4850-b3e3-f2657f252d3e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-27, 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fdc9e99a-157a-4829-bc53-fce190f2507f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-27 09:43:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:43:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:43:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:43:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
,ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-27 09:43:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'listening 63104'
,ok 520 error should be null
,ok 521 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7855F8AD-79AD-4F93-83C6-37C069A6A92D
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] Browser.startListening
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}]'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}]'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 97AC027D-E887-4A31-AA7D-B254708661C6 (syncValue: 0)'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0)
2017-07-27 09:43:13 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","generation":0}]'
2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","generation":0}'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","generation":0}]'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","generation":0}'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}]'
,2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}'
,2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}]'
,2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","generation":0}'
,2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-27 09:43:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-27 09:43:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"327545E6-9804-4ADB-A8DA-5253B0B8EB0E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
[ThaliCore] Advertiser: session connected Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:97AC027D-E887-4A31-AA7D-B254708661C6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,7AC027D-E887-4A31-AA7D-B254708661C6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:43:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
,2017-07-27 09:43:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 327545E6-9804-4ADB-A8DA-5253B0B8EB0E (syncValue: 1)'
2017-07-27 09:43:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", ge,neration: 0)
,[ThaliCore] Session.deinit peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:43:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":"Peer is unavailable","portNumber":null}'
2017-07-2,7 09:43:16 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F1A16AEB-67F5-4902-8B82-F7A5D25F38D1 (syncValue: 2)'
2017-07-27 09:43:16 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncV,alue:retryCount:completion:) Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation:, 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
[ThaliCore] Advertiser: session connected Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63110
,2017-07-27 09:43:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":63110}'
,2017-07-27 09:43:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3630E379-CFFE-462E-BB68-4CD97BA5BD0F (syncValue: 3)'
,2017-07-27 09:43:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
[ThaliCore] Session.startOutputStream(with:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,0 [6, 11, 14, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [6, 11, 14, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0 state: notConnected -> connecting
,2017-07-27 09:43:19 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:43:19 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
,[ThaliCore] Session.session(_:peer:didChange:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
[ThaliCore] Session.startOutputStream(with:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,2 [6, 11, 14, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63116
,2017-07-27 09:43:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":63116}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [6, 11, 14, 20, 21, 22, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:43:21 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:43:21 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,2017-07-27 09:43:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F1A16AEB-67F5-4902-8B82-F7A5D25F38D1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-27, 09:43:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7855F8AD-79AD-4F93-83C6-37C069A6A92D
2017-07-27 09:43:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-27 09:43:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-27 09,:43:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:43:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27, 09:43:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
,[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSo,cketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:22 [6, 11, 14, 20, 21,, 23]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
,[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:20 [6, 11, 14, 21, 23]
,ok 527 error should be null
,ok 528 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [6, 11, 14, 23]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socke,t removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-27 09:43:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 530 error should be null
,ok 531 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 532 getPeerIdentifier
,ok 533 getConnectionType
,ok 534 getActionType
,ok 535 getActionState
,ok 536 getPskIdentity
,ok 537 getPskKey
,# teardown
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [6, 11, 14]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket ,error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# #testThaliPeerAction - start and kill
,ok 538 initial state
ok 539 after start
2017-07-27 09:43:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-27 09:43:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
,ok 550 Entry exists
,ok 551 Size must be 1
,ok 552 Entry counter must be 2
,ok 553 Entry exists
,ok 554 Size must be 2
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
,ok 574 Entries between 20 and MAXSIZE + 20 should exist
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
,ok 584 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 585 is an agent
ok 586 enqueue is fine
ok 587 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 588 is an agent
ok 589 first enqueue is fine
ok 590 is an agent
ok 591 second enqueue is fine
ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
,ok 595 good enqueue
,ok 596 Identity should match
,2017-07-27 09:43:38 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:43:38 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-27 09:43:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 599 is an agent
ok 600 enqueue worked
ok 601 is an agent
ok 602 enqueue 2 worked
,ok 603 enqueue is not available when stopped
,ok 604 start action is killed
,ok 605 killed action is still killed
,ok 606 enqueued action when stopped is killed
,ok 607 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 608 good start
ok 609 good enqueue
ok 610 queue is not empty
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
,ok 617 2nd good enqueue
,ok 618 we are in the pool
,ok 619 We are out of the pool
,ok 620 Action was killed
,ok 621 The original kill was called too
,ok 622 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 623 good enqueue
,ok 624 first kill
,ok 625 second NOOP kill
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
,2017-07-27 09:43:42 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-27 09:43:43 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 636 Got right error
,ok 637 Start should not be called
,ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 639 Got null
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 640 is an agent
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 642 Got Null
,ok 643 Got another null
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 644 is an agent
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 649 should have gotten null
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-27 09:43:44 - DEBUG thaliPeer,PoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 650 Should have stopped nicely
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 654 Null 1
,ok 655 (unnamed assert)
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 656 is an agent
,ok 657 Null 3
,ok 658 Replication not yet called
,ok 659 Notification 2 not yet called
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 666 is an agent
,ok 667 First does not throw
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 668 is an agent
,ok 669 Second does not throw
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
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
,ok 675 peerIdentifier should match
,ok 676 generation should match
,ok 677 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 678 good beacon
,ok 679 good preAmble
,ok 680 public keys match!
,ok 681 must return null after successful call
,ok 682 Once start returns the action should be in KILLED state
,# teardown
,2017-07-27 09:43:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-27 09:43:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-27 09:43:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
,ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-27 09:43:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
,ok 686 correct error message
,# teardown
,2017-07-27 09:43:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-07-27 09:43:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-27 09:43:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-07-27 09:43:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-27 09:43:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-07-27 09:43:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-27 09:43:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
,ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-27 09:43:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 702 publicKeysToNotify cannot be null
,ok 703 ecdh for local device cannot be null
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
,2017-07-27 09:44:03 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
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
ok 732 keys match
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
,2017-07-27 09:44:08 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-27 09:44:08 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-27 09:44:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
,2017-07-27 09:44:09 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-27 09:44:09 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-27 09:44:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-07-27 09:44:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
,ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-27 09:44:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-27 09:44:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-27 09:44:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-27 09:44:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-27 09:44:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-27 09:44:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-27 09:44:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-27 09:44:13 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-07-27 09:44:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-27 09:44:16 - WARN thaliNotificationClient: 'peer is not available'
2017-07-27 09:44:16 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-07-27 09:44:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-27 09:44:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
ok 771 peer state should be RESOLVED
,# teardown
,2017-07-27 09:44:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-27 09:44:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
# teardown
,2017-07-27 09:44:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-27 09:44:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-27 09:44:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-27 09:44:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
,ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-27 09:44:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-27 09:44:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-07-27 09:44:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-27 09:44:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-27 09:44:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
,ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
,ok 803 should be 204
,# teardown
,2017-07-27 09:44:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
,ok 805 should be 204
,# teardown
,2017-07-27 09:44:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-27 09:44:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
,ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-27 09:44:27 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-27 09:44:28 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-27 09:44:29 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-27 09:44:29 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-27 09:44:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-27 09:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-27 09:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-27 09:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-27 09:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-27 09:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-27 09:44:32 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-27 09:44:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-27 09:44:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-27 09:44:35 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-27 09:44:35 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-27 09:44:37 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-27 09:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-27 09:44:39 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-27 09:44:40 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-27 09:44:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-27 09:44:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-27 09:44:43 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-27 09:44:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-27 09:44:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-27 09:44:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-27 09:44:47 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-27 09:44:48 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-27 09:44:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-27 09:44:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 860 action should be killed
,ok 861 Error should be timed out
,# teardown
,2017-07-27 09:44:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-27 09:44:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
,ok 864 Same pouchdB
,ok 865 same localDbName
,ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-27 09:44:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-27 09:44:53 - DEBUG thaliMobileNativeWrapper: 'listening 63243'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] Browser.startListening
,2017-07-27 09:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4B93F383-00C0-458F-9A5F-89AA952BC1DA
,2017-07-27 09:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0)
2017-07-27 09:44:54 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"31FA610D-63B5-4DE0-AB0D-AEAF0401113A","generation":0}]'
2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"31FA610D-63B5-4DE0-AB0D-AEAF0401113A","generation":0}'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"31FA610D-63B5-4DE0-AB0D-AEAF0401113A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-27 09:44:54 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"31FA610D-63B5-4DE0-AB0D-AEAF0401113A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 31FA610D-63B5-4DE0-AB0D-AEAF0401113A (syncValue: 4)'
2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "31FA610D-63B5-4DE0,-AB0D-AEAF0401113A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected,:,notConnected:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0)
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3","generation":0}]'
2017-07-27 09:44:54 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3","generation":0}'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:44:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","generation":0}]'
2017-07-27 09:44:54 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","generation":0}'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:44:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Advertiser: session connected Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A199F954-C675-4B5C-AE40-A799E390F491 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Advertiser: session connected Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C07858DB-C444-45BD-90AB-9D83702F7366 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63246
,2017-07-27 09:44:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":63246}'
,2017-07-27 09:44:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3 (syncValue: 5)'
,2017-07-27 09:44:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [6, 11, 14, 24]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:24 [6, 11, 14]
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [6, 11, 14, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:44:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [6, 11, 14, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [6, 11, 14, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [6, 11, 14, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [6, 11, 14, 25, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-07-27 09:44:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] Session.session(_:peer:didChange:) peer:C07858DB-C444-45BD-90AB-9D83702F7366 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:A199F954-C675-4B5C-AE40-A799E390F491 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [6, 11, 14, 25, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [6, 11, 14, 25, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63256
,2017-07-27 09:45:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":63256}'
,2017-07-27 09:45:00 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3630E379-CFFE-462E-BB68-4CD97BA5BD0F (syncValue: 6)'
,2017-07-27 09:45:00 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0) found active relay
,2017-07-27 09:45:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":63116}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [6, 11, 14, 25, 26, 27, 28, 29, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [6, 11, 14, 25, 26, 27, 28, 29, 30, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [6, 11, 14, 25, 26, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPListener.socketDidDisconnec,t(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-27 09:45:00 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [6, 11, 14, 25, 26, 27, 28, 29, 30, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDi,dDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [6, 11, 14, 25, 26, 27, 28, 29, 30, 32, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [6, 11, 14, 25, 26, 27, 28, 29, 32, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [6, 11, 14, 25, 26, 27, 28, 29, 32, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,2017-07-27 09:45:00 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3630E379-CFFE-462E-BB68-4CD97BA5BD0F (syncValue: 7)'
,2017-07-27 09:45:00 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0) found active relay
,2017-07-27 09:45:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":63116}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.deinit vsID:37 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-27 09:45:00 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-27 09:45:00 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36, 38]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:45:01 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3630E379-CFFE-462E-BB68-4CD97BA5BD0F (syncValue: 8)'
,2017-07-27 09:45:01 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0) found active relay
,2017-07-27 09:45:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":63116}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36, 38, 39, 40, 41]
[ThaliCore] BrowserRela,y.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36, 38, 39, 40]
,2017-07-27 09:45:01 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36, 38, 39, 40, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36, 38, 39, 40, 42, 43]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-27 09:45:01 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [6, 11, 14, 25, 26, 27, 28, 29, 34, 35, 36, 38, 39, 40, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-27 09:45:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:25 [6, 11, 14, 26, 27, 28, 29, 34, 35, 36, 38, 39, 40, 42, 43, 44]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:26 [6, 11, 14, 27, 28, 29, 34, 35, 36, 38, 39, 40, 42, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [6, 11, 14, 28, 29, 34, 35, 36, 38, 39, 40, 42, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:29 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,2017-07-27 09:45:01 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3630E379-CFFE-462E-BB68-4CD97BA5BD0F (syncValue: 9)'
,2017-07-27 09:45:01 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0) found active relay
,2017-07-27 09:45:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":63116}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46, 47, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46, 47, 48]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) soc,ket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-27 09:45:01 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-27 09:45:01 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-27 09:45:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
[ThaliCore] Session.startOutputStream(with:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46, 47, 48, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,1 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46, 47, 48, 50, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:47 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46, 48, 50, 51]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46, 50, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:45:03 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3630E379-CFFE-462E-BB68-4CD97BA5BD0F (syncValue: 10)'
2017-07-27 09:45:03 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0) found active relay
2017-07-27 09:45:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":63116}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46, 50, 51, 52]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
,[ThaliCore] VirtualSocket.deinit vsID:52 [6, 11, 14, 28, 34, 35, 36, 38, 39, 40, 42, 43, 44, 45, 46, 50, 51]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) soc,ket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-27 09:45:03 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-27 09:45:03 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-27 09:45:03 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] BrowserRelay.didCloseVir,tualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] VirtualSocket.deinit vsID:36 [6, 11, 1,4, 28, 34, 35, 38, 39, 40, 42, 43, 44, 45, 46, 50, 51]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoo,p vsID:40
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.deinit vsID:40 [6, 11, 14, 28, 34, 35, 38, 39, 42, 43, 44, 45, 46, 50, 51]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [6, 11, 14, 28, 34, 35, 38, 39, 43, 44, 45, 46, 50, 51]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [6, 11, 14, 28, 34, 35, 38, 39, 43, 44, 45, 50, 51]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
,[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:34 [6, 11, 14, 28, 35, 38, 39, 43, 44, 45, 50, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socke,t error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [6, 11, 14, 28, 35, 39, 43, 44, 45, 50, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected,
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:43 [6, 11, 14, 28, 35, 39, 44, 45, 50, 51]
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
,[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [6, 11, 14, 28, 35, 39, 44, 45, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDis,connect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [6, 11, 14, 28, 39, 44, 45, 51]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [6, 11, 14, 28, 44, 45, 51]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [6, 11, 14, 28, 45, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:), disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [6, 11, 14, 28, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:45:05 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3630E379-CFFE-462E-BB68-4CD97BA5BD0F (syncValue: 11)'
2017-07-27 09:45:05 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0) found active relay
2017-07-27 09:45:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":63116}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [6, 11, 14, 28, 45, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
,[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
,[ThaliCore] VirtualSocket.deinit vsID:53 [6, 11, 14, 28, 45]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-27 09:45:06 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63116
[ThaliCore] Session.disconnect() peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:45:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","generation":0}]'
,2017-07-27 09:45:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","generation":0}'
,2017-07-27 09:45:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-27 09:45:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:45:06 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-27 09:47:55 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-27 09:47:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:47:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:47:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:47:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-27 09:54:53 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
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
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
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
    at SubError@/private/var/containers/Bundle/Appl,ication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
2017-07-27 09:54:53 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,not ok 867 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-27 09:55:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-4,87C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487,C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/049DB093-28C7-487C-B8D2-B5EC6906B9A0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
