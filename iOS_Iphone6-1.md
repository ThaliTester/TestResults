#### Test 64423763d6e7601_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64423763d6e7601/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/43DAE501-2D58-4F4F-B0B8-88D90F9C3ED9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/43DAE501-2D58-4F4F-B0B8-88D90F9C3ED9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64423763d6e7601/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64423763d6e7601/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56253"
,(lldb)     command script import "/tmp/43DAE501-2D58-4F4F-B0B8-88D90F9C3ED9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-29 09:49:20.013 ThaliTest[2343:4352290] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/27133299-421C-44A6-B8C0-CD9F57F96A77/Library/Cookies/Cookies.binarycookies
,2016-03-29 09:49:20.251 ThaliTest[2343:4352290] Apache Cordova native platform version 4.1.0 is starting.
2016-03-29 09:49:20.252 ThaliTest[2343:4352290] Multi-tasking -> Device: YES, App: YES
,2016-03-29 09:49:20.267 ThaliTest[2343:4352290] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 09:49:21.044 ThaliTest[2343:4352290] Using UIWebView
,2016-03-29 09:49:21.047 ThaliTest[2343:4352290] [CDVTimer][handleopenurl] 0.113010ms
2016-03-29 09:49:21.049 ThaliTest[2343:4352290] [CDVTimer][intentandnavigationfilter] 2.161026ms
2016-03-29 09:49:21.049 ThaliTest[2343:4352290] [CDVTimer][gesturehandle,r] 0.104010ms
2016-03-29 09:49:21.049 ThaliTest[2343:4352290] [CDVTimer][TotalPluginStartup] 2.861977ms
,2016-03-29 09:49:24.182 ThaliTest[2343:4352290] Resetting plugins due to page load.
,2016-03-29 09:49:25.550 ThaliTest[2343:4352290] Finished load of: file:///var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/index.html
,2016-03-29 09:49:25.705 ThaliTest[2343:4352290] JXcore Cordova plugin initializing
,2016-03-29 09:49:25.706 ThaliTest[2343:4352455] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-29 09:49:32.783 ThaliTest[2343:4352455] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 09:49:32.783 ThaliTest[2343:4352455] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 09:49:32.784 ThaliTest[2343:4,352455] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 09:49:32.785 ThaliTest[2343:4352455] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE0AC16-6555-4A9A-B443-9DB7F935853F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53285
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53287
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53290
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53294
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
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
DEBUG createNativeListener: listening 53299
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 53303
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
DEBUG createNativeListener: listening 53307
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 53311
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
ok 26 The mux object should be closed
,ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53315
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 53367
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
DEBUG createNativeListener: listening 53371
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
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
,ok 50 firstPromise result
ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
ok 53 secondPromise result
ok 54 secondPromise testValue
ok 55 thirdPromise in promise
ok 56 thirdPromise result
ok 57 thirdPromise testValue
,# teardown
,# setup
,# 18. enqueueAtTop and run backwards
,ok 58 thirdPromise - first to run
ok 59 thirdPromise - in resolve
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
,ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises
# teardown
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
# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 83 specific error should be returned
# teardown
,ok 84 error should be null
ok 85 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 86 specific error should be returned
# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53383
2016-03-29 09:52:12.386 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:12.387 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements: success
,ok 89 error should be null
ok 90 error should be null
2016-03-29 09:52:12.389 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:12.389 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
# teardown
,2016-03-29 09:52:12.549 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening
2016-03-29 09:52:12.549 ThaliTest[2343:4352455] THEMultipeerManager stopping peer
2016-03-29 09:52:12.549 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening: success
2016-03-29 09:52:12.550 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:12.550 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53385
2016-03-29 09:52:13.688 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements
,2016-03-29 09:52:13.690 ThaliTest[2343:4352455] multipeer manager: start client restart timer: 0x156ded70
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:52:13.691 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-29 09:52:13.698 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:52:13.698 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
# teardown
,2016-03-29 09:52:13.705 ThaliTest[2343:4352290] client: found new peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= 0
,2016-03-29 09:52:33.690 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:52:33.697 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:52:36.402 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening
2016-03-29 09:52:36.402 ThaliTest[2343:4352455] THEMultipeerManager stopping peer
2016-03-29 09:52:36.402 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 09:52:36.402 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements
2016-03-29 09:52:36.403 ThaliTest[2343:4352455] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:36.403 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 99 error should be null
ok 100 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53388
2016-03-29 09:52:49.733 ThaliTest[2343:4352455] jxcore: startUpdateAdvertisingAndListening
2016-03-29 09:52:49.733 ThaliTest[2343:4352455] server: starting E64D9D09-7177-4B98-9A96-92B472CDF1BB:1
2016-03-29 09:52:49.734 ThaliTest[2343:4352455] multipeer manager: start client restart timer: 0x156ded70
2016-03-29 09:52:49.734 ThaliTest[2343:4352455] THEMultipeerManager initialized peer E64D9D09-7177-4B98-9A96-92,B472CDF1BB:1
2016-03-29 09:52:49.734 ThaliTest[2343:4352455] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
2016-03-29 09:52:49.740 ThaliTest[2343:4352455] jxcore: startUpdateAdvertisingAndListening
2016-03-29 09:52:49.741 ThaliTest[2343:4352455] THEMultipeerManager stopping peer
2016-03-29 09:52:49.741, ThaliTest[2343:4352455] multipeer manager: stop client timer
2016-03-29 09:52:49.741 ThaliTest[2343:4352455] server: starting E64D9D09-7177-4B98-9A96-92B472CDF1BB:2
2016-03-29 09:52:49.741 ThaliTest[2343:4352455] multipeer manager: start client restart timer: 0x156ded70
2016-03-29 09:52:49.741 ThaliTest[2343:4352455] THEMultipeerManager initialized peer E64D9D09-7177-4B98-9A96-92B472CDF1BB:2
2016-03-29 09:52:49.741 ThaliTest[2343:4352455] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
# teardown
,2016-03-29 09:52:50.710 ThaliTest[2343:4352290] client: found new peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:52:50.753 ThaliTest[2343:4352290] client: found new peer: 84638737-5933-4323-AFE3-F663D82D6EBD:2
,2016-03-29 09:52:52.169 ThaliTest[2343:4352290] client: found new peer: 460896FD-FFE8-4782-BFC9-7EDB16FF2A65:2
,2016-03-29 09:52:54.790 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening
2016-03-29 09:52:54.790 ThaliTest[2343:4352455] THEMultipeerManager stopping peer
2016-03-29 09:52:54.791 ThaliTest[2343:4352455] multipeer manager: stop client timer
20,16-03-29 09:52:54.791 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening: success
2016-03-29 09:52:54.791 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:54.791 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 105 error should be null
ok 106 error should be null
# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53393
2016-03-29 09:52:56.450 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening
2016-03-29 09:52:56.450 ThaliTest[2343:4352455] THEMultipeerManager stoppi,ng peer
2016-03-29 09:52:56.450 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
2016-03-29 09:52:56.452 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening
2016-03-29, 09:52:56.452 ThaliTest[2343:4352455] THEMultipeerManager stopping peer
2016-03-29 09:52:56.452 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
# teardown
,2016-03-29 09:52:58.836 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening
2016-03-29 09:52:58.836 ThaliTest[2343:4352455] THEMultipeerManager stopping peer
2016-03-29 09:52:58.836 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening: success
2016-03-29 09:52:58.836 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:58.837 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements: success
ok 111 error should be null
ok 112 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53395
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
# teardown
,2016-03-29 09:53:04.832 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening
2016-03-29 09:53:04.832 ThaliTest[2343:4352455] THEMultipeerManager stopping peer
2016-03-29 09:53:04.832 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening: success
2016-03-29 09:53:04.832 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:53:04.833 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements: success
,ok 116 error should be null
,ok 117 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53397
2016-03-29 09:53:05.355 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements
2016-03-29 09:53:05.355 ThaliTest[2343:4352455] multipeer manager: sta,rt client restart timer: 0x156ded70
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:53:05.355 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements: success
,2016-03-29 09:53:05.361 ThaliTest[2343:4352455] jxcore: startUpdateAdvertisingAndListening
2016-03-29 09:53:05.361 ThaliTest[2343:4352455] server: starting E64D9D09-7177-4B98-9A96-92B472CDF1BB:3
2016-03-29 09:53:05.361 ThaliTest[2343:4352455] THEMultipeerManager initialized peer E64D9D09-7177-4B98-9A96-92B472CDF1BB:3
2016-03-29 09:53:05.361 ThaliTest[2343:4352455] jxcore: startUpdateAdvertisingAndListening: success
ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
# teardown
,2016-03-29 09:53:05.500 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening
2016-03-29 09:53:05.500 ThaliTest[2343:4352455] THEMultipeerManager stopping peer
2016-03-29 09:53:05.500 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening: success
2016-03-29 09:53:05.500 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements
2016-03-29 09:53:05.500 ThaliTest[2343:4352455] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 09:53:05.501 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 121 error should be null
,ok 122 error should be null
,# setup
,# 32. does not send duplicate availability changes
,ok 123 should be called once
ok 124 should not have been called more than once
,# teardown
,ok 125 error should be null
ok 126 error should be null
,# setup
,# 33. can get the network status
,ok 127 network status should have certain non-empty properties
# teardown
,ok 128 error should be null
,ok 129 error should be null
,# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 130 host address should match
ok 131 port should match
,ok 132 host address should be null
ok 133 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-29 09:53:45.812 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements
2016-03-29 09:53:45.812 ThaliTest[2343:4352455] multipeer manager: start client restart timer: 0x156ded70
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:53:45.813 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-29 09:53:45.813 ThaliTes,t[2343:4352455] jxcore: stopListeningForAdvertisements
2016-03-29 09:53:45.813 ThaliTest[2343:4352455] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:53:45.814 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 09:53:46.051 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 09:53:46.052 ThaliTest[2343:4352455] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-29 09:53:46.053 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening
2016-03-29 09:53:46.053 ThaliTest[2343:4352455] THEMultipeerManager stopping peer
2016-03-29 09:53:46.053 ThaliTest[2343:4352455] jxcore: stopAdvertisingAndListening: suc,cess
ok 139 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-29 09:54:05.702 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements
2016-03-29 09:54:05.702 ThaliTest[2343:4352455] multipeer manager: start client restart timer: 0x156ded70
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:54:05.703 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-29 09:54:05.704 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:54:05.704 ThaliTest[2343:4352455] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-29 09:54:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:54:25.711 ThaliTest[2343:4352290] client: found new peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
,2016-03-29 09:54:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:54:45.709 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:55:05.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:55:05.712 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:55:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:55:25.709 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:55:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:55:45.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,Disconnected from the test server
,2016-03-29 09:56:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:56:05.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:56:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:56:25.717 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:56:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:56:45.711 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:57:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:57:05.709 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:57:25.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:57:25.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,Reconnected to the test server
,2016-03-29 09:57:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:57:45.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:58:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:58:05.711 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:58:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:58:25.709 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:58:45.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:58:45.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:59:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:59:05.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:59:25.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:59:25.707 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 09:59:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 09:59:45.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:00:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:00:05.711 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:00:25.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:00:25.717 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,Disconnected from the test server
,2016-03-29 10:00:45.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:00:45.709 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,Reconnected to the test server
,2016-03-29 10:01:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:01:05.711 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:01:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:01:25.711 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:01:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:01:45.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:02:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:02:05.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:02:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:02:25.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:02:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:02:45.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:03:05.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:03:05.711 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:03:25.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:03:25.709 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:03:45.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:03:45.712 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:04:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:04:05.710 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:04:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:04:25.716 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:04:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:05:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:05:05.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,Disconnected from the test server
,2016-03-29 10:05:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:05:25.718 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:05:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:05:45.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:06:05.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:06:05.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:06:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:06:25.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:06:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:06:45.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:07:05.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:07:05.719 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,Reconnected to the test server
,2016-03-29 10:07:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:07:25.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:07:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:07:45.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:08:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:08:05.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:08:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:08:25.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:08:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:09:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:09:05.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:09:25.703 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:09:25.707 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:09:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:09:45.709 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:10:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:10:05.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:10:25.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:10:25.707 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:10:45.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:10:45.709 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3
,2016-03-29 10:11:05.704 ThaliTest[2343:4352290] multipeer manager: restart client
,2016-03-29 10:11:05.708 ThaliTest[2343:4352290] client: found existing peer: BCC85FC3-1175-4CEC-B0D3-1FD81FA2DA38:3

```
