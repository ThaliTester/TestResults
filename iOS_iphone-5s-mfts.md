#### Test 124853546ae83d78_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/124853546ae83d78/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5F400718-42AD-4233-A394-7AED7C8AF78C/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/5F400718-42AD-4233-A394-7AED7C8AF78C/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/124853546ae83d78/build_ios/ThaliTest.app"
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Current executable set to '/Users/thali/Github/CI/builder/builds/124853546ae83d78/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52297"
,(lldb)     command script import "/tmp/5F400718-42AD-4233-A394-7AED7C8AF78C/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
JXcore engine is started
,2017-06-09 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-09 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-09 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-09 12:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-09 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-09 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-09 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
(lldb) ,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-06-09 12:51:41 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.504572093486786
(lldb) ,2017-06-09 12:51:41 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-06-09 12:51:41 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-06-09 12:51:44 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-09 12:51:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-09 12:51:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-06-09 12:51:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-06-09 12:51:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-06-09 12:51:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-06-09 12:51:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-06-09 12:51:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-06-09 12:51:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-06-09 12:51:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-06-09 12:51:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-06-09 12:51:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-06-09 12:51:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-06-09 12:51:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-06-09 12:51:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-06-09 12:51:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-06-09 12:51:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-06-09 12:51:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-06-09 12:51:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-06-09 12:51:48 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-06-09 12:51:48 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-06-09 12:51:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-09 12:51:51 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-06-09 12:51:51 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-06-09 12:52:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-06-09 12:52:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-06-09 12:52:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-06-09 12:52:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,2017-06-09 12:53:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
(lldb) ,2017-06-09 12:53:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-06-09 12:53:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning, set to false'
2017-06-09 12:53:34 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - closeAll works even with a server that is not listening yet witheatNotRunning set to true, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/privat(lldb) ,e/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C2,5C26B2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:(lldb) ,1(lldb) ,3
    at $9@timers.js:120:1
''
2017-06-09 12:53:34 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-06-09 12:54:43 - DEBUG CoordinatedClient: 'all tests completed'
(lldb) ,2017-06-09 12:57:02 - DEBUG CoordinatedClient: 'test client disconnected'
2017-06-09 12:57:02 - DEBUG CoordinatedClient: 'test client failed'
(lldb) ,2017-06-09 12:57:02 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished', test: 'closeAll works even, with a server that is not listening yet witheatNotRunning set to true'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:291(lldb) ,:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/71B6E298,-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_modules/socket(lldb) ,.,io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Appli(lldb) ,cation/71B6E298-7143-4F5A-99D7-D620C25C26B2/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-06-09 12:57:02 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
