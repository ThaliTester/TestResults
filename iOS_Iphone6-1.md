#### Test 86147834358da51_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86147834358da51/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B2E414CF-53CB-4552-AF37-C57A4E88F27E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B2E414CF-53CB-4552-AF37-C57A4E88F27E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86147834358da51/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86147834358da51/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51013"
,(lldb)     command script import "/tmp/B2E414CF-53CB-4552-AF37-C57A4E88F27E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-05 01:16:54.273 ThaliTest[1872:3338614] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9564F5C6-7CBE-4E01-9EE6-A6AD00CACFAA/Library/Cookies/Cookies.binarycookies
,2016-10-05 01:16:54.345 ThaliTest[1872:3338614] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-05 01:16:54.346 ThaliTest[1872:3338614] Multi-tasking -> Device: YES, App: YES
,2016-10-05 01:16:54.361 ThaliTest[1872:3338614] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-05 01:16:54.766 ThaliTest[1872:3338614] Using UIWebView
,2016-10-05 01:16:54.774 ThaliTest[1872:3338614] [CDVTimer][handleopenurl] 0.523984ms
,2016-10-05 01:16:54.781 ThaliTest[1872:3338614] [CDVTimer][intentandnavigationfilter] 7.175982ms
2016-10-05 01:16:54.782 ThaliTest[1872:3338614] [CDVTimer][gesturehandler] 0.294030ms
2016-10-05 01:16:54.782 ThaliTest[1872:3338614] [CDVTimer][TotalPluginS,tartup] 9.624004ms
,2016-10-05 01:16:59.960 ThaliTest[1872:3338614] Resetting plugins due to page load.
,2016-10-05 01:17:00.431 ThaliTest[1872:3338614] Finished load of: file:///var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/index.html
,2016-10-05 01:17:00.761 ThaliTest[1872:3338614] JXcore Cordova plugin initializing
2016-10-05 01:17:00.762 ThaliTest[1872:3338796] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-04 23:17:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-04 23:17:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-04 23:17:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-04 23:17:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-04 23:17:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,received session: <ThaliCore.Session: 0x13ed49a50>
,Optional("6C8E53B1-0BD5-4CF0-B926-BF6D679330B4")
nil
,nil
,Optional("4AED6A58-6609-4E29-B71B-7132E292B006")
,Optional("0B356CCE-AD37-4B60-97E8-A30A393DF058")
,2016-10-04 23:17:25 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  56
Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.36780595779419
,2016-10-04 23:17:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-04 23:17:26 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-1'
,2016-10-04 23:17:26 - WARN testUtils: 'myNameCallback not set!'
,2016-10-04 23:17:26 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-04 23:17:28 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-04 23:17:28 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-04 23:17:28 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-04 23:17:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-04 23:17:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-04 23:17:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-04 23:17:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-04 23:17:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-04 23:17:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-04 23:17:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-04 23:17:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-04 23:17:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-05 01:17:32.038 ThaliTest[1872:3338614] THREAD WARNING: ['JXcore'] took '6096.542969' ms. Plugin should use a background thread.
,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke2016-10-04 23:17:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,t.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 23:17:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 23:17:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,port.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 23:17:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 23:17:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 23:17:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 23:17:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 23:17:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 23:17:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-04 23:17:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-04 23:17:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D8CEB17D,-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-05 01:17:46.245 ThaliTest[1872:3338796] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coordinated,Client.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_,fileName":"/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emi,tter.prototype.emit@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D,1,891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers/Bundle/Application/D8CEB17D-C143-4,283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/mana,ger.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumbe,r,":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/,containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager,.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/containers/Bundle/Application/D8CEB17D-C,143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var,/,containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www,/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/D8CEB17D-C143-4,283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules,/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/j,x,core/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-04 23:17:46 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/,containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxco,re/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.protot,ype.emitAll@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/D8CEB17D-,C,143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/nod,e_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at, Emitter.prototype.emit@/private/var/containers/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/conta,iners/Bundle/Application/D8CEB17D-C143-4283-B9B1-D1891E231A50/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-04 23:17:46 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undef
```
