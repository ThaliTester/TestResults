#### Test 96918947a106de9_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96918947a106de9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/96634E89-2A21-48E8-8C0E-2245C4677BA6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/96634E89-2A21-48E8-8C0E-2245C4677BA6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96918947a106de9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96918947a106de9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61890"
,(lldb)     command script import "/tmp/96634E89-2A21-48E8-8C0E-2245C4677BA6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-03 14:19:25.138 ThaliTest[3223:8748868] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/58DF8FA4-91B6-4884-A5A0-2B3C87FC4C9A/Library/Cookies/Cookies.binarycookies
,2017-02-03 14:19:25.528 ThaliTest[3223:8748868] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-03 14:19:25.530 ThaliTest[3223:8748868] Multi-tasking -> Device: YES, App: YES
,2017-02-03 14:19:25.552 ThaliTest[3223:8748868] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-03 14:19:27.723 ThaliTest[3223:8748868] Using UIWebView
,2017-02-03 14:19:27.730 ThaliTest[3223:8748868] [CDVTimer][handleopenurl] 0.342011ms
,2017-02-03 14:19:27.737 ThaliTest[3223:8748868] [CDVTimer][intentandnavigationfilter] 6.385982ms
,2017-02-03 14:19:27.737 ThaliTest[3223:8748868] [CDVTimer][gesturehandler] 0.267982ms
,2017-02-03 14:19:27.738 ThaliTest[3223:8748868] [CDVTimer][TotalPluginStartup] 8.520961ms
,2017-02-03 14:19:34.703 ThaliTest[3223:8748868] Resetting plugins due to page load.
,2017-02-03 14:19:38.204 ThaliTest[3223:8748868] Finished load of: file:///var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/index.html
,2017-02-03 14:19:38.477 ThaliTest[3223:8748868] JXcore Cordova plugin initializing
,2017-02-03 14:19:38.478 ThaliTest[3223:8749134] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-03 13:19:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-03 13:19:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-03 13:19:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-03 13:19:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-02-03 13:19:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-03 13:19:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-03 13:19:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-02-03 13:20:17 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  28.0072740316391
,2017-02-03 13:20:18 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
2017-02-03 13:20:18 - WARN testUtils: 'myNameCallback not set!'
,2017-02-03 13:20:20 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-02-03 13:20:20 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-02-03 13:20:20 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-02-03 13:20:21 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-02-03 13:20:22 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-02-03 13:20:22 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-02-03 13:20:22 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-02-03 13:20:22 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-02-03 13:20:22 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-02-03 13:20:22 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-02-03 13:20:22 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-02-03 13:20:23 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-02-03 13:20:24 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-02-03 13:20:24 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-02-03 13:20:24 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-02-03 13:20:24 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-02-03 13:20:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-02-03 13:20:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-02-03 13:20:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-02-03 13:20:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,# teardown
,2017-02-03 13:22:47 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-02-03 13:22:47 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-02-03 13:22:47 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-02-03 13:22:47 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-02-03 13:22:47 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Call of onCheckpointReached handler on a single db change, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/mobile/Containers/Bundle/Application/E640B,C99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/no,de_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:,1
''
2017-02-03 13:22:47 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-02-03 13:24:45 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-02-03 13:24:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:24:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:24:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:24:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:40:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:40:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:40:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6,F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:40:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/E640BC99,-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/E640BC99-6F8C-4F0A-8F19-D32845275BE7/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
