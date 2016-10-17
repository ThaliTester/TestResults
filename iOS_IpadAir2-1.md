#### Test 89624796e90776b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89624796e90776b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/16F473D5-E845-48BE-8998-B4DEAE4863BA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/16F473D5-E845-48BE-8998-B4DEAE4863BA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89624796e90776b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89624796e90776b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63230"
,(lldb)     command script import "/tmp/16F473D5-E845-48BE-8998-B4DEAE4863BA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-17 16:02:55.499 ThaliTest[4331:8547576] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4CF59093-68B5-435F-89FF-943AD90C419E/Library/Cookies/Cookies.binarycookies
,2016-10-17 16:02:55.864 ThaliTest[4331:8547576] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-17 16:02:55.865 ThaliTest[4331:8547576] Multi-tasking -> Device: YES, App: YES
,2016-10-17 16:02:55.886 ThaliTest[4331:8547576] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-17 16:02:57.982 ThaliTest[4331:8547576] Using UIWebView
,2016-10-17 16:02:57.989 ThaliTest[4331:8547576] [CDVTimer][handleopenurl] 0.479996ms
,2016-10-17 16:02:57.997 ThaliTest[4331:8547576] [CDVTimer][intentandnavigationfilter] 6.950974ms
,2016-10-17 16:02:57.997 ThaliTest[4331:8547576] [CDVTimer][gesturehandler] 0.396013ms
,2016-10-17 16:02:57.998 ThaliTest[4331:8547576] [CDVTimer][TotalPluginStartup] 9.788990ms
,2016-10-17 16:03:04.772 ThaliTest[4331:8547576] Resetting plugins due to page load.
,2016-10-17 16:03:08.108 ThaliTest[4331:8547576] Finished load of: file:///var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/index.html
,2016-10-17 16:03:08.376 ThaliTest[4331:8547576] JXcore Cordova plugin initializing
,2016-10-17 16:03:08.377 ThaliTest[4331:8547826] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-17 14:03:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-17 14:03:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-17 14:03:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-17 14:03:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-17 14:03:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-10-17 14:03:50 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  104
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.40375596284866
,2016-10-17 14:03:50 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-17 14:03:51 - DEBUG UnitTest_app: 'My device name is: Apple-IpadAir2-1'
2016-10-17 14:03:51 - WARN testUtils: 'myNameCallback not set!'
2016-10-17 14:03:51 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-17 14:03:53 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-17 14:03:54 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-17 14:03:54 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-17 14:03:55 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-17 14:03:55 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-17 14:03:55 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-17 14:03:55 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-17 16:03:57.169 ThaliTest[4331:8547576] THREAD WARNING: ['JXcore'] took '6500.857910' ms. Plugin should use a background thread.
,2016-10-17 14:03:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 16:04:13.147 ThaliTest[4331:8547826] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coor,dinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/lib/CoordinatedClient.,js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":",7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/App,lication/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Con,tainers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-9,6AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager,.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconn,ect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/man,ager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket,.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-17 14:04:13 - ERROR TestsProcess: 'uncaught exception, error: ',TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle,/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/error,Sub<@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/05BECCC,F-5E6F-4F6C-90CC-96AC879968AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6F-4F6C-90CC-96AC879968AB/Thali,Test.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-17 14:04:13 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/05BECCCF-5E6
```
