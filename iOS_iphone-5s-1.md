#### Test 11335185196ab692_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/DA3A7ECB-432B-4AE0-952A-9BC37F4583E0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DA3A7ECB-432B-4AE0-952A-9BC37F4583E0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63626"
,(lldb)     command script import "/tmp/DA3A7ECB-432B-4AE0-952A-9BC37F4583E0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-13 07:38:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:38:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:38:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:38:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:38:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:38:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-13 07:38:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B37A238D-D458-4D10-8052-0051F2EF57C6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B37A238D-D458-4D10-8052-0051F2EF57C6
,Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:652B9191-6582-4240-9C4A-759F44678ECA
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] ,BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4B9FB56E-0BC7-4E16-B304-C3E71F18FF0D
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort,:errorHandler:) Peer(uuid: "BF459E17-9218-4E73-80EE-B074B325F17E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BF459E17-9218-4E73-80EE-B074B325F17E
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF459E17-9218-4E73-80EE-B074B325F17E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF459E17-9218-4E73-80EE-B074B325F17E", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-13 07:38:27 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.495445013046265
,2017-07-13 07:38:27 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-07-13 07:38:27 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BF459E17-9218-4E73-80EE-B074B325F17E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BF459E17-9218-4E73-80EE-B074B325F17E", generation: 0)
,2017-07-13 07:38:31 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-13 07:38:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-13 07:38:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-13 07:38:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-13 07:38:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-13 07:38:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-13 07:38:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-13 07:38:35 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-13 07:38:35 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-13 07:38:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8,B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8,B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:52 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-13 07:38:52 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-13 07:39:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-13 07:39:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-13 07:39:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-13 07:39:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
2017-07-13 07:39:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
2017-07-13 07:39:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-13 07:39:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-13 07:39:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-13 07:39:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-13 07:39:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-13 07:39:33 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-13 07:39:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:39:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-13 07:39:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2F77C9D4-C003-49D8-89FA-2D209FC456E7
[ThaliCore] Browser.startListening
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 07:39:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {",discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AA77DCD4-7704-4063-A1C2-07BD04B9E398
,[ThaliCore] Browser.startListening
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 07:39:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "31D9C4BC-E348-484A-8640-1D8AB32D11C9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:31D9C4BC-E348-484A-8640-1D8AB32D11C9
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "029E0DC5-DD2A-402E-9844-38495C802E53", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:029E0DC5-DD2A-402E-9844-38495C802E53
2017-07-13 0,7:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "029E0DC5-DD2A-402E-9844-38495C802E53", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:029E0DC5-DD2A-402E-9844-38495C802E53
2017-07-13 0,7:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 84 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87
2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:53, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-13 07:39:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:0C1BD54C-F7CD-42A9-AA83-27D68BA39DD2
[ThaliCore] Browser.startListening
2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advert,isingActive":true}'
,2017-07-13 07:39:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:39:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:668BFA24-1C83-4C25-A698-52B1925BCC32:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "668BFA24-1C83-4C25-A698-52B1925BCC32", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:70DB33E6-66FC-45C7-AE62-2D236D98DD50
[ThaliCore] Browser.startListe,ning
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 07:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:668BFA24-1C83-4C25-A698-52B1925BCC32:0
2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"07BA770A-1623-4693-8CFA-B9750DA025BA","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "668BFA24-1C83-4C25-A698-52B1925BCC32", generation: 0)
,2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 07BA770A-1623-4693-8CFA-B9750DA025BA (syncValue: 1Jz0hMQSAmk1gulFOQDhkw4oLUbIVW4h)'
,2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"668BFA24-1C83-4C25-A698-52B1925BCC32","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0)
[ThaliCore] Session.disconnect() peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:668BFA24-1C83-4C25-A698-52B1925BCC32:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "668BFA24-1C83-4C25-A698-52B1925BCC32", generation: 0)
[ThaliCore] Browser.br,owser(_:foundPeer:withDiscoveryInfo:) found peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
2017-07-13 07:39:56 - DEBUG thaliMobileNativeTestUt,ils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF43B91C-BBA8-4DB3-99C5-7CF7E5038090:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", generation: 0)
,2017-07-13 07:39:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DF43B91C-BBA8-4DB3-99C5-7CF7E5038090","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0),
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1Jz0hMQSAmk1gulFOQDhkw4oLUbIVW4h","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:01 - DEBUG thaliMobileNativeTestUtils: 'Got m,ultiConnectResolved -syncValue: '1Jz0hMQSAmk1gulFOQDhkw4oLUbIVW4h', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":",07BA770A-1623-4693-8CFA-B9750DA025BA","peerAvailable":false,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peer availability changed event with {"peerIdentifier":"07BA770A-1623-4693-8CFA-B9750DA025BA","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChanged,Event due to not being in started state'
,2017-07-13 07:40:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,[ThaliCore] Session.disconnect() peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0)
,2017-07-13 07:40:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 65A3BFA4-3808-4AFD-9773-59BA8C46E2F8 (syncValue: kTzTaNZ4RoNucy2JTVwJP05kMaTTWZMI)'
,2017-07-13 07:40:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C0751906-039A-4376-B8F1-E1498FE84111
[ThaliCore] Advertiser: session connected Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C0751906-039A-4376-B8F1-E1498FE84111 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49679
,2017-07-13 07:40:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kTzTaNZ4RoNucy2JTVwJP05kMaTTWZMI","error":null,"portNumber":49679}'
,2017-07-13 07:40:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kTzTaNZ4RoNucy2JTVwJP05kMaTTWZMI', error: 'null', listeningPort: '49679''
,2017-07-13 07:40:04 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C0751906-039A-4376-B8F1-E1498FE84111
,[ThaliCore] Session.session(_:peer:didChange:) peer:C0751906-039A-4376-B8F1-E1498FE84111 state: connecting -> connected
,2017-07-13 07:40:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 07:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,A,ctive":false}'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49679
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
,# setup
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0770DD0B-3938-42AB-BD22-0A1EE963ACCD
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 102 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9B30D020-EBDA-44F9-9AEA-4C3DBC19223F
,[ThaliCore] Browser.startListening
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.session(_:peer:didChange:) peer:C0751906-039A-4376-B8F1-E1498FE84111 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:C0751906-039A-4376-B8F1-E1498FE84111
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:C0751906-039A-4376-B8F1-E1498FE84111
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:DF43B91C-BBA8-4DB3-99C5-7CF7E5038090:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", generation: 0)
,2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","generation":0}'
,2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 65A3BFA4-3808-4AFD-9773-59BA8C46E2F8 (syncValue: bsQSofkKaRq0peUibgLhvQ0PcJVOF5oi)'
2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-,59BA8C46E2F8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DF43B91C-BBA8-4DB3-99C5-7CF7E5038090","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DF43B91C-BBA8-4DB3-99C5-7CF7E5038090:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
2017-07-13 07:40:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"660CEBE9-D970-4CC3-8112-DBD0DF36D4CE","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:883F5BBE-EDEE-48D4-A797-D586985545C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "883F5BBE-EDEE-48D4-A797-D586985545C4", generation: 0)
,2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"883F5BBE-EDEE-48D4-A797-D586985545C4","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", genera,tion: 0)
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bsQSofkKaRq0peUibgLhvQ0PcJVOF5oi","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'bsQSofkKaRq0peUibgLhvQ0PcJVOF5oi', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 660CEBE9-D970-4CC3-8112-DBD0DF36D4CE (syncValue: 65pvFdb,85prI9JmydAU16cF5agBKpKBE)'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C2E4F2C6-B29F-47CC-A5CC-2EC5EA30AB25
[ThaliCore] Session.session(,_:peer:didChange:) peer:C2E4F2C6-B29F-47CC-A5CC-2EC5EA30AB25 state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliC,ore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNo,tConnected:) Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtual,SocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C2E4F2C6-B29F-47CC-A5CC-2EC5EA30AB25
,[ThaliCore] Session.session(_:peer:didChange:) peer:C2E4F2C6-B29F-47CC-A5CC-2EC5EA30AB25 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C2E4F2C6-B29F-47CC-A5CC-2EC5EA30AB25
[ThaliCore] Session.start,OutputStream(with:) peer:C2E4F2C6-B29F-47CC-A5CC-2EC5EA30AB25
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49687
,2017-07-13 07:40:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"65pvFdb85prI9JmydAU16cF5agBKpKBE","error":null,"portNumber":49687}'
,2017-07-13 07:40:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '65pvFdb85prI9JmydAU16cF5agBKpKBE', error: 'null', listeningPort: '49687''
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
Connecting to the localhost:49687
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,Connected to the localhost:49687
,[ThaliCore] Session.startOutputStream(with:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
,2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-07-13 07:40:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,# teardown
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false so,cket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 07:40:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingA,ctive":false}'
,2017-07-13 07:40:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49687
,[ThaliCore] Session.disconnect() peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C2E4F2C6-B29F-47CC-A5CC-2EC5EA30AB25 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:C2E4F2C6-B29F-47CC-A5CC-2EC5EA30AB25
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:C2E4F2C6-B29F-47CC-A5CC-2EC5EA30AB25
,# setup
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:40:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F7974F8D-9A8D-4B97-8930-80FC4382D89E
2017-07-13 07:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:24, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-13 07:40:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:12270C49-5D89-4651-AC4F-E502CDB61E43
[ThaliCore] Browser.startListening
2017-07-13 07:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,rtisingActive":true}'
2017-07-13 07:40:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:40:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
2017-07-13 07:40:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 65A3BFA4-3808-4AFD-9773-59BA8C46E2F8 (syncValue: 68PjeBUGAYXE4X5G,NyePCuggh5AZvU1T)'
2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-,59BA8C46E2F8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"660CEBE9-D970-4CC3-8112-DBD0DF36D4CE","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
2017-07-13 07:40:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D20CF0E0-AB62-41C0-B39B-9E536E7B86A5","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0)
,2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"724A47F8-A6A9-4ACB-88A5-C246773D2521","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
[ThaliCore] Session.disconnect() peer:65A3BFA4-380,8-4AFD-9773-59BA8C46E2F8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", genera,tion: 0)
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"68PjeBUGAYXE4X5GNyePCuggh5AZvU1T","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '68PjeBUGAYXE4X5GNyePCuggh5AZvU1T', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13, 07:40:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"65A3BFA4-3808-4AFD-9773-59BA8C46E2F8","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 660CEBE9-D970-4CC3-8112-DBD0DF36D4CE (syncValue: xl71kbj,HPcybOiy9GcPviYLLdZVtvST8)'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A
[ThaliCore] Advertiser: session connected Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921
[ThaliCore] Advertiser: session connected Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921
,[ThaliCore] Session.session(_:peer:didChange:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921
[ThaliCore] Session.startOutputStream(with:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921
[ThaliCore] Session.startOutputStream(with:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4, [3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921
[ThaliCore] Session.st,artOutputStream(with:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-13 07:40:33 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 07:40:33 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A
[ThaliCore] Session.startOutputStream(with:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A
,[ThaliCore] Session.startOutputStream(with:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 4, 5, 6, 7]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A
,[ThaliCore] Session.startOutputStream(with:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [3, 4, 5, 6, 7, 8]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (2403 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (7837 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (12004 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStr,eamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [3, 4, 5, 7, 8]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [3, 4, 5, 8]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3,
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server received all data: 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[,ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
VFIG4IIAjSaeCFBQJNoybhzamdHKQ7uv5KNlqwWbLPklFsrHauGlYNtUhmIv381wfY73ceRZ9jsRh5cGuH6hxZXTaIDvUqH3h05sIELIoyXg58ugu6mKg9yGsw3btEy0VNzPMO,Y7zlCJ7Z07p3HUw18IU10LXnjexb8JmuTGd96DxRpldMyaaL57MuU36YhwebDxTf1hMTVsI74Yid9mGP1XdIUu2OdnMraPbKZu6c54JIYYjnCdyKGmVumcyLweTNYWMtfYrUtVm27ABE5ijo8kVZqAXJ9tbzPBfbXsrCaoJD4lL4T9Yc4eYNI6BLjQcDeX5ygqZcAVt5mkMc6RjpM7h3pqi2Jv5yF9QtIgvrzIXoAojDWfUVySxVL91cRlgk8GLF,GObGB2S81PMy9BcfOCazc5tOREwL9G66JlJoVhrl8KB8OjoWzOdg3WczsD9mbKG7O8BYRnWHN7rb92ouAtdDjwzfGl6SG0ZWyL66kigIxe2aLXlvmyETLnaG2ihWgci7XUWaIjdgWRu5tiBVdOS2rMUgBnlukbnQxkUIEP2TUUXOWLE0cekvcNv4D0xN5jKJ95fTUzMSBKxoRsNblKF7Vi1wkttIwgL3ODoH990XLI7i1zf7MlSr8T9mo5ptOTwb,tM6qu9m9NTQOLEEH4UpIhYjV6xKKueyleQxi6fVUooNkAWigvfjB3ZLeXPpZYoCTH5XdqXUWIzMGKSpeX6xGB6d5YAcx1AkFNcQ6wxWAaxLt12zHsRVF5GT2rXoi0B2YRC4MVG5FZ6n90cj6xmc8UhBRoyj3R2x8id9ZKKRG2dZmg4gICO8rpFoGELZydauPpUR4kbUgsc0GZjooXws2FADk7nOYwl4z1e6maoyRpioSl1BsNnN7Mh8HhkvXOlNL,6noJlzFL7RNbvwPkJy2sgp1FACSB0RhcKXtVQQPZX3gMnGx9IFd1Ku1vgjbjNkUzWdTrvtKMbvA8FQ1lPCmdxnwaVQ9ipyIrFwZJG5GVs4PvXO8soJZWrKdA6h[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [3, 5, 8]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSoc,ketDisconnectHandler disconnecting:false
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'
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.hand,leEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.dei,nit vsID:5 [3, 8]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecti,ng:false
2017-07-13 07:40:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [3]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", genera,tion: 0)
2017-07-13 07:40:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xl71kbjHPcybOiy9GcPviYLLdZVtvST8","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:36 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'xl71kbjHPcybOiy9GcPviYLLdZVtvST8', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"660CEBE9-D970-4CC3-8112-DBD0DF36D4CE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13, 07:40:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"660CEBE9-D970-4CC3-8112-DBD0DF36D4CE","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:36 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:36 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D20CF0E0-AB62-41C0-B39B-9E536E7B86A5 (syncValue: AwrhSp0,sHWNqf1FiYytBkWhcfEgEDaDE)'
2017-07-13 07:40:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A,5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49700
,2017-07-13 07:40:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AwrhSp0sHWNqf1FiYytBkWhcfEgEDaDE","error":null,"portNumber":49700}'
,2017-07-13 07:40:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AwrhSp0sHWNqf1FiYytBkWhcfEgEDaDE', error: 'null', listeningPort: '49700''
,Connecting to the localhost:49700
,Connecting to the localhost:49700
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
Connecting to the localhost:49700
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [3, 9]
,Connected to the localhost:49700
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49700
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 9, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49700
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 9, 10, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 07:40:40 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [3, 10, 11]
,ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [3, 10]
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [3]
,ok 114 got the same data back
,# teardown
,2017-07-13 07:40:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:40:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 07:40:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,Active":false}'
,2017-07-13 07:40:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49700
[ThaliCore] Session.disconnect() peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:65D79A99-1105-4E88-86F5-1B73E2B6419A state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:82CE4286-2D50-46D5-8EF4-2FB983849921
,[ThaliCore] Session.deinit peer:82CE4286-2D50-46D5-8EF4-2FB983849921
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:40:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:40:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9717CC7E-1822-4393-B532-B06F5A7A59A4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9717CC7E-1822-4393-B532-B06F5A7A59A4
,2017-07-13 07:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C95F00F6-64B3-4ACD-9825-7E4BD2921946
[ThaliCore] Browser.startListening
2017-07-13 07:40:42 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 07:40:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 07:40:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
2017-07-13 07:40:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"724A47F8-A6A9-4ACB-88A5-C246773D2521","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
,2017-07-13 07:40:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 724A47F8-A6A9-4ACB-88A5-C246773D2521 (syncValue: Cc8W7KD7q6QVkgOjPVGrHbSdy7zjhIAV)'
,2017-07-13 07:40:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 07:40:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D20CF0E0-AB62-41C0-B39B-9E536E7B86A5","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:652433DE-F049-45A3-95C3-0B1092E6E918:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0)
2017-07-13 07:40:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"652433DE-F049-45A3-95C3-0B1092E6E918","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9717CC7E-1822-4393-B532-B06F5A7A59A4:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9717CC7E-1822-4393-B532-B06F5A7A59A4", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D8525647-2B71-4074-8257-C803B73ABEF2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D8525647-2B71-4074-8257-C803B73ABEF2", generation: 0)
,2017-07-13 07:40:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D8525647-2B71-4074-8257-C803B73ABEF2","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", genera,tion: 0)
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Cc8W7KD7q6QVkgOjPVGrHbSdy7zjhIAV","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:48 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'Cc8W7KD7q6QVkgOjPVGrHbSdy7zjhIAV', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"724A47F8-A6A9-4ACB-88A5-C246773D2521","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"724A47F8-A6A9-4ACB-88A5-C246773D2521","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 07:40:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D20CF0E0-AB62-41C0-B39B-9E536E7B86A5 (syncValue: L3uUMYqU7BrFCWca1b5trcWjKUYdUchI)'
,2017-07-13 07:40:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", genera,tion: 0)
2017-07-13 07:40:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"L3uUMYqU7BrFCWca1b5trcWjKUYdUchI","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:53 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'L3uUMYqU7BrFCWca1b5trcWjKUYdUchI', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"D20CF0E0-AB62-41C0-B39B-9E536E7B86A5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,07:40:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D20CF0E0-AB62-41C0-B39B-9E536E7B86A5","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:53 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 652433DE-F049-45A3-95C3-0B1092E6E918 (syncValue: yzc2YTn,yPiqYL7ltE3uy2XgFegzOB0P6)'
2017-07-13 07:40:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:652433DE-F049-45A3-95C3-0B1092E6E91,8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49713
,2017-07-13 07:40:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yzc2YTnyPiqYL7ltE3uy2XgFegzOB0P6","error":null,"portNumber":49713}'
,2017-07-13 07:40:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yzc2YTnyPiqYL7ltE3uy2XgFegzOB0P6', error: 'null', listeningPort: '49713''
,Connecting to the localhost:49713
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:652433DE-F049-45A3-95C3-0B1092E6E918:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [3, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49713
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:12 [3]
,ok 119 got the same data back
,# teardown
,2017-07-13 07:40:57 - DEBUG CoordinatedClient: 'all tests completed'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-13 07:41:56 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Can shift data securely, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest,.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
,    at timeoutTimeout@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-07-13 07:41:56 - ERROR CoordinatedClient: ',failed to run unit tests, platformName: 'ios''
,2017-07-13 07:43:51 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-13 07:43:51 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-13 07:43:51 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Error: run failed, test: 'Can shift data securely', event: 'run_Can shift data securely', sent data: '[{"uuid":"7429bd2a-7ddd-4480-9dee-bcb66c6ea3bf"},{"uuid":"ac0e4d72-52ca-4a,d2-9509-e84c7cd40172"},{"uuid":"26bb0a9c-78ae-475d-ae1e-25e4e9f16cba"}]', received data: '{"success":false}'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/ww,w/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/c,ontainers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTe,st.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emi,t@/private/var/containers/Bundle/Application/0F233BDF-D034-4D8B-911F-C2BFC342F257/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-13 07:43:51 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
