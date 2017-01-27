#### Test 9691894700c7de5_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9691894700c7de5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B85A7D41-B060-4755-A605-0C2BE2E8243B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B85A7D41-B060-4755-A605-0C2BE2E8243B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9691894700c7de5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9691894700c7de5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59797"
,(lldb)     command script import "/tmp/B85A7D41-B060-4755-A605-0C2BE2E8243B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-27 12:10:41.694 ThaliTest[2889:7553613] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/34F04AA2-A7A0-46FE-87E8-D60CA92CC61E/Library/Cookies/Cookies.binarycookies
,2017-01-27 12:10:42.065 ThaliTest[2889:7553613] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-27 12:10:42.066 ThaliTest[2889:7553613] Multi-tasking -> Device: YES, App: YES
,2017-01-27 12:10:42.086 ThaliTest[2889:7553613] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-27 12:10:44.201 ThaliTest[2889:7553613] Using UIWebView
,2017-01-27 12:10:44.208 ThaliTest[2889:7553613] [CDVTimer][handleopenurl] 0.388980ms
,2017-01-27 12:10:44.215 ThaliTest[2889:7553613] [CDVTimer][intentandnavigationfilter] 6.447971ms
,2017-01-27 12:10:44.216 ThaliTest[2889:7553613] [CDVTimer][gesturehandler] 0.277042ms
,2017-01-27 12:10:44.216 ThaliTest[2889:7553613] [CDVTimer][TotalPluginStartup] 8.960009ms
,2017-01-27 12:10:51.392 ThaliTest[2889:7553613] Resetting plugins due to page load.
,2017-01-27 12:10:54.852 ThaliTest[2889:7553613] Finished load of: file:///var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/index.html
,2017-01-27 12:10:55.065 ThaliTest[2889:7553613] JXcore Cordova plugin initializing
,2017-01-27 12:10:55.065 ThaliTest[2889:7553869] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-27 11:11:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-27 11:11:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-27 11:11:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-01-27 11:11:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-27 11:11:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-27 11:11:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-01-27 11:11:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-27 11:11:32 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  26.5292409658432
,2017-01-27 11:11:33 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
2017-01-27 11:11:33 - WARN testUtils: 'myNameCallback not set!'
,2017-01-27 11:11:35 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-01-27 11:11:35 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-01-27 11:11:35 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-01-27 11:11:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-01-27 11:11:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-01-27 11:11:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-01-27 11:11:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-01-27 11:11:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-01-27 11:11:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-01-27 11:11:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-01-27 11:11:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-01-27 11:11:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-01-27 11:11:36 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-01-27 11:11:37 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-01-27 11:11:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-01-27 11:11:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-01-27 11:11:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-01-27 11:11:38 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-01-27 11:11:39 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-01-27 11:11:39 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-01-27 12:11:39.443 ThaliTest[2889:7553613] THREAD WARNING: ['JXcore'] took '10.495850' ms. Plugin should use a background thread.
,2017-01-27 11:11:39 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-01-27 11:11:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-01-27 11:11:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E,9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-01-27 11:11:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/95DB1D35,-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/95DB1D35-E9A9-4C4D-87F5-E6B2FD48EA14/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-01-27 11:11:47 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-01-27 11:11:47 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-01-27 11:11:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-01-27 11:11:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-01-27 11:11:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-01-27 11:12:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,ok 4 the checkpointReached handler should be called once. Called 1 time(s)
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,# teardown
,# setup
,2017-01-27 11:12:18 - ERROR pouchDBCheckpointsPlugin: 'Error while fetching db info: 'Error: ENOENT, lstat '/private/var/mobile/Containers/Data/Application/34F04AA2-A7A0-46FE-87E8-D60CA92CC61E/tmp/pouchdb-test-directory/17jr5yxi24s17jr64jbddp/000003.log'', stack: '@native:jxcore_js_object:3:12
''
,2017-01-27 11:12:18 - ERROR TestsProcess: 'uncaught promise rejection, error: 'Error: ENOENT, lstat '/private/var/mobile/Containers/Data/Application/34F04AA2-A7A0-46FE-87E8-D60CA92CC61E/tmp/pouchdb-test-directory/17jr5yxi24s17jr64jbddp/000003.log'', stack: '@native:jxcore_js_object:3:12
''
,2017-01-27 11:12:18 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
