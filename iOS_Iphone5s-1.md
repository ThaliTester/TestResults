#### Test 878597992c267bc_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/BB960537-CA1B-45CF-AA4C-7EA3CB983E14/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/BB960537-CA1B-45CF-AA4C-7EA3CB983E14/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55189"
,(lldb)     command script import "/tmp/BB960537-CA1B-45CF-AA4C-7EA3CB983E14/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-04 11:46:46.063 ThaliTest[3717:7877458] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5C3DFD18-CB9C-4CF4-9A3D-2BA50C71166E/Library/Cookies/Cookies.binarycookies
,2016-10-04 11:46:46.181 ThaliTest[3717:7877458] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-04 11:46:46.183 ThaliTest[3717:7877458] Multi-tasking -> Device: YES, App: YES
,2016-10-04 11:46:46.209 ThaliTest[3717:7877458] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-04 11:46:47.778 ThaliTest[3717:7877458] Using UIWebView
,2016-10-04 11:46:47.788 ThaliTest[3717:7877458] [CDVTimer][handleopenurl] 0.456989ms
,2016-10-04 11:46:47.799 ThaliTest[3717:7877458] [CDVTimer][intentandnavigationfilter] 10.584950ms
2016-10-04 11:46:47.800 ThaliTest[3717:7877458] [CDVTimer][gesturehandler] 0.388026ms
2016-10-04 11:46:47.800 ThaliTest[3717:7877458] [CDVTimer][TotalPlugin,Startup] 14.407992ms
,2016-10-04 11:46:53.764 ThaliTest[3717:7877458] Resetting plugins due to page load.
,2016-10-04 11:46:56.902 ThaliTest[3717:7877458] Finished load of: file:///var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/index.html
,2016-10-04 11:46:57.214 ThaliTest[3717:7877458] JXcore Cordova plugin initializing
,2016-10-04 11:46:57.215 ThaliTest[3717:7877695] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-04 09:47:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-04 09:47:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-04 09:47:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-04 09:47:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-04 09:47:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,received session: <ThaliCore.Session: 0x10c55d6d0>
,Optional("7837A959-6586-48EB-BD6F-B08D3F98AC86")
,nil
,nil
,Optional("9A4C209B-67D2-4292-A7C6-D8CF000DA9B8")
,Optional("989CA6F7-C2A8-4B97-A1CD-1D0CA56E1C18")
,2016-10-04 09:47:26 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  60
,Number of passed tests:  60
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  15.99071198701859
,2016-10-04 09:47:26 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-10-04 09:47:26 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone5s-1'
2016-10-04 09:47:26 - WARN testUtils: 'myNameCallback not set!'
2016-10-04 09:47:26 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-04 09:47:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-04 09:47:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-04 09:47:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-04 09:47:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-04 09:47:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-04 09:47:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-04 09:47:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-04 09:47:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-04 09:47:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-04 09:47:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-04 09:47:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-04 09:47:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-04 09:47:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-04 09:47:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-04 09:47:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-04 09:47:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-04 09:47:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-04 09:47:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-04 09:47:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-04 09:47:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-04 09:47:32 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-04 09:47:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-04 11:47:33.255 ThaliTest[3717:7877458] THREAD WARNING: ['JXcore'] took '7034.185303' ms. Plugin should use a background thread.
,2016-10-04 09:47:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 11:47:52.092 ThaliTest[3717:7877695] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coor,dinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/lib/CoordinatedClient.,js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":",7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/App,lication/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Con,tainers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A,28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager,.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconn,ect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/man,ager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber",:"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket,.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-04 09:47:52 - ERROR TestsProcess: 'uncaught exception, error: ',TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle,/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/error,Sub<@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6754236,B-6E05-42BE-AFE8-A28B2E963094/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6754236B-6E05-42BE-AFE8-A28B2E963094/Thali,Test.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-04 09:47:52 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/6754236B-6E0
```
