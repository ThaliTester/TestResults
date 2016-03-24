#### Test 639107046ed3de5_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/12C51EAF-1412-4758-91CE-1415E5373BF2/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/12C51EAF-1412-4758-91CE-1415E5373BF2/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55672"
,(lldb)     command script import "/tmp/12C51EAF-1412-4758-91CE-1415E5373BF2/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 16:43:01.832 ThaliTest[1620:3914042] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5D9A77D5-23A7-4C92-B241-9982EDFB5B19/Library/Cookies/Cookies.binarycookies
,2016-03-24 16:43:02.182 ThaliTest[1620:3914042] Apache Cordova native platform version 4.1.0 is starting.
2016-03-24 16:43:02.184 ThaliTest[1620:3914042] Multi-tasking -> Device: YES, App: YES
,2016-03-24 16:43:02.199 ThaliTest[1620:3914042] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 16:43:03.357 ThaliTest[1620:3914042] Using UIWebView
2016-03-24 16:43:03.360 ThaliTest[1620:3914042] [CDVTimer][handleopenurl] 0.233948ms
,2016-03-24 16:43:03.366 ThaliTest[1620:3914042] [CDVTimer][intentandnavigationfilter] 5.010009ms
2016-03-24 16:43:03.366 ThaliTest[1620:3914042] [CDVTimer][gesturehandler] 0.227034ms
2016-03-24 16:43:03.366 ThaliTest[1620:3914042] [CDVTimer][TotalPluginStartup] 6.280005ms
,2016-03-24 16:43:08.245 ThaliTest[1620:3914042] Resetting plugins due to page load.
,2016-03-24 16:43:10.309 ThaliTest[1620:3914042] Finished load of: file:///var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/index.html
,2016-03-24 16:43:10.503 ThaliTest[1620:3914042] JXcore Cordova plugin initializing
2016-03-24 16:43:10.504 ThaliTest[1620:3914182] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-24 16:43:24.650 ThaliTest[1620:3914182] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 16:43:24.652 ThaliTest[1620:3914182] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:43:24.652 ThaliTest[1620:3914182] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {,"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 16:43:24.655 ThaliTest[1620:3914182] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7561ACC0-314F-41A7-9950-76CB8526A83C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52404
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52406
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52409
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
,# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52413
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
DEBUG createNativeListener: listening 52418
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52422
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
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
DEBUG createNativeListener: listening 52426
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52430
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 52434
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creat,ing incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
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
DEBUG createNativeListener: listening 52486
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 52490
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,# 14. multiplex can send data
,ok 47 String should be length:200
,# teardown
,# setup
,# 15. enqueue and run in order
,ok 48 firstPromise setTimeout
ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue
# teardown
,# setup
,# 16. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
ok 58 thirdPromise - in resolve
ok 59 secondPromise - second to run
ok 60 secondPromise - in catch
ok 61 firstPromise - third to run
ok 62 firstPromise - in then
ok 63 testing promises
# teardown
,# setup
,# 17. mix enqueue and enqueueAtTop
,ok 64 fourth
ok 65 fourth
ok 66 second
ok 67 secondPromise - in then
,ok 68 first
ok 69 firstPromise - in catch
ok 70 third
ok 71 thirdPromise - in then
ok 72 testingPromises
,# teardown
,# setup
,# 18. queues handled independently
,ok 73 all short operations completed before the long resolves
# teardown
,# setup
,# 19. basic
,ok 74 sane
# teardown
,# setup
,# 20. another
,ok 75 sane
# teardown
,# setup
,# 21. can pass data in setup
,ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
# teardown
,# setup
,# 22. #startListeningForAdvertisements should fail if start not called
,ok 82 specific error should be returned
# teardown
,ok 83 error should be null
ok 84 error should be null
# setup
,# 23. #startUpdateAdvertisingAndListening should fail if start not called
,ok 85 specific error should be returned
# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52502
,2016-03-24 16:45:54.596 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:54.597 ThaliTest[1620:39141,82] jxcore: stopListeningForAdvertisements: success
ok 88 error should be null
ok 89 error should be null
2016-03-24 16:45:54.601 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUp,dateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:54.601 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
# teardown
,2016-03-24 16:45:54.710 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:54.710 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:45:54.710 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:45:54.711 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:54.712 ThaliTest[1620,:3914182] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
ok 93 error should be null
# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52504
,2016-03-24 16:45:55.084 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements
,2016-03-24 16:45:55.086 ThaliTest[1620:3914182] multipeer manager: start client restart timer: 0x145cc470
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:45:55.087 Th,aliTest[1620:3914182] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
2016-03-24 16:45:55.100 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-24 16:45:55.101 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# teardown
,2016-03-24 16:45:55.919 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:55.919 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:45:55.919 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:45:55.920 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
2016-03-24 16:45:55.920 ThaliTest[1620:3914182] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:55.921 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 98 error should be null
ok 99 error should be null
# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52506
,2016-03-24 16:45:59.058 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:45:59.059 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:1
2016-03-24 16:45:59.059 ThaliTest[1620:3914182] multipeer m,anager: start client restart timer: 0x145cc470
2016-03-24 16:45:59.060 ThaliTest[1620:3914182] THEMultipeerManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:1
2016-03-24 16:45:59.060 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
2016-03-24 16:45:59.072 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:45:59.073 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:45:59.073 ThaliTest[1620:3914182] multipeer manager: stop client timer
2016-03-24 16:45:59.073 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:2
2016-03-24 16:45:59.074 ThaliTest[1620:3914182] multipeer manager: start client restart ,timer: 0x145cc470
2016-03-24 16:45:59.074 ThaliTest[1620:3914182] THEMultipeerManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:2
2016-03-24 16:45:59.074 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-24 16:45:59.104 ThaliTest[1620:3914042] client: found new peer: 5F451984-F7B7-4F39-B182-72023C9FD000:2
,ok 102 error should be null
ok 103 error should be null
# teardown
,2016-03-24 16:45:59.534 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:59.535 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:45:59.535 ThaliTest[1620:3914182] multipeer manager: stop client timer
20,16-03-24 16:45:59.535 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:45:59.536 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:59.536 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 104 error should be null
ok 105 error should be null
# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52511
,2016-03-24 16:46:00.223 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:00.223 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:46:00.224 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: suc,cess
ok 106 error should be null
ok 107 error should be null
2016-03-24 16:46:00.226 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:00.226 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:46:00.227 ,ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
ok 109 error should be null
# teardown
,2016-03-24 16:46:01.610 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:01.610 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:46:01.610 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:46:01.611 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:01.612 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52513
ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
# teardown
,2016-03-24 16:46:02.206 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:02.206 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:46:02.206 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:46:02.207 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:02.208 ThaliTest[1620,:3914182] jxcore: stopListeningForAdvertisements: success
ok 115 error should be null
ok 116 error should be null
# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52515
,2016-03-24 16:46:03.273 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements
2016-03-24 16:46:03.273 ThaliTest[1620:3914182] multipeer manager: start client restart timer: 0x145cc470
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:03.274 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements: success
,2016-03-24 16:46:03.314 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:46:03.315 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:3
2016-03-24 16:46:03.315 ThaliTest[1620:3914182] THEMultipee,rManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:3
2016-03-24 16:46:03.315 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
,ok 118 discovery state matches
ok 119 advertising state matches
# teardown
,2016-03-24 16:46:03.661 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:03.662 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:46:03.662 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:46:03.662 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
2016-03-24 16:46:03.663 ThaliTest[1620:3914182] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:03.664 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 120 error should be null
ok 121 error should be null
# setup
,# 30. does not send duplicate availability changes
,ok 122 should be called once
ok 123 should not have been called more than once
# teardown
,ok 124 error should be null
ok 125 error should be null
,# setup
,# 31. can get the network status
,ok 126 network status should have certain non-empty properties
# teardown
,ok 127 error should be null
ok 128 error should be null
# setup
,# 32. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 129 host address should match
ok 130 port should match
,ok 131 host address should be null
ok 132 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 133 error should be null
ok 134 error should be null
# setup
,# 33. Can call start/stopListeningForAdvertisements
,2016-03-24 16:46:33.819 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements
2016-03-24 16:46:33.820 ThaliTest[1620:3914182] multipeer manager: start client restart timer: 0x145cc470
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:33.821 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements: success
ok 135 Can call startListeningForAdvertisements without error
2016-03-24 16:46:33.822 ThaliTes,t[1620:3914182] jxcore: stopListeningForAdvertisements
2016-03-24 16:46:33.822 ThaliTest[1620:3914182] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-24 16:46:33.823 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
ok 136 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-24 16:46:33.937 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:33.938 ThaliTest[1620:39141,82] jxcore: stopListeningForAdvertisements: success
ok 137 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:46:33.939 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:33.939 ThaliTest[1620:391418,2] THEMultipeerManager stopping peer
2016-03-24 16:46:33.939 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 16:46:34.300 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements
2016-03-24 16:46:34.300 ThaliTest[1620:3914182] multipeer manager: start client restart timer: 0x145cc470
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:34.301 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-24 16:46:34.302 ThaliTes,t[1620:3914182] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:34.303 ThaliTest[1620:3914182] jxcore: startListeningForAdv,ertisements: success
ok 140 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 16:46:34.714 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
2016-03-24 16:46:34.714 ThaliTest[1620:3914182] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-24 16:46:34.715 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:46:34.716 ThaliTest[1620:39141,82] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:34.716 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:46:34.716 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 16:46:41.964 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:46:41.965 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:4
2016-03-24 16:46:41.965 ThaliTest[1620:3914182] multipeer m,anager: start client restart timer: 0x145cc470
2016-03-24 16:46:41.965 ThaliTest[1620:3914182] THEMultipeerManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:4
2016-03-24 16:46:41.965 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-24 16:46:41.967 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:41.967 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016,-03-24 16:46:41.967 ThaliTest[1620:3914182] multipeer manager: stop client timer
2016-03-24 16:46:41.967 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-24 16:47:29.737 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:47:29.738 ThaliTest[1620:39141,82] jxcore: stopListeningForAdvertisements: success
ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:47:29.739 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:47:29.739 ThaliTest[1620:391418,2] THEMultipeerManager stopping peer
2016-03-24 16:47:29.739 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-24 16:48:21.445 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:21.445 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:5
2016-03-24 16:48:21.446 ThaliTest[1620:3914182] multipeer m,anager: start client restart timer: 0x145cc470
2016-03-24 16:48:21.446 ThaliTest[1620:3914182] THEMultipeerManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:5
2016-03-24 16:48:21.446 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-24 16:48:21.447 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:21.448 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
,2016-03-24 16:48:21.448 ThaliTest[1620:3914182] multipeer manager: stop client timer
2016-03-24 16:48:21.454 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:6
2016-03-24 16:48:21.454 ThaliTest[1620:3914182] multipeer manager,: start client restart timer: 0x145cc470
2016-03-24 16:48:21.455 ThaliTest[1620:3914182] THEMultipeerManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:6
2016-03-24 16:48:21.455 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 148 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-24 16:48:21.719 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:48:21.720 ThaliTest[1620:391418,2] jxcore: stopListeningForAdvertisements: success
ok 149 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:48:21.721 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:48:21.721 ThaliTest[1620:3914182,] THEMultipeerManager stopping peer
2016-03-24 16:48:21.722 ThaliTest[1620:3914182] multipeer manager: stop client timer
2016-03-24 16:48:21.722 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. peerAvailabilityChange is called
,2016-03-24 16:48:22.249 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:22.249 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:22.250 ThaliTest[1620:3914182] multipeer m,anager: start client restart timer: 0x145cc470
2016-03-24 16:48:22.250 ThaliTest[1620:3914182] THEMultipeerManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:22.250 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-24 16:48:22.252 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-24 16:48:22.253 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements: success
ok 152 Can call startListeningForAdvertisements without error
,2016-03-24 16:48:23.197 ThaliTest[1620:3914042] client: found new peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
ok 153 peers must be an array
ok 154 peers must not be zero-length
ok 155 peer must have peerIdentifier
ok 156 peerIdentifier must be a string
ok 157 peer must have peerAvailable
ok 158 peer must have pleaseConnect
,# teardown
,2016-03-24 16:48:24.256 ThaliTest[1620:3914042] client: found new peer: 5F451984-F7B7-4F39-B182-72023C9FD000:2
,2016-03-24 16:48:38.999 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:48:39.000 ThaliTest[1620:391418,2] jxcore: stopListeningForAdvertisements: success
ok 159 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:48:39.001 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:48:39.001 ThaliTest[1620:3914182,] THEMultipeerManager stopping peer
2016-03-24 16:48:39.001 ThaliTest[1620:3914182] multipeer manager: stop client timer
2016-03-24 16:48:39.002 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 38. Can connect to a remote peer
,2016-03-24 16:48:39.733 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:39.733 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:48:39.734 ThaliTest[1620:3914182] multipeer m,anager: start client restart timer: 0x145cc470
2016-03-24 16:48:39.734 ThaliTest[1620:3914182] THEMultipeerManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:48:39.734 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 161 Can call startUpdateAdvertisingAndListening without error
2016-03-24 16:48:39.736 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-24 16:48:39.737 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-24 16:48:40.652 ThaliTest[1620:3914042] client: found new peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B8F5135C-E580-4A9F-90CD-0EB35830F,F0E:7","pleaseConnect":0}]
2016-03-24 16:48:40.654 ThaliTest[1620:3914182] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:48:40.654 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:48:40.654 ThaliTest[1620:3914182], client session: reverseConnect
2016-03-24 16:48:40.654 ThaliTest[1620:3914182] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:48:40.659 ThaliTest[1620:3914042] client: found new peer: 5F451984-F7B7-4F39-B182-72023C,9FD000:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5F451984-F7B7-4F39-B182-72023C9FD000:7","pleaseConnect":0}]
,2016-03-24 16:48:40.934 ThaliTest[1620:3914042] client: lost peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:48:40.934 ThaliTest[1620:3914042] client session: onPeerLost: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:48:40.934 ThaliTest[162,0:3914042] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:48:40.935 ThaliTest[1620:3914042] client session: disconnect
2016-03-24 16:48:40.935 ThaliTest[1620:3914042] client session: stateChange:1->0 B8F5135C-E580-4A9F-,90CD-0EB35830FF0E:7
2016-03-24 16:48:40.936 ThaliTest[1620:3914042] client session: no connect callback (server initiated)
,2016-03-24 16:48:41.961 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7","pleaseConnect":0}]
,2016-03-24 16:48:42.083 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:48:42.084 ThaliTest[1620:3914042] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (5AE71735-F944-4906-BE1F-E88A7,F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:48:42.137 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:48:42.139 ThaliTest[1620:3914042] server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:48:45.212 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:48:45.212 ThaliTest[1620:3914042] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:48:45.213 ThaliTest[1620:3914042], server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:48:45.472 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:48:45.472 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:48:45.472 ThaliTest[1620:3914042] server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:48:48.358 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:48:48.358 ThaliTest[1620:3914042] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:48:48.358 ThaliTest[1620:3914042], server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:48:49.185 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:48:49.185 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:48:49.186 ThaliTest[1620:3914042] server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:48:50.655 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-24 16:48:51.519 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:48:51.519 ThaliTest[1620:3914042] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:48:51.520 ThaliTest[1620:3914042] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:48:53.327 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:48:53.327 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:48:53.328 ThaliTest[1620:3914042] server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:48:53.658 ThaliTest[1620:3914182] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:48:53.658 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:48:53.659 ThaliTest[1620:3914182] client session: reverseConnect
2016-03-24 16:48:53.659 ThaliTest[1620:3914182] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
,2016-03-24 16:48:54.067 ThaliTest[1620:3914841] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:48:54.068 ThaliTest[1620:3914841] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:48:54.0,70 ThaliTest[1620:3914841] client session: disconnect
2016-03-24 16:48:54.070 ThaliTest[1620:3914841] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:48:54.071 ThaliTest[1620:3914841] client session: no connect callback (server initiated)
,2016-03-24 16:48:54.598 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:48:54.598 ThaliTest[1620:3914042] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:48:54.599 ThaliTest[1620:3914042], server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:48:57.740 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:48:57.741 ThaliTest[1620:3914042] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:48:57.741 ThaliTest[1620:3914042] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:48:59.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:48:59.759 ThaliTest[1620:3914042] client: found updated peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5F451984-F7B7-4F39-B182-72023,C9FD000:8","pleaseConnect":0}]
2016-03-24 16:48:59.761 ThaliTest[1620:3914042] client: found updated peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8","pleaseConnect":0}]
,2016-03-24 16:49:00.912 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:49:00.912 ThaliTest[1620:3914042] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:49:00.912 ThaliTest[1620:3914042] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:49:03.660 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-24 16:49:04.049 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:49:04.049 ThaliTest[1620:3914042] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:49:04.050 ThaliTest[1620:3914042], server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:49:06.671 ThaliTest[1620:3914182] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:06.671 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:49:06.672 ThaliTest[1620:3914182] client session: reverseConnect
2016-03-24 16:49:06.672 ThaliTest[1620:3914182] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:49:07.210 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:49:07.211 ThaliTest[1620:3914042] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:49:07.211 ThaliTest[1620:3914042] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:49:07.225 ThaliTest[1620:3914840] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:49:07.226 ThaliTest[1620:3914840] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:49:07.2,26 ThaliTest[1620:3914840] client session: disconnect
2016-03-24 16:49:07.226 ThaliTest[1620:3914840] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:49:07.227 ThaliTest[1620:3914840] client session: no connect callb,ack (server initiated)
,2016-03-24 16:49:10.314 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:49:10.315 ThaliTest[1620:3914042] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:49:10.315 ThaliTest[1620:3914042], server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:8 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7)
,2016-03-24 16:49:16.673 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-24 16:49:19.679 ThaliTest[1620:3914182] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:19.679 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:49:19.679 ThaliTest[1620:3914182] client session: reverseConnect
2016-03-24 16:49:19.680 ThaliTest[1620:3914182] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:49:19.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:49:19.756 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:49:19.759 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:49:29.680 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 6
,2016-03-24 16:49:32.690 ThaliTest[1620:3914182] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:32.691 ThaliTest[1620:3914182] client: already connect(ing/ed) to B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:32.691 ThaliTest[1620:3914182] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-24 16:49:35.697 ThaliTest[1620:3914182] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:35.697 ThaliTest[1620:3914182] client: already connect(ing/ed) to B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:35.697 Thali,Test[1620:3914182] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-24 16:49:38.704 ThaliTest[1620:3914182] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:38.704 ThaliTest[1620:3914182] client: already connect(ing/ed) to B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:38.704 Thali,Test[1620:3914182] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-24 16:49:39.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:49:39.757 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:49:39.758 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:49:41.714 ThaliTest[1620:3914182] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:41.715 ThaliTest[1620:3914182] client: already connect(ing/ed) to B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:41.715 Thali,Test[1620:3914182] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-24 16:49:44.729 ThaliTest[1620:3914182] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:44.729 ThaliTest[1620:3914182] client: already connect(ing/ed) to B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:44.729 Thali,Test[1620:3914182] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-24 16:49:47.735 ThaliTest[1620:3914182] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:47.735 ThaliTest[1620:3914182] client: already connect(ing/ed) to B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:49:47.735 Thali,Test[1620:3914182] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
not ok 163 Connect failed!
  ---
    operator: fail
  ...
# teardown
,2016-03-24 16:49:52.686 ThaliTest[1620:3915034] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:49:52.686 ThaliTest[1620:3915034] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:49:52.6,86 ThaliTest[1620:3915034] client session: disconnect
2016-03-24 16:49:52.686 ThaliTest[1620:3915034] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:49:52.690 ThaliTest[1620:3915034] client session: no connect callback (server initiated)
,2016-03-24 16:49:59.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:49:59.758 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:49:59.760 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:50:19.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:50:19.761 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:50:19.762 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:50:39.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:50:39.760 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:50:39.761 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:50:59.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:50:59.759 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:50:59.759 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:51:19.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:51:19.762 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:51:19.762 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:51:39.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:51:39.761 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:51:39.761 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:51:59.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:51:59.759 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:51:59.760 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:52:19.735 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:52:19.753 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:52:19.755 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:52:29.818 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:52:29.819 ThaliTest[1620:391418,2] jxcore: stopListeningForAdvertisements: success
ok 164 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:52:29.820 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:52:29.820 ThaliTest[1620:3914182,] THEMultipeerManager stopping peer
2016-03-24 16:52:29.821 ThaliTest[1620:3914182] multipeer manager: stop client timer
2016-03-24 16:52:29.821 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
ok 165 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can shift large amounts of data
,2016-03-24 16:52:30.786 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:52:30.786 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:52:30.786 ThaliTest[1620:3914182] multipeer manager: start client restart timer: 0x145cc470
,2016-03-24 16:52:30.786 ThaliTest[1620:3914182] THEMultipeerManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:52:30.795 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening: success
ok 166 Can call startUpdateAdv,ertisingAndListening without error
2016-03-24 16:52:30.797 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-2,4 16:52:30.798 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements: success
ok 167 Can call startListeningForAdvertisements without error
,2016-03-24 16:52:30.966 ThaliTest[1620:3914042] client: found new peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:52:30.968 ThaliTest[1620:3914182] jxcore: connect 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:52:30.969 ThaliTest[1620:3,914042] client: found new peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:52:30.968 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:52:30.969 ThaliTest[1620:3914182] client session: reverseConnect
2016-03-24 16:52:30.969 Tha,liTest[1620:3914182] client session: stateChange:0->1 5F451984-F7B7-4F39-B182-72023C9FD000:8
,2016-03-24 16:52:32.514 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:52:32.514 ThaliTest[1620:3914042] server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7,F36E6EE:9 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8)
,2016-03-24 16:52:33.106 ThaliTest[1620:3916202] client session: not connected 5F451984-F7B7-4F39-B182-72023C9FD000:8
,2016-03-24 16:52:33.107 ThaliTest[1620:3916202] client session: onLinkFailure: 5F451984-F7B7-4F39-B182-72023C9FD000
2016-03-24 16:52:33.108 ThaliTest[1620:3916202] client session: disconnect
2016-03-24 16:52:33.108 ThaliTest[1620:3916202] client session:, stateChange:1->0 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:52:33.108 ThaliTest[1620:3916202] client session: no connect callback (server initiated)
,2016-03-24 16:52:36.314 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:52:36.315 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:52:36.315 ThaliTest[1620:3914042] server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:9 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8)
,2016-03-24 16:52:39.452 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:52:39.452 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:52:39.453 ThaliTest[1620:3914042], server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:9 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8)
,2016-03-24 16:52:40.980 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-24 16:52:42.598 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:52:42.598 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:52:42.598 ThaliTest[1620:3914042], server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:9 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8)
,2016-03-24 16:52:43.989 ThaliTest[1620:3914182] jxcore: connect 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:52:43.990 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:52:43.990 ThaliTest[1620:3914182] client session: reverseConn,ect
2016-03-24 16:52:43.990 ThaliTest[1620:3914182] client session: stateChange:0->1 5F451984-F7B7-4F39-B182-72023C9FD000:8
,2016-03-24 16:52:44.225 ThaliTest[1620:3916202] client session: not connected 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:52:44.225 ThaliTest[1620:3916202] client session: onLinkFailure: 5F451984-F7B7-4F39-B182-72023C9FD000
,2016-03-24 16:52:44.225 ThaliTest[1620:3916202] client session: disconnect
2016-03-24 16:52:44.226 ThaliTest[1620:3916202] client session: stateChange:1->0 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:52:44.227 ThaliTest[1620:3916202] client session: no connect callback (server initiated)
,2016-03-24 16:52:45.698 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:52:45.699 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:52:45.699 ThaliTest[1620:3914042], server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:9 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8)
,2016-03-24 16:52:48.889 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:52:48.891 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:52:48.891 ThaliTest[1620:3914042], server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:9 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8)
,2016-03-24 16:52:50.788 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:52:50.813 ThaliTest[1620:3914042] client: found updated peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:52:50.813 ThaliTest[1620:3914042] client: found updated peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:52:51.985 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:52:51.986 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:52:51.986 ThaliTest[1620:3914042] server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:9 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8)
,2016-03-24 16:52:53.991 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-24 16:52:55.150 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:52:55.150 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:52:55.150 ThaliTest[1620:3914042], server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:9 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8)
,2016-03-24 16:52:56.998 ThaliTest[1620:3914182] jxcore: connect 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:52:56.998 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:52:56.998 ThaliTest[1620:3914182] client session: reverseConn,ect
2016-03-24 16:52:56.998 ThaliTest[1620:3914182] client session: stateChange:0->1 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:52:57.352 ThaliTest[1620:3916158] client session: not connected 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:52:57.354 ThaliTest[1620:3916158] client session: onLinkFailure: 5F451984-F7B7-4F39-B182-72023C9FD000
2016-03-24 16:52:57.3,54 ThaliTest[1620:3916158] client session: disconnect
2016-03-24 16:52:57.354 ThaliTest[1620:3916158] client session: stateChange:1->0 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:52:57.356 ThaliTest[1620:3916158] client session: no connect callb,ack (server initiated)
,2016-03-24 16:52:58.333 ThaliTest[1620:3914042] multipeer session: reset timer
2016-03-24 16:52:58.333 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:52:58.333 ThaliTest[1620:3914042] server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to previous generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:9 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8)
,2016-03-24 16:53:01.476 ThaliTest[1620:3914042] multipeer session: reset timer
,2016-03-24 16:53:01.477 ThaliTest[1620:3914042] server: disconnecting to refresh session (B8F5135C-E580-4A9F-90CD-0EB35830FF0E)
2016-03-24 16:53:01.477 ThaliTest[1620:3914042] server: rejecting invitation from B8F5135C-E580-4A9F-90CD-0EB35830FF0E due to p,revious generation (5AE71735-F944-4906-BE1F-E88A7F36E6EE:9 != 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8)
,2016-03-24 16:53:06.999 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-24 16:53:10.005 ThaliTest[1620:3914182] jxcore: connect 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:53:10.005 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:53:10.006 ThaliTest[1620:3914182] client session: reverseConnect
2016-03-24 16:53:10.006 ThaliTest[1620:3914182] client session: stateChange:0->1 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:53:10.578 ThaliTest[1620:3916284] client session: not connected 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:10.578 ThaliTest[1620:3916284] client session: onLinkFailure: 5F451984-F7B7-4F39-B182-72023C9FD000
2016-03-24 16:53:10.5,79 ThaliTest[1620:3916284] client session: disconnect
2016-03-24 16:53:10.579 ThaliTest[1620:3916284] client session: stateChange:1->0 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:10.580 ThaliTest[1620:3916284] client session: no connect callback (server initiated)
,2016-03-24 16:53:10.788 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:53:10.811 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:10.811 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:53:20.007 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 6
,2016-03-24 16:53:23.021 ThaliTest[1620:3914182] jxcore: connect 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:53:23.021 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:53:23.022 ThaliTest[1620:3914182] client session: reverseConnect
2016-03-24 16:53:23.022 ThaliTest[1620:3914182] client session: stateChange:0->1 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:53:23.696 ThaliTest[1620:3916376] client session: not connected 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:23.697 ThaliTest[1620:3916376] client session: onLinkFailure: 5F451984-F7B7-4F39-B182-72023C9FD000
2016-03-24 16:53:23.6,97 ThaliTest[1620:3916376] client session: disconnect
2016-03-24 16:53:23.698 ThaliTest[1620:3916376] client session: stateChange:1->0 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:23.698 ThaliTest[1620:3916376] client session: no connect callback (server initiated)
,2016-03-24 16:53:30.788 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:53:30.813 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:30.813 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:53:33.023 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-24 16:53:36.026 ThaliTest[1620:3914182] jxcore: connect 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:53:36.026 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:53:36.026 ThaliTest[1620:3914182] client session: reverseConnect
2016-03-24 16:53:36.026 ThaliTest[1620:3914182] client session: stateChange:0->1 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:53:36.725 ThaliTest[1620:3916376] client session: not connected 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:36.726 ThaliTest[1620:3916376] client session: onLinkFailure: 5F451984-F7B7-4F39-B182-72023C9FD000
2016-03-24 16:53:36.7,26 ThaliTest[1620:3916376] client session: disconnect
2016-03-24 16:53:36.727 ThaliTest[1620:3916376] client session: stateChange:1->0 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:36.728 ThaliTest[1620:3916376] client session: no connect callback (server initiated)
,2016-03-24 16:53:46.027 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-24 16:53:49.041 ThaliTest[1620:3914182] jxcore: connect 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:53:49.041 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:53:49.041 ThaliTest[1620:3914182] client session: reverseConn,ect
2016-03-24 16:53:49.041 ThaliTest[1620:3914182] client session: stateChange:0->1 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:53:49.303 ThaliTest[1620:3916376] client session: not connected 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:49.305 ThaliTest[1620:3916376] client session: onLinkFailure: 5F451984-F7B7-4F39-B182-72023C9FD000
2016-03-24 16:53:49.3,05 ThaliTest[1620:3916376] client session: disconnect
2016-03-24 16:53:49.305 ThaliTest[1620:3916376] client session: stateChange:1->0 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:49.306 ThaliTest[1620:3916376] client session: no connect callb,ack (server initiated)
,2016-03-24 16:53:50.788 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:53:50.815 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:53:50.816 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:53:59.042 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-24 16:54:02.046 ThaliTest[1620:3914182] jxcore: connect 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:54:02.046 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:54:02.046 ThaliTest[1620:3914182] client session: reverseConn,ect
2016-03-24 16:54:02.046 ThaliTest[1620:3914182] client session: stateChange:0->1 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:54:02.444 ThaliTest[1620:3916429] client session: not connected 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:54:02.444 ThaliTest[1620:3916429] client session: onLinkFailure: 5F451984-F7B7-4F39-B182-72023C9FD000
2016-03-24 16:54:02.4,44 ThaliTest[1620:3916429] client session: disconnect
2016-03-24 16:54:02.444 ThaliTest[1620:3916429] client session: stateChange:1->0 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:54:02.445 ThaliTest[1620:3916429] client session: no connect callback (server initiated)
,2016-03-24 16:54:10.788 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:54:10.813 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:54:10.813 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:54:12.047 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-24 16:54:15.054 ThaliTest[1620:3914182] jxcore: connect 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:54:15.054 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:54:15.055 ThaliTest[1620:3914182] client session: reverseConnect
2016-03-24 16:54:15.055 ThaliTest[1620:3914182] client session: stateChange:0->1 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:54:15.478 ThaliTest[1620:3916429] client session: not connected 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:54:15.479 ThaliTest[1620:3916429] client session: onLinkFailure: 5F451984-F7B7-4F39-B182-72023C9FD000
2016-03-24 16:54:15.4,79 ThaliTest[1620:3916429] client session: disconnect
2016-03-24 16:54:15.479 ThaliTest[1620:3916429] client session: stateChange:1->0 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:54:15.479 ThaliTest[1620:3916429] client session: no connect callback (server initiated)
,2016-03-24 16:54:25.055 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-24 16:54:28.060 ThaliTest[1620:3914182] jxcore: connect 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:54:28.061 ThaliTest[1620:3914182] client: server will connect
2016-03-24 16:54:28.061 ThaliTest[1620:3914182] client session: reverseConn,ect
2016-03-24 16:54:28.061 ThaliTest[1620:3914182] client session: stateChange:0->1 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:54:29.080 ThaliTest[1620:3916457] client session: not connected 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:54:29.081 ThaliTest[1620:3916457] client session: onLinkFailure: 5F451984-F7B7-4F39-B182-72023C9FD000
2016-03-24 16:54:29.0,81 ThaliTest[1620:3916457] client session: disconnect
2016-03-24 16:54:29.082 ThaliTest[1620:3916457] client session: stateChange:1->0 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:54:29.082 ThaliTest[1620:3916457] client session: no connect callback (server initiated)
,2016-03-24 16:54:30.788 ThaliTest[1620:3914042] multipeer manager: restart client
,2016-03-24 16:54:30.813 ThaliTest[1620:3914042] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:54:30.814 ThaliTest[1620:3914042] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:54:38.062 ThaliTest[1620:3914042] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
WARN testThaliMobileNative: Too many connect retries!
not ok 168 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-24 16:54:40.038 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-24 16:54:40.039 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
,ok 169 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:54:40.041 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
,2016-03-24 16:54:40.041 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
,2016-03-24 16:54:40.042 ThaliTest[1620:3914182] multipeer manager: stop client timer
2016-03-24 16:54:40.042 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: success
ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-24 16:54:40.223 ThaliTest[1620:3914182] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:40.224 ThaliTest[1620:3914182] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:40.224 ThaliTest[1620:3,914182] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 16:54:40.225 ThaliTest[1620:3914182] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 40. #startListeningForAdvertisements should fail if start not called
,ok 171 specific error should be returned
# teardown
,# setup
,2016-03-24 16:54:41.498 ThaliTest[1620:3914182] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:41.499 ThaliTest[1620:3914182] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:41.499 ThaliTest[1620:3,914182] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 16:54:41.500 ThaliTest[1620:3914182] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 172 specific error should be returned
# teardown
,# setup
,2016-03-24 16:54:42.425 ThaliTest[1620:3914182] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:42.426 ThaliTest[1620:3914182] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:42.426 ThaliTest[1620:3914182] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 16:54:42.428 ThaliTest[1620:3914182] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52550
,2016-03-24 16:54:43.926 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 16:54:43.928 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
,ok 173 no errors
,2016-03-24 16:54:43.930 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 16:54:43.931 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
,ok 174 still no errors
,# teardown
,2016-03-24 16:54:44.059 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:54:44.059 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:54:44.059 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:54:44.060 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:54:44.061 ThaliTest[1620,:3914182] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-24 16:54:46.665 ThaliTest[1620:3914182] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:46.665 ThaliTest[1620:3914182] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:46.666 ThaliTest[1620:3,914182] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:54:46.667 ThaliTest[1620:3914182] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52552
,2016-03-24 16:54:46.982 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements
,2016-03-24 16:54:46.984 ThaliTest[1620:3914182] multipeer manager: start client restart timer: 0x145cc470
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 16:54:46.989 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements: success
,ok 175 no errors
,2016-03-24 16:54:46.995 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 16:54:46.998 ThaliTest[1620:3914182] jxcore: startListeningForAdvertisements: success
,ok 176 still no errors
,# teardown
,2016-03-24 16:54:47.581 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening
2016-03-24 16:54:47.582 ThaliTest[1620:3914182] THEMultipeerManager stopping peer
2016-03-24 16:54:47.582 ThaliTest[1620:3914182] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:54:47.582 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements
2016-03-24 16:54:47.583 ThaliTest[1620:3914182] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 16:54:47.584 ThaliTest[1620:3914182] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-24 16:54:48.037 ThaliTest[1620:3914182] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:48.038 ThaliTest[1620:3914182] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:48.038 ThaliTest[1620:3,914182] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 16:54:48.039 ThaliTest[1620:3914182] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 44. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52554
2016-03-24 16:54:50.196 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:54:50.197 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:10
,2016-03-24 16:54:50.197 ThaliTest[1620:3914182] multipeer manager: start client restart timer: 0x145cc470
2016-03-24 16:54:50.200 ThaliTest[1620:3914182] THEMultipeerManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:10
2016-03-24 16:54:50.200, ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening: success
ok 177 no errors
2016-03-24 16:54:50.202 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:54:50.202 ThaliTest[1620:3914182] THEMultipeerManager ,stopping peer
2016-03-24 16:54:50.202 ThaliTest[1620:3914182] multipeer manager: stop client timer
2016-03-24 16:54:50.202 ThaliTest[1620:3914182] server: starting 5AE71735-F944-4906-BE1F-E88A7F36E6EE:11
2016-03-24 16:54:50.203 ThaliTest[1620:3914182] multipeer manager: start client restart timer: 0x145cc470
,2016-03-24 16:54:50.203 ThaliTest[1620:3914182] THEMultipeerManager initialized peer 5AE71735-F944-4906-BE1F-E88A7F36E6EE:11
2016-03-24 16:54:50.211 ThaliTest[1620:3914182] jxcore: startUpdateAdvertisingAndListening: success
ok 178 still no errors
# teardown
,* thread #1: tid = 0x3bb93a, 0x36f5bae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x91ade030)
  * frame #0: 0x36f5bae6 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x2508e91a CFNetwork`<redacted> + 18
    frame #2: 0x250da5a6 CFNetwork`CFNetServiceScheduleWithRunLoop + 34
    frame #3: 0x251798b8 CFNetwork`<redacted> + 100
    frame #4: 0x251794dc CFNetwork`<redacted> + 328
    frame #5: 0x2517bc1c CFNetwork`<redacted> + 784
    frame #6: 0x2517b32c CFNetwork`<redacted> + 36
    frame #7: 0x250d8df0 CFNetwork`<redacted> + 668
    frame #8: 0x37738bcc libsystem_dnssd.dylib`<redacted> + 128
    frame #9: 0x37737490 libsystem_dnssd.dylib`DNSServiceProcessResult + 528
    frame #10: 0x250d8798 CFNetwork`<redacted> + 20
    frame #11: 0x258544f6 CoreFoundation`<redacted> + 818
    frame #12: 0x258507c6 CoreFoundation`<redacted> + 14
    frame #13: 0x25850348 CoreFoundation`<redacted> + 344
    frame #14: 0x2584e71e CoreFoundation`<redacted> + 806
    frame #15: 0x257a10d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #16: 0x257a0ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #17: 0x2eb16af8 GraphicsServices`GSEventRunModal + 160
    frame #18: 0x29a2a2dc UIKit`UIApplicationMain + 144
    frame #19: 0x000ab572 ThaliTest`main + 50

```
