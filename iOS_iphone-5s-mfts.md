#### Test 1041482374baf670_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1041482374baf670/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/310D69A9-81C7-4D26-BAF4-72EEFAFB6B91/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/310D69A9-81C7-4D26-BAF4-72EEFAFB6B91/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1041482374baf670/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1041482374baf670/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55718"
,(lldb)     command script import "/tmp/310D69A9-81C7-4D26-BAF4-72EEFAFB6B91/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-13 18:51:10.443 ThaliTest[1481:4391668] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/371B35D1-6174-483A-8E73-5451B24A4BD3/Library/Cookies/Cookies.binarycookies
,2017-02-13 18:51:10.499 ThaliTest[1481:4391668] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-13 18:51:10.501 ThaliTest[1481:4391668] Multi-tasking -> Device: YES, App: YES
,2017-02-13 18:51:10.523 ThaliTest[1481:4391668] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-13 18:51:10.782 ThaliTest[1481:4391668] Using UIWebView
,2017-02-13 18:51:10.787 ThaliTest[1481:4391668] [CDVTimer][handleopenurl] 0.169992ms
,2017-02-13 18:51:10.790 ThaliTest[1481:4391668] [CDVTimer][intentandnavigationfilter] 2.870023ms
2017-02-13 18:51:10.790 ThaliTest[1481:4391668] [CDVTimer][gesturehandler] 0.135005ms
2017-02-13 18:51:10.790 ThaliTest[1481:4391668] [CDVTimer][TotalPluginStartup] 3.908992ms
,2017-02-13 18:51:14.167 ThaliTest[1481:4391668] Resetting plugins due to page load.
,2017-02-13 18:51:14.459 ThaliTest[1481:4391668] Finished load of: file:///var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/index.html
,2017-02-13 18:51:14.866 ThaliTest[1481:4391668] JXcore Cordova plugin initializing
2017-02-13 18:51:14.867 ThaliTest[1481:4391840] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-13 17:51:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-13 17:51:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-13 17:51:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-02-13 17:51:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-02-13 17:51:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-13 17:51:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-02-13 17:51:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 5 seconds, with unfulfilled expectations: "Browser peer found Advertiser peer". in file: Optional("<unknown>"), line: 0
,failed - BrowserManager does not have available peers to connect in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 133
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/VirtualSocketTests.swift"), line: 139
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/VirtualSocketTests.swift"), line: 93
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-02-13 17:51:56 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  112
Number of failed tests:  4
Number of ignored tests:  0
Total duration:  27.23484802246094
Failed to execute UT.
2017-02-13 17:51:56 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2017-02-13 17:51:57 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-02-13 17:51:57 - WARN testUtils: 'myNameCallback not set!'
,2017-02-13 17:52:02 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-02-13 17:52:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-02-13 17:52:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-02-13 17:52:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-02-13 17:52:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-02-13 17:52:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-02-13 17:52:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-02-13 17:52:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-02-13 17:52:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-02-13 17:52:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-02-13 17:52:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-02-13 17:52:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-02-13 17:52:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-02-13 17:52:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-02-13 17:52:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-02-13 17:52:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-02-13 17:52:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-02-13 17:52:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-02-13 17:52:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-02-13 17:52:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-02-13 17:52:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-02-13 17:52:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-02-13 17:52:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-02-13 17:52:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-02-13 17:52:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-02-13 17:52:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-02-13 17:52:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-02-13 17:52:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-02-13 17:52:11 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-02-13 17:52:11 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-02-13 17:52:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 17:52:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445,C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-02-13 17:52:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 17:52:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445,C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 17:52:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 17:52:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 17:52:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C9A92167-FF94-4,45C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-02-13 17:52:38 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-02-13 17:52:38 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-02-13 17:52:38 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
,2017-02-13 17:52:38 - DEBUG CoordinatedClient: 'test client failed'
,2017-02-13 17:52:38 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-02-13 17:52:38 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2,/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:252:22
tryCatcher@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/B,undle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873D,C3E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/C9A92167-FF94-445C-9418-CE99873DC3E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
,2017-02-13 17:52:38 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
