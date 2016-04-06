#### Test 6539483973f7970_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/2D043555-AC7A-4CD1-BBF6-36516B32407C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2D043555-AC7A-4CD1-BBF6-36516B32407C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51008"
,(lldb)     command script import "/tmp/2D043555-AC7A-4CD1-BBF6-36516B32407C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-06 03:10:05.665 ThaliTest[490:700142] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4890E266-DEE9-43E3-B004-DD0C9AABA8F8/Library/Cookies/Cookies.binarycookies
,2016-04-06 03:10:06.123 ThaliTest[490:700142] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-06 03:10:06.125 ThaliTest[490:700142] Multi-tasking -> Device: YES, App: YES
,2016-04-06 03:10:06.143 ThaliTest[490:700142] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-06 03:10:08.473 ThaliTest[490:700142] Using UIWebView
,2016-04-06 03:10:08.480 ThaliTest[490:700142] [CDVTimer][handleopenurl] 0.511050ms
,2016-04-06 03:10:08.487 ThaliTest[490:700142] [CDVTimer][intentandnavigationfilter] 6.543994ms
,2016-04-06 03:10:08.488 ThaliTest[490:700142] [CDVTimer][gesturehandler] 0.302017ms
,2016-04-06 03:10:08.488 ThaliTest[490:700142] [CDVTimer][TotalPluginStartup] 8.839965ms
,2016-04-06 03:10:16.690 ThaliTest[490:700142] Resetting plugins due to page load.
,2016-04-06 03:10:20.991 ThaliTest[490:700142] Finished load of: file:///var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/index.html
,2016-04-06 03:10:21.199 ThaliTest[490:700142] JXcore Cordova plugin initializing
,2016-04-06 03:10:21.199 ThaliTest[490:700403] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-06 03:10:27.640 ThaliTest[490:700403] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-06 03:10:27.641 ThaliTest[490:700403] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-06 03:10:27.641 ThaliTest[490:700403] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-06 03:10:27.643 ThaliTest[490:700403] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64C8AFFB-ED01-4C8F-8C3D-42F93DDAC645/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-06 03:10:33.455 ThaliTest[490:700142] THREAD WARNING: ['JXcore'] took '5538.804932' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51334
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51336
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
,DEBUG createNativeListener: listening 51339
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
,DEBUG createNativeListener: listening 51343
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
,DEBUG createNativeListener: listening 51348
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
,DEBUG createNativeListener: listening 51352
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
,DEBUG createNativeListener: listening 51356
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
,DEBUG createNativeListener: listening 51360
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
,DEBUG createNativeListener: listening 51364
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
,DEBUG createNativeListener: listening 51416
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
,DEBUG createNativeListener: listening 51420
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
,# 16. enqueue and run in order
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
,ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# teardown
,# setup
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# teardown
,# setup
,# 18. mix enqueue and enqueueAtTop
,ok 64 fourth
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
,# setup
,# 20. basic
,ok 74 sane
,# teardown
,# setup
,# 21. another
,ok 75 sane
,# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"23004744-777a-4286-80e8-7c39ced52031","data":"custom data"},{"uuid":"b9648362-bd7c-4ccf-8c9e-e657f2368bf5","data":"custom data"},{"uuid":"1e708892-c95f-4713-9eb4-ebedb0ff7757","data":"custom data"},{"uuid":"c99173ba-aafb-407b-a44f-72a198cb56d8",",data":"custom data"}]
,ok 76 test participant has uuid
,ok 77 participant data matches
,ok 78 test participant has uuid
,ok 79 participant data matches
,ok 80 test participant has uuid
,ok 81 participant data matches
,ok 82 test participant has uuid
,ok 83 participant data matches
,ok 84 own UUID is found from the participants list
,# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 85 specific error should be returned
,# teardown
,ok 86 error should be null
,ok 87 error should be null
,# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
,# teardown
,ok 89 error should be null
,ok 90 error should be null
,# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51430
,2016-04-06 03:13:23.338 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:13:23.340 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-06 03:13:23.344 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:13:23.345 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-06 03:13:23.485 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:23.485 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:13:23.486 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,2016-04-06 03:13:23.487 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:13:23.489 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51432
,2016-04-06 03:13:23.669 ThaliTest[490:700403] jxcore: startListeningForAdvertisements
,2016-04-06 03:13:23.671 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-06 03:13:23.674 ThaliTest[490:700403] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-06 03:13:23.698 ThaliTest[490:700403] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-06 03:13:23.700 ThaliTest[490:700403] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-06 03:13:23.956 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:13:23.956 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:13:23.957 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,2016-04-06 03:13:23.958 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,2016-04-06 03:13:23.959 ThaliTest[490:700403] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:13:23.963 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51434
,2016-04-06 03:13:24.460 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening
,2016-04-06 03:13:24.461 ThaliTest[490:700403] server: starting 8C5B19F5-9879-44C8-A20C-4970704F4B6A:1
,2016-04-06 03:13:24.463 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
2016-04-06 03:13:24.464 ThaliTest[490:700403] THEMultipeerManager initialized peer 8C5B19F5-9879-44C8-A20C-4970704F4B6A:1
2016-04-06 03:13:24.465 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-06 03:13:24.500 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening
,2016-04-06 03:13:24.501 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:13:24.502 ThaliTest[490:700403] multipeer manager: stop client timer
,2016-04-06 03:13:24.503 ThaliTest[490:700403] server: starting 8C5B19F5-9879-44C8-A20C-4970704F4B6A:2
,2016-04-06 03:13:24.505 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
2016-04-06 03:13:24.506 ThaliTest[490:700403] THEMultipeerManager initialized peer 8C5B19F5-9879-44C8-A20C-4970704F4B6A:2
2016-04-06 03:13:24.506 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-06 03:13:24.632 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:13:24.632 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:13:24.633 ThaliTest[490:700403] multipeer manager: stop client timer
,2016-04-06 03:13:24.636 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:24.637 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:13:24.639 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51439
,2016-04-06 03:13:32.857 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:13:32.858 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:13:32.858 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-06 03:13:32.865 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:13:32.865 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:13:32.866 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-06 03:13:49.753 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:49.753 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:13:49.754 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,2016-04-06 03:13:49.755 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:13:49.757 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51441
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-06 03:14:00.217 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
2016-04-06 03:14:00.217 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:14:00.218 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,2016-04-06 03:14:00.219 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:14:00.221 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51443
,2016-04-06 03:14:00.410 ThaliTest[490:700403] jxcore: startListeningForAdvertisements
,2016-04-06 03:14:00.411 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-06 03:14:00.413 ThaliTest[490:700403] jxcore: startListeningForAdvertisements: success
,2016-04-06 03:14:00.438 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening
,2016-04-06 03:14:00.439 ThaliTest[490:700403] server: starting 8C5B19F5-9879-44C8-A20C-4970704F4B6A:3
,2016-04-06 03:14:00.440 ThaliTest[490:700403] THEMultipeerManager initialized peer 8C5B19F5-9879-44C8-A20C-4970704F4B6A:3
2016-04-06 03:14:00.441 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-06 03:14:00.675 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:14:00.676 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:14:00.676 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,2016-04-06 03:14:00.678 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
2016-04-06 03:14:00.678 ThaliTest[490:700403] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:14:00.681 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 123 error should be null
,ok 124 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
,ok 126 should not have been called more than once
,# teardown
,ok 127 error should be null
,ok 128 error should be null
,# setup
,# 32. can get the network status
,ok 129 network status should have certain non-empty properties
,# teardown
,ok 130 error should be null
,ok 131 error should be null
,# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
,ok 133 port should match
,ok 134 host address should be null
,ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
,ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-06 03:14:47.311 ThaliTest[490:700403] jxcore: startListeningForAdvertisements
,2016-04-06 03:14:47.312 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-06 03:14:47.315 ThaliTest[490:700403] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
,2016-04-06 03:14:47.321 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,2016-04-06 03:14:47.321 ThaliTest[490:700403] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:14:47.325 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-06 03:14:47.404 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:14:47.406 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:14:47.409 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:14:47.409 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:14:47.410 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-06 03:14:47.738 ThaliTest[490:700403] jxcore: startListeningForAdvertisements
,2016-04-06 03:14:47.738 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-06 03:14:47.741 ThaliTest[490:700403] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
,2016-04-06 03:14:47.746 ThaliTest[490:700403] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-06 03:14:47.748 ThaliTest[490:700403] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-06 03:14:48.084 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,2016-04-06 03:14:48.085 ThaliTest[490:700403] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:48.088 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:14:48.091 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:14:48.091 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:14:48.092 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-06 03:14:48.281 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:14:48.283 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-06 03:14:48.286 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:14:48.288 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-06 03:15:02.186 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:15:02.188 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:15:02.190 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:15:02.191 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:15:02.191 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-06 03:15:34.607 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening
,2016-04-06 03:15:34.608 ThaliTest[490:700403] server: starting 8C5B19F5-9879-44C8-A20C-4970704F4B6A:4
,2016-04-06 03:15:34.610 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
2016-04-06 03:15:34.610 ThaliTest[490:700403] THEMultipeerManager initialized peer 8C5B19F5-9879-44C8-A20C-4970704F4B6A:4
2016-04-06 03:15:34.611 Thal,iTest[490:700403] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:15:34.615 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:34.615 ThaliTest[490:700403] THEMultipeerManager stopping peer
2016-04-06 03:15:34.616 Th,aliTest[490:700403] multipeer manager: stop client timer
2016-04-06 03:15:34.616 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-06 03:15:35.062 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:15:35.064 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:15:35.067 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:35.068 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:15:35.068 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-06 03:15:36.452 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening
,2016-04-06 03:15:36.452 ThaliTest[490:700403] server: starting 8C5B19F5-9879-44C8-A20C-4970704F4B6A:5
,2016-04-06 03:15:36.454 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
2016-04-06 03:15:36.454 ThaliTest[490:700403] THEMultipeerManager initialized peer 8C5B19F5-9879-44C8-A20C-4970704F4B6A:5
2016-04-06 03:15:36.455 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening: success
,ok 154 Can call startUpdateAdvertisingAndListening without error
,2016-04-06 03:15:36.458 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:15:36.459 ThaliTest[490:700403] THEMultipeerManager stopping peer
2016-04-06 03:15:36.459 ThaliTest[490:700403] multipeer manager: stop client timer
2,016-04-06 03:15:36.459 ThaliTest[490:700403] server: starting 8C5B19F5-9879-44C8-A20C-4970704F4B6A:6
2016-04-06 03:15:36.461 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
2016-04-06 03:15:36.461 ThaliTest[490:700403] THE,MultipeerManager initialized peer 8C5B19F5-9879-44C8-A20C-4970704F4B6A:6
2016-04-06 03:15:36.461 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-06 03:15:36.958 ThaliTest[490:700142] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:6
,2016-04-06 03:15:39.895 ThaliTest[490:700142] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:6
,2016-04-06 03:15:42.501 ThaliTest[490:700142] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:6
,2016-04-06 03:15:43.272 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-06 03:15:43.275 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:15:43.277 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:15:43.278 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:15:43.279 ThaliTest[490:700403] multipeer manager: stop client timer
,2016-04-06 03:15:43.281 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-06 03:16:39.241 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:16:39.241 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:16:39.242 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-06 03:16:39.245 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:16:39.245 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:16:39.246 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-06 03:16:39.337 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:16:39.339 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:16:39.342 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:16:39.342 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:16:39.343 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-06 03:16:39.549 ThaliTest[490:700403] jxcore: connect foo
,2016-04-06 03:16:39.550 ThaliTest[490:700403] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-06 03:16:39.686 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:16:39.688 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:16:39.691 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:16:39.691 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:16:39.692 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-06 03:16:39.869 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening
,2016-04-06 03:16:39.870 ThaliTest[490:700403] server: starting 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
,2016-04-06 03:16:39.871 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
2016-04-06 03:16:39.872 ThaliTest[490:700403] THEMultipeerManager initialized peer 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:16:39.872 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening: success
,ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-06 03:16:39.879 ThaliTest[490:700403] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-06 03:16:39.881 ThaliTest[490:700403] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-06 03:16:41.898 ThaliTest[490:700142] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:6
2016-04-06 03:16:41.899 ThaliTest[490:700142] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:6
2016-04-06 03:16:41.899 ThaliTest[49,0:700142] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,ok 167 peers must be an array
ok 168 peers must not be zero-length
,ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-06 03:16:47.539 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-06 03:16:47.542 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:16:47.544 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:16:47.545 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:16:47.546 ThaliTest[490:700403] multipeer manager: stop client timer
,2016-04-06 03:16:47.547 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-06 03:16:48.219 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening
,2016-04-06 03:16:48.219 ThaliTest[490:700403] server: starting 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
,2016-04-06 03:16:48.220 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
2016-04-06 03:16:48.221 ThaliTest[490:700403] THEMultipeerManager initialized peer 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:16:48.222 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening: success
,ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-06 03:16:48.224 ThaliTest[490:700403] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-06 03:16:48.227 ThaliTest[490:700403] jxcore: startListeningForAdvertisements: success
,ok 176 Can call startListeningForAdvertisements without error
,2016-04-06 03:16:49.173 ThaliTest[490:700142] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:16:49.174 ThaliTest[490:700142] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:49.174 ThaliTest[490:700142] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C5E616F6-311E-4AAE-ABEF-071095D8F02C:7","pleaseConnect":0}]
,2016-04-06 03:16:49.178 ThaliTest[490:700403] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:16:49.179 ThaliTest[490:700403] client: server will connect
2016-04-06 03:16:49.179 ThaliTest[490:700403] client session: reverseConnect
,2016-04-06 03:16:49.180 ThaliTest[490:700403] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7","pleaseConnect":0}]
,2016-04-06 03:16:50.478 ThaliTest[490:700142] multipeer session: reset timer
,2016-04-06 03:16:50.479 ThaliTest[490:700142] server: rejecting invitation from 7DE50CBF-CC92-4CD5-AA12-B28CD384766D due to previous generation (8C5B19F5-9879-44C8-A20C-4970704F4B6A:8 != 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7)
,2016-04-06 03:16:50.661 ThaliTest[490:701254] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:16:50.661 ThaliTest[490:701254] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
,2016-04-06 03:16:50.662 ThaliTest[490:701254] client session: disconnect
,2016-04-06 03:16:50.663 ThaliTest[490:701254] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:16:50.664 ThaliTest[490:701254] client session: no connect callback (server initiated)
,2016-04-06 03:16:59.181 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-06 03:17:02.192 ThaliTest[490:700403] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:17:02.193 ThaliTest[490:700403] client: server will connect
,2016-04-06 03:17:02.194 ThaliTest[490:700403] client session: reverseConnect
,2016-04-06 03:17:02.195 ThaliTest[490:700403] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:17:02.595 ThaliTest[490:701253] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:17:02.595 ThaliTest[490:701253] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:17:02.596 T,haliTest[490:701253] client session: disconnect
,2016-04-06 03:17:02.596 ThaliTest[490:701253] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:17:02.598 ThaliTest[490:701253] client session: no connect callback (server initiated)
,2016-04-06 03:17:02.653 ThaliTest[490:700142] multipeer session: reset timer
,2016-04-06 03:17:02.653 ThaliTest[490:700142] server: disconnecting to refresh session (7DE50CBF-CC92-4CD5-AA12-B28CD384766D)
,2016-04-06 03:17:02.654 ThaliTest[490:700142] server: rejecting invitation from 7DE50CBF-CC92-4CD5-AA12-B28CD384766D due to previous generation (8C5B19F5-9879-44C8-A20C-4970704F4B6A:8 != 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7)
,2016-04-06 03:17:08.222 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:17:08.248 ThaliTest[490:700142] client: found updated peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:08.249 ThaliTest[490:700142] client: found updated peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:17:08.250 ThaliTest[490:700142] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C5E616F6-311E-4AAE-ABEF-071095D8F02C:8","pleaseConnect":0}]
,2016-04-06 03:17:12.195 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-06 03:17:15.203 ThaliTest[490:700403] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:17:15.204 ThaliTest[490:700403] client: server will connect
,2016-04-06 03:17:15.205 ThaliTest[490:700403] client session: reverseConnect
,2016-04-06 03:17:15.205 ThaliTest[490:700403] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:17:15.442 ThaliTest[490:701330] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:17:15.442 ThaliTest[490:701330] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:17:15.443 T,haliTest[490:701330] client session: disconnect
,2016-04-06 03:17:15.443 ThaliTest[490:701330] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:17:15.444 ThaliTest[490:701330] client session: no connect callback (server initiated)
,2016-04-06 03:17:16.080 ThaliTest[490:700142] multipeer session: reset timer
,2016-04-06 03:17:16.081 ThaliTest[490:700142] server: disconnecting to refresh session (7DE50CBF-CC92-4CD5-AA12-B28CD384766D)
,2016-04-06 03:17:16.081 ThaliTest[490:700142] server: rejecting invitation from 7DE50CBF-CC92-4CD5-AA12-B28CD384766D due to previous generation (8C5B19F5-9879-44C8-A20C-4970704F4B6A:8 != 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7)
,2016-04-06 03:17:25.206 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-06 03:17:28.211 ThaliTest[490:700403] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:17:28.213 ThaliTest[490:700403] client: server will connect
2016-04-06 03:17:28.213 ThaliTest[490:700403] client session: reverseConnect
,2016-04-06 03:17:28.214 ThaliTest[490:700403] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:17:28.222 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:17:28.260 ThaliTest[490:700142] client: lost peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:17:28.261 ThaliTest[490:700142] client session: onPeerLost: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:17:28.261 ThaliTest[490:700142] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:17:28.261 ThaliTest[490:700142] client session: disconnect
,2016-04-06 03:17:28.262 ThaliTest[490:700142] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:17:28.263 ThaliTest[490:700142] client session: no connect callback (server initiated)
,2016-04-06 03:17:28.264 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:28.265 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:28.265 Th,aliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C5E616F6-311E-4AAE-ABEF-071095D8F02C:8","pleaseConnect":0}]
,2016-04-06 03:17:38.215 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-06 03:17:41.222 ThaliTest[490:700403] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:17:41.223 ThaliTest[490:700403] client: server will connect
,2016-04-06 03:17:41.224 ThaliTest[490:700403] client session: reverseConnect
,2016-04-06 03:17:41.224 ThaliTest[490:700403] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:17:41.515 ThaliTest[490:701483] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:17:41.516 ThaliTest[490:701483] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:17:41.516 ThaliTest[490:701483] client session: disconnect
2016-04-06 03:17:41.517 ThaliTest[490:701483] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:17:41.517 ThaliTest[490:701483] client session: no connect callback (server initiated)
,2016-04-06 03:17:48.222 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:17:48.249 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:48.249 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:48.249 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:17:51.225 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-06 03:17:54.230 ThaliTest[490:700403] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:17:54.231 ThaliTest[490:700403] client: server will connect
2016-04-06 03:17:54.232 ThaliTest[490:700403] client session: reverseConnect
,2016-04-06 03:17:54.232 ThaliTest[490:700403] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:17:54.346 ThaliTest[490:701512] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:17:54.347 ThaliTest[490:701512] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:17:54.347 T,haliTest[490:701512] client session: disconnect
,2016-04-06 03:17:54.347 ThaliTest[490:701512] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:17:54.348 ThaliTest[490:701512] client session: no connect callback (server initiated)
,2016-04-06 03:18:04.233 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-06 03:18:07.242 ThaliTest[490:700403] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:18:07.243 ThaliTest[490:700403] client: server will connect
,2016-04-06 03:18:07.244 ThaliTest[490:700403] client session: reverseConnect
2016-04-06 03:18:07.244 ThaliTest[490:700403] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:07.528 ThaliTest[490:701556] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:07.528 ThaliTest[490:701556] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:18:07.528 ThaliTest[490:701556] client session: disconnect
,2016-04-06 03:18:07.529 ThaliTest[490:701556] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:07.530 ThaliTest[490:701556] client session: no connect callback (server initiated)
,2016-04-06 03:18:08.222 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:18:08.251 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:08.252 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:08.253 Th,aliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:18:17.245 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-06 03:18:20.261 ThaliTest[490:700403] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:18:20.262 ThaliTest[490:700403] client: server will connect
,2016-04-06 03:18:20.263 ThaliTest[490:700403] client session: reverseConnect
2016-04-06 03:18:20.264 ThaliTest[490:700403] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:20.634 ThaliTest[490:701559] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:20.635 ThaliTest[490:701559] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
,2016-04-06 03:18:20.635 ThaliTest[490:701559] client session: disconnect
,2016-04-06 03:18:20.637 ThaliTest[490:701559] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:20.638 ThaliTest[490:701559] client session: no connect callback (server initiated)
,2016-04-06 03:18:28.222 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:18:28.251 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:28.251 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:18:28.252 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:30.264 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-06 03:18:33.269 ThaliTest[490:700403] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:18:33.270 ThaliTest[490:700403] client: server will connect
2016-04-06 03:18:33.270 ThaliTest[490:700403] client session: reverseConnect
,2016-04-06 03:18:33.271 ThaliTest[490:700403] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:33.791 ThaliTest[490:701618] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:33.792 ThaliTest[490:701618] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:18:33.792 ThaliTest[490:701618] client session: disconnect
2016-04-06 03:18:33.792 ThaliTest[490:701618] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:33.793 ThaliTest[490:701618] client session: no connect callback (server initiated)
,2016-04-06 03:18:43.272 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-06 03:18:46.276 ThaliTest[490:700403] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:18:46.277 ThaliTest[490:700403] client: server will connect
,2016-04-06 03:18:46.278 ThaliTest[490:700403] client session: reverseConnect
,2016-04-06 03:18:46.279 ThaliTest[490:700403] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:46.386 ThaliTest[490:701647] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:46.386 ThaliTest[490:701647] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:18:46.387 ThaliTest[490:701647] client session: disconnect
,2016-04-06 03:18:46.387 ThaliTest[490:701647] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:46.388 ThaliTest[490:701647] client session: no connect callback (server initiated)
,2016-04-06 03:18:48.222 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:18:56.279 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-04-06 03:18:56.413 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-06 03:18:56.415 ThaliTest[490:700403] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:18:56.418 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening
,2016-04-06 03:18:56.418 ThaliTest[490:700403] THEMultipeerManager stopping peer
,2016-04-06 03:18:56.421 ThaliTest[490:700403] multipeer manager: stop client timer
,2016-04-06 03:18:56.431 ThaliTest[490:700403] jxcore: stopAdvertisingAndListening: success
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-06 03:18:57.638 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening
,2016-04-06 03:18:57.638 ThaliTest[490:700403] server: starting 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:18:57.640 ThaliTest[490:700403] multipeer manager: start client restart timer: 0x14d62dd0
2016-04-06 03:18:57.640 ThaliTest[490:700403] THEMultipeerManager initialized peer 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:18:57.641 ThaliTest[490:700403] jxcore: startUpdateAdvertisingAndListening: success
,ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:18:57.644 ThaliTest[490:700403] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-06 03:18:57.646 ThaliTest[490:700403] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-06 03:18:58.516 ThaliTest[490:700142] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:18:58.517 ThaliTest[490:700142] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:18:58.520 ThaliTest[490:700403] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:18:58.521 ThaliTest[490:700142] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:58.522 ThaliTest[490:700403] client: server will connect
2016-04-06 03:18:58.522 ThaliTest[490:700403] client session: reverseConnect
2016-04-06 03:18:58.522 ThaliTest[490:700403] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:00.222 ThaliTest[490:701668] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:00.223 ThaliTest[490:701668] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:19:00.224 ThaliTest[490:701668] client session: disconnect
2016-04-06 03:19:00.224 ThaliTest[490:701668] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:00.225 ThaliTest[490:701668] client session: no connect callback (server initiated)
,2016-04-06 03:19:08.533 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-06 03:19:11.539 ThaliTest[490:700403] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:19:11.540 ThaliTest[490:700403] client: server will connect
,2016-04-06 03:19:11.540 ThaliTest[490:700403] client session: reverseConnect
2016-04-06 03:19:11.541 ThaliTest[490:700403] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:11.807 ThaliTest[490:701692] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:11.808 ThaliTest[490:701692] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:19:11.809 ThaliTest[490:701692] client session: disconnect
2016-04-06 03:19:11.810 ThaliTest[490:701692] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:11.810 ThaliTest[490:701692] client session: no connect callback (server initiated)
,2016-04-06 03:19:17.641 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:19:17.663 ThaliTest[490:700142] client: found updated peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:19:17.664 ThaliTest[490:700142] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:19:17.664 ThaliTest[490:700142] client: found updated peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:21.542 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-06 03:19:24.548 ThaliTest[490:700403] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:24.548 ThaliTest[490:700403] client: server will connect
,2016-04-06 03:19:24.550 ThaliTest[490:700403] client session: reverseConnect
,2016-04-06 03:19:24.550 ThaliTest[490:700403] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:19:24.704 ThaliTest[490:701731] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:19:24.705 ThaliTest[490:701731] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:19:24.705 T,haliTest[490:701731] client session: disconnect
,2016-04-06 03:19:24.707 ThaliTest[490:701731] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:19:24.708 ThaliTest[490:701731] client session: no connect callback (server initiated)
,2016-04-06 03:19:34.550 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-06 03:19:37.556 ThaliTest[490:700403] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:37.557 ThaliTest[490:700403] client: server will connect
,2016-04-06 03:19:37.557 ThaliTest[490:700403] client session: reverseConnect
,2016-04-06 03:19:37.558 ThaliTest[490:700403] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:19:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:19:37.666 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:19:37.666 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:37.667 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:19:47.559 ThaliTest[490:700142] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-06 03:19:50.569 ThaliTest[490:700403] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:50.570 ThaliTest[490:700403] client: already connect(ing/ed) to BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:50.570 ThaliTest[490:700403] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-06 03:19:53.583 ThaliTest[490:700403] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:53.584 ThaliTest[490:700403] client: already connect(ing/ed) to BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:53.585 ThaliTest[490:700403] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-06 03:19:56.599 ThaliTest[490:700403] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:56.600 ThaliTest[490:700403] client: already connect(ing/ed) to BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:19:56.601 ThaliTest[490:700403] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-06 03:19:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:19:57.673 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:19:57.674 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:57.674 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:19:59.615 ThaliTest[490:700403] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:59.616 ThaliTest[490:700403] client: already connect(ing/ed) to BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:19:59.617 ThaliTest[490:700403] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-06 03:20:02.636 ThaliTest[490:700403] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:20:02.637 ThaliTest[490:700403] client: already connect(ing/ed) to BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:20:02.638 ThaliTest[490:700403] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-06 03:20:05.654 ThaliTest[490:700403] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:20:05.654 ThaliTest[490:700403] client: already connect(ing/ed) to BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:20:05.655 ThaliTest[490:700403] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-06 03:20:10.505 ThaliTest[490:701957] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:20:10.506 ThaliTest[490:701957] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
,2016-04-06 03:20:10.506 ThaliTest[490:701957] client session: disconnect
,2016-04-06 03:20:10.507 ThaliTest[490:701957] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:20:10.508 ThaliTest[490:701957] client session: no connect callback (server initiated)
,2016-04-06 03:20:17.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:20:17.671 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:20:17.672 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:20:17.672 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:20:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:20:37.671 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:37.672 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:20:37.672 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:20:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:20:57.673 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:20:57.673 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:57.674 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:21:17.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:21:17.671 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:21:17.671 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:21:17.672 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:21:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:21:37.674 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:21:37.675 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:21:37.676 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:21:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:21:57.675 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:21:57.675 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:21:57.676 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:22:17.641 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:22:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:22:37.664 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:22:37.665 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:22:37.665 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:22:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:22:57.664 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:22:57.665 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:22:57.665 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:23:17.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:23:17.664 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:23:17.665 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:23:17.665 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:23:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:23:37.665 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:23:37.665 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:23:37.666 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:23:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:23:57.666 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:23:57.667 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:23:57.667 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:24:17.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:24:17.665 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:24:17.665 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:24:17.666 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:24:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:24:37.664 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:24:37.665 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:24:37.665 Th,aliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:24:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:24:57.666 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:24:57.667 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:24:57.667 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:25:17.641 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:25:17.662 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:25:17.663 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:25:17.664 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:25:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:25:37.667 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:25:37.667 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:25:37.667 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:25:57.641 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:25:57.666 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:25:57.666 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:25:57.667 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:26:17.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:26:17.665 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:26:17.666 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:26:17.666 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:26:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:26:37.664 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:26:37.665 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:26:37.665 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:26:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:26:57.664 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:26:57.665 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:26:57.665 Th,aliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:27:17.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:27:17.666 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:27:17.666 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:27:17.667 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:27:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:27:37.667 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:27:37.668 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:27:37.668 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:27:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:27:57.665 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:27:57.665 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:27:57.666 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:28:17.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:28:17.663 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:28:17.666 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:28:17.666 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:28:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:28:37.666 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:28:37.666 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:28:37.667 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:28:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:28:57.664 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:28:57.664 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:28:57.665 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:29:17.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:29:17.665 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:29:17.666 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:29:17.666 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:29:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:29:37.665 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:29:37.666 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:29:37.666 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:29:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:29:57.666 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:29:57.667 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:29:57.667 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:30:17.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:30:17.664 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:30:17.664 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:30:17.664 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:30:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:30:37.667 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:30:37.667 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:30:37.668 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:30:57.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:30:57.668 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:30:57.668 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:30:57.669 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:31:17.641 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:31:17.664 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:17.665 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:31:17.665 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:31:37.642 ThaliTest[490:700142] multipeer manager: restart client
,2016-04-06 03:31:37.666 ThaliTest[490:700142] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:31:37.667 ThaliTest[490:700142] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:31:37.667 ThaliTest[490:700142] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9

```
