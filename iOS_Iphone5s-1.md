#### Test 86147834358da51_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86147834358da51/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/42250C97-C192-409C-B0C6-21231FB8AEA4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/42250C97-C192-409C-B0C6-21231FB8AEA4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86147834358da51/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86147834358da51/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51017"
,(lldb)     command script import "/tmp/42250C97-C192-409C-B0C6-21231FB8AEA4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-05 01:16:58.731 ThaliTest[3743:7965315] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B4855DC8-D3FA-4C9B-B2AC-B2CE4DE159CD/Library/Cookies/Cookies.binarycookies
,2016-10-05 01:16:58.856 ThaliTest[3743:7965315] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-05 01:16:58.858 ThaliTest[3743:7965315] Multi-tasking -> Device: YES, App: YES
,2016-10-05 01:16:58.879 ThaliTest[3743:7965315] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-05 01:17:00.391 ThaliTest[3743:7965315] Using UIWebView
,2016-10-05 01:17:00.402 ThaliTest[3743:7965315] [CDVTimer][handleopenurl] 0.487030ms
,2016-10-05 01:17:00.411 ThaliTest[3743:7965315] [CDVTimer][intentandnavigationfilter] 8.359015ms
2016-10-05 01:17:00.412 ThaliTest[3743:7965315] [CDVTimer][gesturehandler] 0.359952ms
2016-10-05 01:17:00.412 ThaliTest[3743:7965315] [CDVTimer][TotalPluginS,tartup] 11.025012ms
,2016-10-05 01:17:07.494 ThaliTest[3743:7965315] Resetting plugins due to page load.
,2016-10-05 01:17:12.179 ThaliTest[3743:7965315] Finished load of: file:///var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/index.html
,2016-10-05 01:17:12.480 ThaliTest[3743:7965315] JXcore Cordova plugin initializing
,2016-10-05 01:17:12.481 ThaliTest[3743:7965534] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-04 23:17:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-04 23:17:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-04 23:17:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-04 23:17:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-04 23:17:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,received session: <ThaliCore.Session: 0x127cc2700>
,Optional("E7E475B3-B76F-46A0-8431-8D3B948FEC21")
,nil
,nil
,Optional("44A99991-C2BE-4581-B0FB-E74662444F4F")
,Optional("9CD090BF-7270-4D7D-BE46-C5CB3B9D7D3D")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-04 23:17:40 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.72568601369858
,2016-10-04 23:17:40 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-10-04 23:17:40 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone5s-1'
2016-10-04 23:17:40 - WARN testUtils: 'myNameCallback not set!'
,2016-10-04 23:17:40 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-04 23:17:42 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-04 23:17:43 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-04 23:17:43 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-04 23:17:44 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-04 23:17:44 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-04 23:17:44 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-04 23:17:44 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-04 23:17:45 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-04 23:17:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-04 23:17:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-04 23:17:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-04 23:17:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-04 23:17:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-04 23:17:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-04 23:17:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-10-04 23:17:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-04 23:17:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-04 23:17:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-05 01:17:47.384 ThaliTest[3743:7965315] THREAD WARNING: ['JXcore'] took '7223.195801' ms. Plugin should use a background thread.
,2016-10-04 23:17:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:18:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:18:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:18:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 01:18:01.623 ThaliTest[3743:7965534] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coor,dinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/lib/CoordinatedClient.,js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":",7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/App,lication/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Con,tainers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-0,00228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager,.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconn,ect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/man,ager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber",:"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket,.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-04 23:18:01 - ERROR TestsProcess: 'uncaught exception, error: ',TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle,/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/error,Sub<@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/5CABD4A,E-CD0F-402D-86BC-000228D5BD17/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0F-402D-86BC-000228D5BD17/Thali,Test.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-04 23:18:01 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/5CABD4AE-CD0
```
