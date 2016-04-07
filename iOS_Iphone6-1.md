#### Test 656816764cf5745_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5A573341-16F2-46FC-896A-377C6FD2DAFE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5A573341-16F2-46FC-896A-377C6FD2DAFE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51796"
,(lldb)     command script import "/tmp/5A573341-16F2-46FC-896A-377C6FD2DAFE/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-07 21:22:52.445 ThaliTest[2910:5781786] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/545B22B1-2DDA-4A33-9BBA-B60EC8C701E0/Library/Cookies/Cookies.binarycookies
,2016-04-07 21:22:52.676 ThaliTest[2910:5781786] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-07 21:22:52.677 ThaliTest[2910:5781786] Multi-tasking -> Device: YES, App: YES
,2016-04-07 21:22:52.691 ThaliTest[2910:5781786] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-07 21:22:53.462 ThaliTest[2910:5781786] Using UIWebView
2016-04-07 21:22:53.464 ThaliTest[2910:5781786] [CDVTimer][handleopenurl] 0.133991ms
2016-04-07 21:22:53.466 ThaliTest[2910:5781786] [CDVTimer][intentandnavigationfilter] 2.104998ms
2016-04-07 21:22:53.466 ThaliTest[2910:5781786] [CDVTimer][gesturehandler] 0.096977ms
2016-04-07 21:22:53.467 ThaliTest[2910:5781786] [CDVTimer][TotalPluginStartup] 2.760053ms
,2016-04-07 21:22:56.585 ThaliTest[2910:5781786] Resetting plugins due to page load.
,2016-04-07 21:22:57.969 ThaliTest[2910:5781786] Finished load of: file:///var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/index.html
,2016-04-07 21:22:58.138 ThaliTest[2910:5781786] JXcore Cordova plugin initializing
,2016-04-07 21:22:58.223 ThaliTest[2910:5781970] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-07 21:23:05.183 ThaliTest[2910:5781970] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-07 21:23:05.183 ThaliTest[2910:5781970] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-07 21:23:05.183 ThaliTest[2910:5781970] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-07 21:23:05.186 ThaliTest[2910:5781970] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C1DF7399-5B91-4674-90A7-BB3344BD4555/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57992
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57994
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57997
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
,ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58001
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58006
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58010
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58014
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58018
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58022
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
DEBUG createNativeListener: listening 58074
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58078
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
,# teardown
,# setup
,# 12. closeAll can close even when connections open
,ok 45 not possible to connect to the server anymore
# teardown
,# setup
,# 13. closeAll with promise
,ok 46 not possible to connect to the server anymore
# teardown
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
ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue
# teardown
,# setup
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
ok 58 thirdPromise - in resolve
ok 59 secondPromise - second to run
ok 60 secondPromise - in catch
ok 61 firstPromise - third to run
ok 62 firstPromise - in then
ok 63 testing promises
# teardown
,# setup
,# 18. mix enqueue and enqueueAtTop
,ok 64 fourth
,ok 65 fourth
ok 66 second
ok 67 secondPromise - in then
,ok 68 first
ok 69 firstPromise - in catch
ok 70 third
ok 71 thirdPromise - in then
,ok 72 testingPromises
# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
# teardown
,# setup
,# 20. basic
,ok 74 sane
# teardown
,# setup
,# 21. another
,ok 75 sane
# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"03445e62-5e92-48cc-8875-30b0fdcb1b59","data":"custom data"},{"uuid":"cc977dc9-3774-4da7-8114-07bc6d4a1955","data":"custom data"},{"uuid":"856d22a5-0926-412e-b7a9-ad2877c2c912","data":"custom data"},{"uuid":"1019d4f9-108b-42a3-b511-e8f2013d3ebb",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83 participant data matches
ok 84 own UUID is found from the participants list
# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 85 specific error should be returned
# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
# teardown
,ok 89 error should be null
ok 90 error should be null
# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58088
2016-04-07 21:25:37.391 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:37.393 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 e,rror should be null
2016-04-07 21:25:37.394 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:37.395, ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-07 21:25:37.545 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
,2016-04-07 21:25:37.545 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
,2016-04-07 21:25:37.545 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
,2016-04-07 21:25:37.546 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:25:37.547 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58090
,2016-04-07 21:25:37.754 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements
2016-04-07 21:25:37.755 ThaliTest[2910:5781970] multipeer manager: start client restart timer: 0x145b6190
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:25:37.755 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
,2016-04-07 21:25:37.762 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:25:37.763 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-07 21:25:38.071 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:38.071 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:25:38.071 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:38.071 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
2016-04-07 21:25:38.071 ThaliTest[2910:5781970] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:38.072 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58092
2016-04-07 21:25:38.673 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:25:38.673 ThaliTest[2910:5781970] server: starting 3A,9DE2CF-AEE1-4BE9-994B-D8804B4E2499:1
2016-04-07 21:25:38.674 ThaliTest[2910:5781970] multipeer manager: start client restart timer: 0x145b6190
2016-04-07 21:25:38.674 ThaliTest[2910:5781970] THEMultipeerManager initialized peer 3A9DE2CF-AEE1-4BE9-994B-D8,804B4E2499:1
2016-04-07 21:25:38.674 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-07 21:25:38.680 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:25:38.680 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:25:38.680, ThaliTest[2910:5781970] multipeer manager: stop client timer
2016-04-07 21:25:38.680 ThaliTest[2910:5781970] server: starting 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:2
2016-04-07 21:25:38.681 ThaliTest[2910:5781970] multipeer manager: start client restart ,timer: 0x145b6190
2016-04-07 21:25:38.681 ThaliTest[2910:5781970] THEMultipeerManager initialized peer 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:2
2016-04-07 21:25:38.681 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
,# teardown
,2016-04-07 21:25:39.855 ThaliTest[2910:5781786] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:2
2016-04-07 21:25:39.856 ThaliTest[2910:5781786] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:2
,2016-04-07 21:25:40.012 ThaliTest[2910:5781786] client: found new peer: BF68E1C5-762A-429C-BDD9-41F21131A115:2
,2016-04-07 21:25:40.531 ThaliTest[2910:5781786] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-07 21:25:40.710 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:40.710 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:25:40.710 ThaliTest[2910:5781970] multipeer manager: stop client timer
2016-04-07 21:25:40.710 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:25:40.710 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:40.711 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58097
2016-04-07 21:25:41.381 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:41.381 ThaliTest[2910:5781970] THEMultipeerManager stoppi,ng peer
2016-04-07 21:25:41.381 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
2016-04-07 21:25:41.382 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07, 21:25:41.383 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:25:41.383 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-07 21:25:42.157 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:42.157 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:25:42.157 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:25:42.158 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:42.158 ThaliTest[2910,:5781970] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58099
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-07 21:25:42.665 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:42.666 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:25:42.666 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:25:42.666 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:42.666 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58101
2016-04-07 21:25:42.908 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements
2016-04-07 21:25:42.908 ThaliTest[2910:5781970] multipeer manager: sta,rt client restart timer: 0x145b6190
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:25:42.909 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements: success
,2016-04-07 21:25:42.916 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:25:42.916 ThaliTest[2910:5781970] server: starting 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:3
2016-04-07 21:25:42.916 ThaliTest[2910:5781970] THEMultipee,rManager initialized peer 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:3
2016-04-07 21:25:42.916 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-07 21:25:43.253 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:43.253 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:25:43.254 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:43.254 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
2016-04-07 21:25:43.254 ThaliTest[2910:5781970] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:25:43.254 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 123 error should be null
,ok 124 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
,ok 126 should not have been called more than once
,# teardown
,ok 127 error should be null
ok 128 error should be null
# setup
,# 32. can get the network status
,ok 129 network status should have certain non-empty properties
# teardown
,ok 130 error should be null
ok 131 error should be null
# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
,ok 133 port should match
,ok 134 host address should be null
ok 135 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-07 21:26:12.403 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements
2016-04-07 21:26:12.403 ThaliTest[2910:5781970] multipeer manager: start client restart timer: 0x145b6190
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:26:12.404 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-07 21:26:12.404 ThaliTes,t[2910:5781970] jxcore: stopListeningForAdvertisements
2016-04-07 21:26:12.404 ThaliTest[2910:5781970] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:26:12.405 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-07 21:26:36.135 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:26:36.136 ThaliTest[2910:57819,70] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:26:36.136 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:26:36.136 ThaliTest[2910:57819,70] THEMultipeerManager stopping peer
2016-04-07 21:26:36.136 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-07 21:26:54.449 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements
2016-04-07 21:26:54.450 ThaliTest[2910:5781970] multipeer manager: start client restart timer: 0x145b6190
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:26:54.450 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-07 21:26:54.451 ThaliTes,t[2910:5781970] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:26:54.451 ThaliTest[2910:5781970] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-07 21:26:55.247 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
2016-04-07 21:26:55.247 ThaliTest[2910:5781970] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:26:55.248 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:26:55.248 ThaliTest[2910:5781,970] jxcore: stopAdvertisingAndListening
2016-04-07 21:26:55.248 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:26:55.248 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-07 21:27:20.993 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:20.994 ThaliTest[2910:57819,70] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-07 21:27:20.994 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:20.995 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-07 21:27:21.170 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:21.171 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:21.171 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:21.171 ThaliTest[2910:57819,70] THEMultipeerManager stopping peer
2016-04-07 21:27:21.171 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-07 21:27:21.459 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:21.460 ThaliTest[2910:5781970] server: starting 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:4
2016-04-07 21:27:21.460 ThaliTest[2910:5781970] multipeer manager: start client restart timer: 0x145b6190
2016-04-07 21:27:21.460 ThaliTest[2910:5781970] THEMultipeerManager initialized peer 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:4
2016-04-07 21:27:21.460 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:27:21.461 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:21.461 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
,2016-04-07 21:27:21.461 ThaliTest[2910:5781970] multipeer manager: stop client timer
2016-04-07 21:27:21.464 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-07 21:27:21.780 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:21.781 ThaliTest[2910:57819,70] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:21.781 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:21.781 ThaliTest[2910:57819,70] THEMultipeerManager stopping peer
2016-04-07 21:27:21.781 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-07 21:27:22.232 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:22.232 ThaliTest[2910:5781970] server: starting 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:5
2016-04-07 21:27:22.233 ThaliTest[2910:5781970] multipeer m,anager: start client restart timer: 0x145b6190
2016-04-07 21:27:22.233 ThaliTest[2910:5781970] THEMultipeerManager initialized peer 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:5
2016-04-07 21:27:22.233 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:27:22.234 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:22.234 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
,2016-04-07 21:27:22.234 ThaliTest[2910:5781970] multipeer manager: stop client timer
2016-04-07 21:27:22.237 ThaliTest[2910:5781970] server: starting 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:6
2016-04-07 21:27:22.237 ThaliTest[2910:5781970] multipeer manager,: start client restart timer: 0x145b6190
2016-04-07 21:27:22.237 ThaliTest[2910:5781970] THEMultipeerManager initialized peer 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:6
2016-04-07 21:27:22.237 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-07 21:27:22.389 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-07 21:27:22.390 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:27:22.391 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:22.391 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:27:22.391 ThaliTest[2910:5781970] multipeer manager: stop client timer
20,16-04-07 21:27:22.392 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-07 21:27:25.927 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:25.927 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:27:25.927 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:27:25.928 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:25.928 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:27,:25.928 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-07 21:27:52.201 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:52.202 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:52.203 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:52.203 ThaliTest[2910:57819,70] THEMultipeerManager stopping peer
2016-04-07 21:27:52.203 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-07 21:27:55.525 ThaliTest[2910:5781970] jxcore: connect foo
2016-04-07 21:27:55.525 ThaliTest[2910:5781970] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-07 21:27:55.652 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:55.653 ThaliTest[2910:57819,70] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:55.653 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:55.653 ThaliTest[2910:57819,70] THEMultipeerManager stopping peer
2016-04-07 21:27:55.653 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-07 21:27:55.840 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:55.840 ThaliTest[2910:5781970] server: starting 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:7
2016-04-07 21:27:55.840 ThaliTest[2910:5781970] multipeer manager: start client restart timer: 0x145b6190
2016-04-07 21:27:55.840 ThaliTest[2910:5781970] THEMultipeerManager initialized peer 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:7
2016-04-07 21:27:55.840 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-07 21:27:55.841 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-07 21:27:55.841 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-07 21:27:56.964 ThaliTest[2910:5781786] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:27:56.965 ThaliTest[2910:5781786] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-07 21:27:56.994 ThaliTest[2910:5781786] client: found new peer: BF68E1C5-762A-429C-BDD9-41F21131A115:7
,2016-04-07 21:27:59.810 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:27:59.811 ThaliTest[2910:578197,0] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:59.811 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:59.811 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:27:59.812 ThaliTest[2910:5781970] multipeer manager: stop client timer
2016-04-07 21:27:59.812 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-07 21:28:30.762 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:28:30.762 ThaliTest[2910:5781970] server: starting 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:28:30.762 ThaliTest[2910:5781970] multipeer m,anager: start client restart timer: 0x145b6190
2016-04-07 21:28:30.763 ThaliTest[2910:5781970] THEMultipeerManager initialized peer 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:28:30.763 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:28:30.763 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-07 21:28:30.764 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-07 21:28:33.442 ThaliTest[2910:5781786] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"750E93F7-2E92-4298-982A-D1BFBCF07378:7","pleaseConnect":0}]
2016-04-07 21:28:33.444 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:33.444 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:28:33.444 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:28:33.444 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:7
,2016-04-07 21:28:34.420 ThaliTest[2910:5781786] client: found new peer: BF68E1C5-762A-429C-BDD9-41F21131A115:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BF68E1C5-762A-429C-BDD9-41F21131A115:7","pleaseConnect":0}]
,2016-04-07 21:28:34.727 ThaliTest[2910:5781786] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7","pleaseConnect":0}]
,2016-04-07 21:28:35.193 ThaliTest[2910:5783767] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:35.194 ThaliTest[2910:5783767] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:35.194 ThaliTest[2910:5783767] client session: disconnect
2016-04-07 21:28:35.194 ThaliTest[2910:5783767] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:35.195 ThaliTest[2910:5783767] client session: no connect callb,ack (server initiated)
,2016-04-07 21:28:35.555 ThaliTest[2910:5781786] multipeer session: reset timer
2016-04-07 21:28:35.556 ThaliTest[2910:5781786] server session: connect
2016-04-07 21:28:35.556 ThaliTest[2910:5781786] server session: stateChange:0->1 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:28:35.560 ThaliTest[2910:5781786] server: accepting invitation E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:28:38.275 ThaliTest[2910:5783788] server session: p2p link connected
,2016-04-07 21:28:38.344 ThaliTest[2910:5781786] server relay: connected (to port: 58108)
2016-04-07 21:28:38.344 ThaliTest[2910:5781786] server session: stateChange:1->2 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:28:43.445 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 9
,2016-04-07 21:28:46.459 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:46.459 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:28:46.459 ThaliTest[2910:5781970] client session: reverseConn,ect
2016-04-07 21:28:46.459 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:7
,2016-04-07 21:28:46.596 ThaliTest[2910:5783766] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:46.597 ThaliTest[2910:5783766] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:46.597 ThaliTest[2910:5783766] client session: disconnect
2016-04-07 21:28:46.597 ThaliTest[2910:5783766] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:46.597 ThaliTest[2910:5783766] client session: no connect callb,ack (server initiated)
,2016-04-07 21:28:50.764 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:28:50.774 ThaliTest[2910:5781786] client: found updated peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"750E93F7-2E92-4298-982A-D1BFB,CF07378:8","pleaseConnect":0}]
2016-04-07 21:28:50.776 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
2016-04-07 21:28:50.776 ThaliTest[2910:5781786] client: found updated peer: BF68E1C5-762A-429C-BDD9-41F2113,1A115:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BF68E1C5-762A-429C-BDD9-41F21131A115:8","pleaseConnect":0}]
,2016-04-07 21:28:56.460 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-04-07 21:28:59.463 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:59.464 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:28:59.465 ThaliTest[2910:5781970] client session: reverseConn,ect
2016-04-07 21:28:59.465 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:28:59.881 ThaliTest[2910:5783830] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:28:59.882 ThaliTest[2910:5783830] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:59.8,82 ThaliTest[2910:5783830] client session: disconnect
2016-04-07 21:28:59.883 ThaliTest[2910:5783830] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:28:59.884 ThaliTest[2910:5783830] client session: no connect callb,ack (server initiated)
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-07 21:29:09.466 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-07 21:29:10.764 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:29:10.775 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:29:10.775 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:10.77,5 ThaliTest[2910:5781786] client: found updated peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8","pleaseConnect":0}]
,2016-04-07 21:29:12.467 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:29:12.467 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:29:12.467 ThaliTest[2910:5781970] client session: reverseConn,ect
2016-04-07 21:29:12.467 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:29:12.739 ThaliTest[2910:5784021] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:12.739 ThaliTest[2910:5784021] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:29:12.740 ThaliTest[2910:5784021] client session: disconnect
2016-04-07 21:29:12.740 ThaliTest[2910:5784021] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:29:12.741 ThaliTest[2910:5784021] client session: no connect callback (server initiated)
,2016-04-07 21:29:22.468 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-07 21:29:25.475 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:29:25.475 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:29:25.475 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:29:25.476 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:29:25.839 ThaliTest[2910:5784077] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:29:25.840 ThaliTest[2910:5784077] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:29:25.840 ThaliTest[2910:5784077] client session: disconnect
2016-04-07 21:29:25.840 ThaliTest[2910:5784077] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:25.840 ThaliTest[2910:5784077] client session: no connect callback (server initiated)
,2016-04-07 21:29:30.764 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:29:30.771 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:29:30.772 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:30.772 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:35.476 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-07 21:29:38.478 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:29:38.479 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:29:38.479 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:29:38.479 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:29:38.681 ThaliTest[2910:5784121] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:38.681 ThaliTest[2910:5784121] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:29:38.6,81 ThaliTest[2910:5784121] client session: disconnect
2016-04-07 21:29:38.681 ThaliTest[2910:5784121] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:38.681 ThaliTest[2910:5784121] client session: no connect callback (server initiated)
,2016-04-07 21:29:48.480 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-07 21:29:50.763 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:29:50.775 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:50.775 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:29:50.77,6 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:51.493 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:29:51.493 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:29:51.493 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:29:51.493 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:29:51.656 ThaliTest[2910:5784148] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:51.656 ThaliTest[2910:5784148] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:29:51.6,56 ThaliTest[2910:5784148] client session: disconnect
2016-04-07 21:29:51.656 ThaliTest[2910:5784148] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:51.656 ThaliTest[2910:5784148] client session: no connect callback (server initiated)
,2016-04-07 21:30:01.494 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-07 21:30:04.505 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:30:04.505 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:30:04.505 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:30:04.505 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:30:04.658 ThaliTest[2910:5784121] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:04.659 ThaliTest[2910:5784121] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
,2016-04-07 21:30:04.659 ThaliTest[2910:5784121] client session: disconnect
2016-04-07 21:30:04.660 ThaliTest[2910:5784121] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:04.660 ThaliTest[2910:5784121] client session: no connect callback (server initiated)
,2016-04-07 21:30:10.763 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:30:10.773 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:10.773 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:30:10.77,3 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:14.506 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 21:30:17.518 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:30:17.519 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:30:17.519 ThaliTest[2910:5781970] client session: reverseConn,ect
2016-04-07 21:30:17.519 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:30:17.609 ThaliTest[2910:5784121] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:17.610 ThaliTest[2910:5784121] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:30:17.610 ThaliTest[2910:5784121] client session: disconnect
2016-04-07 21:30:17.610 ThaliTest[2910:5784121] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:30:17.611 ThaliTest[2910:5784121] client session: no connect callback (server initiated)
,2016-04-07 21:30:27.520 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-07 21:30:30.523 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:30:30.523 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:30:30.523 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:30:30.523 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:30:30.764 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:30:30.779 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:30.780 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:30:30.780 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:40.524 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-04-07 21:30:40.956 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements
2016-04-07 21:30:40.957 ThaliTest[2910:5781786] server relay: socket disconnected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingA,ctive":true,"discoveryActive":false}
2016-04-07 21:30:40.957 ThaliTest[2910:5781970] jxcore: stopListeningForAdvertisements: success
2016-04-07 21:30:40.958 ThaliTest[2910:5781786] server relay: 0x15c85c20 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
ok 178 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:30:40.958 ThaliTest[2910:5781970] jxcore: stopAdve,rtisingAndListening
2016-04-07 21:30:40.958 ThaliTest[2910:5781970] THEMultipeerManager stopping peer
2016-04-07 21:30:40.959 ThaliTest[2910:5781970] server session: disconnect
2016-04-07 21:30:40.959 ThaliTest[2910:5781970] server session: stateChange:,2->0 E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:40.963 ThaliTest[2910:5781970] client session: disconnect
2016-04-07 21:30:40.963 ThaliTest[2910:5781970] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:40.963 ThaliTest[2910:5781970] multipeer m,anager: stop client timer
2016-04-07 21:30:40.963 ThaliTest[2910:5781970] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-07 21:30:49.603 ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:30:49.604 ThaliTest[2910:5781970] server: starting 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:30:49.605 ThaliTest[2910:5781970] multipeer manager: start client restart timer: 0x145b6190
2016-04-07 21:30:49.605 ThaliTest[2910:5781970] THEMultipeerManager initialized peer 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:30:49.605 ,ThaliTest[2910:5781970] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:30:49.606 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeW,rapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-07 21:30:49.606 ThaliTest[2910:5781970] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-07 21:30:49.613 ThaliTest[2910:5781786] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:49.614 ThaliTest[2910:5781786] client: found new peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
,2016-04-07 21:30:49.616 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:49.616 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:30:49.616 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:30:49.617 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:30:50.364 ThaliTest[2910:5784298] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:50.365 ThaliTest[2910:5784298] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:30:50.3,65 ThaliTest[2910:5784298] client session: disconnect
2016-04-07 21:30:50.365 ThaliTest[2910:5784298] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:50.366 ThaliTest[2910:5784298] client session: no connect callb,ack (server initiated)
,2016-04-07 21:30:59.618 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-07 21:31:02.621 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:31:02.621 ThaliTest[2910:5781970] client: server will connect
,2016-04-07 21:31:02.621 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:31:02.622 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:31:02.945 ThaliTest[2910:5784145] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:31:02.946 ThaliTest[2910:5784145] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:31:02.946 ThaliTest[2910:5784145] client session: disconnect
2016-04-07 21:31:02.946 ThaliTest[2910:5784145] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:31:02.946 ThaliTest[2910:5784145] client session: no connect callback (server initiated)
,2016-04-07 21:31:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:31:09.614 ThaliTest[2910:5781786] client: found updated peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:31:09.614 ThaliTest[2910:5781786] client: found updated peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:12.622 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-07 21:31:15.634 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:31:15.634 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:31:15.634 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:31:15.634 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:15.862 ThaliTest[2910:5784428] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:15.863 ThaliTest[2910:5784428] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:31:15.8,63 ThaliTest[2910:5784428] client session: disconnect
2016-04-07 21:31:15.863 ThaliTest[2910:5784428] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:15.863 ThaliTest[2910:5784428] client session: no connect callback (server initiated)
,2016-04-07 21:31:25.635 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-07 21:31:28.645 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:31:28.645 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:31:28.645 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:31:28.645 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:29.149 ThaliTest[2910:5784463] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:29.149 ThaliTest[2910:5784463] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
,2016-04-07 21:31:29.149 ThaliTest[2910:5784463] client session: disconnect
2016-04-07 21:31:29.150 ThaliTest[2910:5784463] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:29.150 ThaliTest[2910:5784463] client sess,ion: no connect callback (server initiated)
,2016-04-07 21:31:29.605 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:31:29.613 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:29.613 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:31:30.272 ThaliTest[2910:5781786] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:31:38.646 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-07 21:31:41.658 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:31:41.659 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:31:41.659 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:31:41.659 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:41.808 ThaliTest[2910:5784470] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:41.808 ThaliTest[2910:5784470] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:31:41.8,08 ThaliTest[2910:5784470] client session: disconnect
2016-04-07 21:31:41.809 ThaliTest[2910:5784470] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:41.809 ThaliTest[2910:5784470] client session: no connect callback (server initiated)
,2016-04-07 21:31:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:31:49.616 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:49.616 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:31:49.617 ThaliTest[2910:5781786] client: found updated peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:31:51.660 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-07 21:31:54.668 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:31:54.669 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:31:54.669 ThaliTest[2910:5781970] client session: reverseConn,ect
,2016-04-07 21:31:54.669 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:54.790 ThaliTest[2910:5784526] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:54.791 ThaliTest[2910:5784526] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:31:54.792 ThaliTest[2910:5784526] client session: disconnect
2016-04-07 21:31:54.792 ThaliTest[2910:5784526] client session:, stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:54.792 ThaliTest[2910:5784526] client session: no connect callback (server initiated)
,2016-04-07 21:32:04.669 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-07 21:32:07.681 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:32:07.681 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:32:07.681 ThaliTest[2910:5781970] client session: reverseConn,ect
2016-04-07 21:32:07.682 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:32:07.878 ThaliTest[2910:5784600] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:07.878 ThaliTest[2910:5784600] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
,2016-04-07 21:32:07.878 ThaliTest[2910:5784600] client session: disconnect
2016-04-07 21:32:07.878 ThaliTest[2910:5784600] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:07.878 ThaliTest[2910:5784600] client session: no connect callback (server initiated)
,2016-04-07 21:32:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:32:09.613 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:09.614 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:32:09.614 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:32:17.682 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-07 21:32:20.689 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:32:20.689 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:32:20.689 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:32:20.689 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:32:20.904 ThaliTest[2910:5784598] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:20.904 ThaliTest[2910:5784598] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:32:20.904 ThaliTest[2910:5784598] client session: disconnect
,2016-04-07 21:32:20.905 ThaliTest[2910:5784598] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:20.905 ThaliTest[2910:5784598] client session: no connect callback (server initiated)
,2016-04-07 21:32:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:32:29.616 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:32:29.616 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:32:29.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:32:30.690 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 21:32:33.697 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:32:33.697 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:32:33.698 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:32:33.698 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:32:33.837 ThaliTest[2910:5784682] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:32:33.838 ThaliTest[2910:5784682] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:32:33.838 ThaliTest[2910:5784682] client session: disconnect
2016-04-07 21:32:33.838 ThaliTest[2910:5784682] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:33.838 ThaliTest[2910:5784682] client session: no connect callback (server initiated)
,2016-04-07 21:32:43.698 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-07 21:32:46.704 ThaliTest[2910:5781970] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:32:46.705 ThaliTest[2910:5781970] client: server will connect
2016-04-07 21:32:46.705 ThaliTest[2910:5781970] client session: reverseConnect
2016-04-07 21:32:46.705 ThaliTest[2910:5781970] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:32:47.112 ThaliTest[2910:5784686] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:47.112 ThaliTest[2910:5784686] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:32:47.112 ThaliTest[2910:5784686] client session: disconnect
2016-04-07 21:32:47.112 ThaliTest[2910:5784686] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:47.112 ThaliTest[2910:5784686] client session: no connect callb,ack (server initiated)
,2016-04-07 21:32:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:32:49.618 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:49.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:32:49.619 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:32:56.706 ThaliTest[2910:5781786] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
WARN testThaliMobileNative: Too many connect retries!
,2016-04-07 21:33:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:33:09.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:33:09.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:33:09.617 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:33:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:33:29.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:33:29.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:33:29.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:33:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:33:49.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:33:49.619 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:33:49.619 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:34:09.605 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:34:09.616 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:34:09.617 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:34:09.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:34:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:34:29.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:34:29.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:34:29.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:34:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:34:49.616 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:34:49.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:34:49.61,9 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:35:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:35:09.616 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:35:09.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:35:09.617 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:35:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:35:29.618 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:35:29.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:35:29.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:35:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:35:49.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:35:49.617 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:35:49.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:36:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:36:09.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:36:09.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:36:09.618 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:36:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:36:29.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:36:29.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:36:29.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:36:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:36:49.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:36:49.618 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:36:49.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:37:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:37:09.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:37:09.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:37:09.619 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:37:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:37:29.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:37:29.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:37:29.617 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:37:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:37:49.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:37:49.618 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:37:49.619 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:38:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:38:09.622 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:38:09.622 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:38:09.622 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:38:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:38:29.622 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:38:29.623 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:38:29.623 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:38:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:38:49.618 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:38:49.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:38:49.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:39:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:39:09.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:39:09.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:39:09.619 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:39:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:39:29.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:39:29.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:39:29.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:39:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:39:49.619 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:39:49.619 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:39:49.619 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:40:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:40:09.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:40:09.618 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:40:09.620 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:40:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:40:29.618 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:40:29.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:40:29.619 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:40:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:40:49.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:40:49.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:40:49.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:41:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:41:09.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:41:09.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:41:09.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:41:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:41:29.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:41:29.617 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:41:29.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:41:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:41:49.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:41:49.619 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:41:49.620 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:42:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:42:09.616 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:42:09.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:42:09.619 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:42:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:42:29.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:42:29.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:42:29.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:42:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:42:49.616 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:42:49.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:42:49.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:43:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:43:09.616 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:43:09.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:43:09.619 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:43:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:43:29.616 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:43:29.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:43:29.617 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:43:49.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:43:49.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:43:49.618 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:43:49.618 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:44:09.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:44:09.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:44:09.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:44:09.617 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:44:29.606 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:44:29.617 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:44:29.617 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:44:29.617 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:44:49.562 ThaliTest[2910:5781786] multipeer manager: restart client
,2016-04-07 21:44:49.573 ThaliTest[2910:5781786] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:44:49.573 ThaliTest[2910:5781786] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:44:49.574 ThaliTest[2910:5781786] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9

```
