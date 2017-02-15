#### Test 1062586553e7ecec_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1062586553e7ecec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3E38054A-B7ED-452D-B51A-8DEE841D86D3/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/3E38054A-B7ED-452D-B51A-8DEE841D86D3/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1062586553e7ecec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1062586553e7ecec/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55490"
,(lldb)     command script import "/tmp/3E38054A-B7ED-452D-B51A-8DEE841D86D3/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-15 13:07:06.959 ThaliTest[2525:10201713] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7F74817F-F6FF-479E-ABEE-B34D76A07C4E/Library/Cookies/Cookies.binarycookies
,2017-02-15 13:07:07.114 ThaliTest[2525:10201713] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-15 13:07:07.118 ThaliTest[2525:10201713] Multi-tasking -> Device: YES, App: YES
,2017-02-15 13:07:07.151 ThaliTest[2525:10201713] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-15 13:07:07.943 ThaliTest[2525:10201713] Using UIWebView
,2017-02-15 13:07:07.950 ThaliTest[2525:10201713] [CDVTimer][handleopenurl] 0.398040ms
,2017-02-15 13:07:07.957 ThaliTest[2525:10201713] [CDVTimer][intentandnavigationfilter] 7.262051ms
2017-02-15 13:07:07.958 ThaliTest[2525:10201713] [CDVTimer][gesturehandler] 0.367045ms
2017-02-15 13:07:07.958 ThaliTest[2525:10201713] [CDVTimer][TotalPlug,inStartup] 9.409010ms
,2017-02-15 13:07:18.483 ThaliTest[2525:10201713] Resetting plugins due to page load.
,2017-02-15 13:07:19.189 ThaliTest[2525:10201713] Finished load of: file:///var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/index.html
,2017-02-15 13:07:19.434 ThaliTest[2525:10201713] JXcore Cordova plugin initializing
,2017-02-15 13:07:19.436 ThaliTest[2525:10201904] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-15 12:08:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-15 12:08:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-15 12:08:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-15 12:08:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-02-15 12:08:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-15 12:08:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-15 12:08:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-02-15 12:08:35 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  33.74640899896622
,2017-02-15 12:08:35 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-mini-mfts''
,2017-02-15 12:08:35 - WARN testUtils: 'myNameCallback not set!'
,2017-02-15 12:08:43 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-02-15 12:08:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-02-15 12:08:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-02-15 12:08:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-02-15 12:08:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-02-15 12:08:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-02-15 12:08:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-02-15 12:08:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-02-15 12:08:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-02-15 12:08:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-02-15 12:08:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-02-15 12:08:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-02-15 12:08:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-02-15 12:08:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-02-15 12:08:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-02-15 12:08:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-02-15 12:08:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-02-15 12:08:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-02-15 12:08:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-02-15 12:08:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-02-15 12:08:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-02-15 12:08:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-02-15 12:08:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-02-15 12:08:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-02-15 12:08:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-02-15 12:08:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-02-15 12:08:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-02-15 12:08:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-02-15 12:08:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-02-15 12:08:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-02-15 12:08:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-02-15 12:08:56 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2017-02-15 13:08:56.960 ThaliTest[2525:10201713] THREAD WARNING: ['JXcore'] took '38.066162' ms. Plugin should use a background thread.
,2017-02-15 12:08:57 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-02-15 12:08:57 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-02-15 12:13:55 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-02-15 12:13:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47C,E-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:13:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-4,7CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47C,E-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-4,7CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47C,E-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-4,7CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47C,E-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-4,7CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47C,E-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-4,7CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47C,E-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-4,7CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47C,E-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-4,7CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47C,E-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:14:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-4,7CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47C,E-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-4,7CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47C,E-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-4,7CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/014E3FF8-4F19-47CE-8E47-393C267F345B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-15 12:15:56 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
,2017-02-15 12:15:56 - DEBUG CoordinatedClient: 'test client failed'
,2017-02-15 12:15:56 - ERROR CoordinatedClient: 'reconnect_error error: 'timeout', description: 'undefined', stack: 'undefined''
,2017-02-15 12:15:56 - DEBUG CoordinatedClient: 'test client failed'
,2017-02-15 12:15:56 - DEBUG CoordinatedClient: '20000'
,2017-02-15 12:15:56 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
,2017-02-15 12:15:56 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
