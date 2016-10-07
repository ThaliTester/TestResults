#### Test 88496963915c2f2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/88496963915c2f2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E5C867B4-7351-4ED6-8ACE-58856B4EA368/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E5C867B4-7351-4ED6-8ACE-58856B4EA368/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/88496963915c2f2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/88496963915c2f2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51212"
,(lldb)     command script import "/tmp/E5C867B4-7351-4ED6-8ACE-58856B4EA368/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-07 22:07:38.041 ThaliTest[3875:8417485] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/28DDA787-764C-4151-9CF5-0C1282615AAE/Library/Cookies/Cookies.binarycookies
,2016-10-07 22:07:38.168 ThaliTest[3875:8417485] Apache Cordova native platform version 4.2.1 is starting.
2016-10-07 22:07:38.169 ThaliTest[3875:8417485] Multi-tasking -> Device: YES, App: YES
,2016-10-07 22:07:38.193 ThaliTest[3875:8417485] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-07 22:07:40.086 ThaliTest[3875:8417485] Using UIWebView
,2016-10-07 22:07:40.094 ThaliTest[3875:8417485] [CDVTimer][handleopenurl] 0.419974ms
,2016-10-07 22:07:40.105 ThaliTest[3875:8417485] [CDVTimer][intentandnavigationfilter] 10.537982ms
2016-10-07 22:07:40.106 ThaliTest[3875:8417485] [CDVTimer][gesturehandler] 0.380993ms
2016-10-07 22:07:40.106 ThaliTest[3875:8417485] [CDVTimer][TotalPluginStartup] 13.342023ms
,2016-10-07 22:07:47.884 ThaliTest[3875:8417485] Resetting plugins due to page load.
,2016-10-07 22:07:52.189 ThaliTest[3875:8417485] Finished load of: file:///var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/index.html
,2016-10-07 22:07:52.509 ThaliTest[3875:8417485] JXcore Cordova plugin initializing
,2016-10-07 22:07:52.511 ThaliTest[3875:8417726] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-07 20:08:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-07 20:08:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-07 20:08:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-07 20:08:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-07 20:08:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,received session: <ThaliCore.Session: 0x160a96c70>
,Optional("E8CD7E61-677E-4B35-BA42-94812BD66805")
,nil
,nil
,Optional("C0D3AFAD-8C8A-44D7-B770-B7EEB56B6909")
,Optional("D12BDEE6-0EB9-4222-B831-F1E57CB2A9E2")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-07 20:08:20 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  60
Number of passed tests:  60
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  14.94190394878387
,2016-10-07 20:08:20 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-10-07 20:08:20 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone5s-1'
2016-10-07 20:08:20 - WARN testUtils: 'myNameCallback not set!'
2016-10-07 20:08:20 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-10-07 20:08:23 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-07 20:08:23 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-07 20:08:23 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-07 20:08:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-07 20:08:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-07 20:08:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-07 20:08:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-07 20:08:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-07 20:08:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-07 20:08:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-07 20:08:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-07 20:08:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-07 20:08:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-07 22:08:27.817 ThaliTest[3875:8417485] THREAD WARNING: ['JXcore'] took '6844.730957' ms. Plugin should use a background thread.
,2016-10-07 20:08:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 20:08:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-07 22:08:41.568 ThaliTest[3875:8417726] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coor,dinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/lib/CoordinatedClient.,js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":",7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/App,lication/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Con,tainers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4,CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager,.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconn,ect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/man,ager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber",:"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket,.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-07 20:08:41 - ERROR TestsProcess: 'uncaught exception, error: ',TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle,/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/error,Sub<@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/DB0FAA4,4-9C89-4845-A28E-4CF4B1AE7E46/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C89-4845-A28E-4CF4B1AE7E46/Thali,Test.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-07 20:08:41 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/DB0FAA44-9C8
```
