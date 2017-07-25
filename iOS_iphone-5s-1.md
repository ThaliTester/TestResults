#### Test 13228325722939a4_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/54433D20-D58C-4C87-9A84-45955E4E6476/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/54433D20-D58C-4C87-9A84-45955E4E6476/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60712"
,(lldb)     command script import "/tmp/54433D20-D58C-4C87-9A84-45955E4E6476/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-07-25 16:23:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:23:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:23:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:23:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:23:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:23:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "82F91D89-D7F8-4057-9F03-03D9695651D2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:82F91D89-D7F8-4057-9F03-03D9695651D2
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EE0752AA-F6CD-4DF6-A6E1-6D97DBF987A0
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5F68FEDE-,E087-4E60-BB0F-C0C9263DC6B4
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4E23DDFF-79AF-4753-BD62-707D6FD677EE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4E23DDFF-79AF-4753-BD62-707D6FD677EE
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4E23DDFF-79AF-4753-BD62-707D6FD677EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4E23DDFF-79AF-4753-BD62-707D6FD677EE", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-25 16:23:44 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.562758982181549
201,7-07-25 16:23:44 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-07-25 16:23:44 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4E23DDFF-79AF-4753-BD62-707D6FD677EE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4E23DDFF-79AF-4753-BD62-707D6FD677EE", generation: 0)
,2017-07-25 16:23:47 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-25 16:23:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-25 16:23:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-25 16:23:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-25 16:23:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-25 16:23:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-25 16:23:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-25 16:23:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-25 16:23:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-25 16:23:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-25 16:23:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-25 16:23:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-25 16:23:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-25 16:23:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-25 16:23:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-25 16:23:51 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-25 16:23:51 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-25 16:23:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:23:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:58 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-25 16:23:59 - DEBUG CoordinatedClient: 'connected to the test server'
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
2017-07-25 16:24:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
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
,ok 5 should be equal
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
,2017-07-25 16:24:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-25 16:24:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-25 16:24:18 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:09724ADE-F196-4A1B-B05E-A1F29434D552
[ThaliCore] Browser.startListening
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-25 16:24:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,,"advertisingActive":false}'
2017-07-25 16:24:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
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
,2017-07-25 16:24:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A6E5D2CD-A04B-4055-8547-B56FC99CBDE5
[ThaliCore] Browser.startListening
2017-07-25 16:24:23 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-25 16:24:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-25 16:24:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-25 16:24:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-25 16:24:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:24 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
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
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9F9CA672-4DBC-42F8-8B8B-5B3BC3C47257", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9F9CA672-4DBC-42F8-8B8B-5B3BC3C47257
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9F9CA672-4DBC-42F8-8B8B-5B3BC3C47257
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1F160F75-5A89-4A48-BDA6-630D2FAB358F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1F160F75-5A89-4A48-BDA6-630D2FAB358F
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1F160F75-5A89-4A48-BDA6-630D2FAB358F", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:1F160F75-5A89-4A48-BDA6-630D2FAB358F
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1F160F75-5A89-4A48-BDA6-630D2FAB358F
[ThaliCore] Advertiser.stopAdvertising() peerID:1F160F75-5A89-4A48-BDA6-630D2FAB358F,
2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e,).'
2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:27, - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:30 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7B282771-861D-4DFE-84EC-9BD1796CBBD6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7B282771-861D-4DFE-84EC-9BD1796CBBD6
2017-07-25 1,6:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9B06E35E-24CE-4E50-A6FB-3DE09D163DF6
[ThaliCore] Browser.startListen,ing
2017-07-25 16:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-25 16:24:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true,}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1584D9F-F535-451B-BC16-C39558E5F073:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1584D9F-F535-451B-BC16-C39558E5F073", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0793BEDD-38B1-4AB4-A184-0B8B6241AD5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0793BEDD-38B1-4AB4-A184-0B8B6241AD5C", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 ,16:24:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
,2017-07-25 16:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7B282771-861D-4DFE-84EC-9BD1796CBBD6
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FABBB17E-2F2C-4F1E-8192-036793CA1965
2017-07-25 1,6:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DC8C7BD9-C2BA-4F08-B470-D87E25646211
[Thal,i,Core] Browser.startListening
2017-07-25 16:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:24:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-25 16:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:21A3C260-F346-4981-BED5-324227116BB4
,[ThaliCore] Advertiser: session connected Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:21A3C260-F346-4981-BED5-324227116BB4 state: notConn,ected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
2017-07-25 16:24:45 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58D6DF15-0B01-44D3-B565-43125AB2A311","generation":0}'
2017-07-25 16:24:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 58D6DF15-0B01-44D3-B565-43125AB2A311, (syncValue: oqYYqcFko8iEZsZxuUZaJBxzbZDPG9vM)'
2017-07-25 16:24:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB,2A311", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
2017-07-25 16:24:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D2D0A921-E533-432A-9587-695A643E972C","generation":0}'
2017-07-25 16:24:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:24:46 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD5BBB9F-C625-4B4D-92C2-1F497D66583B
[ThaliCore] Advertiser: session connected Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DD5BBB9F-C625-4B4D-92C2-1F497D66583B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:21A3C260-F346-4981-BED5-324227116BB4
,[ThaliCore] Session.session(_:peer:didChange:) peer:21A3C260-F346-4981-BED5-324227116BB4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61747
,2017-07-25 16:24:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oqYYqcFko8iEZsZxuUZaJBxzbZDPG9vM","error":null,"portNumber":61747}'
,2017-07-25 16:24:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oqYYqcFko8iEZsZxuUZaJBxzbZDPG9vM', error: 'null', listeningPort: '61747''
,2017-07-25 16:24:48 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DD5BBB9F-C625-4B4D-92C2-1F497D66583B
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD5BBB9F-C625-4B4D-92C2-1F497D66583B state: connecting -> connected
,2017-07-25 16:24:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:FABBB17E-2F2C-4F1E-8192-036793CA1965
2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16,:,24:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:58D6DF15-0B01-44D3-B565-43125AB2A311
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61747
,[ThaliCore] Session.disconnect() peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:21A3C260-F346-4981-BED5-324227116BB4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DD5BBB9F-C625-4B4D-92C2-1F497D66583B
,[ThaliCore] Session.deinit peer:DD5BBB9F-C625-4B4D-92C2-1F497D66583B
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.deinit
2017-07-25 16:24:51 - DEBUG thaliMobileNative,Wrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:51 - DEBUG thaliMobileNativeWrapper: 'Method multiCo,nnectResolved registered to native'
,2017-07-25 16:24:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:24:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B7B955AE-E51A-415A-B1E2-A27D544FD210
2017-07-25 1,6:24:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BA32C405-89E2-44A4-BB9D-6FD7F5A71D82
[Thal,iCore] Browser.startListening
2017-07-25 16:24:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-25 16:24:52 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58D6DF15-0B01-44D3-B565-43125AB2A311","generation":0}'
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 58D6DF15-0B01-44D3-B565-43125AB2A311 (syncValue: 5xj4rO4hssmEe0KCba4otNvsfgN13TNS)'
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
2017-07-25 16:24:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DA0E2C5F-B8AB-424C-989C-BDF114DA1928","generation":0}'
2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:24:54 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
2017-07-25 16:24:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A","generation":0}'
2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58,D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,8D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:18D486AE-AFD3-48C7-92E4-8E0F17F10FA6
[ThaliCore] Advertiser: session connected Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:18D486AE-AFD3-48C7-92E4-8E0F17F10FA6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:18D486AE-AFD3-48C7-92E4-8E0F17F10FA6
,[ThaliCore] Session.session(_:peer:didChange:) peer:18D486AE-AFD3-48C7-92E4-8E0F17F10FA6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18D486AE-AFD3-48C7-92E4-8E0F17F10FA6
,[ThaliCore] Session.startOutputStream(with:) peer:18D486AE-AFD3-48C7-92E4-8E0F17F10FA6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-25 16:24:58 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-25 16:24:58 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-25 16:24:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-25 16:24:58 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1,
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58,D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,8D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3DAFDFB3-FFED-447E-8BA5-267430214F0E
[ThaliCore] Advertiser: session connected Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3DAFDFB3-FFED-447E-8BA5-267430214F0E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:58D6DF15-0B01-44D3-B565-43125AB2A311 error: max retries exceeded
,2017-07-25 16:25:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5xj4rO4hssmEe0KCba4otNvsfgN13TNS","error":"Connection could not be established","portNumber":null}'
,2017-07-25 16:25:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5xj4rO4hssmEe0KCba4otNvsfgN13TNS', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-25 16:25:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"58D6DF15-0B01-44D3-B565-43125AB2A311","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:25:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"58D6DF15-0B01-44D3-B565-43125AB2A311","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-25 16:25:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:03 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-25 16:25:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DA0E2C5F-B8AB-424C-989C-BDF114DA1928 (syncValue: EU0vzgyjmVq87dzHOd2MvzWBLr3BtWG3)'
,2017-07-25 16:25:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-25 16:25:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3DAFDFB3-FFED-447E-8BA5-267430214F0E
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3DAFDFB3-FFED-447E-8BA5-267430214F0E state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61754
2017-07-25 16:25:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EU0vzgyjmVq87dzHOd2MvzWBLr3BtWG3",,"error":null,"portNumber":61754}'
2017-07-25 16:25:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EU0vzgyjmVq87dzHOd2MvzWBLr3BtWG3', error: 'null', listeningPort: '61754''
,Connecting to the localhost:61754
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
,Connected to the localhost:61754
,2017-07-25 16:25:05 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-25 16:25:05 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3DAFDFB3-FFED-447E-8BA5-267430214F0E
[ThaliCore] Session.startOutputStream(with:) peer:3DAFDFB3-FFED-447E-8BA5-267430214F0E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:3
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-07-25 16:25:07 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-25 16:25:07 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-25 16:25:07 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-25 16:25:07 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:2,
[ThaliCore] VirtualSocket.deinit vsID:2 [3]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDi,sconnectHandler disconnecting:false
,2017-07-25 16:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 ,16:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-25 16:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B7B955AE-E51A-415A-B1E2-A,27D544FD210
2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61754
[ThaliCore] Session.disconnect() peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:3DAFDFB3-FFED-447E-8BA5-267430214F0E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uu,id: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] S,ession.disconnect() peer:3DAFDFB3-FFED-447E-8BA5-267430214F0E
,[ThaliCore] Session.session(_:peer:didChange:) peer:18D486AE-AFD3-48C7-92E4-8E0F17F10FA6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5A615210-A54A-4ECF-9E75-112BFEB948A6
,2017-07-25 16:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:294D0065-BE38-4005-A916-16306AC00B8B
[ThaliCore] Browser.startListening
,2017-07-25 16:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:25:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-25 16:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:3DAFDFB3-FFED-447E-8BA5-267430214F0E
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
2017-07-25 16:25:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A","generation":0}'
,2017-07-25 16:25:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A (syncValue: nA6ySEOVkBwwa3SNfUUHkR5RC5ojBnvc)'
,2017-07-25 16:25:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:25:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DA0E2C5F-B8AB-424C-989C-BDF114DA1928","generation":0}'
2017-07-25 16:25:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
2017-07-25 16:25:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45CBB222-33C6-4C7F-9C48-5051955F679C","generation":0}'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"82E20146-F4E8-4EC3-B45C-563776045682","generation":0}'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB,38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,B38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", ,generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB,38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,B38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB,38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:DB38B4FE,-1E0F-4F45-9FAA-A91B54DC6C1A error: max retries exceeded
2017-07-25 16:25:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nA6ySEOVkBwwa3SNfUUHkR5RC5ojBnvc","error":"Connection could not be established","portNumber":null}'
2017-0,7-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nA6ySEOVkBwwa3SNfUUHkR5RC5ojBnvc', error: 'Connection could not be established', listeningPort: '%s''
2017-07-25 16:25:20 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:25:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-25 16:25:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-25 16:25:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DA0E2C5F-B8AB-424C-989C-BDF114DA1928 (syncValue: N3dJG5V,8LZ6M7Y1VGgQcZMxvewpNlBIV)'
2017-07-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DA0E2C5F-B8AB,-424C-989C-BDF114DA1928:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-07-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8
[ThaliCore] Advertiser: session connected Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
[ThaliCore] Advertiser: session connected Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
,[ThaliCore] Session.session(_:peer:didChange:) peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DA,0E2C5F-B8AB-424C-989C-BDF114DA1928:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8 state: connecting -> connected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-25 16:25:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"N3dJG5V8LZ6M7Y1VGgQcZMxvewpNlBIV","error":"Peer is unavailable","portNumber":null}'
,2017-07-25 16:25:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'N3dJG5V8LZ6M7Y1VGgQcZMxvewpNlBIV', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-25 16:25:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DA0E2C5F-B8AB-424C-989C-BDF114DA1928","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:25:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DA0E2C5F-B8AB-424C-989C-BDF114DA1928","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-25 16:25:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:23 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-25 16:25:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 45CBB222-33C6-4C7F-9C48-5051955F679C (syncValue: SNG2EeRicUU4xNZrQlTELKCoiJ30Rj2H)'
,2017-07-25 16:25:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-25 16:25:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8
[ThaliCore] Session.startOutputStream(with:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8
[ThaliCore] Session.startOutputStream(with:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8
[ThaliCore] Session.startOutputStream(with:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8
[ThaliCore] Session.deinit peer:DA0E2C5F-B8AB-424C-989C-BDF114DA,1928:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC state: connecting -> connected
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:peer:didChange:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
[ThaliCore] Session.startOutputStream(with:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7, [3, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
[ThaliCore] Session.startOutputStream(with:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [3, 4, 5, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
[ThaliCore] Session.startOutputStream(with:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [3, 4, 5, 6, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (14194 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received all data: 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,2,K97tRC8yphTGvLm7h35AxyPV4LDtYjoVW1VGt9BX45LuQNIxAcafcxsUVUXz1W4OgKD3eZHSFh5XAfC1AzNanpOn6hMBBfUUrNsQjSIUkjzwkzPwWv8zM9O51KOtO6BYBSEmtMzvMAK6F4v6gm3WmnCykuDqCpfB7lWRsWfzGSTWoQKN3Xy0r4BBDfoluJcUSK3qXxRwREuoX5MTmTaKwBgW4PiPtFcN5hS0LmpuTsfkQXWFqoVj2ydK3JX84p6K,YegKiS6wsGVtTpH6lZdpWlTWFuhDiTX25TYDZxExxYG1aI9eib1PWlWAC16TpnBzpxNriFON5xFeOE5GEfDIy7BTA01Cf32zCUxjRnkgM8prFbJfpJ8u0QbC7KDKtEdjQ9wbRZVG1yGT3MO8Bx3LjXgZcv31YpJqbZhAYK5VWQBVxDXFlnn5JYxYBR8yJ9ioLluSNXzyuujGFzoPMq3Wls0mAvxaqX5srMioKpooLwUfLkJe4tHGOJnPzcQ2v8Pw,uOm5RQDR2Pe1c7uPoghqG0rD8slbjeyIn8glEhvuSC62C5jdDABaLPO4JAz1owTwLiwiAyYimeV60hZVLD9VrHLETWZoLvN64KinbCsTyuUoYovl5rTpNZNoqNssIa4KmvXkHiOOuhmn4Zm7wR0NWd8p63bIfujwC0NoI0g31iOSRz5BdOC9mNFLbrOb2fv6fBo1kjhCcykcojEatUN8oumTcqjMER1yJJnjsMSqTasclBIdK2Y6c7y8YncB1IVB,2toldIPCaRZglQjDfb7uM0Nzpy4M23CgA8YCaxdoBlODWKj46qgfQvB2Em30BTJuq73ULZrYR3qYGrnNHkx9VHGAkHbYIhGdkbsylwnr7JaZpcMxnzMIP3ByVph2zyLXuLY5cEzZW5OQCNwXIJSKsy8HsvvpyaS26ls4OfIpnjIiyH6yzSjosNbqyg1r8X4gQDfKD1J1p8hfG38zzhybRUa3i7DaQUg4RcpDveyXaMDh2NpV5OcF8aSoye6c6BDM,vrVsMyOlqlwPTLK5zIRFsd1BKH0SnzHHLFz9bMRf9fMA9UFyGFBAqFjHwFcBuNzCKD8DYKKgdKsgrAtp2hs2X9OVjLMpKvPp6YN8gQkI8otpn9MJ2Ia1e3E6tUWkXUDasjodOjKUaARN6nDmjiRb72ssx382i8WO0k6EmkGKTKjf4q5WAXwR9cZgp9W2D3AOpoKlyabhsUl7Qff81NvSSiFgvAZ4MNeEa9NPcK3DXXVPmVtfbUxHDy2i9gmAw3Pw,585zv9z2fPdMl1n1CtEDQrUlcmVy33cZKbZ6fLYAXwdkwdEVOldf3kNVPkxcLB9BPvag7sBBaCaSV4Nf7JeT9LVRm4fi9nytY3MWTwsUhBs1OpJclw4fgimSbGDMUhfVWkYLxPkLbqqd5wXohsh0re8hNkuANUQz6lGM4yyBoJ7HyYvxkl64jYTOEvQi9qIFlUOIRADckq3Ewk87idNmb2fJcrA0OINH9rN9VA3bJYmNvNxU1YziqgWHvbHIdG6u,vwcEMRgjkmxhg9G8qWa5AKdBDtpy4U90PdZjjrn0opCFiYDiI56p8Ae3sC3yasp28B9VrgCBwNibaF1Dv7LnNwezFetwIwGUrZqQyXUgky0ZO7AkF1vPVLHvBlGFLQFHfGlfmdEg59mboMOrT45QlsEIfKwClyWhTxSCVOmbBd65eJ8SLLnE2syFNZ1hJPnibsPdrmYC2Ql7DfDcDJ0x2PWdussE7OipblPRFrecBT9x2li241ET7zbqtnne7WOY,l1fmVG3tg0Ch6zvivG7FescZ3wOcyTIm0cAcFxWQzPoLjWLLmqAC5NrRAVpCg2T6Z5csmmFl6Fdh2aCMKHkgSyvxdKFQcZ3LXrGdvGr9sUtyvrQVYfsTSyRhJu68tBGTNZLUkypTVH5rjmexAHCjMIx2nO8KBVK542ClxmOX2NOenrdsaz849DUdVhPEI2pETObDEjXLXmeK3yOZ72WPexIjh6Ryx4AYnA7Lx1AoDIjgxRcZXf5v8UGF0t68FFvC,vMBDkvHB5qMRM2WX79LEuSdHw2y7UkXFsZWHSDIeczIRY80aqzIJGv8pTtVfDRsPo1YaUUoBixYdriWdtq96mlsZoqFSXDwOD21yt5eaH4fEWBEUoAXw8rJjPBj34GePUzp0piRK38EfRyceh5ZznoQnUOgbue7KN1Iw9om96XhoI6L7vh8uCXbXqZwwMhjmLrnBzCoqCllyuDpsncTTSjDV6GepEISBWLPTfG4NyeLbvSe3zpv5VaaNDhqh9mQk,Q1XdDsee3J5lxEpkiA3vQSHWZPXnOoGKUdks7EU6xaqs3SOj70tB1hRftHfUnudaRrJGqE9SpZOIyHovxJCRPS0SCNh0tmqyVH9N8zqkLxXeFGZ2TMa918ylV4YoZpsx6ugw6iRGGlV6KD7ALWhfFXP5tHr5APAgVJLnWooK4o3cIKQC3PeHYLnq7V15r3EYc7Q5c82EwvoOg1qppqo2KJMKctSsPq8oFdMCg4tsSgCfxv5hyuVvl916BBYhfkW2,EDdm2rG5xclJuIK2kRY6OkI5TWEkTC09Tbbqk4SG4qJcE5Umejuw4X8ntbCmSgP331XjstgJeTxbKBVtulYAmPncFoIMaX3NLQkfzf3k5rI71pxnYSSUfoHWBT3k2m5ogYNwUYCJNUtLKVL85XJj0q7gv6u7aFU8HmfYzXWOI4hHok0ErNw54bdYJVfbVQUNMmteWO4uOLFhEqS6Y0m522u3rG0B2vFksiFizfBk2toa1kUUOtGvMrgZ54LNI27d,PPLp7OOZCd0ao4DJwBvJu2qwfdcg557e0WFla2oh2jkXh7YM1oGNF96T3ysb7V1dzf4NOwgJ24tHxJtw2FvxVHiU6xaF2yd966XASd84OHTAPJ7WjGmGIvz0SN7WbnufqJGzuwAd27Z9YmlDaiyJ8RP5rLWfhJS7mps5swiSrA3uwzIDu5uOf0rDkTVyeKMvBU6UhJnDOrabWLti9afSBN2jKHpW6BuzdpRX7bSpNKvjC0puykXg0yrL9XiktJ5S,dDP4gZifDDvFMB4fkq6OEwAiRnRRdbUDFlz3yzjgIF0ntFjLMDTFm3RCa6hHrGge7jhnlaXuqiusyaTa7rQJbXeb6oydTI1IwTC3RHtK1yqcmWVU2mmQtnGUy14UVw5IlLgzyRbj1tSNtPnzCULidK4ffPWWoCKhmQWIrdmTeUNTD1lTlM5zWU5vulSv29cl232F7BdBNCIekxv32IsQtTH0qaP3pqaRuty3L8CipVK8PSYYIZBv9APBPLUFt8M7,uqNcFfqbA7SHYnJCMpzEMHu1JdwBpiHOfYWWthsVPW7Iiexk0BR8ucKu99LUxkPJWoVarmUgI9I1TUhwjLN5wXcHuQqeF7syvhDwGFahbk0QIFz7UMU6pgULKKMhP2JxhygI32EmZaQVpojmwsaifdkqI9oDLfwC1u51Ryh1QEvVqabK3MQLTS4g03T3J5Xfp1Kun68ebZZMoGYgyTc6Mzauy7EuWG7EhaRvSrgJozA0cYyoBJRcTwr9eevb8HLu,8FGTY3dI22DeVZ5BRXc5I2j3rKl86wxqlHyJ1VAvWCNHPWKf7TwpXT5Jy4A2mn8mgLjVgN2fN9491Y0s1xh0MEQGouTzECIVi7rR3fIU6eDF8KzWIFySB4jLu79DiWQBCpFgbl0EMIJU0TGH4sm0cxhfEB0EDiN8UfEmb9ZsaF3L7DWpc8yQ3ZAE64lNrS0wjT8OmX50J1jGBAli3KrZh1nvtBQjnGCsh5YqfPOcHFzMVlzLOSiGkTLNKBlhhLxV,vN3ZVKuMpTE2G9I0uwD6Yvr1MYALLG8K3uUccp9mnrTLjZ68iPPQgLzFBNeKGjQe2SqU1Bka5zNCHTy8GXKjGSTzIBjo726Lj8Fj4VAjgARxGcsqSJpGhSAKLVg0CHaGj751Ee5DWW8No53czRTeNphWdI5axeihMTdTh22lpg6U6XixrEsOWGx1Pje6eLj7tmiJpR7MXqmpciZEQNCi9pOCPpHCNz1RwjxcoqBl2P6oZssBqumSH9OUlJoaAEK,A,4bZDKd5taoVG876WnTyN5xz8gmZOglj47DOPjBXRQ5FkKHlv05fJGVbNOOAtJervT4IFiN5kgmGEL7LDY2pI7BtZ5BbzCjz1Ukg2qGUngIPSYpMcAR0yD11SBdLtKVoOAJjBcK5rNtu7tihqQ9EbDUDjtiQbmeUO6YizVGdtPe9mxwjnnM9njpe9rfPWKQgRbDdJn4ZKd9pG9KviXw71NHrNV1du9jQYTzvKTecMhYuX0SjlJyjJGecePkiyEVHM,lIpSsWDDIfMKn4y8DnWd9hmfYGfbW8I9MUt0UUaevLvu3qcU6fAUROtWth0IOPOQuWhKxG6h4lC87MRo27koX7idM9w2y2Dkk70Zv00u2bwSNROnYPn9mUQC8kUuA0tLmxgNT8QijS0S7nlmlvd0elXFDp8aeDI8J7wpFuC0M5DCmRZ7Zww34DTvJlBPPikbeX2w0SViI3pdjckJvmdPSb5InoT5fnSMwY4tjVjNccLxWbH1FfmPFxmwa7bMRzB9,lpDoikeZgQfKXftYMrythGBo9eRNZmgnAqCAUAUkDp7KZsatt6YIxIje95nVx5QGuQ923pHBWrnfgJKJnv0Vkbx2CdfY8OKvLy6rL60a6CGquCCpTCpDFJkbVVpIYZuwA2Nsc1rHlASyd8GjzSGXSuZc1JjOpdgP5IdxkJXyUJBKFwpJw9V4r3pxV80w3vyIV3gKLgOIgCFLi1cnZKfbFZiGnREoZHgorL7mJ1EX5atJJ8jaa0eVBMKa0s7tSu3E,1k3SLsUwQ4vIwW44ukqKnSrhaOsdgQI2GwbwpZBTlLzv1NzNrNcGb9luamgUsh3CLmxoAGQP3FQ3kBDpDg6EabWfI4jo30jI0CZKOStvyk4tJrpvRcTevoC6bu6FzZA2RekspRoZ6eNKxtkdy7ViEQ2QM3xMDkdz9uDXT77r9UBHTjew7ZBIjtiPUZgfvrywHz7WZ9L6WeZlgwll4y0wfjB5SfEXRlZg5SOKRAMQmOrEdDgAUCqIcPpekwxGjaVI,eOiA9R1RfIKwsCigInD7RkVFUJ2LQMkQsnNGuwCBArt0aL2HGryUJ8glrvocgzTqcQz1hswWMB77XipMKoUVNEkrYNOczNH6EPSWtIAIvHvxdH7CpRUdE0PocH6gldsYmbn8FQv0dzZqr2sApzhjWvYN5DOpYIhREzzTpjIWVKMUgJ4iqWqn182OgA27wAHwobonjvj6QB1mC9IFUOHMC0JpuZ9yX1Iuyoi8TTZga54nufcLydC6NLvYvsMyy5Or,Uf2VNRVaG2veXnaewY8n9VSYa0o50Hk9gDElbX6NEymEKwtjYM6opc5Tjj2CJcPTig5pphUTKEXnLNvEtMN5Xn9yhjFYRya171Nad5wB6mpu1FVcgOKQlDJpzBaz4BCFOncxuVkapQdpFrpOnRqiGdD4tPTSxF0aIYE7ANPB1DXt9mW6uHkMM1SBclGAr9itSxOn370qAwUneZdBLR27KWL1bQgMldOx2VSgrpQCHyg1O1Lm706848bBzgW7tcX8,QrtmU41lqwELrPdhht1cG1GudEmm2ENGU15bnrhGrsY4kW0IfABxgZSyeUvflGkhGhRDTz7B9tMUaS1swhyyD5ogQdugKZqIoS3dP7MdDnraqqKejhdfE22IuwKfohuxra5YOM82zhRr78bCGED7IbbaZw0nW73BsMrbtXWnm3v4WwWfEUOiCF2dKq772GpfDAJUvXwVRM98SfEJ9QF5IXLtkRJV7wtxK8m7Rjmhl0jIx3jkp5A6caYiaBxpAF9d,XaQovXbPmuvjKdzMTo46axEt3x4HsvjnfcJAOKKkDTip9kLUsdsXWbwmozRqJ2ovA4KqCFBAkSaLMtUWmtUDOo46xF6vu42qLa7cFDft4zjYflbiSpr6JoCQtlDP78N3HkJeiVCmSfiszXOE6gKj1kuge1lRIuGnt1XlIifMvT8oxWM6Ix6CpHQhs554Ij5WQGVelH0M86wLtSmnyc3BuV8yCsIpp1HqQYrv1IhWdDIDr54344C62WVuJDhGhvz,D,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,F,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'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (12288 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [3, 4, 5, 7, 8, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [3, 5, 7, 8, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [3, 7, 8, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [3, 8, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received (6529 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-25 16:25:24 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [3, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61773
,2017-07-25 16:25:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SNG2EeRicUU4xNZrQlTELKCoiJ30Rj2H","error":null,"portNumber":61773}'
,2017-07-25 16:25:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SNG2EeRicUU4xNZrQlTELKCoiJ30Rj2H', error: 'null', listeningPort: '61773''
,Connecting to the localhost:61773
,Connecting to the localhost:61773
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] TCPListener,.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
Connecting to the localhost:61773
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
,Connected to the localhost:61773
,Connected to the localhost:61773
,Connected to the localhost:61773
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 9, 10]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 9, 10, 11]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [3, 9, 10, 11, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-25 16:25:26 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [3, 9, 11, 12]
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [3, 9, 12]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
ok 96 got the same data back
,# teardown
,2017-07-25 16:25:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:5A615210-A54A-4ECF-9E75-112BFEB948A6
2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16,:25:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:45CBB222-33C6-4C7F-9C48-5051955F679C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61773
[ThaliCore] Session.disconnect() p,eer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
,[ThaliCore] Session.deinit peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:25:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:A57F35BB-C86D-4B2F-B133-1D0E6C9F1CBC
,[ThaliCore] Session.session(_:peer:didChange:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:02A53CE0-2039-4785-8EFB-491EDF350756
,2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ED0BEEFA-FEFC-43DD-98A1-0802DBCC79D6
[ThaliCore] Browser.startListe,ning
,2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:25:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45CBB222-33C6-4C7F-9C48-5051955F679C","generation":0}'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 45CBB222-33C6-4C7F-9C48-5051955F679C (syncValue: YNWBkFSKdcSCNJEO9XiaIh1kLmxajm0r)'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"82E20146-F4E8-4EC3-B45C-563776045682","generation":0}'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","generation":0}'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"891E67C8-0FC1-47E5-93ED-81CAFB5D34F9","generation":0}'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:45,CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,5CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:45,CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,5CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-25 16:25:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YNWBkFSKdcSCNJEO9XiaIh1kLmxajm0r","error":"Peer is unavailable",,"portNumber":null}'
2017-07-25 16:25:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YNWBkFSKdcSCNJEO9XiaIh1kLmxajm0r', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-25 16:25:34 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"45CBB222-33C6-4C7F-9C48-5051955F679C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:25:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-25 16:25:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"45CBB222-33C6-4C7F-9C48-5051955F679C","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-25 16:25:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-25 16:25:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BA8A39C9-4FC3-4403-9F86-8EC579378B0C (syncValue: zrUCwZyqCJu4qs4YBQQrfen,6zSyRL0i0)'
2017-07-25 16:25:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BA8A39C9-4FC3-4403-9F86-8EC57,9378B0C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:25:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61787
,2017-07-25 16:25:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zrUCwZyqCJu4qs4YBQQrfen6zSyRL0i0","error":null,"portNumber":61787}'
,2017-07-25 16:25:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zrUCwZyqCJu4qs4YBQQrfen6zSyRL0i0', error: 'null', listeningPort: '61787''
,Connecting to the localhost:61787
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [3, 9, 12, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:61787
,2017-07-25 16:25:38 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-25 16:25:38 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [3, 9, 12]
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EE089DA9-2DDC-4F9C-9C7D-18433029E756
[ThaliCore] Advertiser: session connected Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EE089DA9-2DDC-4F9C-9C7D-18433029E756 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EE089DA9-2DDC-4F9C-9C7D-18433029E756
,[ThaliCore] Session.session(_:peer:didChange:) peer:EE089DA9-2DDC-4F9C-9C7D-18433029E756 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EE089DA9-2DDC-4F9C-9C7D-18433029E756
[ThaliCore] Session.startOutputStream(with:) peer:EE089DA9-2DDC-4F9C-9C7D-18433029E756
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [3, 9, 12, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-25 16:25:52 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-25 16:25:52 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-25 16:25:52 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
,2017-07-25 16:25:52 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-25 16:25:52 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optiona,l(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSock,etDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:,false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [3, 9, 12]
,2017-07-25 16:25:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:25:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:02A53CE0-2039-4785-8EFB-491EDF350756
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61787
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:25:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:EE089DA9-2DDC-4F9C-9C7D-18433029E756 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:EE089DA9-2DDC-4F9C-9C7D-18433029E756
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zrUCwZyqCJu4qs4YBQQrfen6zSyRL0i0","error":"Session disconnected","portNumber":null}'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:EE089DA9-2DDC-4F9C-9C7D-18433029E756
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D
2017-07-25 16:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B34F3865-6E0C-4368-AE3B-DD68B33C0E37
[ThaliCore] Browser.startList,ening
,2017-07-25 16:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:25:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
2017-07-25 16:25:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","generation":0}'
2017-07-25 16:25:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BA8A39C9-4FC3-4403-9F86-8EC579378B0C, (syncValue: WaFtqr55EjgrTwNkWh8aJpEfADsxPz9z)'
2017-07-25 16:25:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC5793,78B0C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo,:) found peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
2017-07-25 16:25:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"891E67C8-0FC1-47E5-93ED-81CAFB5D34F9","generation":0}'
,2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
2017-07-25 16:25:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
2017-07-25 16:25:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1633D717-BAB5-409E-9E10-582EE947BE7C","generation":0}'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BA,8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,A8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BA,8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,A8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-25 16:26:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WaFtqr55EjgrTwNkWh8aJpEfADsxPz9z","error":"Peer is unavailable",,"portNumber":null}'
2017-07-25 16:26:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WaFtqr55EjgrTwNkWh8aJpEfADsxPz9z', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-25 16:26:00 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:26:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-25 16:26:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-25 16:26:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-25 16:26:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 891E67C8-0FC1-47E5-93ED-81CAFB5D34F9 (syncValue: wiqJJpIG6ne3U2n5asIIHuP,I6K5xcfy9)'
2017-07-25 16:26:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:891E67C8-0FC1-47E5-93ED-81CAF,B5D34F9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:26:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
2017-07-25 16:26:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","generation":0}'
2017-07-25 16:26:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:01 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:26:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,1E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,91E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,1E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,91E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,1E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,91E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,1E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:891E67C8,-0FC1-47E5-93ED-81CAFB5D34F9 error: max retries exceeded
2017-07-25 16:26:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wiqJJpIG6ne3U2n5asIIHuPI6K5xcfy9","error":"Connection could not be established","portNumber":null}'
2017-0,7-25 16:26:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wiqJJpIG6ne3U2n5asIIHuPI6K5xcfy9', error: 'Connection could not be established', listeningPort: '%s''
2017-07-25 16:26:11 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"891E67C8-0FC1-47E5-93ED-81CAFB5D34F9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:26:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-25 16:26:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"891E67C8-0FC1-47E5-93ED-81CAFB5D34F9","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-25 16:26:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-25 16:26:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 41B683AE-0F9D-4E22-8D46-1F9101EFBDED (syncValue: Ca6p940,hAyhTwdd2tGSVeEww5J1tEVVb)'
2017-07-25 16:26:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:41B683AE-0F9D,-4E22-8D46-1F9101EFBDED:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:26:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61808
2017-07-25 16:26:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Ca6p940hAyhTwdd2tGSVeEww5J1tEVVb",,"error":null,"portNumber":61808}'
2017-07-25 16:26:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Ca6p940hAyhTwdd2tGSVeEww5J1tEVVb', error: 'null', listeningPort: '61808''
,Connecting to the localhost:61808
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
Connected to the localh,ost:61808
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [3, 9, 12, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,ok 102 got the same data back
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] VirtualSocket.deinit vsID:15 [3, 9, 12]
,# teardown
,2017-07-25 16:26:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61808
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
,[ThaliCore] Session.deinit peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:577A8771-0646-4466-9947-6A06B9D51B0D
,[ThaliCore] Browser.startListening
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2934D003-1200-4C9E-AB23-8F76E83DCD2A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2934D003-1200-4C9E-AB23-8F76E83DCD2A
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1633D717-BAB5-409E-9E10-582EE947BE7C","generation":0}]'
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1633D717-BAB5-409E-9E10-582EE947BE7C","generation":0}'
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"891E67C8-0FC1-47E5-93ED-81CAFB5D34F9","generation":0}]'
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"891E67C8-0FC1-47E5-93ED-81CAFB5D34F9","generation":0}'
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}]'
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}'
,2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
2017-07-25 16:26:16 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED","generation":0}]'
2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED","generation":0}'
2017-07-25 16:26:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2934D003-1200-4C9E-AB23-8F76E83DCD2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2934D003-1200-4C9E-AB23-8F76E83DCD2A", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
2017-07-25 16:26:19 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}]'
2017-07-25 16:26:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"41B683AE-0F9D-4E22-8D46-1F9101EFBDED","generation":0}'
2017-07-25 16:26:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 ,16:26:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-25 16:26:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2934D003-1200-4C9E-AB23-8,F76E83DCD2A
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8B0917FE-A9A1-45A6-AD45-0006B5E7202C
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3E7EEDA2-61C5-4B62-87C6-A02AFBED108A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3E7EEDA2-61C5-4B62-87C6-A02AFBED108A
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3E7EEDA2-61C5-4B62-87C6-A02AFBED108A
ok 111 discoveryActive should be false
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
,2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-25 16:26:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
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
2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:e6d80528-356f-4020-b13c-b22c49280614 error: startListeningNotActive
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sVpeFUXTAXSqoWHtevLQuJ6xjQ6tYN07","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"e6d80528-356f-4020-b13c-b22c49280614","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"e6d80528-356f-4020-b13c-b22c49280614","peerAvailable":true,"portNumber":null,"recreated":true}'
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BC0E259A-6611-4261-B105-7B71F6D9C1AD
,[ThaliCore] Browser.startListening
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-25 16:26:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"djgWeCI9f39eKn6c4hPloGMYm0lXI1RD","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2259B29E-1601-4393-8CF7-A381DFEF24A0
,[ThaliCore] Browser.startListening
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-25 16:26:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:26 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:adaddde8-cb4a-4acf-81fa-8443e731a119
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browse,r.init(serviceType:foundPeer:lostPeer:) peer:B1FF8E98-5CD7-4FDF-83DE-B235AE46F72C
[ThaliCore] Browser.startListening
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:26:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
,2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED","generation":0}'
,2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED (syncValue: nPRyvNyTl9n4wxVjbd4pB9MDWXG015fv)'
,2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
,2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3638CC74-F640-40BF-A15A-F9FFB9A8E833","generation":0}'
,2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45A0ED46-6443-4763-9D77-FD1894FD6FB9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
2017-07-25 16:26:28 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45A0ED46-6443-4763-9D77-FD1894FD6FB9","generation":0}'
2017-07-25 16:26:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:28 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:26:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7C,11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F211700F-EAFA-4D3C-8CB7-EE7C96AB5E7E
[ThaliCore] Advertiser: session connected Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F211700F-EAFA-4D3C-8CB7-EE7C96AB5E7E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7C,11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7C,11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F211700F-EAFA-4D3C-8CB7-EE7C96AB5E7E
,[ThaliCore] Session.session(_:peer:didChange:) peer:F211700F-EAFA-4D3C-8CB7-EE7C96AB5E7E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F211700F-EAFA-4D3C-8CB7-EE7C96AB5E7E
,[ThaliCore] Session.startOutputStream(with:) peer:F211700F-EAFA-4D3C-8CB7-EE7C96AB5E7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [3, 9, 12, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A36A438A-627C-41D5-A9D7-AE7EC38215C2
[ThaliCore] Advertiser: session connected Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A36A438A-627C-41D5-A9D7-AE7EC38215C2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7C,11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7C11DC55,-1A5C-4DA6-9974-2913C4B3F7ED error: max retries exceeded
2017-07-25 16:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nPRyvNyTl9n4wxVjbd4pB9MDWXG015fv","error":"Connection could not be established","portNumber":null}'
2017-07-25 16:26:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nPRyvNyTl9n4wxVjbd4pB9MDWXG015fv', error: 'Connection could not be established', listeningPort: '%s''
2017-07-25 16:26:38 - DEBUG thaliMobileNativeWrapper: 'Received ,peer availability changed event with {"peerIdentifier":"7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:26:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-25 16:26:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-25 16:26:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-25 16:26:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3638CC74-F640-40BF-A15A-F9FFB9A8E833 (syncValue: AsV9nt7QntnZu16rkJ6nob1I1H9BGyje)'
,2017-07-25 16:26:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:26:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A36A438A-627C-41D5-A9D7-AE7EC38215C2
,[ThaliCore] Session.session(_:peer:didChange:) peer:A36A438A-627C-41D5-A9D7-AE7EC38215C2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A36A438A-627C-41D5-A9D7-AE7EC38215C2
,[ThaliCore] Session.startOutputStream(with:) peer:A36A438A-627C-41D5-A9D7-AE7EC38215C2
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [3, 9, 12, 16, 17]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61826
2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AsV9nt7QntnZu16rkJ6nob1I1H9BGyje",,"error":null,"portNumber":61826}'
2017-07-25 16:26:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AsV9nt7QntnZu16rkJ6nob1I1H9BGyje', error: 'null', listeningPort: '61826''
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket,:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
ok 143 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Pee,r(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0) found active relay
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"39MSxp9AG6p2SIA4lcFrgQTNv8H0gqBz","error":null,"portNumber":61826}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
ok 144 No error
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [3, 9, 12, 16, 17, 18]
ok 145 Ports equal
[ThaliCore] BrowserRela,y.didOpenVirtualSocketStreamsHandler
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0) found active relay
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"og0IW53HooiiYeQymRATT1aicZT3aXmK","error":null,"portNumber":61826}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,2017-07-25 16:26:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:26:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:26:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4
2017-07-2,5 16:26:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[Thal,iCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient,.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeStream,s() vsID:16
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] BrowserManager.disconnect peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] AdvertiserRelay.didSocketDiscon,nectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61826
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
,[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:16 [3, 9, 12, 17, 18]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:A36A438A-627C-41D5-A9D7-AE7EC38215C2 state: connected -> notConnected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:A36A438A-627C-41D5-A9D7-AE7EC38215C2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] TCPClient.deinit
[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.deinit vsID:17 [3, 9, 12, 18]
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:18 [3, 9, 12]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-25 16:26:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F211700F-EAFA-4D3C-8CB7-EE7C96AB5E7E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
,# setup
,2017-07-25 16:26:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AsV9nt7QntnZu16rkJ6nob1I1H9BGyje","error":"Session disconnected","portNumber":null}'
,2017-07-25 16:26:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3638CC74-F640-40BF-A15A-F9FFB9A8E833","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:26:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3638CC74-F640-40BF-A15A-F9FFB9A8E833","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-25 16:26:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# initial peer discovery
,2017-07-25 16:26:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,[ThaliCore] Session.deinit peer:A36A438A-627C-41D5-A9D7-AE7EC38215C2
,[ThaliCore] Session.deinit peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserRelay.deinit
,# teardown
,2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-25 16:26:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
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
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-25 16:26:49 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-25 16:26:49 - DEBUG createNativeListener: 'listening 61829'
ok 149 Should throw
,# teardown
,2017-07-25 16:26:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:49 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 61831'
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
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 61834'
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
2017-07-25 16:26:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming ,- incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 61838'
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
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 61843'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
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
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'listening 61847'
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
2017-07-25 16:26:51 - DEBUG createNativeListener: 'listening 61851'
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
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'listening 61855'
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
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'listening 61859'
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
,2017-07-25 16:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-25 16:26:54 - DEBUG createNativeListener: 'listening 61911'
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
,2017-07-25 16:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'listening 61915'
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
2017-07-25 16:26:56 - DEBUG createNativeListener: 'listening 61918'
ok 196 port must be in range
,# teardown
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'listening 61919'
,ok 197 second start should return same port
,# teardown
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'listening 61921'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - close'
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
,listening on 61923
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:26:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0EA925B4-0B46-484F-8B3B-75C44871A9AD
,[ThaliCore] Browser.startListening
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:26:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:26:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:45A0ED46-6443-4763-9D77-FD1894FD6FB9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3638CC74-F640-40BF-A15A-F9FFB9A8E833","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B037CFD3-4481-4DF6,-9B8E-99CE54716E19:0
2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3638CC74-F640-40BF-A15A-F9FFB9A8E833 (syncValue: liKQUpJ3Yag5QNKcdHu5a09yiTPl4d1x)'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B037CF,D3-4481-4DF6-9B8E-99CE54716E19", generation: 0)
2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "36,38CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45A0ED46-6443-4763-9D77-FD1894FD6FB9","generation":0}'
2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B037CFD3-4481-4DF6-9B8E-99CE54716E19","generation":0}'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0)
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"56E48F0C-5C40-4592-82B8-A52B84B2813F","generation":0}'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,38CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:45A0ED46-6443-4763-9D77-FD1894FD6FB9:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
,[ThaliCore] Session.deinit peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:19C99E7C-5CB4-47FC-985C-860D669DEBF5
[ThaliCore] Advertiser: session connected Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:19C99E7C-5CB4-47FC-985C-860D669DEBF5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,38CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"liKQUpJ3Yag5QNKcdHu5a09yiTPl4d1x","error":"Peer is unavailable","portNumber":null}'
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'liKQUpJ3Yag5QNKcdHu5a09yiTPl4d1x', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3638CC74-F640-40BF-A15A-F9FFB9A8E833","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3638CC74-F640-40BF-A15A-F9FFB9A8E833","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:27:04 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B037CFD3-4481-4DF6-9B8E-99CE54716E19 (syncValue: bKiw4cVMsdbzK9FwSXiswSVD2SgRZSee)'
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B037CFD3-4481-4DF6-9B8E-99CE54716E19:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserRelay.deinit
,2017-07-25 16:27:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B037CFD3-4481-4DF6-9B8E-99CE54716E19:0 state: notConnected -> connecting
,2017-07-25 16:27:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:117E516B-B78F-493E-A3A5-2C5D5138CE0D
[ThaliCore] Advertiser: session connected Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:117E516B-B78F-493E-A3A5-2C5D5138CE0D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:19C99E7C-5CB4-47FC-985C-860D669DEBF5
,[ThaliCore] Session.session(_:peer:didChange:) peer:19C99E7C-5CB4-47FC-985C-860D669DEBF5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B037CFD3-4481-4DF6-9B8E-99CE54716E19:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B037CFD3-4481-4DF6-9B8E-99CE54716E19:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61933
,2017-07-25 16:27:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bKiw4cVMsdbzK9FwSXiswSVD2SgRZSee","error":null,"portNumber":61933}'
,2017-07-25 16:27:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bKiw4cVMsdbzK9FwSXiswSVD2SgRZSee', error: 'null', listeningPort: '61933''
,ok 210 should be equal
,2017-07-25 16:27:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 56E48F0C-5C40-4592-82B8-A52B84B2813F (syncValue: 1H80gLe0s5xB9EuaGpuYba4NEigP0HcX)'
,2017-07-25 16:27:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:27:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:peer:didChange:) peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:117E516B-B78F-493E-A3A5-2C5D5138CE0D
,[ThaliCore] Session.session(_:peer:didChange:) peer:117E516B-B78F-493E-A3A5-2C5D5138CE0D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61938
,2017-07-25 16:27:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1H80gLe0s5xB9EuaGpuYba4NEigP0HcX","error":null,"portNumber":61938}'
,2017-07-25 16:27:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1H80gLe0s5xB9EuaGpuYba4NEigP0HcX', error: 'null', listeningPort: '61938''
,ok 211 should be equal
,# teardown
,2017-07-25 16:27:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4,543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-25 16:28:10 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-25 16:28:10 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-25 16:,28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-25 16:28:10 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-25 16:28:10 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Single coordinated request ios native, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122,413A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/tim,ers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-25 16:28:10 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-25 16:28:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4,543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:30 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:350:16
$9@timers.,js:120:1
''
,2017-07-25 16:30:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4,543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4,543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4,543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4,543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4,543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4,543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-454,3-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:40 - ERROR CoordinatedClient: 'reconnect_failed error: 'undefined', description: '%s,',, stack: '%s''
2017-07-25 16:43:40 - DEBUG CoordinatedClient: 'test client failed'
2017-07-25 16:43:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'T,ransport.prototype.onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers,/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxc,ore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6CB7A295-03DE-4543-98BB-E4C2C122413A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:,4,3:40 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-07-25 16:43:40 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
