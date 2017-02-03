#### Test 96918947a106de9_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96918947a106de9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/38934D38-8A41-49F4-A56A-8F19853300C2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/38934D38-8A41-49F4-A56A-8F19853300C2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96918947a106de9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96918947a106de9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61894"
,(lldb)     command script import "/tmp/38934D38-8A41-49F4-A56A-8F19853300C2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-03 14:19:29.860 ThaliTest[3271:8608336] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F82FBB7-885D-4BE1-90C3-36ABE126AA7E/Library/Cookies/Cookies.binarycookies
,2017-02-03 14:19:29.975 ThaliTest[3271:8608336] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-03 14:19:29.977 ThaliTest[3271:8608336] Multi-tasking -> Device: YES, App: YES
,2017-02-03 14:19:30.001 ThaliTest[3271:8608336] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-03 14:19:31.856 ThaliTest[3271:8608336] Using UIWebView
,2017-02-03 14:19:31.864 ThaliTest[3271:8608336] [CDVTimer][handleopenurl] 0.414014ms
,2017-02-03 14:19:31.873 ThaliTest[3271:8608336] [CDVTimer][intentandnavigationfilter] 8.203983ms
2017-02-03 14:19:31.874 ThaliTest[3271:8608336] [CDVTimer][gesturehandler] 0.363052ms
2017-02-03 14:19:31.874 ThaliTest[3271:8608336] [CDVTimer][TotalPluginS,tartup] 10.890007ms
,2017-02-03 14:19:39.139 ThaliTest[3271:8608336] Resetting plugins due to page load.
,2017-02-03 14:19:43.767 ThaliTest[3271:8608336] Finished load of: file:///var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/index.html
,2017-02-03 14:19:44.084 ThaliTest[3271:8608336] JXcore Cordova plugin initializing
,2017-02-03 14:19:44.085 ThaliTest[3271:8608572] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-03 13:19:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-03 13:19:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-03 13:19:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-03 13:19:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-02-03 13:19:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-03 13:19:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-03 13:19:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-02-03 13:20:23 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.50792002677917
,2017-02-03 13:20:24 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-02-03 13:20:24 - WARN testUtils: 'myNameCallback not set!'
,2017-02-03 13:20:27 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-02-03 13:20:27 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-02-03 13:20:27 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-02-03 13:20:27 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-02-03 13:20:28 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-02-03 13:20:29 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-02-03 13:20:29 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-02-03 13:20:29 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-02-03 13:20:29 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-02-03 13:20:29 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-02-03 13:20:29 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-02-03 13:20:29 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-02-03 13:20:29 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-02-03 13:20:31 - INFO testLoader: 'loading file: /private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-02-03 13:20:31 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-02-03 14:20:31.713 ThaliTest[3271:8608336] THREAD WARNING: ['JXcore'] took '13.771973' ms. Plugin should use a background thread.
,2017-02-03 13:20:31 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-02-03 13:20:31 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-02-03 13:20:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-02-03 13:20:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-02-03 13:20:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-02-03 13:20:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,# teardown
,2017-02-03 13:22:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-02-03 13:22:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-02-03 13:22:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-02-03 13:22:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-02-03 13:22:45 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Call of onCheckpointReached handler on a single db change, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/mobile/Containers/Bundle/Application/5F007,911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/no,de_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:,1
''
,2017-02-03 13:22:45 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-02-03 13:24:43 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-02-03 13:24:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:24:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:24:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:24:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:24:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:24:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:25:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:26:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:27:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:28:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:29:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:30:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:31:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:32:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:33:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:34:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:35:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:36:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:37:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:38:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:39:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:40:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:40:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:40:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4,923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/ww,w/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
o,nerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-03 13:40:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5F007911,-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/,www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1,
onerror@/private/var/mobile/Containers/Bundle/Application/5F007911-4923-4A34-9301-B64748B1D293/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
