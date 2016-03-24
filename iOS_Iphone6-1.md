#### Test 640346198400100_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7B066F17-CE01-4088-90A9-075EDE66C9C3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7B066F17-CE01-4088-90A9-075EDE66C9C3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55552"
,(lldb)     command script import "/tmp/7B066F17-CE01-4088-90A9-075EDE66C9C3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 15:01:43.123 ThaliTest[2088:3648485] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E093F1A4-0C58-4C66-8A44-FC5DB53777A6/Library/Cookies/Cookies.binarycookies
,2016-03-24 15:01:43.355 ThaliTest[2088:3648485] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 15:01:43.356 ThaliTest[2088:3648485] Multi-tasking -> Device: YES, App: YES
,2016-03-24 15:01:43.371 ThaliTest[2088:3648485] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 15:01:44.158 ThaliTest[2088:3648485] Using UIWebView
2016-03-24 15:01:44.160 ThaliTest[2088:3648485] [CDVTimer][handleopenurl] 0.110984ms
,2016-03-24 15:01:44.163 ThaliTest[2088:3648485] [CDVTimer][intentandnavigationfilter] 3.213048ms
2016-03-24 15:01:44.164 ThaliTest[2088:3648485] [CDVTimer][gesturehandler] 0.109017ms
2016-03-24 15:01:44.164 ThaliTest[2088:3648485] [CDVTimer][TotalPluginStartup] 3.906012ms
,2016-03-24 15:01:47.273 ThaliTest[2088:3648485] Resetting plugins due to page load.
,2016-03-24 15:01:48.505 ThaliTest[2088:3648485] Finished load of: file:///var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/index.html
,2016-03-24 15:01:48.665 ThaliTest[2088:3648485] JXcore Cordova plugin initializing
,2016-03-24 15:01:48.667 ThaliTest[2088:3648676] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 15:01:55.713 ThaliTest[2088:3648676] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 15:01:55.715 ThaliTest[2088:3648676] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-24 15:01:55.715 ThaliTest[2088:3648676] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 15:01:55.718 ThaliTest[2088:3648676] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/64D33C61-DE34-425D-8704-1BE65B3124B6/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-24 15:02:01.312 ThaliTest[2088:3648485] THREAD WARNING: ['JXcore'] took '5293.948242' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51297
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51299
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
DEBUG createNativeListener: listening 51302
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51306
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
DEBUG createNativeListener: listening 51311
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
DEBUG createNativeListener: listening 51315
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
DEBUG createNativeListener: listening 51319
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51323
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 51327
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
DEBUG createNativeListener: creating incoming mux
D,EBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creati,ng incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNat,iveListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 51379
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
,ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51383
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: stream close:
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
ok 52 secondPromise result
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
# teardown
,# setup
,# 18. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
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
,# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51395
2016-03-24 15:04:19.315 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.315 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements: success
ok 88 error should be null
ok 89 error should be null
2016-03-24 15:04:19.317 ThaliTest[2088:3648676] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.317 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
# teardown
,2016-03-24 15:04:19.419 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:19.419 ThaliTest[2088:3648676] THEMultipeerManager stopping peer
2016-03-24 15:04:19.420 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:04:19.420 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.420 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51397
2016-03-24 15:04:19.593 ThaliTest[2088:3648676] jxcore: startListeningForAdvertisements
,2016-03-24 15:04:19.594 ThaliTest[2088:3648676] multipeer manager: start client restart timer: 0x17ef6550
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:04:19.595 Th,aliTest[2088:3648676] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
2016-03-24 15:04:19.600 ThaliTest[2088:3648676] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:04:19.601 ThaliTest[2088:3648676] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# teardown
,2016-03-24 15:04:19.870 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:19.870 ThaliTest[2088:3648676] THEMultipeerManager stopping peer
2016-03-24 15:04:19.870 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:04:19.870 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements
2016-03-24 15:04:19.870 ThaliTest[2088:3648676] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.871 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51399
,2016-03-24 15:04:20.378 ThaliTest[2088:3648676] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:04:20.378 ThaliTest[2088:3648676] server: starting 38F74798-916B-4172-8BBF-5B87280DA6DA:1
2016-03-24 15:04:20.378 ThaliTest[2088:3648676] multipeer manager: start client restart timer: 0x17ef6550
2016-03-24 15:04:20.379 ThaliTest[2088:3648676] THEMultipeerManager initialized peer 38F74798-916B-4172-8BBF-5B87280DA6DA:1
2016-03-24 15:04:20.379 ThaliTest[2088:3648676] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-24 15:04:20.386 ThaliTest[2088:3648676] jxcore: startUpdateAdvertisingAndListening
,2016-03-24 15:04:20.386 ThaliTest[2088:3648676] THEMultipeerManager stopping peer
,2016-03-24 15:04:20.387 ThaliTest[2088:3648676] multipeer manager: stop client timer
,2016-03-24 15:04:20.388 ThaliTest[2088:3648676] server: starting 38F74798-916B-4172-8BBF-5B87280DA6DA:2
,2016-03-24 15:04:20.390 ThaliTest[2088:3648676] multipeer manager: start client restart timer: 0x17ef6550
,2016-03-24 15:04:20.392 ThaliTest[2088:3648676] THEMultipeerManager initialized peer 38F74798-916B-4172-8BBF-5B87280DA6DA:2
,2016-03-24 15:04:20.394 ThaliTest[2088:3648676] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-24 15:04:20.510 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening
,2016-03-24 15:04:20.510 ThaliTest[2088:3648676] THEMultipeerManager stopping peer
2016-03-24 15:04:20.510 ThaliTest[2088:3648676] multipeer manager: stop client timer
2016-03-24 15:04:20.510 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:04:20.511 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:20.512 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51404
2016-03-24 15:04:44.139 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:44.139 ThaliTest[2088:3648676] THEMultipeerManager stoppi,ng peer
2016-03-24 15:04:44.139 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening: success
ok 106 error should be null
ok 107 error should be null
2016-03-24 15:04:44.140 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:44.141 ThaliTest[2088:3648676] THEMultipeerManager stopping peer
2016-03-24 15:04:44.141 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
,ok 109 error should be null
# teardown
,2016-03-24 15:04:44.313 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:44.313 ThaliTest[2088:3648676] THEMultipeerManager stopping peer
2016-03-24 15:04:44.313 ThaliTest[2088:3648676] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:04:44.313 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:44.313 ThaliTest[2088:3648676] jxcore: stopListeningForAdvertisements: success
ok 110 error should be null
ok 111 error should be null
# setup

```
