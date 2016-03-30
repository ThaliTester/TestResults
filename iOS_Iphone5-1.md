#### Test 646862831c69957_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646862831c69957/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/BA99304C-71AC-4D0E-AA5E-47E40A30923B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/BA99304C-71AC-4D0E-AA5E-47E40A30923B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/646862831c69957/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646862831c69957/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49421"
,(lldb)     command script import "/tmp/BA99304C-71AC-4D0E-AA5E-47E40A30923B/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-30 22:16:44.625 ThaliTest[1886:4835040] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/91249157-A8B9-4D7B-BB34-C4E8435C0F44/Library/Cookies/Cookies.binarycookies
,2016-03-30 22:16:44.735 ThaliTest[1886:4835040] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-30 22:16:44.737 ThaliTest[1886:4835040] Multi-tasking -> Device: YES, App: YES
,2016-03-30 22:16:44.759 ThaliTest[1886:4835040] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-30 22:16:45.935 ThaliTest[1886:4835040] Using UIWebView
2016-03-30 22:16:45.939 ThaliTest[1886:4835040] [CDVTimer][handleopenurl] 0.229001ms
,2016-03-30 22:16:45.945 ThaliTest[1886:4835040] [CDVTimer][intentandnavigationfilter] 5.592048ms
2016-03-30 22:16:45.945 ThaliTest[1886:4835040] [CDVTimer][gesturehandler] 0.230968ms
2016-03-30 22:16:45.945 ThaliTest[1886:4835040] [CDVTimer][TotalPluginStartup] 6.909013ms
,2016-03-30 22:16:50.953 ThaliTest[1886:4835040] Resetting plugins due to page load.
,2016-03-30 22:16:53.452 ThaliTest[1886:4835040] Finished load of: file:///var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/index.html
,2016-03-30 22:16:53.659 ThaliTest[1886:4835040] JXcore Cordova plugin initializing
2016-03-30 22:16:53.661 ThaliTest[1886:4835190] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-30 22:17:08.025 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:17:08.027 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:17:08.027 ThaliTest[1886:4,835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:17:08.030 ThaliTest[1886:4835190] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69CF3777-1AA4-44C2-ACFF-E3DFB1A3A275/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55331
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55333
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55336
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 55340
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55345
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
DEBUG createNativeListener: listening 55349
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55353
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
DEBUG createNativeListener: listening 55357
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 Th,e mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55361
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 55413
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
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55417
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
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
,ok 43 The mux object should be closed
,ok 44 The mux stream should be closed
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
# teardown
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
ok 50 firstPromise result
ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
ok 53 secondPromise result
ok 54 secondPromise testValue
ok 55 thirdPromise in promise
,ok 56 thirdPromise result
ok 57 thirdPromise testValue
# teardown
,# setup
,# 18. enqueueAtTop and run backwards
,ok 58 thirdPromise - first to run
,ok 59 thirdPromise - in resolve
ok 60 secondPromise - second to run
ok 61 secondPromise - in catch
ok 62 firstPromise - third to run
ok 63 firstPromise - in then
ok 64 testing promises
# teardown
,# setup
,# 19. mix enqueue and enqueueAtTop
,ok 65 fourth
ok 66 fourth
ok 67 second
ok 68 secondPromise - in then
,ok 69 first
ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises
,# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
,# teardown
,# setup
,# 21. basic
,ok 75 sane
# teardown
,# setup
,# 22. another
,ok 76 sane
# teardown
,# setup
,# 23. can pass data in setup
,ok 77 test participant has uuid
ok 78 participant data matches
ok 79 test participant has uuid
ok 80 participant data matches
ok 81 test participant has uuid
ok 82 participant data matches
ok 83 own UUID is found from the participants list
# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 84 specific error should be returned
# teardown
,ok 85 error should be null
,ok 86 error should be null
,# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 87 specific error should be returned
# teardown
,ok 88 error should be null
ok 89 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55429
,2016-03-30 22:19:45.383 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:45.386 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 e,rror should be null
2016-03-30 22:19:45.389 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:45.390, ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
# teardown
,2016-03-30 22:19:45.568 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:45.568 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:19:45.568 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:19:45.568 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:45.569 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55431
2016-03-30 22:19:45.933 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
,2016-03-30 22:19:45.935 ThaliTest[1886:4835190] multipeer manager: start client restart timer: 0x165b8920
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:19:45.937 Th,aliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
ok 97 error should be null
2016-03-30 22:19:45.948 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-30 22:19:45.949 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
ok 98 error should be null
ok 99 error should be null
# teardown
,2016-03-30 22:19:46.265 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:46.265 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:19:46.265 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:19:46.266 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
2016-03-30 22:19:46.266 ThaliTest[1886:4835190] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:46.267 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 100 error should be null
ok 101 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55433
,2016-03-30 22:19:46.932 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:19:46.933 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:1
2016-03-30 22:19:46.933 ThaliTest[1886:4835190] multipeer m,anager: start client restart timer: 0x165b8920
2016-03-30 22:19:46.934 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:1
2016-03-30 22:19:46.934 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
2016-03-30 22:19:46.947 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:19:46.947 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:19:46.947 ThaliTest[1886:4835190] multipeer manager: stop client timer
2016-03-30 22:19:46.948 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:2
2016-03-30 22:19:46.948 ThaliTest[1886:4835190] multipeer manager: start client restart ,timer: 0x165b8920
,2016-03-30 22:19:46.948 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:2
2016-03-30 22:19:46.954 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
,ok 105 error should be null
,# teardown
,2016-03-30 22:19:47.900 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:47.901 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:19:47.901 ThaliTest[1886:4835190] multipeer manager: stop client timer
20,16-03-30 22:19:47.901 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:19:47.902 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:47.903 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 106 error should be null
ok 107 error should be null
# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55438
2016-03-30 22:19:49.549 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:49.549 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:19:49.549 ThaliTest[1886:4835,190] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
ok 109 error should be null
2016-03-30 22:19:49.552 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:49.552 ThaliTest[1886:4835190] THEMultipeerMa,nager stopping peer
2016-03-30 22:19:49.552 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
ok 110 error should be null
ok 111 error should be null
# teardown
,2016-03-30 22:19:49.880 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:49.880 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:19:49.880 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:19:49.881 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:49.882 ThaliTest[1886,:4835190] jxcore: stopListeningForAdvertisements: success
,ok 112 error should be null
ok 113 error should be null
,# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55440
,ok 114 first call should succeed
ok 115 first call should succeed
ok 116 specific error should be returned
# teardown
,2016-03-30 22:19:50.446 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:50.447 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:19:50.447 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:19:50.447 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:50.448 ThaliTest[1886,:4835190] jxcore: stopListeningForAdvertisements: success
ok 117 error should be null
ok 118 error should be null
,# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55442
,2016-03-30 22:19:50.992 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
2016-03-30 22:19:50.993 ThaliTest[1886:4835190] multipeer manager: start client restart timer: 0x165b8920
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:19:50.994 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
,2016-03-30 22:19:51.008 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:19:51.009 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:3
2016-03-30 22:19:51.009 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:3
2016-03-30 22:19:51.009 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening: success
,ok 119 called only once
ok 120 discovery state matches
ok 121 advertising state matches
# teardown
,2016-03-30 22:19:51.599 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:51.599 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:19:51.600 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:19:51.600 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
2016-03-30 22:19:51.600 ThaliTest[1886:4835190] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:51.601 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 122 error should be null
,ok 123 error should be null
,# setup
,# 32. does not send duplicate availability changes
,ok 124 should be called once
ok 125 should not have been called more than once
# teardown
,ok 126 error should be null
ok 127 error should be null
# setup
,# 33. can get the network status
,ok 128 network status should have certain non-empty properties
# teardown
,ok 129 error should be null
ok 130 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 131 host address should match
ok 132 port should match
,ok 133 host address should be null
,ok 134 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 135 error should be null
ok 136 error should be null
,# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-30 22:20:16.577 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
2016-03-30 22:20:16.578 ThaliTest[1886:4835190] multipeer manager: start client restart timer: 0x165b8920
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:20:16.579 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
2016-03-30 22:20:16.580 ThaliTes,t[1886:4835190] jxcore: stopListeningForAdvertisements
2016-03-30 22:20:16.580 ThaliTest[1886:4835190] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-30 22:20:16.581 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
ok 138 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-30 22:20:16.789 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:20:16.790 ThaliTest[1886:48351,90] jxcore: stopListeningForAdvertisements: success
ok 139 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:16.791 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:16.791 ThaliTest[1886:483519,0] THEMultipeerManager stopping peer
2016-03-30 22:20:16.791 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-30 22:20:17.229 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
2016-03-30 22:20:17.229 ThaliTest[1886:4835190] multipeer manager: start client restart timer: 0x165b8920
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:20:17.231 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements without error
2016-03-30 22:20:17.232 ThaliTes,t[1886:4835190] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:20:17.233 ThaliTest[1886:4835190] jxcore: startListeningForAdv,ertisements: success
ok 142 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-30 22:20:17.363 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
2016-03-30 22:20:17.365 ThaliTest[1886:4835190] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:20:17.366 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
ok 143 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:17.367 ThaliTest[1886:48351,90] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:17.367 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:20:17.367 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdve,rtisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-30 22:20:18.493 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:18.494 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:4
2016-03-30 22:20:18.494 ThaliTest[1886:4835190] multipeer m,anager: start client restart timer: 0x165b8920
2016-03-30 22:20:18.494 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:4
2016-03-30 22:20:18.495 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening: success
ok 145 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:20:18.496 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:18.496 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
,2016-03-30 22:20:18.496 ThaliTest[1886:4835190] multipeer manager: stop client timer
2016-03-30 22:20:18.502 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
ok 146 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-30 22:20:18.682 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:20:18.683 ThaliTest[1886:48351,90] jxcore: stopListeningForAdvertisements: success
ok 147 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:18.684 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:18.684 ThaliTest[1886:483519,0] THEMultipeerManager stopping peer
2016-03-30 22:20:18.685 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-30 22:20:19.153 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:19.154 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:5
2016-03-30 22:20:19.154 ThaliTest[1886:4835190] multipeer manager: start client restart timer: 0x165b8920
2016-03-30 22:20:19.154 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:5
2016-03-30 22:20:19.154 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 149 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:20:19.156 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:19.156 ThaliTest[1886:4835190] THEMultipeerManager stopping pee,r
2016-03-30 22:20:19.156 ThaliTest[1886:4835190] multipeer manager: stop client timer
2016-03-30 22:20:19.157 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:6
2016-03-30 22:20:19.157 ThaliTest[1886:4835190] multipeer mana,ger: start client restart timer: 0x165b8920
2016-03-30 22:20:19.163 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:6
2016-03-30 22:20:19.163 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-30 22:20:19.321 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-30 22:20:19.322 ThaliTest[1886:483519,0] jxcore: stopListeningForAdvertisements: success
ok 151 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:19.323 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:19.324 ThaliTest[1886:4835190,] THEMultipeerManager stopping peer
2016-03-30 22:20:19.324 ThaliTest[1886:4835190] multipeer manager: stop client timer
2016-03-30 22:20:19.324 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-30 22:20:19.714 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:19.714 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:19.715 ThaliTest[1886:4835190] multipeer m,anager: start client restart timer: 0x165b8920
2016-03-30 22:20:19.715 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:19.715 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 153 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-30 22:20:19.717 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-30 22:20:19.719 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error
,2016-03-30 22:20:21.104 ThaliTest[1886:4835040] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:7
ok 155 peers must be an array
ok 156 peers must not be zero-length
ok 157 peer must have peerIdentifier
ok 158 peerIdentifier must be a string
ok 159 peer must have peerAvailable
ok 160 peer must have pleaseConnect
,# teardown
,2016-03-30 22:20:21.930 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-30 22:20:21.931 ThaliTest[1886:483519,0] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:21.932 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:21.932 ThaliTest[1886:4835190,] THEMultipeerManager stopping peer
2016-03-30 22:20:21.932 ThaliTest[1886:4835190] multipeer manager: stop client timer
2016-03-30 22:20:21.932 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. Can connect to a remote peer
,2016-03-30 22:20:22.687 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:22.687 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:20:22.687 ThaliTest[1886:4835190] multipeer m,anager: start client restart timer: 0x165b8920
2016-03-30 22:20:22.687 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:20:22.688 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 163 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:20:22.689 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-30 22:20:22.690 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-30 22:20:24.657 ThaliTest[1886:4835040] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"10864D2D-6C65-445D-AFFE-A77AB0B7C,823:8","pleaseConnect":0}]
2016-03-30 22:20:24.659 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:24.660 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:20:24.660 ThaliTest[1886:4835190], client session: reverseConnect
2016-03-30 22:20:24.660 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:20:24.771 ThaliTest[1886:4835040] client: found new peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"A3E18F7B-F512-41AB-86C7-5683F62667F5:8","pleaseConnect":0}]
,2016-03-30 22:20:24.852 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:20:24.853 ThaliTest[1886:4835040] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7)
2016-03-30 22:20:24.853 ThaliTest[1886:4835563] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:24.854 ThaliTest[1886:4835563] client session: onLinkFailure: 10864,D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:20:24.855 ThaliTest[1886:4835563] client session: disconnect
2016-03-30 22:20:24.855 ThaliTest[1886:4835563] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:24.855 ThaliTest[1886:4835563] client session: no connect callback (server initiated)
,2016-03-30 22:20:28.454 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:20:28.454 ThaliTest[1886:4835040] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:20:28.454 ThaliTest[1886:4835040] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7)
,2016-03-30 22:20:32.058 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:20:32.058 ThaliTest[1886:4835040] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:20:32.058 ThaliTest[1886:4835040], server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7)
,2016-03-30 22:20:34.661 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-30 22:20:35.786 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:20:35.786 ThaliTest[1886:4835040] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:20:35.786 ThaliTest[1886:4835040], server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7)
,2016-03-30 22:20:37.676 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:37.676 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:20:37.676 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:20:37.677 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:20:38.274 ThaliTest[1886:4835570] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:38.275 ThaliTest[1886:4835570] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:20:38.2,75 ThaliTest[1886:4835570] client session: disconnect
2016-03-30 22:20:38.275 ThaliTest[1886:4835570] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:38.277 ThaliTest[1886:4835570] client session: no connect callback (server initiated)
,2016-03-30 22:20:39.462 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:20:39.462 ThaliTest[1886:4835040] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:20:39.462 ThaliTest[1886:4835040], server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7)
,2016-03-30 22:20:42.688 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:20:42.704 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:20:42.705 ThaliTest[1886:4835040] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:20:43.209 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:20:43.210 ThaliTest[1886:4835040] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:20:43.210 ThaliTest[1886:4835040] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7)
,2016-03-30 22:20:46.909 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:20:46.909 ThaliTest[1886:4835040] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:20:46.909 ThaliTest[1886:4835040] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7)
,2016-03-30 22:20:47.678 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-30 22:20:50.682 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:50.682 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:20:50.682 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:20:50.682 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:20:51.453 ThaliTest[1886:4835563] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:51.454 ThaliTest[1886:4835563] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:20:51.4,54 ThaliTest[1886:4835563] client session: disconnect
2016-03-30 22:20:51.454 ThaliTest[1886:4835563] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:51.455 ThaliTest[1886:4835563] client session: no connect callback (server initiated)
,2016-03-30 22:20:51.518 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:20:51.519 ThaliTest[1886:4835040] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:20:51.519 ThaliTest[1886:4835040] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7)
,2016-03-30 22:20:55.183 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:20:55.184 ThaliTest[1886:4835040] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:20:55.184 ThaliTest[1886:4835040], server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7)
,2016-03-30 22:20:58.794 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:20:58.794 ThaliTest[1886:4835040] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:20:58.794 ThaliTest[1886:4835040] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7)
,2016-03-30 22:21:00.683 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-30 22:21:02.689 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:21:02.717 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:02.720 ThaliTest[1886:4835040] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:21:03.692 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:03.692 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:21:03.693 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:21:03.693 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:21:04.483 ThaliTest[1886:4835728] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:04.483 ThaliTest[1886:4835728] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:21:04.4,83 ThaliTest[1886:4835728] client session: disconnect
2016-03-30 22:21:04.484 ThaliTest[1886:4835728] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:04.484 ThaliTest[1886:4835728] client session: no connect callback (server initiated)
,2016-03-30 22:21:13.694 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-30 22:21:16.705 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:16.705 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:21:16.705 ThaliTest[1886:4835190] client session: reverseConn,ect
2016-03-30 22:21:16.706 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:21:18.500 ThaliTest[1886:4835753] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:18.501 ThaliTest[1886:4835753] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:21:18.5,02 ThaliTest[1886:4835753] client session: disconnect
2016-03-30 22:21:18.502 ThaliTest[1886:4835753] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:18.503 ThaliTest[1886:4835753] client session: no connect callback (server initiated)
,2016-03-30 22:21:22.688 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:21:22.705 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:21:22.709 ThaliTest[1886:4835040] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:21:26.706 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 5
,2016-03-30 22:21:29.715 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:29.715 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:21:29.716 ThaliTest[1886:4835190] client session: reverseConn,ect
2016-03-30 22:21:29.716 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:21:30.565 ThaliTest[1886:4835753] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:30.567 ThaliTest[1886:4835753] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:21:30.5,67 ThaliTest[1886:4835753] client session: disconnect
2016-03-30 22:21:30.567 ThaliTest[1886:4835753] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:30.568 ThaliTest[1886:4835753] client session: no connect callback (server initiated)
,2016-03-30 22:21:39.717 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-30 22:21:42.689 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:21:42.706 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:42.707 ThaliTest[1886:4835040] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:21:42.725 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:42.726 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:21:42.726 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:21:42.726 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:21:43.019 ThaliTest[1886:4835815] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:43.021 ThaliTest[1886:4835815] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:21:43.0,21 ThaliTest[1886:4835815] client session: disconnect
2016-03-30 22:21:43.021 ThaliTest[1886:4835815] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:43.022 ThaliTest[1886:4835815] client session: no connect callb,ack (server initiated)
,2016-03-30 22:21:52.727 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-30 22:21:55.736 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:55.737 ThaliTest[1886:4835190] client: server will connect
,2016-03-30 22:21:55.737 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:21:55.739 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:21:55.998 ThaliTest[1886:4835815] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:55.999 ThaliTest[1886:4835815] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:21:55.9,99 ThaliTest[1886:4835815] client session: disconnect
2016-03-30 22:21:55.999 ThaliTest[1886:4835815] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:21:56.000 ThaliTest[1886:4835815] client session: no connect callb,ack (server initiated)
,2016-03-30 22:22:02.689 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:22:02.707 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:02.710 ThaliTest[1886:4835040] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:22:05.738 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-30 22:22:08.751 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:08.751 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:22:08.751 ThaliTest[1886:4835190] client session: reverseConn,ect
2016-03-30 22:22:08.752 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:09.165 ThaliTest[1886:4835846] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:09.166 ThaliTest[1886:4835846] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:09.1,66 ThaliTest[1886:4835846] client session: disconnect
2016-03-30 22:22:09.166 ThaliTest[1886:4835846] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:09.168 ThaliTest[1886:4835846] client session: no connect callback (server initiated)
,2016-03-30 22:22:18.752 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-30 22:22:21.760 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:21.760 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:22:21.761 ThaliTest[1886:4835190] client session: reverseConn,ect
2016-03-30 22:22:21.761 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:22.258 ThaliTest[1886:4835895] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:22.260 ThaliTest[1886:4835895] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:22.2,60 ThaliTest[1886:4835895] client session: disconnect
2016-03-30 22:22:22.260 ThaliTest[1886:4835895] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:22.261 ThaliTest[1886:4835895] client session: no connect callback (server initiated)
,2016-03-30 22:22:22.689 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:22:22.714 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:22.716 ThaliTest[1886:4835040] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:22:31.762 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
WARN testThaliMobileNative: Too many connect retries!
not ok 165 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-03-30 22:22:32.621 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-30 22:22:32.622 ThaliTest[1886:483519,0] jxcore: stopListeningForAdvertisements: success
ok 166 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:22:32.624 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:22:32.624 ThaliTest[1886:4835190,] THEMultipeerManager stopping peer
2016-03-30 22:22:32.624 ThaliTest[1886:4835190] multipeer manager: stop client timer
2016-03-30 22:22:32.624 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
ok 167 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 41. Can shift large amounts of data
,2016-03-30 22:22:35.717 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:22:35.717 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9
2016-03-30 22:22:35.717 ThaliTest[1886:4835190] multipeer m,anager: start client restart timer: 0x165b8920
2016-03-30 22:22:35.718 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9
2016-03-30 22:22:35.718 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 168 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:22:35.719 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-30 22:22:35.720 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
ok 169 Can call startListeningForAdvertisements without error
,2016-03-30 22:22:35.750 ThaliTest[1886:4835040] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:35.750 ThaliTest[1886:4835040] client: found new peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:22:35.752 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:35.752 ThaliTest[1886:4835190] client: server will connect
,2016-03-30 22:22:35.752 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:22:35.758 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:37.987 ThaliTest[1886:4835916] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:37.987 ThaliTest[1886:4835916] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:37.989 ThaliTest[1886:4835916] client session: disconnect
2016-03-30 22:22:37.989 ThaliTest[1886:4835916] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:37.990 ThaliTest[1886:4835916] client session: no connect callback (server initiated)
,2016-03-30 22:22:38.634 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:22:38.634 ThaliTest[1886:4835040] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10D,E895F2C:9 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8)
,2016-03-30 22:22:42.595 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:22:42.595 ThaliTest[1886:4835040] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:22:42.595 ThaliTest[1886:4835040] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8)
,2016-03-30 22:22:45.753 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-30 22:22:46.467 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:22:46.467 ThaliTest[1886:4835040] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:22:46.467 ThaliTest[1886:4835040] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8)
,2016-03-30 22:22:48.759 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:48.760 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:22:48.760 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:22:48.760 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:49.000 ThaliTest[1886:4835956] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:49.002 ThaliTest[1886:4835956] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:49.0,02 ThaliTest[1886:4835956] client session: disconnect
2016-03-30 22:22:49.003 ThaliTest[1886:4835956] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:49.003 ThaliTest[1886:4835956] client session: no connect callback (server initiated)
,2016-03-30 22:22:50.474 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:22:50.474 ThaliTest[1886:4835040] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:22:50.475 ThaliTest[1886:4835040] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8)
,2016-03-30 22:22:54.324 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:22:54.325 ThaliTest[1886:4835040] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:22:54.325 ThaliTest[1886:4835040] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8)
,2016-03-30 22:22:55.719 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:22:55.749 ThaliTest[1886:4835040] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:22:55.751 ThaliTest[1886:4835040] client: found updated peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:22:58.424 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:22:58.424 ThaliTest[1886:4835040] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:22:58.425 ThaliTest[1886:4835040], server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8)
,2016-03-30 22:22:58.761 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-30 22:23:01.205 ThaliTest[1886:4835040] client: lost peer: A3E18F7B-F512-41AB-86C7-5683F62667F5
,2016-03-30 22:23:01.205 ThaliTest[1886:4835040] client session: onPeerLost: A3E18F7B-F512-41AB-86C7-5683F62667F5
,2016-03-30 22:23:01.770 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:23:01.770 ThaliTest[1886:4835190] client: server will connect
,2016-03-30 22:23:01.771 ThaliTest[1886:4835190] client session: reverseConnect
,2016-03-30 22:23:01.771 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:02.044 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:23:02.044 ThaliTest[1886:4835040] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:23:02.044 ThaliTest[1886:4835040], server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8)
,2016-03-30 22:23:02.103 ThaliTest[1886:4836000] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:23:02.103 ThaliTest[1886:4836000] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
,2016-03-30 22:23:02.103 ThaliTest[1886:4836000] client session: disconnect
2016-03-30 22:23:02.104 ThaliTest[1886:4836000] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:23:02.104 ThaliTest[1886:4836000] client session: no connect callback (server initiated)
,2016-03-30 22:23:05.658 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:23:05.659 ThaliTest[1886:4835040] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:23:05.659 ThaliTest[1886:4835040], server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8)
,2016-03-30 22:23:09.314 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:23:09.315 ThaliTest[1886:4835040] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:23:09.315 ThaliTest[1886:4835040] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8)
,2016-03-30 22:23:11.772 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-30 22:23:12.986 ThaliTest[1886:4835040] multipeer session: reset timer
2016-03-30 22:23:12.986 ThaliTest[1886:4835040] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:23:12.986 ThaliTest[1886:4835040], server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (0D4FB91C-5072-4219-BFC9-CC10DE895F2C:9 != 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8)
,2016-03-30 22:23:14.782 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:23:14.783 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:23:14.783 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:23:14.783 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:15.090 ThaliTest[1886:4835998] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:23:15.091 ThaliTest[1886:4835998] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:23:15.0,92 ThaliTest[1886:4835998] client session: disconnect
2016-03-30 22:23:15.092 ThaliTest[1886:4835998] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:23:15.095 ThaliTest[1886:4835998] client session: no connect callback (server initiated)
,2016-03-30 22:23:15.719 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:23:15.802 ThaliTest[1886:4835040] client: found updated peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:9
,2016-03-30 22:23:15.825 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:24.784 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-30 22:23:27.791 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:23:27.791 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:23:27.792 ThaliTest[1886:4835190] client session: reverseConn,ect
2016-03-30 22:23:27.792 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:28.255 ThaliTest[1886:4836188] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:23:28.256 ThaliTest[1886:4836188] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:23:28.256 ThaliTest[1886:4836188] client session: disconnect
2016-03-30 22:23:28.256 ThaliTest[1886:4836188] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:28.258 ThaliTest[1886:4836188] client session: no connect callback (server initiated)
,2016-03-30 22:23:35.719 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:23:35.737 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:35.741 ThaliTest[1886:4835040] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:9
,2016-03-30 22:23:37.793 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-30 22:23:40.805 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:23:40.805 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:23:40.805 ThaliTest[1886:4835190] client session: reverseConn,ect
2016-03-30 22:23:40.805 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:41.475 ThaliTest[1886:4836224] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:41.476 ThaliTest[1886:4836224] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:23:41.477 ThaliTest[1886:4836224] client session: disconnect
2016-03-30 22:23:41.477 ThaliTest[1886:4836224] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:23:41.478 ThaliTest[1886:4836224] client session: no connect callback (server initiated)
,2016-03-30 22:23:50.806 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-30 22:23:53.811 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:23:53.811 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:23:53.811 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:23:53.812 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:54.003 ThaliTest[1886:4836244] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:23:54.005 ThaliTest[1886:4836244] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
,2016-03-30 22:23:54.005 ThaliTest[1886:4836244] client session: disconnect
2016-03-30 22:23:54.005 ThaliTest[1886:4836244] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:54.006 ThaliTest[1886:4836244] client session: no connect callback (server initiated)
,2016-03-30 22:23:55.719 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:23:55.750 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:23:55.752 ThaliTest[1886:4835040] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:9
,2016-03-30 22:24:03.813 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-30 22:24:06.817 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:24:06.817 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:24:06.817 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:24:06.818 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:24:07.625 ThaliTest[1886:4836291] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:24:07.627 ThaliTest[1886:4836291] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:24:07.6,27 ThaliTest[1886:4836291] client session: disconnect
2016-03-30 22:24:07.627 ThaliTest[1886:4836291] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:24:07.628 ThaliTest[1886:4836291] client session: no connect callback (server initiated)
,2016-03-30 22:24:15.719 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:24:15.747 ThaliTest[1886:4835040] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:9
2016-03-30 22:24:15.747 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:24:16.819 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-30 22:24:19.821 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:24:19.821 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:24:19.822 ThaliTest[1886:4835190] client session: reverseConn,ect
2016-03-30 22:24:19.822 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:24:20.272 ThaliTest[1886:4836309] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:24:20.272 ThaliTest[1886:4836309] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:24:20.272 ThaliTest[1886:4836309] client session: disconnect
2016-03-30 22:24:20.272 ThaliTest[1886:4836309] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:24:20.274 ThaliTest[1886:4836309] client session: no connect callback (server initiated)
,2016-03-30 22:24:29.823 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-30 22:24:32.836 ThaliTest[1886:4835190] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:24:32.836 ThaliTest[1886:4835190] client: server will connect
2016-03-30 22:24:32.837 ThaliTest[1886:4835190] client session: reverseConnect
2016-03-30 22:24:32.837 ThaliTest[1886:4835190] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:24:33.840 ThaliTest[1886:4836352] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:24:33.841 ThaliTest[1886:4836352] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:24:33.841 ThaliTest[1886:4836352] client session: disconnect
2016-03-30 22:24:33.841 ThaliTest[1886:4836352] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:24:33.842 ThaliTest[1886:4836352] client session: no connect callback (server initiated)
,2016-03-30 22:24:35.719 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:24:42.837 ThaliTest[1886:4835040] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 170 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-30 22:24:45.116 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-30 22:24:45.117 ThaliTest[1886:483519,0] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:24:45.118 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:24:45.119 ThaliTest[1886:4835190,] THEMultipeerManager stopping peer
2016-03-30 22:24:45.119 ThaliTest[1886:4835190] multipeer manager: stop client timer
2016-03-30 22:24:45.119 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,2016-03-30 22:24:57.198 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:24:57.199 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:24:57.199 ThaliTest[1886:4,835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:24:57.201 ThaliTest[1886:4835190] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 173 specific error should be returned
# teardown
,ok 174 must be stopped
# setup
,2016-03-30 22:25:04.485 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:04.486 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:04.486 ThaliTest[1886:4,835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:25:04.488 ThaliTest[1886:4835190] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 175 specific error should be returned
,# teardown
,ok 176 must be stopped
,# setup
,2016-03-30 22:25:24.125 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:24.126 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:24.126 ThaliTest[1886:4,835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:25:24.127 ThaliTest[1886:4835190] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55478
,2016-03-30 22:25:25.559 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:25.560 ThaliTest[1886:48351,90] jxcore: stopListeningForAdvertisements: success
ok 177 no errors
2016-03-30 22:25:25.561 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,,"discoveryActive":false}
2016-03-30 22:25:25.562 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
ok 178 still no errors
# teardown
,2016-03-30 22:25:25.751 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:25.751 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:25:25.751 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:25:25.751 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:25.752 ThaliTest[1886,:4835190] jxcore: stopListeningForAdvertisements: success
ok 179 must be stopped
# setup
,2016-03-30 22:25:26.055 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:26.056 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-30 22:25:26.056 ThaliTest[1886:4835190] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:25:26.059 ThaliTest[1886:4835190] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55480
,2016-03-30 22:25:26.389 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
2016-03-30 22:25:26.389 ThaliTest[1886:4835190] multipeer manager: start client restart timer: 0x165b8920
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:25:26.390 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
ok 180 no errors
,2016-03-30 22:25:26.395 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:25:26.398 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
ok 181 still no errors
,# teardown
,2016-03-30 22:25:26.707 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:26.708 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:25:26.708 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:25:26.708 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
2016-03-30 22:25:26.708 ThaliTest[1886:4835190] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:26.709 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
ok 182 must be stopped
# setup
,2016-03-30 22:25:27.176 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:27.176 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:27.177 ThaliTest[1886:4,835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:25:27.178 ThaliTest[1886:4835190] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55482
2016-03-30 22:25:28.337 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:25:28.338 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:10
2016-03-30 22,:25:28.338 ThaliTest[1886:4835190] multipeer manager: start client restart timer: 0x165b8920
2016-03-30 22:25:28.338 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:10
2016-03-30 22:25:28.338 ThaliTest[18,86:4835190] jxcore: startUpdateAdvertisingAndListening: success
ok 183 no errors
2016-03-30 22:25:28.340 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:25:28.340 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
,2016-03-30 22:25:28.340 ThaliTest[1886:4835190] multipeer manager: stop client timer
2016-03-30 22:25:28.347 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:11
2016-03-30 22:25:28.348 ThaliTest[1886:4835190] multipeer manage,r: start client restart timer: 0x165b8920
2016-03-30 22:25:28.348 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:11
2016-03-30 22:25:28.348 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening: success
ok 184 still no errors
# teardown
,2016-03-30 22:25:28.968 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:28.968 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:25:28.968 ThaliTest[1886:4835190] multipeer manager: stop client timer
20,16-03-30 22:25:28.968 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:25:28.969 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:28.970 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
ok 185 must be stopped
# setup
,2016-03-30 22:25:29.712 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:29.713 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:29.713 ThaliTest[1886:4835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:25:29.715 ThaliTest[1886:4835190] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,# 47. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55486
,2016-03-30 22:25:30.033 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:30.033 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:25:30.033 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: suc,cess
ok 186 no errors
2016-03-30 22:25:30.036 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:30.036 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:25:30.036 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
ok 187 still no errors
# teardown
,2016-03-30 22:25:30.801 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:30.801 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:25:30.801 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:25:30.802 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:30.803 ThaliTest[1886,:4835190] jxcore: stopListeningForAdvertisements: success
ok 188 must be stopped
# setup
,2016-03-30 22:25:31.368 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:31.369 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:31.369 ThaliTest[1886:4,835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:25:31.370 ThaliTest[1886:4835190] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 48. can get the network status before starting
,ok 189 network status should have certain non-empty properties
# teardown
,ok 190 must be stopped
,# setup
,2016-03-30 22:26:01.689 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:01.690 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:01.690 ThaliTest[1886:4,835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:26:01.692 ThaliTest[1886:4835190] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 49. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 191 specific error expected
,# teardown
,ok 192 must be stopped
,# setup
,2016-03-30 22:26:08.559 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:08.560 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:08.560 ThaliTest[1886:4,835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:08.562 ThaliTest[1886:4835190] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 50. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55488
,2016-03-30 22:26:08.944 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
2016-03-30 22:26:08.945 ThaliTest[1886:4835190] multipeer manager: start client restart timer: 0x165b8920
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:26:08.946 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
2016-03-30 22:26:08.947 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
201,6-03-30 22:26:08.947 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:12
2016-03-30 22:26:08.947 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:12
2016-03-30 22:26:08.947 Tha,liTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 193 connection to servers manager should succeed after starting
,ok 194 connection to router server should succeed after starting
,2016-03-30 22:26:08.996 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
,2016-03-30 22:26:08.996 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
,2016-03-30 22:26:08.998 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
,2016-03-30 22:26:09.000 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
,2016-03-30 22:26:09.003 ThaliTest[1886:4835190] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:26:09.006 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 195 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 196 connection to servers manager should fail after stopping
,ok 197 connection to router server should fail after stopping
,# teardown
,ok 198 must be stopped
# setup
,2016-03-30 22:26:09.848 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:09.849 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:09.849 ThaliTest[1886:4835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:26:09.850 ThaliTest[1886:4835190] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 51. make sure terminateConnection is properly hooked up
,ok 199 called with right arguments
,# teardown
,ok 200 must be stopped
,# setup
,2016-03-30 22:26:14.941 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:14.942 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:14.942 ThaliTest[1886:4835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:26:14.943 ThaliTest[1886:4835190] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 52. make sure terminateListener is properly hooked up
,ok 201 called with right arguments
# teardown
,ok 202 must be stopped
# setup
,2016-03-30 22:26:25.140 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:25.141 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:25.141 ThaliTest[1886:4,835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:26:25.142 ThaliTest[1886:4835190] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 53. make sure we actually call kill connections properly
,2016-03-30 22:26:25.250 ThaliTest[1886:4835190] jxcore: killConnections
2016-03-30 22:26:25.251 ThaliTest[1886:4835190] jxcore: killConnections: badParam
not ok 203 should not fail on iOS
  ---
    operator: fail
  ...
# teardown
,ok 204 must be stopped
,# setup
,2016-03-30 22:26:25.535 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-30 22:26:25.537 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-30 22:26:25.538 ThaliTest[1886:4835190] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:25.540 ThaliTest[1886:4835190] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55495
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":55494,"error":{}}
2016-03-30 22:26:25.669 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:26:25.670 ThaliTest[1886:4835190] THEMultipeerManager stopping p,eer
2016-03-30 22:26:25.670 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:26:25.670 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP,: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:26:25.671 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
,ok 205 failure reason is as expected
ok 206 error description is as expected
ok 207 must be stopped
# teardown
,ok 208 must be stopped
# setup
,2016-03-30 22:26:25.885 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:25.886 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:25.886 ThaliTest[1886:4835190] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:26:25.887 ThaliTest[1886:4835190] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 55. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55497
ok 209 peerIdentifier matches
ok 210 error description matches
,# teardown
,2016-03-30 22:26:26.325 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
2016-03-30 22:26:26.326 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
2016-03-30 22:26:26.326 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:26:26.327 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:26:26.328 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
ok 211 must be stopped
# setup
,2016-03-30 22:26:26.518 ThaliTest[1886:4835190] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-30 22:26:26.519 ThaliTest[1886:4835190] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-30 22:26:26.520 ThaliTest[1886:4835190] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:26.522 ThaliTest[1886:4835190] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 56. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55499
,2016-03-30 22:26:26.768 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements
,2016-03-30 22:26:26.770 ThaliTest[1886:4835190] multipeer manager: start client restart timer: 0x165b8920
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,ok 212 discoveryActive matches
,ok 213 advertisingActive matches
,2016-03-30 22:26:26.780 ThaliTest[1886:4835190] jxcore: startListeningForAdvertisements: success
,2016-03-30 22:26:26.781 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening
,2016-03-30 22:26:26.783 ThaliTest[1886:4835190] THEMultipeerManager stopping peer
,2016-03-30 22:26:26.783 ThaliTest[1886:4835190] jxcore: stopAdvertisingAndListening: success
,2016-03-30 22:26:26.785 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements
,2016-03-30 22:26:26.788 ThaliTest[1886:4835190] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,ok 214 discoveryActive matches
,ok 215 advertisingActive matches
,2016-03-30 22:26:26.792 ThaliTest[1886:4835190] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55501
,2016-03-30 22:26:26.805 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening
,2016-03-30 22:26:26.806 ThaliTest[1886:4835190] server: starting 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:26:26.810 ThaliTest[1886:4835190] multipeer manager: start client restart timer: 0x165b8920
,2016-03-30 22:26:26.813 ThaliTest[1886:4835190] THEMultipeerManager initialized peer 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:26:26.816 ThaliTest[1886:4835190] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-30 22:26:27.968 ThaliTest[1886:4835040] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:26:46.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:26:46.835 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:27:06.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:27:06.826 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:27:26.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:27:26.832 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:27:46.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:27:46.828 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:28:06.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:28:06.832 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:28:26.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:28:26.830 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:28:46.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:28:46.832 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:29:06.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:29:06.826 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:29:26.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:29:26.833 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:29:46.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:29:46.832 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:30:06.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:30:06.832 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:30:26.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:30:26.831 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:30:46.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:30:46.827 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:31:06.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:31:06.834 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:31:26.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:31:26.831 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:31:46.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:31:46.834 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:32:06.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:32:06.835 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:32:26.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:32:26.827 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:32:46.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:32:46.831 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:33:06.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:33:06.835 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:33:26.813 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:33:26.831 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:33:46.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:34:06.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:34:06.824 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:34:26.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:34:26.824 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:34:46.814 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:34:46.823 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:35:06.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:35:06.770 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:35:26.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:35:26.768 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:35:46.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:35:46.767 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:36:06.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:36:06.765 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:36:26.755 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:36:26.763 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:36:46.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:36:46.765 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:37:06.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:37:06.764 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:37:26.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:37:26.767 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:37:46.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:37:46.764 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:38:06.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:38:06.765 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:38:26.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:38:26.767 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:38:46.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:38:46.765 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
,2016-03-30 22:39:06.756 ThaliTest[1886:4835040] multipeer manager: restart client
,2016-03-30 22:39:06.764 ThaliTest[1886:4835040] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13

```
