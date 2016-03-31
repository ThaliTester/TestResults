#### Test 646138038b5bc7c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/D05FAF45-8707-4993-B577-4FA8B0BB0978/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D05FAF45-8707-4993-B577-4FA8B0BB0978/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49916"
,(lldb)     command script import "/tmp/D05FAF45-8707-4993-B577-4FA8B0BB0978/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 17:39:03.408 ThaliTest[216:4913] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F1BDD67F-4227-4346-91F9-7C68D5CA40BD/Library/Cookies/Cookies.binarycookies
,2016-03-31 17:39:03.834 ThaliTest[216:4913] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 17:39:03.836 ThaliTest[216:4913] Multi-tasking -> Device: YES, App: YES
,2016-03-31 17:39:03.861 ThaliTest[216:4913] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 17:39:05.915 ThaliTest[216:4913] Using UIWebView
,2016-03-31 17:39:05.922 ThaliTest[216:4913] [CDVTimer][handleopenurl] 0.383973ms
,2016-03-31 17:39:05.931 ThaliTest[216:4913] [CDVTimer][intentandnavigationfilter] 8.142054ms
,2016-03-31 17:39:05.932 ThaliTest[216:4913] [CDVTimer][gesturehandler] 0.384033ms
,2016-03-31 17:39:05.932 ThaliTest[216:4913] [CDVTimer][TotalPluginStartup] 10.550976ms
,2016-03-31 17:39:14.007 ThaliTest[216:4913] Resetting plugins due to page load.
,2016-03-31 17:39:18.211 ThaliTest[216:4913] Finished load of: file:///var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/index.html
,2016-03-31 17:39:18.461 ThaliTest[216:4913] JXcore Cordova plugin initializing
,2016-03-31 17:39:18.461 ThaliTest[216:5161] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 17:39:24.943 ThaliTest[216:5161] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:39:24.943 ThaliTest[216:5161] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:39:24.943 ThaliTest[216:5161] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:39:24.945 ThaliTest[216:5161] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EC82D4E0-5FF3-48F7-9843-C281315F92CA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-31 17:39:30.185 ThaliTest[216:4913] THREAD WARNING: ['JXcore'] took '4963.008057' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49380
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49382
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49385
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
,ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49389
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
,ok 9 Send/recvd #2 should be equal length
,ok 10 Send/recvd #2 should be same
,ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49394
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49398
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
,ok 16 incoming is cleaned up
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49402
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49406
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,ok 22 native server is nulled out
,ok 23 native server should be closed
,ok 24 incoming has been removed
,ok 25 Incoming should be done
,ok 26 The mux object should be closed
,ok 27 The mux stream should be closed
,DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49410
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,ok 28 native server is nulled out
,ok 29 native server should be closed
,ok 30 incoming has been removed
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49462
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
,ok 33 server should be fine
,ok 34 server should be open
,ok 35 incoming has been removed
,ok 36 The mux object should be closed
,ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49466
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
,ok 40 server should be fine
,ok 41 server should be open
,ok 42 incoming has been removed
,ok 43 The mux object should be closed
,ok 44 The mux stream should be closed
,# teardown
,# setup
,# 12. closeAll can close even when connections open
,ok 45 not possible to connect to the server anymore
,# teardown
,# setup
,# 13. closeAll with promise
,ok 46 not possible to connect to the server anymore
,# teardown
,# setup
,# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
,ok 47 Got the right error
,# teardown
,# setup
,# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
,# teardown
,# setup
,# 16. multiplex can send data
,ok 48 String should be length:200
,# teardown
,# setup
,# 17. enqueue and run in order
,ok 49 firstPromise setTimeout
,ok 50 firstPromise result
,ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
,ok 53 secondPromise result
,ok 54 secondPromise testValue
,ok 55 thirdPromise in promise
,ok 56 thirdPromise result
,ok 57 thirdPromise testValue
,# teardown
,# setup
,# 18. enqueueAtTop and run backwards
,ok 58 thirdPromise - first to run
,ok 59 thirdPromise - in resolve
,ok 60 secondPromise - second to run
,ok 61 secondPromise - in catch
,ok 62 firstPromise - third to run
,ok 63 firstPromise - in then
,ok 64 testing promises
,# teardown
,# setup
,# 19. mix enqueue and enqueueAtTop
,ok 65 fourth
,ok 66 fourth
,ok 67 second
,ok 68 secondPromise - in then
,ok 69 first
,ok 70 firstPromise - in catch
,ok 71 third
,ok 72 thirdPromise - in then
,ok 73 testingPromises
,# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
,# teardown
,# setup
,# 21. basic
,ok 75 sane
,# teardown
,# setup
,# 22. another
,ok 76 sane
,# teardown
,# setup
,# 23. can pass data in setup
,[{"uuid":"93b06dd5-4156-4a62-b430-5e379b5bf668","data":"custom data"},{"uuid":"d360614e-eafc-47a4-b232-9db4049e83cd","data":"custom data"},{"uuid":"2d44cdcc-6331-4fd1-8321-40772b7965dd","data":"custom data"},{"uuid":"5a159754-f32d-49c6-9977-dc42c1fa4a99","data":"custom data"}]
,ok 77 test participant has uuid
,ok 78 participant data matches
,ok 79 test participant has uuid
,ok 80 participant data matches
,ok 81 test participant has uuid
,ok 82 participant data matches
,ok 83 test participant has uuid
,ok 84 participant data matches
,ok 85 own UUID is found from the participants list
,# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 86 specific error should be returned
,# teardown
,ok 87 error should be null
,ok 88 error should be null
,# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 89 specific error should be returned
,# teardown
,ok 90 error should be null
,ok 91 error should be null
,# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49478
,2016-03-31 17:41:32.775 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:41:32.777 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,2016-03-31 17:41:32.781 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:41:32.783 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,# teardown
,2016-03-31 17:41:32.886 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:41:32.887 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:41:32.887 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,2016-03-31 17:41:32.889 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:41:32.891 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49480
,2016-03-31 17:41:33.218 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
,2016-03-31 17:41:33.220 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 17:41:33.223 ThaliTest[216:5161] jxcore: startListeningForAdvertisements: success
,ok 98 error should be null
,ok 99 error should be null
,2016-03-31 17:41:33.248 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 17:41:33.250 ThaliTest[216:5161] jxcore: startListeningForAdvertisements: success
,ok 100 error should be null
,ok 101 error should be null
,# teardown
,2016-03-31 17:41:33.557 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:41:33.557 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:41:33.558 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,2016-03-31 17:41:33.559 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,2016-03-31 17:41:33.560 ThaliTest[216:5161] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:33.563 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 102 error should be null
,ok 103 error should be null
,# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49482
,2016-03-31 17:41:34.166 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 17:41:34.167 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:1
,2016-03-31 17:41:34.169 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
2016-03-31 17:41:34.169 ThaliTest[216:5161] THEMultipeerManager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:1
2016-03-31 17:41:34.170 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
,ok 105 error should be null
,2016-03-31 17:41:34.188 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 17:41:34.188 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:41:34.190 ThaliTest[216:5161] multipeer manager: stop client timer
2016-03-31 17:41:34.190 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:2
,2016-03-31 17:41:34.192 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
2016-03-31 17:41:34.192 ThaliTest[216:5161] THEMultipeerManager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:2
2016-03-31 17:41:34.194 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening: success
,ok 106 error should be null
,ok 107 error should be null
,# teardown
,2016-03-31 17:41:35.035 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:41:35.036 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:41:35.037 ThaliTest[216:5161] multipeer manager: stop client timer
2016-03-31 17:41:35.037 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,2016-03-31 17:41:35.038 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:35.045 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 108 error should be null
,ok 109 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49487
,2016-03-31 17:41:40.433 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:41:40.433 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:41:40.434 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,ok 110 error should be null
,ok 111 error should be null
,2016-03-31 17:41:40.440 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:41:40.440 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:41:40.441 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,ok 112 error should be null
,ok 113 error should be null
,# teardown
,2016-03-31 17:41:40.760 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:41:40.760 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:41:40.761 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,2016-03-31 17:41:40.762 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:41:40.764 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 114 error should be null
,ok 115 error should be null
,# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49489
,ok 116 first call should succeed
,ok 117 first call should succeed
,ok 118 specific error should be returned
,# teardown
,2016-03-31 17:41:42.908 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:41:42.908 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:41:42.909 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,2016-03-31 17:41:42.910 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:41:42.912 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 119 error should be null
,ok 120 error should be null
,# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49491
,2016-03-31 17:41:56.221 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
,2016-03-31 17:41:56.222 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 17:41:56.228 ThaliTest[216:5161] jxcore: startListeningForAdvertisements: success
,2016-03-31 17:41:56.247 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 17:41:56.248 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:3
,2016-03-31 17:41:56.249 ThaliTest[216:5161] THEMultipeerManager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:3
,2016-03-31 17:41:56.249 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening: success
,ok 121 called only once
,ok 122 discovery state matches
,ok 123 advertising state matches
,# teardown
,2016-03-31 17:41:56.420 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:41:56.420 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:41:56.421 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,2016-03-31 17:41:56.422 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,2016-03-31 17:41:56.423 ThaliTest[216:5161] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:56.426 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 124 error should be null
,ok 125 error should be null
,# setup
,# 32. does not send duplicate availability changes
,ok 126 should be called once
,ok 127 should not have been called more than once
,# teardown
,ok 128 error should be null
,ok 129 error should be null
,# setup
,# 33. can get the network status
,ok 130 network status should have certain non-empty properties
,# teardown
,ok 131 error should be null
,ok 132 error should be null
,# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 133 host address should match
,ok 134 port should match
,ok 135 host address should be null
,ok 136 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 137 error should be null
,ok 138 error should be null
,# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-31 17:42:39.329 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
,2016-03-31 17:42:39.331 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 17:42:39.333 ThaliTest[216:5161] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
,2016-03-31 17:42:39.338 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,2016-03-31 17:42:39.339 ThaliTest[216:5161] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:42:39.343 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 140 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-31 17:42:39.696 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:42:39.698 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:42:39.701 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:42:39.701 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:42:39.702 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 17:42:42.190 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
,2016-03-31 17:42:42.191 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:42:42.193 ThaliTest[216:5161] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements without error
,2016-03-31 17:42:42.197 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 17:42:42.200 ThaliTest[216:5161] jxcore: startListeningForAdvertisements: success
,ok 144 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-31 17:42:45.537 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,2016-03-31 17:42:45.538 ThaliTest[216:5161] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:42:45.541 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:42:45.544 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:42:45.545 ThaliTest[216:5161] THEMultipeerManager stopping peer
2016-03-31 17:42:45.545 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 17:42:49.908 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 17:42:49.909 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:4
,2016-03-31 17:42:49.910 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
2016-03-31 17:42:49.911 ThaliTest[216:5161] THEMultipeerManager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:4
2016-03-31 17:42:49.911 ThaliTes,t[216:5161] jxcore: startUpdateAdvertisingAndListening: success
,ok 147 Can call startUpdateAdvertisingAndListening without error
,2016-03-31 17:42:49.920 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:42:49.922 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:42:49.923 ThaliTest[216:5161] multipeer manager: stop client timer
,2016-03-31 17:42:49.926 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,ok 148 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-31 17:42:52.370 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:42:52.372 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:42:52.374 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:42:52.375 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:42:52.375 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,ok 150 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 17:42:57.594 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 17:42:57.595 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:5
,2016-03-31 17:42:57.596 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
2016-03-31 17:42:57.596 ThaliTest[216:5161] THEMultipeerManager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:5
2016-03-31 17:42:57.597 ThaliTes,t[216:5161] jxcore: startUpdateAdvertisingAndListening: success
ok 151 Can call startUpdateAdvertisingAndListening without error
,2016-03-31 17:42:57.600 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:42:57.601 ThaliTest[216:5161] THEMultipeerManager stopping peer
2016-03-31 17:42:57.602 ThaliTest[216:5161] multipeer manager: stop client timer
2016-03-31 17:42:57.603 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:6
2016-03-31 17:42:57.604 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
2016-03-31 17:42:57.605 ThaliTest[216:5161] THEMultipeerMan,ager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:6
2016-03-31 17:42:57.605 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening: success
ok 152 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-03-31 17:42:58.833 ThaliTest[216:4913] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:2
,2016-03-31 17:42:58.898 ThaliTest[216:4913] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:2
,2016-03-31 17:43:00.706 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 17:43:00.709 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:43:00.712 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:43:00.712 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:43:00.713 ThaliTest[216:5161] multipeer manager: stop client timer
2016-03-31 17:43:00.713 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. peerAvailabilityChange is called
,2016-03-31 17:43:16.941 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 17:43:16.941 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:7
,2016-03-31 17:43:16.943 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
2016-03-31 17:43:16.943 ThaliTest[216:5161] THEMultipeerManager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:7
,2016-03-31 17:43:16.943 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening: success
,ok 155 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 17:43:16.946 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-31 17:43:16.949 ThaliTest[216:5161] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-31 17:43:17.707 ThaliTest[216:4913] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:6
,ok 157 peers must be an array
,ok 158 peers must not be zero-length
,ok 159 peer must have peerIdentifier
,ok 160 peerIdentifier must be a string
,ok 161 peer must have peerAvailable
,ok 162 peer must have pleaseConnect
,# teardown
,2016-03-31 17:43:18.304 ThaliTest[216:4913] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:6
,2016-03-31 17:43:19.814 ThaliTest[216:4913] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:21.147 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 17:43:21.149 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:43:21.151 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:43:21.152 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:43:21.153 ThaliTest[216:5161] multipeer manager: stop client timer
,2016-03-31 17:43:21.154 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. Can connect to a remote peer
,2016-03-31 17:43:21.711 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 17:43:21.712 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:43:21.713 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
2016-03-31 17:43:21.714 ThaliTest[216:5161] THEMultipeerManager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:8
2016-03-31 17:43:21.714 ThaliTes,t[216:5161] jxcore: startUpdateAdvertisingAndListening: success
,ok 165 Can call startUpdateAdvertisingAndListening without error
,2016-03-31 17:43:21.718 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 17:43:21.722 ThaliTest[216:5161] jxcor,e: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-03-31 17:43:22.512 ThaliTest[216:4913] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2","pleaseConnect":0}]
,2016-03-31 17:43:22.516 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:22.517 ThaliTest[216:5161] client session: connect
2016-03-31 17:43:22.518 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:23.977 ThaliTest[216:4913] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:43:23.977 ThaliTest[216:4913] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:7","pleaseConnect":0}]
,2016-03-31 17:43:25.114 ThaliTest[216:5709] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
2016-03-31 17:43:25.115 ThaliTest[216:5709] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:25.116 ThaliTest[216:5709] client session: disconnect
,2016-03-31 17:43:25.116 ThaliTest[216:5709] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:25.117 ThaliTest[216:5709] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:43:25.117 ThaliTest[216:5709] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 17:43:28.128 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:28.128 ThaliTest[216:5161] client session: connect
,2016-03-31 17:43:28.129 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:28.735 ThaliTest[216:5711] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
2016-03-31 17:43:28.735 ThaliTest[216:5711] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:43:28.736 ThaliTest[216:5711] client session: disconnect
2016-03-31 17:43:28.736 ThaliTest[216:5711] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:28.738 ThaliTest[216:5711] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:43:28.738 ThaliTest[216:5711] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 17:43:31.744 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:31.744 ThaliTest[216:5161] client session: connect
,2016-03-31 17:43:31.745 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:32.187 ThaliTest[216:5749] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:32.187 ThaliTest[216:5749] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:32.189 ThaliTest[216:5749] client session: disconnect
,2016-03-31 17:43:32.189 ThaliTest[216:5749] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:32.190 ThaliTest[216:5749] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:43:32.190 ThaliTest[216:5749] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 17:43:35.197 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:35.198 ThaliTest[216:5161] client session: connect
2016-03-31 17:43:35.198 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:36.109 ThaliTest[216:5709] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
2016-03-31 17:43:36.110 ThaliTest[216:5709] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:36.110 Thali,Test[216:5709] client session: disconnect
,2016-03-31 17:43:36.110 ThaliTest[216:5709] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:36.112 ThaliTest[216:5709] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:36.112 ThaliTest[216:5709] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 17:43:39.122 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:39.123 ThaliTest[216:5161] client session: connect
,2016-03-31 17:43:39.124 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:40.376 ThaliTest[216:5760] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
2016-03-31 17:43:40.376 ThaliTest[216:5760] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:40.376 Thali,Test[216:5760] client session: disconnect
,2016-03-31 17:43:40.377 ThaliTest[216:5760] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:40.377 ThaliTest[216:5760] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:43:40.378 ThaliTest[216:5760] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 17:43:41.715 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:43:41.742 ThaliTest[216:4913] client: found updated peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:43:41.743 ThaliTest[216:4913] client: found updated peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:41.744 ThaliTest[216:4913] client: found updated peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8","pleaseConnect":0}]
,2016-03-31 17:43:43.386 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:43.387 ThaliTest[216:5161] client session: connect
,2016-03-31 17:43:43.388 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:44.567 ThaliTest[216:5760] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:44.568 ThaliTest[216:5760] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:43:44.568 ThaliTest[216:5760] client session: disconnect
,2016-03-31 17:43:44.570 ThaliTest[216:5760] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:44.571 ThaliTest[216:5760] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:43:44.572 ThaliTest[216:5760] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 17:43:47.578 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:47.579 ThaliTest[216:5161] client session: connect
2016-03-31 17:43:47.579 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:48.658 ThaliTest[216:5712] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:48.658 ThaliTest[216:5712] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:48.659 ThaliTest[216:5712] client session: disconnect
,2016-03-31 17:43:48.660 ThaliTest[216:5712] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:48.661 ThaliTest[216:5712] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:48.661 ThaliTest[216:5712] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 17:43:51.675 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:51.676 ThaliTest[216:5161] client session: connect
,2016-03-31 17:43:51.676 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:53.809 ThaliTest[216:5749] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:53.810 ThaliTest[216:5749] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:53.812 ThaliTest[216:5749] client session: disconnect
2016-03-31 17:43:53.812 ThaliTest[216:5749] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:53.813 ThaliTest[216:5749] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:43:53.813 ThaliTest[216:5749] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 17:43:56.821 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:43:56.822 ThaliTest[216:5161] client session: connect
,2016-03-31 17:43:56.823 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:58.631 ThaliTest[216:5760] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:58.632 ThaliTest[216:5760] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:43:58.632 ThaliTest[216:5760] client session: disconnect
,2016-03-31 17:43:58.634 ThaliTest[216:5760] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:58.635 ThaliTest[216:5760] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:58.635 ThaliTest[216:5760] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 17:44:01.648 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:44:01.649 ThaliTest[216:5161] client session: connect
,2016-03-31 17:44:01.649 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:44:01.715 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:44:01.747 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:01.747 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:44:01.748 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:44:21.715 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:44:21.745 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:44:21.746 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:44:21.746 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:44:34.586 ThaliTest[216:5842] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:44:34.587 ThaliTest[216:5842] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:44:34.587 ThaliTest[216:5842] client session: disconnect
,2016-03-31 17:44:34.588 ThaliTest[216:5842] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:44:34.589 ThaliTest[216:5842] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:44:34.590 ThaliTest[216:5842] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 167 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-31 17:44:41.715 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:44:41.747 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:44:41.748 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:41.749 ThaliT,est[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:01.715 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:45:01.746 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:01.747 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:45:01.747 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:21.715 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:45:21.744 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:45:21.745 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:21.746 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:31.112 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 17:45:31.115 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 168 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:45:31.117 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:45:31.118 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:45:31.118 ThaliTest[216:5161] multipeer manager: stop client timer
,2016-03-31 17:45:31.119 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
ok 169 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. Can shift large amounts of data
,2016-03-31 17:45:34.807 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 17:45:34.808 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:9
,2016-03-31 17:45:34.809 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
2016-03-31 17:45:34.809 ThaliTest[216:5161] THEMultipeerManager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:45:34.810 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening: success
,ok 170 Can call startUpdateAdvertisingAndListening without error
,2016-03-31 17:45:34.813 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 17:45:34.816 ThaliTest[216:5161] jxcore: startListeningForAdvertisements: success
ok 171 Can call startListeningForAdvertisements without error
,2016-03-31 17:45:36.531 ThaliTest[216:4913] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:36.532 ThaliTest[216:4913] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:36.535 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:36.536 ThaliTest[216:5161] client session: connect
2016-03-31 17:45:36.536 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:37.683 ThaliTest[216:4913] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:45:38.642 ThaliTest[216:5842] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:38.642 ThaliTest[216:5842] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:38.642 ThaliTest[216:5842] client session: disconnect
2016-03-31 17:45:38.643 ThaliTest[216:5842] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:38.643 ThaliTest[216:5842] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:45:38.644 ThaliTest[216:5842] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 17:45:41.659 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:41.660 ThaliTest[216:5161] client session: connect
,2016-03-31 17:45:41.661 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:42.804 ThaliTest[216:6064] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:42.805 ThaliTest[216:6064] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:42.805 ThaliTest[216:6064] client session: disconnect
,2016-03-31 17:45:42.805 ThaliTest[216:6064] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:42.807 ThaliTest[216:6064] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:42.808 ThaliTest[216:6064] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 17:45:45.819 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:45.820 ThaliTest[216:5161] client session: connect
,2016-03-31 17:45:45.821 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:48.054 ThaliTest[216:6065] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:48.054 ThaliTest[216:6065] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:48.054 ThaliTest[216:6065] client session: disconnect
2016-03-31 17:45:48.055 ThaliTest[216:6065] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:48.057 ThaliTest[216:6065] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:48.057 ThaliTest[216:6065] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 17:45:51.070 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:51.071 ThaliTest[216:5161] client session: connect
,2016-03-31 17:45:51.071 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:54.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:45:54.842 ThaliTest[216:4913] client: found updated peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:45:54.843 ThaliTest[216:4913] client: found updated peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
2016-03-31 17:45:54.843 ThaliTest[216:4913] client: found updated peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
,2016-03-31 17:46:14.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:46:14.842 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:14.843 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:46:14.844 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:46:23.966 ThaliTest[216:6183] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:23.966 ThaliTest[216:6183] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:23.967 Thali,Test[216:6183] client session: disconnect
2016-03-31 17:46:23.967 ThaliTest[216:6183] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:23.968 ThaliTest[216:6183] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:23.968 ThaliTest[216:6183] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 17:46:26.983 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:46:26.984 ThaliTest[216:5161] client session: connect
,2016-03-31 17:46:26.984 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:34.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:46:34.839 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:46:34.840 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:46:34.840 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:54.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:46:54.841 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:54.841 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:46:54.842 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:46:59.965 ThaliTest[216:6328] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:59.966 ThaliTest[216:6328] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:59.966 ThaliTest[216:6328] client session: disconnect
2016-03-31 17:46:59.967 ThaliTest[216:6328] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:59.967 ThaliTest[216:6328] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:59.968 ThaliTest[216:6328] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 17:47:02.975 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:47:02.976 ThaliTest[216:5161] client session: connect
,2016-03-31 17:47:02.977 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:47:14.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:47:14.842 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:47:14.843 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:47:14.844 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:47:34.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:47:34.839 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:47:34.840 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:47:34.842 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:47:35.980 ThaliTest[216:6464] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:47:35.980 ThaliTest[216:6464] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:47:35.981 ThaliTest[216:6464] client session: disconnect
,2016-03-31 17:47:35.981 ThaliTest[216:6464] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:47:35.983 ThaliTest[216:6464] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:47:35.983 ThaliTest[216:6464] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 17:47:38.989 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:47:38.990 ThaliTest[216:5161] client session: connect
,2016-03-31 17:47:38.990 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:47:54.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:47:54.841 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:47:54.841 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
2016-03-31 17:47:54.842 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:11.965 ThaliTest[216:6606] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:48:11.966 ThaliTest[216:6606] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:48:11.966 ThaliTest[216:6606] client session: disconnect
,2016-03-31 17:48:11.967 ThaliTest[216:6606] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:11.969 ThaliTest[216:6606] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:48:11.969 ThaliTest[216:6606] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 17:48:14.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:48:14.839 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:48:14.839 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:48:14.842 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:48:14.975 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:48:14.976 ThaliTest[216:5161] client session: connect
2016-03-31 17:48:14.977 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:34.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:48:34.842 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:48:34.843 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:34.845 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:48:47.965 ThaliTest[216:6769] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:47.966 ThaliTest[216:6769] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:48:47.967 ThaliTest[216:6769] client session: disconnect
,2016-03-31 17:48:47.967 ThaliTest[216:6769] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:47.969 ThaliTest[216:6769] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:48:47.969 ThaliTest[216:6769] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 17:48:50.982 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:48:50.983 ThaliTest[216:5161] client session: connect
,2016-03-31 17:48:50.984 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:54.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:48:54.843 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
2016-03-31 17:48:54.844 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:48:54.844 ThaliT,est[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:49:14.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:49:14.842 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:49:14.842 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:49:14.842 ThaliT,est[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:49:23.965 ThaliTest[216:6841] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:49:23.966 ThaliTest[216:6841] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:49:23.966 Thali,Test[216:6841] client session: disconnect
2016-03-31 17:49:23.966 ThaliTest[216:6841] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:49:23.967 ThaliTest[216:6841] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:49:23.968 ThaliTest[216:6841] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 17:49:26.982 ThaliTest[216:5161] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:49:26.983 ThaliTest[216:5161] client session: connect
,2016-03-31 17:49:26.984 ThaliTest[216:5161] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:49:34.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:49:34.843 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:49:34.843 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:49:34.844 ThaliT,est[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:49:54.811 ThaliTest[216:4913] multipeer manager: restart client
,2016-03-31 17:49:54.840 ThaliTest[216:4913] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
2016-03-31 17:49:54.840 ThaliTest[216:4913] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:49:54.840 ThaliTest[216:4913] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
,2016-03-31 17:49:59.965 ThaliTest[216:6902] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:49:59.965 ThaliTest[216:6902] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:49:59.966 Thali,Test[216:6902] client session: disconnect
2016-03-31 17:49:59.966 ThaliTest[216:6902] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:49:59.967 ThaliTest[216:6902] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:49:59.967 ThaliTest[216:6902] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 172 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-31 17:50:00.351 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 17:50:00.354 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:50:00.356 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:50:00.357 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:50:00.358 ThaliTest[216:5161] multipeer manager: stop client timer
2016-03-31 17:50:00.358 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-31 17:50:11.014 ThaliTest[216:5161] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 17:50:11.015 ThaliTest[216:5161] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 17:50:11.016 ThaliTest[216:5161] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:11.019 ThaliTest[216:5161] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 175 specific error should be returned
,# teardown
,ok 176 must be stopped
,# setup
,2016-03-31 17:50:23.575 ThaliTest[216:5161] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 17:50:23.576 ThaliTest[216:5161] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 17:50:23.577 ThaliTest[216:5161] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:23.580 ThaliTest[216:5161] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 177 specific error should be returned
,# teardown
,ok 178 must be stopped
,# setup
,2016-03-31 17:50:24.924 ThaliTest[216:5161] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 17:50:24.925 ThaliTest[216:5161] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 17:50:24.926 ThaliTest[216:5161] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:24.929 ThaliTest[216:5161] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49546
,2016-03-31 17:50:25.335 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:50:25.338 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 179 no errors
,2016-03-31 17:50:25.343 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:50:25.345 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 180 still no errors
,# teardown
,2016-03-31 17:50:26.179 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:50:26.180 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:50:26.180 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,2016-03-31 17:50:26.182 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:50:26.184 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 181 must be stopped
,# setup
,2016-03-31 17:50:32.346 ThaliTest[216:5161] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 17:50:32.347 ThaliTest[216:5161] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 17:50:32.348 ThaliTest[216:5161] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:32.351 ThaliTest[216:5161] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49548
,2016-03-31 17:50:56.812 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
,2016-03-31 17:50:56.813 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 17:50:56.815 ThaliTest[216:5161] jxcore: startListeningForAdvertisements: success
,ok 182 no errors
,2016-03-31 17:50:56.823 ThaliTest[216:5161] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 17:50:56.825 ThaliTest[216:5161] jxcore: startListeningForAdvertisements: success
,ok 183 still no errors
,# teardown
,2016-03-31 17:50:58.411 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:50:58.411 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:50:58.412 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
,2016-03-31 17:50:58.413 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
,2016-03-31 17:50:58.414 ThaliTest[216:5161] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:50:58.417 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 184 must be stopped
,# setup
,2016-03-31 17:51:15.081 ThaliTest[216:5161] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 17:51:15.083 ThaliTest[216:5161] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 17:51:15.084 ThaliTest[216:5161] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:51:15.087 ThaliTest[216:5161] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49550
,2016-03-31 17:51:19.983 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 17:51:19.984 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:10
,2016-03-31 17:51:19.985 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
2016-03-31 17:51:19.985 ThaliTest[216:5161] THEMultipeerManager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:10
2016-03-31 17:51:19.986 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening: success
,ok 185 no errors
,2016-03-31 17:51:19.994 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:51:19.995 ThaliTest[216:5161] THEMultipeerManager stopping peer
2016-03-31 17:51:19.995 ThaliTest[216:5161] multipeer manager: stop client timer
2016-03,-31 17:51:19.996 ThaliTest[216:5161] server: starting 4F791D6C-3E6B-4315-830D-E0F106215081:11
2016-03-31 17:51:19.996 ThaliTest[216:5161] multipeer manager: start client restart timer: 0x14d32bd0
2016-03-31 17:51:19.997 ThaliTest[216:5161] THEMultipeerMa,nager initialized peer 4F791D6C-3E6B-4315-830D-E0F106215081:11
2016-03-31 17:51:19.997 ThaliTest[216:5161] jxcore: startUpdateAdvertisingAndListening: success
ok 186 still no errors
,# teardown
,2016-03-31 17:51:21.085 ThaliTest[216:4913] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:51:23.360 ThaliTest[216:4913] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:51:29.595 ThaliTest[216:4913] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
,2016-03-31 17:51:29.788 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening
,2016-03-31 17:51:29.789 ThaliTest[216:5161] THEMultipeerManager stopping peer
,2016-03-31 17:51:29.790 ThaliTest[216:5161] multipeer manager: stop client timer
,2016-03-31 17:51:29.790 ThaliTest[216:5161] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:51:29.794 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-31 17:51:29.797 ThaliTest[216:5161] jxcore: stopListeningForAdvertisements: success
,ok 187 must be stopped
,# setup

```
