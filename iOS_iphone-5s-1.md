#### Test 969189473645b2d_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A3C8D362-84A3-447E-B1C7-5DC91EB51249/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A3C8D362-84A3-447E-B1C7-5DC91EB51249/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49830"
,(lldb)     command script import "/tmp/A3C8D362-84A3-447E-B1C7-5DC91EB51249/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 16:56:54.973 ThaliTest[1422:3058710] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/735309A2-E680-47A7-A954-084A1B50CBED/Library/Cookies/Cookies.binarycookies
,2016-12-26 16:56:55.104 ThaliTest[1422:3058710] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 16:56:55.105 ThaliTest[1422:3058710] Multi-tasking -> Device: YES, App: YES
,2016-12-26 16:56:55.124 ThaliTest[1422:3058710] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 16:56:56.632 ThaliTest[1422:3058710] Using UIWebView
,2016-12-26 16:56:56.641 ThaliTest[1422:3058710] [CDVTimer][handleopenurl] 0.636041ms
,2016-12-26 16:56:56.652 ThaliTest[1422:3058710] [CDVTimer][intentandnavigationfilter] 10.351002ms
2016-12-26 16:56:56.653 ThaliTest[1422:3058710] [CDVTimer][gesturehandler] 0.393987ms
2016-12-26 16:56:56.654 ThaliTest[1422:3058710] [CDVTimer][TotalPlugin,Startup] 13.386965ms
,2016-12-26 16:57:02.273 ThaliTest[1422:3058710] Resetting plugins due to page load.
,2016-12-26 16:57:05.535 ThaliTest[1422:3058710] Finished load of: file:///var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/index.html
,2016-12-26 16:57:05.839 ThaliTest[1422:3058710] JXcore Cordova plugin initializing
,2016-12-26 16:57:05.841 ThaliTest[1422:3058921] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 15:57:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 15:57:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 15:57:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-12-26 15:57:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-26 15:57:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 15:57:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-12-26 15:57:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-26 15:57:44 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.94681000709534
,2016-12-26 15:57:44 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-12-26 15:57:44 - DEBUG UnitTest_app: 'My device name is: Apple-iphone-5s-1'
2016-12-26 15:57:44 - WARN testUtils: 'myNameCallback not set!'
,2016-12-26 15:57:47 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2016-12-26 15:57:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-12-26 15:57:48 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-12-26 15:57:48 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-12-26 15:57:49 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-12-26 15:57:49 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-12-26 15:57:49 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-12-26 15:57:50 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-12-26 15:57:50 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-12-26 15:57:50 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-12-26 15:57:50 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2016-12-26 15:57:50 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-12-26 15:57:50 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-12-26 15:57:51 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-12-26 15:57:51 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-12-26 15:57:51 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-12-26 15:57:51 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-12-26 15:57:51 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-12-26 15:57:51 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-12-26 15:57:51 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-12-26 15:57:51 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-12-26 15:57:51 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-12-26 15:57:51 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-12-26 15:57:52 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-12-26 15:57:52 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2016-12-26 16:57:52.478 ThaliTest[1422:3058710] THREAD WARNING: ['JXcore'] took '8212.927002' ms. Plugin should use a background thread.
,2016-12-26 15:57:54 - DEBUG CoordinatedClient: 'connected to the test server'
,2016-12-26 16:02:45 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2016-12-26 16:02:50 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510D,B2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/node_modules/en,gine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobi,le/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-26 16:02:50 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-26 16:02:50 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510D,B2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/node_modules/en,gine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobi,le/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-26 16:02:50 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-26 16:02:50 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/node_modul,es/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocke,t.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/0798DE98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/0798D,E98-AEBB-43F8-8CC5-FE7B80510DB2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-26 16:02:50 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
