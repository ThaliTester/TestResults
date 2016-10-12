#### Test 8883810243c6d6d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8883810243c6d6d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A11B21C1-C872-4889-B701-0337098B1965/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A11B21C1-C872-4889-B701-0337098B1965/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8883810243c6d6d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8883810243c6d6d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60817"
,(lldb)     command script import "/tmp/A11B21C1-C872-4889-B701-0337098B1965/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-12 16:03:08.243 ThaliTest[2141:4304436] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6E6232BD-DFBB-4EE7-9344-EE560ACF764B/Library/Cookies/Cookies.binarycookies
,2016-10-12 16:03:08.285 ThaliTest[2141:4304436] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-12 16:03:08.286 ThaliTest[2141:4304436] Multi-tasking -> Device: YES, App: YES
,2016-10-12 16:03:08.298 ThaliTest[2141:4304436] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-12 16:03:08.579 ThaliTest[2141:4304436] Using UIWebView
,2016-10-12 16:03:08.582 ThaliTest[2141:4304436] [CDVTimer][handleopenurl] 0.136971ms
,2016-10-12 16:03:08.586 ThaliTest[2141:4304436] [CDVTimer][intentandnavigationfilter] 3.418028ms
2016-10-12 16:03:08.586 ThaliTest[2141:4304436] [CDVTimer][gesturehandler] 0.128984ms
2016-10-12 16:03:08.586 ThaliTest[2141:4304436] [CDVTimer][TotalPluginStartup] 4.459023ms
,2016-10-12 16:03:14.320 ThaliTest[2141:4304436] Resetting plugins due to page load.
,2016-10-12 16:03:14.621 ThaliTest[2141:4304436] Finished load of: file:///var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/index.html
,2016-10-12 16:03:14.960 ThaliTest[2141:4304436] JXcore Cordova plugin initializing
,2016-10-12 16:03:14.962 ThaliTest[2141:4304655] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-12 14:03:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-12 14:03:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-12 14:03:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-12 14:03:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-12 14:03:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-12 14:03:45 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  74
Number of passed tests:  74
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  19.81630998849869
,2016-10-12 14:03:45 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-10-12 14:03:46 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-1'
,2016-10-12 14:03:46 - WARN testUtils: 'myNameCallback not set!'
,2016-10-12 14:03:46 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-12 14:03:48 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-12 14:03:48 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-12 14:03:48 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-12 14:03:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-12 14:03:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-12 14:03:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-12 14:03:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-12 14:03:50 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-12 14:03:50 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-12 14:03:50 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-12 14:03:50 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-12 14:03:51 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-12 16:03:51.824 ThaliTest[2141:4304436] THREAD WARNING: ['JXcore'] took '6149.490967' ms. Plugin should use a background thread.
,2016-10-12 14:03:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:03:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-12 14:03:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-12 14:03:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:03:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:03:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:03:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:03:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:03:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:03:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:03:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:03:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:03:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transp,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:03:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:03:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:03:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:03:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:04:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:04:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transp,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:04:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:04:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:04:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:04:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:04:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:04:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:04:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:04:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:04:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 14:04:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-12 14:04:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8F1CCFD9,-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-12 16:04:06.300 ThaliTest[2141:4304655] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/lib/CoordinatedClie,n,t.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/li,b/CoordinatedClient.js:220:1"},{"_fileName":"/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_co,lumnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Appl,ication/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers,/,Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node,_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager,.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:,5,07:5"},{"_fileName":"/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnN,umber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/contai,ners/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototy,pe.connect/errorSub<@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-,A,486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/,Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/Tha,liTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486,-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-12 14:04:06 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedCl,i,ent.prototype._error@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-E,EA07730B4D2/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/sock,et.js:133:5
    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/contai,ners/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA077,3,0B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/socket.io-c,lient/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.pr,ototype.onError@/private/var/containers/Bundle/Application/8F1CCFD9-6800-4983-A486-EEA07730B4D2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-12 14:04:06 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED
```
