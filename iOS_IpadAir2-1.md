#### Test 86147834358da51_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86147834358da51/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6514DE26-7A8B-4082-84F4-687935A90651/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6514DE26-7A8B-4082-84F4-687935A90651/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86147834358da51/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86147834358da51/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51011"
,(lldb)     command script import "/tmp/6514DE26-7A8B-4082-84F4-687935A90651/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-05 01:16:55.118 ThaliTest[3805:7007344] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5ACD181F-A03E-4C25-8FFE-05FE0BA0191E/Library/Cookies/Cookies.binarycookies
,2016-10-05 01:16:55.489 ThaliTest[3805:7007344] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-05 01:16:55.490 ThaliTest[3805:7007344] Multi-tasking -> Device: YES, App: YES
,2016-10-05 01:16:55.510 ThaliTest[3805:7007344] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-05 01:16:57.475 ThaliTest[3805:7007344] Using UIWebView
,2016-10-05 01:16:57.493 ThaliTest[3805:7007344] [CDVTimer][handleopenurl] 0.352979ms
,2016-10-05 01:16:57.500 ThaliTest[3805:7007344] [CDVTimer][intentandnavigationfilter] 6.361008ms
,2016-10-05 01:16:57.500 ThaliTest[3805:7007344] [CDVTimer][gesturehandler] 0.286043ms
,2016-10-05 01:16:57.501 ThaliTest[3805:7007344] [CDVTimer][TotalPluginStartup] 8.574009ms
,2016-10-05 01:17:03.751 ThaliTest[3805:7007344] Resetting plugins due to page load.
,2016-10-05 01:17:06.904 ThaliTest[3805:7007344] Finished load of: file:///var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/index.html
,2016-10-05 01:17:07.112 ThaliTest[3805:7007344] JXcore Cordova plugin initializing
,2016-10-05 01:17:07.112 ThaliTest[3805:7007618] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-04 23:17:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-04 23:17:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-04 23:17:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-04 23:17:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-04 23:17:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,received session: <ThaliCore.Session: 0x161630690>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("C258D0BC-E05E-49F7-9AB8-06AA6BAC2A7B")
,nil
,nil
,Optional("EC857485-8613-4A18-B131-DF219E6699BD")
,Optional("71E7F938-2860-4430-AF52-302C2D2ADBF9")
,2016-10-04 23:17:36 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  54
,Number of failed tests:  2
Number of ignored tests:  0
,Total duration:  19.47939199209213
,Failed to execute UT.
,2016-10-04 23:17:36 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-10-04 23:17:36 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-04 23:17:36 - DEBUG UnitTest_app: 'My device name is: Apple-IpadAir2-1'
,2016-10-04 23:17:36 - WARN testUtils: 'myNameCallback not set!'
,2016-10-04 23:17:36 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-04 23:17:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-04 23:17:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-04 23:17:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-04 23:17:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-04 23:17:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-04 23:17:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-04 23:17:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-04 23:17:40 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-04 23:17:40 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-04 23:17:40 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-04 23:17:40 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-04 23:17:40 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-04 23:17:41 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-05 01:17:41.641 ThaliTest[3805:7007344] THREAD WARNING: ['JXcore'] took '5428.646240' ms. Plugin should use a background thread.
,2016-10-04 23:17:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 01:17:56.264 ThaliTest[3805:7007618] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coor,dinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/lib/CoordinatedClient.,js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":",7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/App,lication/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Con,tainers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9,FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager,.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconn,ect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/man,ager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber",:"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket,.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-04 23:17:56 - ERROR TestsProcess: 'uncaught exception, error: ',TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle,/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/error,Sub<@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6B545B5,B-3BDF-486D-8836-9FA63BED3B71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BDF-486D-8836-9FA63BED3B71/Thali,Test.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-04 23:17:56 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/6B545B5B-3BD
```
