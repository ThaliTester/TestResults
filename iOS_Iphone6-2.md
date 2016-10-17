#### Test 89624796e90776b_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89624796e90776b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/71B431D8-559F-469A-BC1E-5946C04827B9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/71B431D8-559F-469A-BC1E-5946C04827B9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89624796e90776b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89624796e90776b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63233"
,(lldb)     command script import "/tmp/71B431D8-559F-469A-BC1E-5946C04827B9/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-17 07:03:07.740 ThaliTest[2459:4462327] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8598E0C2-E213-4E08-BCC6-AF6B3F2209A3/Library/Cookies/Cookies.binarycookies
,2016-10-17 07:03:07.797 ThaliTest[2459:4462327] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-17 07:03:07.798 ThaliTest[2459:4462327] Multi-tasking -> Device: YES, App: YES
,2016-10-17 07:03:07.811 ThaliTest[2459:4462327] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-17 07:03:08.162 ThaliTest[2459:4462327] Using UIWebView
,2016-10-17 07:03:08.167 ThaliTest[2459:4462327] [CDVTimer][handleopenurl] 0.173986ms
,2016-10-17 07:03:08.171 ThaliTest[2459:4462327] [CDVTimer][intentandnavigationfilter] 4.480958ms
2016-10-17 07:03:08.172 ThaliTest[2459:4462327] [CDVTimer][gesturehandler] 0.153005ms
2016-10-17 07:03:08.172 ThaliTest[2459:4462327] [CDVTimer][TotalPluginStartup] 5.649030ms
,2016-10-17 07:03:16.075 ThaliTest[2459:4462327] Resetting plugins due to page load.
,2016-10-17 07:03:16.402 ThaliTest[2459:4462327] Finished load of: file:///var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/index.html
,2016-10-17 07:03:16.737 ThaliTest[2459:4462327] JXcore Cordova plugin initializing
,2016-10-17 07:03:16.738 ThaliTest[2459:4462526] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-17 14:03:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-17 14:03:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-17 14:03:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-17 14:03:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-17 14:03:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-17 14:03:50 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  104
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.35257297754288
,2016-10-17 14:03:50 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-10-17 14:03:51 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-2'
2016-10-17 14:03:51 - WARN testUtils: 'myNameCallback not set!'
2016-10-17 14:03:51 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-17 14:03:53 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-17 14:03:53 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-17 14:03:53 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-17 14:03:54 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-17 14:03:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-17 14:03:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-17 14:03:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-17 14:03:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-17 14:03:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-17 14:03:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-17 14:03:57 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-17 07:03:57.100 ThaliTest[2459:4462327] THREAD WARNING: ['JXcore'] took '6276.038086' ms. Plugin should use a background thread.
,2016-10-17 14:03:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-17 14:03:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-17 14:03:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:03:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-17 14:03:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-17 14:04:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-17 14:04:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-17 14:04:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-17 14:04:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-17 14:04:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 14:04:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5D221496,-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-17 07:04:15.984 ThaliTest[2459:4462526] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coordinated,Client.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_,fileName":"/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emi,tter.prototype.emit@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-7,2,976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers/Bundle/Application/5D221496-18BE-4,45E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/mana,ger.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumbe,r,":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/,containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager,.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/containers/Bundle/Application/5D221496-1,8BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var,/,containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www,/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/5D221496-18BE-4,45E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules,/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/j,x,core/node_modules/engine.io-client/lib/socket.js:670:3"}]
,2016-10-17 14:04:16 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976,443563A/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at So,cket.prototype.emit@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/5D22,1496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_mo,dules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Ma,nager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/containers/Bundle/Appl,ication/5D221496-18BE-445E-9CEC-72976443563A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/containers/Bundle/Application/5D221496-18BE-445E-9CEC-7297644356,3A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-17 14:04:16 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
