#### Test 1133518513e6abb0_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1133518513e6abb0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/D006A78F-26EB-4F38-AF71-4946C90F0D79/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/D006A78F-26EB-4F38-AF71-4946C90F0D79/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1133518513e6abb0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1133518513e6abb0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59060"
,(lldb)     command script import "/tmp/D006A78F-26EB-4F38-AF71-4946C90F0D79/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-07-21 08:41:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:41:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:41:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:41:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:41:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "225DED64-CDAC-48BC-9AFA-EB5B470EFB89", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:225DED64-CDAC-48BC-9AFA-,EB5B470EFB89
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7B05D463-40B5-4B35-BBA1-D5319A11E688
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:20F8EEC1-,55BF-405A-9193-A68046A9705D
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EE9B66D2-6BDF-4903-80DB-71EBD1778DCD", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:EE9B66D2-6BDF-4903-80DB-71EBD1778DCD
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EE9B66D2-6BDF-4903-80DB-71EBD1778DCD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EE9B66D2-6BDF-4903-80DB-71EBD1778DCD", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-21 08:41:06 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
,Number of passed tests:  13
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.68061900138855
,2017-07-21 08:41:07 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-21 08:41:07 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EE9B66D2-6BDF-4903-80DB-71EBD1778DCD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EE9B66D2-6BDF-4903-80DB-71EBD1778DCD", generation: 0)
,2017-07-21 08:41:10 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 08:41:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 08:41:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 08:41:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 08:41:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 08:41:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 08:41:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 08:41:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 08:41:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 08:41:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 08:41:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 08:41:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 08:41:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 08:41:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 08:41:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 08:41:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 08:41:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 08:41:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 08:41:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 08:41:14 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 08:41:14 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 08:41:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:42:00 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-21 08:42:00 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 08:42:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-21 08:42:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 08:42:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 08:42:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-21 08:42:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-21 08:42:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-21 08:42:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-21 08:42:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-21 08:42:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 08:42:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 08:42:33 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-21 08:42:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 08:42:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4CE21E0A-1D7E-4D4D-8C6A-27D19B5008E9
[ThaliCore] Browser.startListening
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-21 08:42:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:47 - INFO tha,l,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:30D00BB6-5509-41BC-998F-ED3D093E3F73
[ThaliCore] Browser.startListening
2017-07-21 08:42:49 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:42:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 08:42:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:42:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:42:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "481FF078-D6B4-4882-B34E-C9B2B36BC911", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:481FF078-D6B4-4882-B34E-C9B2B36BC911
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:52, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 08:42:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Adve,rtiser.stopAdvertising() peerID:481FF078-D6B4-4882-B34E-C9B2B36BC911
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:52 - INFO thaliMobil,e,: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A641172C-639D-4D32-B1A9-497359EB2D5D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A641172C-639D-4D32-B1A9-497359EB2D5D
2017-07-21 0,8:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A641172C-639D-4D32-B1A9-497359EB2D5D", generation: 1)
[ThaliCore] ,A,dvertiser.startAdvertising with peerID:A641172C-639D-4D32-B1A9-497359EB2D5D
2017-07-21 08:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:42:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A641172C-639D-4D32-B1A9-497359EB2D5D
[ThaliCore] Advertiser.stopAdvertising() peerID:A641172C-639D-4D32-B1A9-497359EB2D5D,
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e,).'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:59 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:42:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:42:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:42:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:06B916F2-4AD1-4258-B3BA-A806E40E233A
2017-07-21 0,8:43:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F3BB181D-BDE1-41A0-9326-DF641A62A9D4
[ThaliCore] Browser.startListening
2017-07-21 08:43:04 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:43:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 08:43:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:06B916F2-4AD1-4258-B3BA-A806E40E233A
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1211860E-3540-4274-8371-7D60BFB282B3
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A15BD485-472B-43F5-B1FC-EFC96900E0EC
,[ThaliCore] Browser.startListening
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
,2017-07-21 08:43:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"77BBFECF-121D-4B80-B600-51C99929A3D9","generation":0}'
,2017-07-21 08:43:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 77BBFECF-121D-4B80-B600-51C99929A3D9 (syncValue: m6MgnegHSgcq1uBDKmfr1xh2PiKzXKap)'
2017-07-21 08:43:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
2017-07-21 08:43:07 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA866320-E8DD-46F0-82DE-6644335CB228","generation":0}'
2017-07-21 08:43:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:07 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"9AB7820A-F8F3-453E-834B-995FF5171EC1","generation":0}'
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:77,BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,7BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:43:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"m6MgnegHSgcq1uBDKmfr1xh2PiKzXKap","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:43:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'm6MgnegHSgcq1uBDKmfr1xh2PiKzXKap', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:43:10 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"77BBFECF-121D-4B80-B600-51C99929A3D9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:43:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:43:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"77BBFECF-121D-4B80-B600-51C99929A3D9","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
,2017-07-21 08:43:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 08:43:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EA866320-E8DD-46F0-82DE-6644335CB228 (syncValue: cyBF1L7mriWdSLRjdAfKC79sKPRDIaOt)'
,2017-07-21 08:43:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 08:43:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57582
2017-07-21 08:43:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cyBF1L7mriWdSLRjdAfKC79sKPRDIaOt","error":null,"portN,umber":57582}'
2017-07-21 08:43:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cyBF1L7mriWdSLRjdAfKC79sKPRDIaOt', error: 'null', listeningPort: '57582''
,2017-07-21 08:43:13 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-21 08:43:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,08:43:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1211860E-3540-4274-8371-7,D60BFB282B3
2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:EA866320-E8DD-46F0-82DE-6644335CB228
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57582
[ThaliCore] Session.disconnect() p,eer:EA866320-E8DD-46F0-82DE-6644335CB228:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EDC94BDF-633A-4D81-89CA-4D03B57A38FB
2017-07-21 0,8:43:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE
[ThaliCore] Browser.startListe,ning
2017-07-21 08:43:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:43:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisi,ngStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
2017-07-21 08:43:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9AB7820A-F8F3-453E-834B-995FF5171EC1","generation":0}'
2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9AB7820A-F8F3-453E-834B-995FF5171EC1, (syncValue: AuHGgJOj6DRruUcakB5hKHN1QHVwGpJ1)'
2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF51,71EC1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
2017-07-21 08:43:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9F4AE99C-CB76-483A-8EBC-33C6B96E91C4","generation":0}'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","generation":0}'
,2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9A,B7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:43:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AuHGgJOj6DRruUcakB5hKHN1QHVwGpJ1","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:43:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AuHGgJOj6DRruUcakB5hKHN1QHVwGpJ1', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:43:19 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"9AB7820A-F8F3-453E-834B-995FF5171EC1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:43:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
,2017-07-21 08:43:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9AB7820A-F8F3-453E-834B-995FF5171EC1","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:43:19 - DEBUG thaliMobile,NativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 08:43:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9F4AE99C-CB76-483A-8EBC-33C6B96E91C4 (syncValue: l1w8faag1Pi3u9I9Ct9TdPraC6kP61Od)'
,2017-07-21 08:43:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:43:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: connecting -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F4A,E99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9F4,AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] Session.init(session:identi,fier:connected:notConnected:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.deinit p,e,er:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57590
,2017-07-21 08:43:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l1w8faag1Pi3u9I9Ct9TdPraC6kP61Od","error":null,"portNumber":57590}'
,2017-07-21 08:43:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'l1w8faag1Pi3u9I9Ct9TdPraC6kP61Od', error: 'null', listeningPort: '57590''
,Connecting to the localhost:57590
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
,Connected to the localhost:57590
,2017-07-21 08:43:36 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 08:43:36 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
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
,2017-07-21 08:43:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,08:43:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EDC94BDF-633A-4D81-89CA-4,D03B57A38FB
2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57590
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l1w8faag1Pi3u9I9Ct9TdPraC6kP61Od","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9F4AE99C-CB76-483A-8EBC-33C6B96E91C4","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9F4AE99C-CB76-483A-8EBC-33C6B96E91C4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B73B52DC-F7A7-4412-9E88-BAB14F24676C
2017-07-21 0,8:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
[ThaliCore] Browser.startListening
2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:43:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
2017-07-21 08:43:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9F4AE99C-CB76-483A-8EBC-33C6B96E91C4","generation":0}'
2017-07-21 08:43:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9F4AE99C-CB76-483A-8EBC-33C6B96E91C4, (syncValue: nyzyz7yvlak7X2ckBzoysNX2x2ANqNpG)'
2017-07-21 08:43:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96,E91C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
2017-07-21 08:43:41, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","generation":0}'
2017-07-21 08:43:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:41 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C01","generation":0}'
2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14", generation: 0)
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14","generation":0}'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607
[ThaliCore] Advertiser: session connected Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607
,[ThaliCore] Session.session(_:peer:didChange:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607
[ThaliCore] Session.startOutputStream(with:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607
,[ThaliCore] Session.startOutputStream(with:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607
[ThaliCore] Session.startOutputStream(with:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4, [1, 2, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 08:43:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:43:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-21 08:43:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9F4AE99C,-CB76-483A-8EBC-33C6B96E91C4 error: max retries exceeded
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nyzyz7yvlak7X2ckBzoysNX2x2ANqNpG","error":"Connection could not be established","portNumber":null}'
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nyzyz7yvlak7X2ckBzoysNX2x2ANqNpG', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9F4AE99C-CB76-483A-8EBC-33C6B96E91C4","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9F4AE99C-CB76-483A-8EBC-33C6B96E91C4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:52 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,[ThaliCore] Session.deinit peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B98D732E-24B1-45E1-B5D1-9838E2970C6A (syncValue: ivyRAdFh0uRP7aVID3sX8LWT6dRrl0Nm)'
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:52 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 08:43:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:43:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [1, 3, 4]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (163,84 bytes):'
2017-07-21 08:43:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client di,sconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,8D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
,[ThaliCore] Session.deinit peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,8D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
[ThaliCore] Advertiser: session connected Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
,[ThaliCore] Session.session(_:peer:didChange:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,8D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
[ThaliCore] Session.startOutputStream(with:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [1, 3, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
[ThaliCore] Session.startOutputStream(with:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
[,ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 3, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
,[ThaliCore] Session.startOutputStream(with:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 3, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (2220 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 3, 6, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cli,ent disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [1, 3, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [1, 3]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,8D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B98D732E,-24B1-45E1-B5D1-9838E2970C6A error: max retries exceeded
2017-07-21 08:44:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ivyRAdFh0uRP7aVID3sX8LWT6dRrl0Nm","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:44:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ivyRAdFh0uRP7aVID3sX8LWT6dRrl0Nm', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:44:03 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:44:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 08:44:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 08:44:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:03 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:44:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C91ADCD2-C046-4AA4-A330-A15E9E6C4C01 (syncValue: TLOPi0a,GVr5N2bzxewfXgclh4cSEpGLN)'
2017-07-21 08:44:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C91ADCD2-C046,-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:44:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57620
,2017-07-21 08:44:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TLOPi0aGVr5N2bzxewfXgclh4cSEpGLN","error":null,"portNumber":57620}'
,2017-07-21 08:44:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TLOPi0aGVr5N2bzxewfXgclh4cSEpGLN', error: 'null', listeningPort: '57620''
,Connecting to the localhost:57620
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
Connecting to the localhost:57620
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 3, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connecting to the localhost:57620
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
,Connected to the localhost:57620
,Connected to the localhost:57620
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 8, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 3, 8, 9, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:57620
,ok 91 correct string length
,2017-07-21 08:44:06 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 94 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3, 9, 10]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 95 got the same data b,ack
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams,() vsID:9
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:9 [1, 3, 10]
,ok 96 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-21 08:44:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,08:44:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 08:44:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B73B52DC-F7A7-4412-9E88-B,AB14F24676C
2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57620
[ThaliCore] Session.disconnect() peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
,[ThaliCore] Session.deinit peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:44:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
,# Can shift data securely
,[ThaliCore] Session.session(_:peer:didChange:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45E607 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A
,2017-07-21 08:44:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:09B96C17-6759-44ED-AB0C-84B9366E4D7E
[ThaliCore] Browser.startListening
2017-07-21 08:44:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:44:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 08:44:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
2017-07-21 08:44:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C01","generation":0}'
,2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C91ADCD2-C046-4AA4-A330-A15E9E6C4C01 (syncValue: lbsxHnLZUhzW3nUDYDbXGo2QgypYwO6i)'
,2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
2017-07-21 08:44:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","generation":0}'
2017-07-21 08:44:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:10 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
2017-07-21 08:44:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
,2017-07-21 08:44:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
2017-07-21 08:44:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","generation":0}'
2017-07-21 08:44:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:11 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:44:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C9,1ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C9,1ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C9,1ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9D9FAEF4-411C-448B-9D20-057A4E07889E
[ThaliCore] Advertiser: session connected Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9D9FAEF4-411C-448B-9D20-057A4E07889E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01 error: max retries exceeded
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lbsxHnLZUhzW3nUDYDbXGo2QgypYwO6i","error":"Connection could not be established","portNumber":null}'
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lbsxHnLZUhzW3nUDYDbXGo2QgypYwO6i', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C01","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C01","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 36797C19-C4DE-4D06-8AE0-EA5972815BBE (syncValue: Yq9AXSm2qltKVHM87QrxGMyQLD0n27iQ)'
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:44:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F4B435F-5E0B-4866-9A20-B919CF8A1E0D
[ThaliCore] Advertiser: session connected Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3F4B435F-5E0B-4866-9A20-B919CF8A1E0D state: notConnected -> connecting
,[ThaliCore] Session.deinit peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9D9FAEF4-411C-448B-9D20-057A4E07889E
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D9FAEF4-411C-448B-9D20-057A4E07889E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D9FAEF4-411C-448B-9D20-057A4E07889E
[ThaliCore] Session.startOutputStream(with:) peer:9D9FAEF4-411C-448B-9D20-057A4E07889E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 3, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57639
2017-07-21 08:44:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Yq9AXSm2qltKVHM87QrxGMyQLD0n27iQ",,"error":null,"portNumber":57639}'
2017-07-21 08:44:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Yq9AXSm2qltKVHM87QrxGMyQLD0n27iQ', error: 'null', listeningPort: '57639''
,Connecting to the localhost:57639
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
,Server received psk id: psk-id
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 3, 10, 11, 12]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:57639
2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 10, 11]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3F4B435F-5E0B-4866-9A20-B919CF8A1E0D
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F4B435F-5E0B-4866-9A20-B919CF8A1E0D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F4B435F-5E0B-4866-9A20-B919CF8A1E0D
[ThaliCore] Session.startOutputStream(with:) peer:3F4B435F-5E0B-4866-9A20-B919CF8A1E0D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 3, 10, 11, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocket,DisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStream,sHandler disconnecting:false
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [1, 3, 10, 11]
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 3, 10]
,2017-07-21 08:44:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D9FAEF4-411C-448B-9D20-057A4E07889E state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:3F4B435F-5E0B-4866-9A20-B919CF8A1E0D
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57639
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:3F4B435F-5E0B-4866-9A20-B919CF8A1E0D
[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Yq9AXSm2qltKVHM87QrxGMyQLD0n27iQ","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5E5BE70F-136E-443D-9F11-E27DA37D9C01", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5E5BE70F-136E-443D-9F11-E27DA37D9C01
,2017-07-21 08:44:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1A462663-AE7A-4988-A9E0-172273A06F5D
[ThaliCore] Browser.startListening
2017-07-21 08:44:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:44:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
2017-07-21 08:44:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C01","generation":0}'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C91ADCD2-C046-4AA4-A330-A15E9E6C4C01, (syncValue: w3wAfXy6jbBARmUcyO5eL44pXMIyOcGk)'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6,C4C01", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","generation":0}'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A","generation":0}'
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
2017-07-21 08:44:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:25 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
2017-07-21 08:44:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","generation":0}'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:25 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestU,tils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E5BE70F-136E-443D-9F11-E27DA37D9C01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E5BE70F-136E-443D-9F11-E27DA37D9C01", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C9,1ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C9,1ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 08:44:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"w3wAfXy6jbBARmUcyO5eL44pXMIyOcGk","error":"Peer is unavailable","portNumber":null}'
2017-07-21 08:44:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolve,d -syncValue: 'w3wAfXy6jbBARmUcyO5eL44pXMIyOcGk', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:44:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C,01","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:44:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 08:44:33 - DEBUG thaliMobileNativeWrapper:, 'Received peer availability changed event with {"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C01","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:44:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityCh,angedEvent due to not being in started state'
,2017-07-21 08:44:33 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 08:44:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 741F0AA8-1BCC-4724-89EE-9E3D1B5337DF (syncValue: hy3NVeGr8lcIJpqojE7lcLTmuQGyprlU)'
,2017-07-21 08:44:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:44:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57652
,2017-07-21 08:44:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hy3NVeGr8lcIJpqojE7lcLTmuQGyprlU","error":null,"portNumber":57652}'
,2017-07-21 08:44:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hy3NVeGr8lcIJpqojE7lcLTmuQGyprlU', error: 'null', listeningPort: '57652''
,Connecting to the localhost:57652
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
,Connected to the localhost:57652
,2017-07-21 08:44:36 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 08:44:36 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 3, 10, 14]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,ok 102 got the same data back
,[ThaliCore] VirtualSocket.deinit vsID:14 [1, 3, 10]
,# teardown
,2017-07-21 08:44:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:5E5BE70F-136E-443D-9F11-E27DA37D9C01
2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08,:,44:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57652
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hy3NVeGr8lcIJpqojE7lcLTmuQGyprlU","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserRelay.deinit
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A82D9AAA-85F1-4547-9251-1EB3C5540D7C
[ThaliCore] Browser.startListening
2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:44:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 08:44:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:,errorHandler:) Peer(uuid: "69DEB6CB-9101-44A3-A4F2-AEE6F73A7B03", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:69DEB6CB-9101-44A3-A4F2-AEE6F73A7B03
2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpda,teNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:44:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"ne,t,workType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}]'
2017-07-21 08:44:44 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}'
,2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69DEB6CB-9101-44A3-A4F2-AEE6F73A7B03:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69DEB6CB-9101-44A3-A4F2-AEE6F73A7B03", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9DF51DA4-C820-4929-9B7F-F9FC8ADF5DD7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9DF51DA4-C820-4929-9B7F-F9FC8ADF5DD7", generation: 0)
2017-07-21 08:44:44 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9DF51DA4-C820-4929-9B7F-F9FC8ADF5DD7","generation":0}]'
2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"9DF51DA4-C820-4929-9B7F-F9FC8ADF5DD7","generation":0}'
2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,08:44:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:69DEB6CB-9101-44A3-A4F2-A,EE6F73A7B03
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-21 08:44:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C0799A9C-453C-4600-81FC-8EC678F6B696
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1CAFF781-246D-4A24-A80D-D93FF4BA6951", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1CAFF781-246D-4A24-A80D-D93FF4BA6951
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
ok 110 advertisingActive should be tr,ue
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1CAFF781-246D-4A24-A80D-D93FF4BA6951
ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-21 08:44:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 08:44:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 08:44:53 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 08:44:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:54 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 08:44:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 08:44:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 08:44:55 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4a4f855a-1d8a-4be2-8e8b-e4121b481065 error: startListeningNotActive
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"F69RM0DDINjKqiMRhOGQ7s1m5qnP7VsN","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
,ok 130 listeningPort is null
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4a4f855a-1d8a-4be2-8e8b-e4121b481065","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4a4f855a-1d8a-4be2-8e8b-e4121b481065","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FC13E276-7D86-4EC5-8755-172C65CD3BF1
,[ThaliCore] Browser.startListening
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z1dusVgfaSViLwLQtZQwhqqPnddETgty","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 08:44:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:41FB8E71-730D-4AF5-B551-405E05B84F59
,[ThaliCore] Browser.startListening
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
,ok 138 Got right error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","generation":0}'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}]'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}'
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Filt,ered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:210772dc-8e78-46ae-bac5-2d6638b927b0
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:42482938-AF2F-480B-B29A-69D1D0864D42
2017-07-21 0,8:44:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:90256AE2-A1A8-41AF-8741-55727912E1A1
[ThaliCore] Browser.startListening
2017-07-21 08:44:59 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:44:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
2017-07-21 08:44:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","generation":0}'
,2017-07-21 08:44:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E0B635E3-F14B-483A-B337-CC90A5ACF439 (syncValue: fx6sN3RMKiickXeI71WaiOsOKYw7CBIS)'
2017-07-21 08:44:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0,B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-21 08:44:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}'
,2017-07-21 08:44:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
2017-07-21 08:45:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B9F325A6-C7EE-4930-9B90-2AB7F638F9EB","generation":0}'
2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
,2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"66D54677-E5CE-4872-AF60-920DE29F35DA","generation":0}'
,2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:45:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fx6sN3RMKiickXeI71WaiOsOKYw7CBIS","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:45:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fx6sN3RMKiickXeI71WaiOsOKYw7CBIS', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:45:05 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:45:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:45:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:45:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:45:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B9F325A6-C7EE-4930-9B90-2AB7F638F9EB (syncValue: jT5XkVcntlBT7EuJ4CDXPcX,uSMTbL333)'
2017-07-21 08:45:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9F325A6-C7EE-4930-9B90-2AB7F,638F9EB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:45:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57665
2017-07-21 08:45:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jT5XkVcntlBT7EuJ4CDXPcXuSMTbL333",,"error":null,"portNumber":57665}'
2017-07-21 08:45:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jT5XkVcntlBT7EuJ4CDXPcXuSMTbL333', error: 'null', listeningPort: '57665''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0) found active relay
,2017-07-21 08:45:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"D8Zj5fgMcLZ5r4j52DFyT1UoMSCw8OzS","error":null,"portNumber":57665}'
,ok 144 No error
,ok 145 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 10, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0) found active relay
,2017-07-21 08:45:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"20mrFvpxQjnPnSotaN7nWLJgkckS3cjl","error":null,"portNumber":57665}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,2017-07-21 08:45:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:45:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 08:45:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:42482938-AF2F-480B-B29A-69D1D0864D42
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:45:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57665
[ThaliCore] VirtualSocket.closeStr,eams() vsID:15
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:15 [1, 3, 10]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jT5XkVcntlBT7EuJ4CDXPcXuSMTbL333","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B9F325A6-C7EE-4930-9B90-2AB7F638F9EB","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B9F325A6-C7EE-4930-9B90-2AB7F638F9EB","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-07-21 08:45:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 08:45:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 08:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 08:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 08:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 08:45:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 08:45:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:14 - DEBUG createNativeListener: 'listening 57668'
,ok 149 Should throw
,# teardown
,2017-07-21 08:45:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:14 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'listening 57670'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'listening 57673'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'listening 57677'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client co,nnection to node - 0 - 0 - closed'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP cli,ent connection <-> Mux - 0 - close'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'listening 57682'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'listening 57686'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'listening 57690'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'listening 57694'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'listening 57698'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 08:45:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 08:45:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:19 - DEBUG createNativeListener: 'listening 57750'
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'listening 57754'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:21 - DEBUG createNativeListener: 'listening 57757'
ok 196 port must be in range
,# teardown
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:21 - DEBUG createNativeListener: 'listening 57758'
ok 197 second start should return same port
,# teardown
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'listening 57760'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 08:45:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-21 08:45:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-21 08:45:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 57762
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:45:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Me,thod peerAvailabilityChanged registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F178AC04-DA74-48EA-963C-5633E8815F6D
2017-07-21 0,8:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C
[ThaliCore] Browser.startListening
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"66D54677-E5CE-4872-AF60-920DE29F35DA","generation":0}'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 66D54677-E5CE-4872-AF60-920DE29F35DA (syncValue: GBLqX24gj1q2xrc1ILoQjexU2kkdMb1F)'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
2017-07-21 08:45:23 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0518CF61-E252-42B9-9611-C4C458B9CB70","generation":0}'
2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:23 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
2017-07-21 08:45:23 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DE913D1C-0249-4CCF-AF63-177E5F6EFB18","generation":0}'
2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:23 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,6D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,6D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,6D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:66D54677,-E5CE-4872-AF60-920DE29F35DA error: max retries exceeded
2017-07-21 08:45:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GBLqX24gj1q2xrc1ILoQjexU2kkdMb1F","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:45:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GBLqX24gj1q2xrc1ILoQjexU2kkdMb1F', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:45:33 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"66D54677-E5CE-4872-AF60-920DE29F35DA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:45:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 08:45:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"66D54677-E5CE-4872-AF60-920DE29F35DA","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 08:45:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:33 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:45:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0518CF61-E252-42B9-9611-C4C458B9CB70 (syncValue: oOjIobz,0q2WOw2OBZQtfyy9gC9p98wfF)'
2017-07-21 08:45:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0518CF61-E252,-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:45:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772
[ThaliCore] Advertiser: session connected Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57777
,2017-07-21 08:45:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oOjIobz0q2WOw2OBZQtfyy9gC9p98wfF","error":null,"portNumber":57777}'
,2017-07-21 08:45:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oOjIobz0q2WOw2OBZQtfyy9gC9p98wfF', error: 'null', listeningPort: '57777''
,ok 210 should be equal
,2017-07-21 08:45:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DE913D1C-0249-4CCF-AF63-177E5F6EFB18 (syncValue: eYrhWE9Gv1ZEJGCtBrNf0vRmRMknsjcy)'
,2017-07-21 08:45:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:45:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772
,[ThaliCore] Session.session(_:peer:didChange:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57781
,2017-07-21 08:45:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eYrhWE9Gv1ZEJGCtBrNf0vRmRMknsjcy","error":null,"portNumber":57781}'
,2017-07-21 08:45:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eYrhWE9Gv1ZEJGCtBrNf0vRmRMknsjcy', error: 'null', listeningPort: '57781''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9
[ThaliCore] Advertiser: session connected Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,08:45:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 08:45:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F178AC04-DA74-48EA-963C-5,633E8815F6D
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:45:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:0518CF61-E252-42B9-9611-C4C458B9CB70
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57777
,[ThaliCore] Session.disconnect() peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:CE8BE39E-B612-4A41-A856-2534FC139BD9
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57781
,[ThaliCore] Session.disconnect() peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CE8BE39E-B612-4A41-A856-2534FC139BD9
,[ThaliCore] Session.session(_:peer:didChange:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
,[ThaliCore] Session.deinit peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:45:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 57783
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:45:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Me,thod peerAvailabilityChanged registered to native'
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:184ABA8E-200B-45B1-B43C-D18C7DCD96DA
2017-07-21 0,8:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:86F951D8-EEC1-4408-BE41-8D2039509318
[ThaliCore] Browser.startListening
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:45:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
2017-07-21 08:45:48 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DE913D1C-0249-4CCF-AF63-177E5F6EFB18","generation":0}'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DE913D1C-0249-4CCF-AF63-177E5F6EFB18, (syncValue: FN7kwjUmUOPeI0UBVROIL3FZ6PPoPLKM)'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6,EFB18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
,2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0518CF61-E252-42B9-9611-C4C458B9CB70","generation":0}'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
2017-07-21 08:45:48 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:48 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
,2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DE,913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,E913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DE,913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,E913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DE,913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,E913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:45:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FN7kwjUmUOPeI0UBVROIL3FZ6PPoPLKM","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:45:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FN7kwjUmUOPeI0UBVROIL3FZ6PPoPLKM', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:45:56 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"DE913D1C-0249-4CCF-AF63-177E5F6EFB18","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:45:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:45:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DE913D1C-0249-4CCF-AF63-177E5F6EFB18","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 08:45:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:45:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1D07C8CF-1737-4DDE-9F61-B35248B29157 (syncValue: o6xkdusm0MgwaHXcP0hwDE4,vEALMUQL4)'
2017-07-21 08:45:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1D07C8CF-1737-4DDE-9F61-B3524,8B29157:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:45:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57798
2017-07-21 08:45:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"o6xkdusm0MgwaHXcP0hwDE4vEALMUQL4",,"error":null,"portNumber":57798}'
2017-07-21 08:45:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'o6xkdusm0MgwaHXcP0hwDE4vEALMUQL4', error: 'null', listeningPort: '57798''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-21 08:45:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0012F678-84C7-457A-A520-2401E6F33249 (syncValue: Lfgv32zC5dotxscCorus3Ji6V7bgMEKK)'
,2017-07-21 08:45:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0012F678-84C7-457A-A520-2401E6F33249:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0012F678-84C7-457A-A520-2401E6F33249:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0012F678-84C7-457A-A520-2401E6F33249:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57805
,2017-07-21 08:46:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Lfgv32zC5dotxscCorus3Ji6V7bgMEKK","error":null,"portNumber":57805}'
,2017-07-21 08:46:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Lfgv32zC5dotxscCorus3Ji6V7bgMEKK', error: 'null', listeningPort: '57805''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ED34D69B-9B8A-4289-B861-3ADB0758843A
[ThaliCore] Advertiser: session connected Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ED34D69B-9B8A-4289-B861-3ADB0758843A state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3
[ThaliCore] Session.session(_:peer:didChange:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3 state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ED34D69B-9B8A-4289-B861-3ADB0758843A
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED34D69B-9B8A-4289-B861-3ADB0758843A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,08:46:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:184ABA8E-200B-45B1-B43C-D,18C7DCD96DA
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:1D07C8CF-1737-4DDE-9F61-B35248B29157
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57798
[ThaliCore] Session.disconnect() peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[Thali,Core] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:0012F678-84C7-457A-A520-2401E6F33249
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57805
[ThaliCore] Session.disconnect() peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED34D69B-9B8A-4289-B861-3ADB0758843A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] Session.deinit peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] Session.deinit peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:46:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:16 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'listening 57809'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 57810'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5EED64A4-D719-4179-A16B-C3ADDBFDCD7A
[ThaliCore] Browser.st,artListening
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 230 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAd,vertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"adv,ertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 57811'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "83873A2D-A41B-47DC-A8CE-7945C0261FF8", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:83873A2D-A41B-47DC-A8CE-7945C0261FF8
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:4,6:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "83873A2D-A41B-47DC-A8CE-7945C0261FF8", gen,eration: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:83873A2D-A41B-47DC-A8CE-7945C0261FF8
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:83873A2D-A41B-47DC-A8CE-7945C0261FF8
,[ThaliCore] Advertiser.stopAdvertising() peerID:83873A2D-A41B-47DC-A8CE-7945C0261FF8
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'listening 57814'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 08:46:19 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'listening 57815'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D7F2D336-B5E6-4D70-B59E-7E8FA83F08DB
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EACC5E74-B128-4160-A4DE-7625B3B08923", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EACC5E74-B128-4160-A4DE-7625B3B08923
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
,ok 243 all connection succeed
,# teardown
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}]'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}]'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:EACC5E74-B128-4160-A4DE-7625B3B08923
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'listening 57818'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D4C32E31-074F-4E29-AE26-2087B7ACC3FC
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "01527F4E-8932-4332-861B-1073C8911AC0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:01527F4E-8932-4332-861B-1073C8911AC0
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D07C8C,F-1737-4DDE-9F61-B35248B29157", generation: 0)
,# teardown
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}]'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}]'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:01527F4E-8932-4332-861B-1073C8911AC0
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'listening 57820'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7ECC4BD6-2A89-42CF-9B99-091E4915ED9C
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "72F981B0-28D9-4555-B9E2-0A74813B7C01", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:72F981B0-28D9-4555-B9E2-0A74813B7C01
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:20 ,- INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType,":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:72F981B0-28D9-4555-B9E2-0A74813B7C01
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 247 is stopped after calling stop,
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}]'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 08:46:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:22 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 08:46:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 08:46:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 08:46:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 08:46:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 08:46:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 08:46:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 08:46:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 08:46:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 08:46:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'listening 57823'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FB5A5288-F04B-4DBB-9D81-32515F662DD7
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-21 08:46:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'listening 57824'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8505CC01-3763-4E88-AD89-8999B75A692F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8505CC01-3763-4E88-AD89-8999B75A692F
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:8505CC01-3763-4E88-AD89-8999B75A692F
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'listening 57826'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'listening 57827'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E92B03C9-8F52-4FDD-ADCE-9EA8F3D4CEF0
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8612FE02-B68E-496A-8634-5D5B7D6BC112", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8612FE02-B68E-496A-8634-5D5B7D6BC112
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}]'
2017-07-21 08:46:27 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D07C8CF-1737-4DDE-9F61-B35248B291,57:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"generation":0,"portNumber":null}'
ok 277 portNumber equal null
,# teardown
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}]'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8612FE02-B68E-496A-8634-5D5B7D6BC112
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-21 08:46:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-21 08:46:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 08:46:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 08:46:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'listening 57829'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9366C858-869E-4C6B-B9C3-2F5DE82E0A93
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CC9895C0-1863-4433-8EB2-717D7B77F3A7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CC9895C0-1863-4433-8EB2-717D7B77F3A7
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation",:0}'
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0012F678-84C7-457A-A520-2401E6F33249 (syncValue: F9iZGQ0G5OliKRnjdaAhp9nj0w3v451c)'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}]'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:46:29 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}]'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 08:46:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
2017-07-21 08:46:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","generation":0}]'
2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","generation":0}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:46:30 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:46:30 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0)
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","generation":0}]'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","generation":0}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CC9895C0-1863-4433-8EB2-717D7B77F3A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CC9895C0-1863-4433-8EB2-717D7B77F3A7", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0012F678-84C7-457A-A520-2401E6F33249:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:00,12F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,012F678-84C7-457A-A520-2401E6F33249", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0012F678-84C7-457A-A520-2401E6F33249:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0012F678-84C7-457A-A520-2401E6F33249:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:00,12F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,012F678-84C7-457A-A520-2401E6F33249", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0012F678-84C7-457A-A520-2401E6F33249:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,2017-07-21 08:46:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}]'
,2017-07-21 08:46:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
,2017-07-21 08:46:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 08:46:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0012F678-84C7-457A-A520-2401E6F33249:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:00,12F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,012F678-84C7-457A-A520-2401E6F33249", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:46:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"F9iZGQ0G5OliKRnjdaAhp9nj0w3v451c","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:46:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'F9iZGQ0G5OliKRnjdaAhp9nj0w3v451c', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:46:38 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:46:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:46:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 08:46:38 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:46:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:0012F678-84C7-457A-A520-2401E6F33249
,2017-07-21 08:46:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 08:46:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9A320958-A40E-4FA4-A2BE-93FF8B9E07DE (syncValue: cBZQ1tEbfcgEg9woDx4txK9R7Is06TMg)'
,2017-07-21 08:46:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0012F678-84C7-457A-A520-2401E6F33249:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57838
2017-07-21 08:46:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cBZQ1tEbfcgEg9woDx4txK9R7Is06TMg",,"error":null,"portNumber":57838}'
2017-07-21 08:46:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cBZQ1tEbfcgEg9woDx4txK9R7Is06TMg', error: 'null', listeningPort: '57838''
,2017-07-21 08:46:41 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 3, 10, 16]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:46:43 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:46:43 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CC9895C0-1863-4433-8EB2-717D7B77F3A7
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:16 [1, 3, 10]
ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57838
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cBZQ1tEbfcgEg9woDx4txK9R7Is06TMg","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
[ThaliCore] BrowserRelay.deinit
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:45 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 08:46:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 08:46:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:46 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-21 08:46:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:46:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'listening 57840'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'listening 57841'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:74BD86BB-D41C-4D83-907B-C060779584A4
[ThaliCore] Browser.st,artListening
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
ok 309 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","generation":0}]'
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","generation":0}'
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:46:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 08:46:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'listening 57842'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5973346E-5F70-41AA-A27C-3150B4C84BF3", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:5973346E-5F70-41AA-A27C-3150B4C84BF3
2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5973346E-5F70-41AA-A27C-3150B4C84BF3", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:5973346E-5F70-41AA-A27C-3150B4C84BF3
2017-07-21 0,8:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 315 error should be null
,ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:5973346E-5F70-41AA-A27C-3150B4C84BF3
,[ThaliCore] Advertiser.stopAdvertising() peerID:5973346E-5F70-41AA-A27C-3150B4C84BF3
2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 08:46:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'listening 57845'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
,ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 08:46:48 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
ok 328 native router should be bad
,# teardown
,ok 329 error should be null
,ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 08:46:49 - DEBUG thaliMobileNativeWrapper: 'listening 57846'
,ok 332 first call should succeed
,ok 333 first call should succeed
,ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:49 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 08:46:49 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
,ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 08:46:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 08:46:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e6189fee-974e-45da-87f3-43e761d91bdd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
ok 345 should not have been called more than once
,# teardown
,2017-07-21 08:46:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e6189fee-974e-45da-87f3-43e761d91bdd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
ok 347 error should be null
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
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bf9958ae-b4fd-45e3-af8b-6134326e086d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 354 peer should be available
,ok 355 cache contains native peer
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bf9958ae-b4fd-45e3-af8b-6134326e086d","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 356 peer should be unavailable
,ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
,ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"edd759c7-2128-44e6-8dd9-c2b8c4d537bb","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 362 peer should be available
,ok 363 cache contains wifi peer
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"edd759c7-2128-44e6-8dd9-c2b8c4d537bb","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 364 peer should be unavailable
,ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"31e53294-c1e8-4f0c-bef2-eaf14557e70c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bb9f761b-a355-4fee-8ccb-69f28d68119e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"31e53294-c1e8-4f0c-bef2-eaf14557e70c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bb9f761b-a355-4fee-8ccb-69f28d68119e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
2017-07-21 08:46:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6f92f9b-1343-4a60-ab8e-380a6cbd3fd6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 376 peer is available
,# teardown
,2017-07-21 08:46:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a6f92f9b-1343-4a60-ab8e-380a6cbd3fd6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 08:46:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 08:46:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"60d5a934-0435-498a-9364-a0a76ce084fc","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be ,available
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"60d5a934-0435-498a-9364-a0a76ce084fc","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be ,available
ok 388 should store correct generation
,# teardown
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"60d5a934-0435-498a-9364-a0a76ce084fc","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
,ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'listening 57847'
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bf594cc8-0626-40c2-937b-e1d89808e707","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bf594cc8-0626-40c2-937b-e1d89808e707","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bf594cc8-0626-40c2-937b-e1d89808e707","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'listening 57848'
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9e252497-0070-45c3-beb2-0630bb838f5f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9e252497-0070-45c3-beb2-0630bb838f5f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
,ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ce8d697a-4e64-4562-b5fb-81e1a8c72280","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ce8d697a-4e64-4562-b5fb-81e1a8c72280","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 405 peer should be unavailable
,ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
,ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'listening 57849'
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2e5a0b0-55f1-420f-b02d-60fe95bb4117","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83343549-4b77-4c23-a40a-774a83183b13","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 411 second peer is expected to be available
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83343549-4b77-,4c23-a40a-774a83183b13","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 412 peer became unavailable
ok 413 it was wifi peer
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83343549-4b77-4c23-a40a-774a83183b13","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83343549-4b77-4c23-a40a-774a83183b13","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a2e5a0b0-55f1-420f-b02d-60fe95bb4117","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 08:46:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'listening 57850'
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"23c2791d-3951-4e63-961f-f94f7a5355d2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 424 first peer is expected to be available
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0a8a1aa1-c0b7-4734-9ddb-6a92f75efa05","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 425 second peer is expected to be available
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"23c2791d-3951-4e63-961f-f94f7a5355d2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0a8a1aa1-c0b7-4734-9ddb-6a92f75efa05","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 08:46:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 08:46:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3bd52041-82f3-4190-828c-d15491664a93","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 437 peer discovered ,first time does not have new address
2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3bd52041-82f3-4190-828c-d15491664a93","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 438 address has not been changed
2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3bd52041-82f3-4190-828c-d15491664a93","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 439 new port handled correctly
,2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3bd52041-82f3-4190-828c-d15491664a93","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 440 new host handled, correctly
2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3bd52041-82f3-4190-828c-d15491664a93","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 441 new,AddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
,ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 08:46:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
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
,2017-07-21 08:46:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 452 error should be null
,ok 453 error should be null
,# setup
,ok 454 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 455 should be equal
,# teardown
,ok 456 error should be null
ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-21 08:46:57 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
ok 463 the same hostAddress
ok 464 the same portNumber
,# teardown
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
,ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
,ok 469 the same hostAddress
,ok 470 the same portNumber
,# teardown
,2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'listening 57851'
,2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"302d1d79-828a-41bd-a042-038a1888d8aa","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 474 Got specific error message
,# teardown
,2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"302d1d79-828a-41bd-a042-038a1888d8aa","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'listening 57852'
,2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ee2cc1e0-8e8c-4ba9-b47d-72051065e2c0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:ee2cc1e0-8e8c-4ba9-b47d-72051065e2c0
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ee2cc1e0-8e8c-4ba9-b47d-72051065e2c0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 08:46:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 08:46:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
,ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 08:46:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 08:46:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 08:46:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
,ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 08:47:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 08:47:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'listening 57853'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E266476D-878D-496A-822D-A530CBA4AD23
,[ThaliCore] Browser.startListening
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"44980ba9-07fe-4776-b490-8b8e3aa2692c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9e131205-99b9-4099-b085-1f44af3f8230","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"44980ba9-07fe-4776-b490-8b8e3aa2692c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9e131205-99b9-4099-b085-1f44af3f8230","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:47:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'listening 57854'
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"45d3806a-b00e-476b-ae74-5a0b40a00d28","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 1
,ok 513 2
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"59010565-5c31-4f33-9c2b-3ad6efa03d66","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 08:47:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"45d3806a-b00e-476b-ae74-5a0b40a00d28","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:47:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"59010565-5c31-4f33-9c2b-3ad6efa03d66","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-21 08:47:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:47:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:47:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:47:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:47:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
,ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 08:47:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'listening 57855'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4,FA7347D935", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8459AAD8-241C-4AD7-BE87-B4FA7347D935
2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
,ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53
,[ThaliCore] Browser.startListening
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", generation: 0)
2017-07-21 08:47:05 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A0E2F326-018E-4AE7-AA79-6AF20D5C5C11","generation":0}]'
2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"A0E2F326-018E-4AE7-AA79-6AF20D5C5C11","generation":0}'
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A0E2F326-018E-4AE7-AA79-6AF20D5C5C11","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:47:05 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A0E2F326-018E-4AE7-AA79-6AF20D5C5C11","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for A0E2F326-018E-4AE7-AA79-6AF20D5C5C11 (syncValue: 0)'
2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A0E2F326-018E-4AE7,-AA79-6AF20D5C5C11", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0)
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E271E485-9892-4779-A404-B48D6F6DDB5A","generation":0}]'
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E271E485-9892-4779-A404-B48D6F6DDB5A","generation":0}'
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E271E485-9892-4779-A404-B48D6F6DDB5A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:47:05 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E271E485-9892-4779-A404-B48D6F6DDB5A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7
[ThaliCore] Session.session(_:peer:didChange:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7
[ThaliCore] Session.startOutputStream(with:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,7 [1, 3, 10, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport,:57860
,2017-07-21 08:47:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":57860}'
,2017-07-21 08:47:09 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E271E485-9892-4779-A404-B48D6F6DDB5A (syncValue: 1)'
,2017-07-21 08:47:09 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 3, 10, 17, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:47:09 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:47:09 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57863
,2017-07-21 08:47:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":57863}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 3, 10, 17, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:47:12 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:47:12 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC
[ThaliCore] Advertiser: session connected Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC
,[ThaliCore] Session.startOutputStream(with:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 3, 10, 17, 18, 19, 20]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:47:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A0E2F326-018E-4AE7-AA79-6AF20D5C5C11","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:47:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E271E485-9892-4779-A404-B48D6F6DDB5A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:8459AAD8-241C-4AD7-BE87-B4FA7347D935
,2017-07-21 08:47:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [1, 3, 10, 17, 19, 20]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 08:47:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 08:47:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 08:47:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:47:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:47:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeS,treams() vsID:17
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeS,treams() vsID:20
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [1, 3, 10, 19, 20]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [1, 3, 10, 19]
,ok 527 error should be null
,ok 528 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
,[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:19 [1, 3, 10]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 08:47:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
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
,# #testThaliPeerAction - start and kill
,ok 538 initial state
ok 539 after start
2017-07-21 08:47:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 08:47:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
ok 548 agent is destroyed
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
,ok 586 enqueue is fine
,ok 587 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 588 is an agent
,ok 589 first enqueue is fine
,ok 590 is an agent
,ok 591 second enqueue is fine
,ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
,ok 595 good enqueue
,ok 596 Identity should match
,2017-07-21 08:47:31 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:47:31 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-21 08:47:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 610 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 611 null arg
ok 612 wrong arg type
ok 613 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 614 good enqueue
ok 615 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 616 good enqueue
ok 617 2nd good enqueue
ok 618 we are in the pool
ok 619 We are out of the pool
ok 620 Action was killed
ok 621 The original kill was called too
ok 622 second item is still in queue
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
,ok 627 2nd good enqueue
,ok 628 1st action is in the pool
,ok 629 2nd action is in the pool
,ok 630 1st action is out of the pool
,ok 631 2st action is out of the pool
,ok 632 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-21 08:47:33 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:47:34 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 636 Got right error
,ok 637 Start should not be called
,ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 639 Got null
,2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 640 is an agent
2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'actio,n returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 642 Got Null
,ok 643 Got another null
,2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 644 is an agent
,2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 649 should have gotten null
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-21 08:47:36 - DEBUG thaliPeer,PoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 650 Should have stopped nicely
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 654 Null 1
ok 655 (unnamed assert)
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 656 is an agent
ok 657 Null 3
,ok 658 Replication not yet called
ok 659 Notification 2 not yet called
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 666 is an agent
ok 667 First does, not throw
2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 668 is an agent
ok 669 Second does not throw
2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 08:47:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 08:47:38 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-07-21 08:47:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 08:47:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 08:47:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
,ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 08:47:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
,ok 686 correct error message
,# teardown
,2017-07-21 08:47:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-07-21 08:47:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-21 08:47:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-07-21 08:47:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-21 08:47:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-07-21 08:47:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 08:47:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
,ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-21 08:47:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 709 should be equal
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
2017-07-21 08:47:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 719 should be equal
ok 720 should be equal
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
,ok 732 keys match
,ok 733 secrets match
,ok 734 We have an entry!
,ok 735 keys match
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
,2017-07-21 08:47:58 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 08:47:58 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 08:47:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
2017-07-21 08:48:01 - WARN thaliNotificationClient: 'peer is not available'
ok 746 notification peer dictionary does not contain any peers
2017-07-21 08:48:01 - DEBUG thaliPeerPoolDefault: 'Got, err   peer not available'
,# teardown
,2017-07-21 08:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-07-21 08:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
,ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-21 08:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-21 08:48:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-21 08:48:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-21 08:48:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 08:48:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:48:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:48:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:48:06 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-07-21 08:48:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 08:48:08 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 08:48:08 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-07-21 08:48:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 08:48:09 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
,ok 771 peer state should be RESOLVED
,# teardown
,2017-07-21 08:48:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 08:48:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
,# teardown
,2017-07-21 08:48:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-21 08:48:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-21 08:48:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-21 08:48:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
,ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
,# teardown
,2017-07-21 08:48:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 08:48:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-07-21 08:48:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 08:48:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 08:48:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
,ok 803 should be 204
,# teardown
,2017-07-21 08:48:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
ok 805 should be 204
,# teardown
,2017-07-21 08:48:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-21 08:48:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 08:48:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-21 08:48:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 812 First start and on called correctly
,ok 813 First stop and removeListener called correctly
,ok 814 first action kill called
,ok 815 second action kill called
ok 816 first cleared dictionary
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
,2017-07-21 08:48:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 821 listener has been set
,ok 822 peer dictionary has expected number of entries
,ok 823 Dictionary and pool have same action
,ok 824 ads match
,ok 825 PouchDB matches
,ok 826 DB Names match
ok 827 public keys match
,ok 828 peer dictionary has expected number of entries
,ok 829 Dictionary and pool have same action
,ok 830 ads match
,ok 831 PouchDB matches
,ok 832 DB Names match
,ok 833 public keys match
,2017-07-21 08:48:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-21 08:48:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 08:48:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:48:22 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 08:48:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-21 08:48:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 08:48:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 08:48:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-21 08:48:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 08:48:24 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 08:48:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-21 08:48:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 08:48:24 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 08:48:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-21 08:48:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 08:48:25 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 08:48:25 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-21 08:48:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 08:48:28 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:48:28 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:48:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-07-21 08:48:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 08:48:33 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:48:33 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:48:36 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-21 08:48:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 08:48:36 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:48:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:48:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-21 08:48:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 08:48:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:48:41 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-21 08:48:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:48:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 860 action should be killed
,ok 861 Error should be timed out
,# teardown
,2017-07-21 08:48:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-21 08:48:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 08:48:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 08:48:45 - DEBUG thaliMobileNativeWrapper: 'listening 57991'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Browser.startListening
,2017-07-21 08:48:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:52D46020-2085-46B8-B61C-0464BC17069B
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0)
2017-07-21 08:48:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B4AFDE44-9DFC-487A-ACDF-78DA33AF1092","generation":0}]'
2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B4AFDE44-9DFC-487A-ACDF-78DA33AF1092","generation":0}'
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4AFDE44-9DFC-487A-ACDF-78DA33AF1092","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:48:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B4AFDE44-9DFC-487A-ACDF-78DA33AF1092","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B4AFDE44-9DFC-487A-ACDF-78DA33AF1092 (syncValue: 2)'
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0)
2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"71D9EF6F-6E7A-4A39-8A89-C097EA09540E","generation":0}]'
2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"71D9EF6F-6E7A-4A39-8A89-C097EA09540E","generation":0}'
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"71D9EF6F-6E7A-4A39-8A89-C097EA09540E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:48:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"71D9EF6F-6E7A-4A39-8A89-C097EA09540E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52D46020-2085-46B8-B61C-0464BC17069B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57994
2017-07-21 08:48:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":57994,}'
,2017-07-21 08:48:48 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 71D9EF6F-6E7A-4A39-8A89-C097EA09540E (syncValue: 3)'
,2017-07-21 08:48:48 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 3, 10, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [1, 3, 10, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Advertiser: session connected Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Advertiser: session connected Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D300F900-F958-490F-97A7-9933875788EF state: notConnected -> connecting
,2017-07-21 08:48:50 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [1, 3, 10, 21, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [1, 3, 10, 21, 22, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 3, 10, 21, 22, 23, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 3, 10, 21, 22, 23, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58003
,2017-07-21 08:48:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":58003}'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain, Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] Brow,serRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [1, 3, 10, 21, 22, 23, 24, 26]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [1, 3, 10, 21, 22, 23, 24, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 3, 10, 21, 22, 23, 24, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [1, 3, 10, 21, 22, 23, 24, 26, 28]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [1, 3, 10, 21, 22, 23, 24, 26]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 3, 10, 21, 22, 23, 24, 26, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 3, 10, 21, 22, 23, 24, 26, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [1, 3, 10, 21, 22, 23, 24, 29, 30]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [1, 3, 10, 21, 22, 23, 24, 29, 30, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [1, 3, 10, 21, 22, 23, 24, 30, 31]
,2017-07-21 08:48:51 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:48:52 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:48:52 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] Session.session(_:peer:didChange:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:D300F900-F958-490F-97A7-9933875788EF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 34]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 34, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 34, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,8 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 34, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 08:48:53 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:48:53 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:48:53 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40, 41, 42, 43, 44]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40, 41, 42, 44]
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40, 42, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withE,rror:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40, 42, 44, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40, 42, 44, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40, 42, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-21 08:48:54 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [1, 3, 10, 21, 22, 23, 24, 30, 31, 32, 33, 36, 37, 38, 39, 40, 42, 44, 45, 47]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:48:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:48:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:30
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] TCPListener.socketDidDi,sconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) ac,cepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliC,ore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] VirtualSocket.deinit vsID:30 [1, ,3, 10, 21, 22, 23, 24, 31, 32, 33, 36, 37, 38, 39, 40, 42, 44, 45, 47]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHand,ler socket removed, count:1
[ThaliCore] VirtualSocket.deinit vsID:32 [1, 3, 10, 21, 22, 23, 24, 31, 33, 36, 37, 38, 39, 40, 42, 44, 45, 47]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [1, 3, 10, 21, 22, 23, 24, 31, 36, 37, 38, 39, 40, 42, 44, 45, 47]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [1, 3, 10, 21, 22, 23, 24, 31, 36, 37, 38, 39, 40, 42, 44, 47]
,2017-07-21 08:48:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 08:48:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] TCPListener.socketDidDis,connect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) soc,ket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [1, 3, 10, 21, 23, 24, 31, 36, 37, 38, 39, 40, 42, 44, 47]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [1, 3, 10, 21, 24, 31, 36, 37, 38, 39, 40, 42, 44, 47]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [1, 3, 10, 21, 31, 36, 37, 38, 39, 40, 42, 44, 47]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [1, 3, 10, 21, 36, 37, 38, 39, 40, 42, 44, 47]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[Thali,Core] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[T,haliCore] VirtualSocket.deinit vsID:36 [1, 3, 10, 21, 37, 38, 39, 40, 42, 44, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[T,haliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [1, 3, 10, 21, 38, 39, 40, 42, 44, 47]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [1, 3, 10, 21, 38, 39, 42, 44, 47]
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [1, 3, 10, 21, 38, 39, 42, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconne,ct(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [1, 3, 10, 21, 39, 42, 47]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [1, 3, 10, 21, 42, 47]
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket,.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:f,alse socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:fa,lse
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [1, 3, 10, 21, 47]
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [1, 3, 10, 21]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:51:45 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-21 08:51:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:51:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:51:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:51:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-4,1B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-4,1B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-4,1B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-4,1B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-4,1B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-21 08:58:45 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07,-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGG,ER result: passed - enqueue and run in order'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and en,queueAtTop'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously',
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-21 08:58:45 - INFO CoordinatedC,lient: '***TEST_LOGGER result: passed - another'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
2017-07-21 08:58:45 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-21 08:58:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-4,1B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 867 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-21 08:58:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-4,1B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-4,1B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-4,1B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-4,1B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:01:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B,0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:01:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/74C419B7-9152-41B0-A11A-260C820D0CF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
