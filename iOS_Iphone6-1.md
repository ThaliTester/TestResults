#### Test 878597992c267bc_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/61FEC7A8-C1AF-48A4-BEE3-E573DE475743/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/61FEC7A8-C1AF-48A4-BEE3-E573DE475743/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55073"
,(lldb)     command script import "/tmp/61FEC7A8-C1AF-48A4-BEE3-E573DE475743/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-04 11:46:34.268 ThaliTest[1857:3268696] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0D2E40A3-FD07-4591-B757-D52F70369769/Library/Cookies/Cookies.binarycookies
,2016-10-04 11:46:34.313 ThaliTest[1857:3268696] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-04 11:46:34.314 ThaliTest[1857:3268696] Multi-tasking -> Device: YES, App: YES
,2016-10-04 11:46:34.327 ThaliTest[1857:3268696] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-04 11:46:34.642 ThaliTest[1857:3268696] Using UIWebView
2016-10-04 11:46:34.645 ThaliTest[1857:3268696] [CDVTimer][handleopenurl] 0.153959ms
2016-10-04 11:46:34.649 ThaliTest[1857:3268696] [CDVTimer][intentandnavigationfilter] 3.713012ms
2016-10,-04 11:46:34.649 ThaliTest[1857:3268696] [CDVTimer][gesturehandler] 0.128984ms
2016-10-04 11:46:34.649 ThaliTest[1857:3268696] [CDVTimer][TotalPluginStartup] 4.680037ms
,2016-10-04 11:46:39.820 ThaliTest[1857:3268696] Resetting plugins due to page load.
,2016-10-04 11:46:40.176 ThaliTest[1857:3268696] Finished load of: file:///var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/index.html
,2016-10-04 11:46:40.522 ThaliTest[1857:3268696] JXcore Cordova plugin initializing
2016-10-04 11:46:40.523 ThaliTest[1857:3268865] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-04 09:46:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-04 09:46:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-04 09:46:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-04 09:46:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-04 09:46:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,received session: <ThaliCore.Session: 0x146062800>
,Optional("D1B43E70-FAAE-4831-A49B-6815F3A7B697")
nil
,nil
,Optional("74CE37E3-D229-4092-BDE9-AD8BFF9389F8")
,Optional("51F75CA6-D124-4354-AD7E-B4ABE22084E0")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-10-04 09:47:07 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  60
Number of passed tests:  60
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  16.44009298086166
201,6-10-04 09:47:07 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-10-04 09:47:08 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-1'
,2016-10-04 09:47:08 - WARN testUtils: 'myNameCallback not set!'
,2016-10-04 09:47:08 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-04 09:47:10 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-04 09:47:10 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-04 09:47:10 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-04 09:47:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-04 09:47:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-04 09:47:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-04 09:47:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-04 09:47:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-04 09:47:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-04 09:47:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-04 09:47:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-04 09:47:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-04 11:47:14.011 ThaliTest[1857:3268696] THREAD WARNING: ['JXcore'] took '6210.776123' ms. Plugin should use a background thread.
,2016-10-04 09:47:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 09:47:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 09:47:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/37CF1E56,-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 11:47:27.776 ThaliTest[1857:3268865] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/lib/CoordinatedClie,n,t.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/li,b/CoordinatedClient.js:220:1"},{"_fileName":"/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_co,lumnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Appl,ication/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers,/,Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node,_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager,.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:,5,07:5"},{"_fileName":"/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnN,umber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/contai,ners/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototy,pe.connect/errorSub<@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-,A,04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/,Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/Tha,liTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F,-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-04 09:47:27 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedCl,i,ent.prototype._error@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C,7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/sock,et.js:133:5
    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/contai,ners/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEE,A3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/socket.io-c,lient/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.pr,ototype.onError@/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
,2016-10-04 09:47:27 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/containers/Bundle/Application/37CF1E56-852A-40E0-A04F-C7FFEEEA3C68/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js 220:0
```
