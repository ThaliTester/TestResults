#### Test 931424420cf4179_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/931424420cf4179/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/E2E62E21-0F34-4331-B498-FAC121252E21/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E2E62E21-0F34-4331-B498-FAC121252E21/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/931424420cf4179/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/931424420cf4179/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49836"
,(lldb)     command script import "/tmp/E2E62E21-0F34-4331-B498-FAC121252E21/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 14:28:32.448 ThaliTest[294:333356] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/687A3D85-D279-4C2C-960B-36C48E341BB7/Library/Cookies/Cookies.binarycookies
,2016-11-21 14:28:32.822 ThaliTest[294:333356] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 14:28:32.824 ThaliTest[294:333356] Multi-tasking -> Device: YES, App: YES
,2016-11-21 14:28:32.844 ThaliTest[294:333356] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 14:28:35.016 ThaliTest[294:333356] Using UIWebView
,2016-11-21 14:28:35.026 ThaliTest[294:333356] [CDVTimer][handleopenurl] 0.382960ms
,2016-11-21 14:28:35.033 ThaliTest[294:333356] [CDVTimer][intentandnavigationfilter] 6.424963ms
,2016-11-21 14:28:35.034 ThaliTest[294:333356] [CDVTimer][gesturehandler] 0.288010ms
2016-11-21 14:28:35.034 ThaliTest[294:333356] [CDVTimer][TotalPluginStartup] 8.673012ms
,2016-11-21 14:28:41.649 ThaliTest[294:333356] Resetting plugins due to page load.
,2016-11-21 14:28:44.683 ThaliTest[294:333356] Finished load of: file:///var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/index.html
,2016-11-21 14:28:44.930 ThaliTest[294:333356] JXcore Cordova plugin initializing
,2016-11-21 14:28:44.931 ThaliTest[294:333581] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 13:28:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 13:28:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 13:28:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-21 13:28:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-21 13:28:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 13:28:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-21 13:29:21 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  27.20670402050018
,2016-11-21 13:29:21 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-11-21 13:29:22 - DEBUG UnitTest_app: 'My device name is: Apple-IpadAir2-1'
2016-11-21 13:29:22 - WARN testUtils: 'myNameCallback not set!'
,2016-11-21 13:29:24 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: ios'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-11-21 13:29:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-11-21 13:29:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-11-21 13:29:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-11-21 13:29:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-11-21 13:29:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-11-21 13:29:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-11-21 13:29:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-11-21 13:29:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-11-21 13:29:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-11-21 13:29:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-11-21 13:29:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-11-21 14:29:27.755 ThaliTest[294:333356] THREAD WARNING: ['JXcore'] took '5973.182861' ms. Plugin should use a background thread.
,2016-11-21 13:29:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 14:29:43.578 ThaliTest[294:333581] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coordi,natedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js,:223:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7",,"_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Appli,cation/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Conta,iners/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/ww,w/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922,A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules,/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnec,t/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manag,er.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":",235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/,private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumbe,r":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/privat,e/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.p,rototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-11-21 13:29:43 - ERROR TestsProcess: 'uncaught exception, error: 'Ty,peError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:223:1
 ,   at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle/A,pplication/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.ap,p/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:,507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/errorSu,b<@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/1893877A-,17C5-426D-952F-922A5F096764/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-426D-952F-922A5F096764/ThaliTe,st.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-11-21 13:29:43 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/1893877A-17C5-
```
