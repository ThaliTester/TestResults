#### Test 639808779d5bfaa_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639808779d5bfaa/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/FF86637D-C024-4C29-BAC2-5DD95A23D7BF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/FF86637D-C024-4C29-BAC2-5DD95A23D7BF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639808779d5bfaa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639808779d5bfaa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56330"
,(lldb)     command script import "/tmp/FF86637D-C024-4C29-BAC2-5DD95A23D7BF/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-29 11:04:22.220 ThaliTest[1804:4613182] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CAA6CBF9-83DE-4512-89B3-A97A3CAEDAB9/Library/Cookies/Cookies.binarycookies
,2016-03-29 11:04:22.320 ThaliTest[1804:4613182] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-29 11:04:22.322 ThaliTest[1804:4613182] Multi-tasking -> Device: YES, App: YES
,2016-03-29 11:04:22.341 ThaliTest[1804:4613182] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 11:04:23.522 ThaliTest[1804:4613182] Using UIWebView
,2016-03-29 11:04:23.527 ThaliTest[1804:4613182] [CDVTimer][handleopenurl] 0.259995ms
2016-03-29 11:04:23.532 ThaliTest[1804:4613182] [CDVTimer][intentandnavigationfilter] 4.289985ms
2016-03-29 11:04:23.532 ThaliTest[1804:4613182] [CDVTimer][gesturehandle,r] 0.190973ms
2016-03-29 11:04:23.532 ThaliTest[1804:4613182] [CDVTimer][TotalPluginStartup] 5.908966ms
,2016-03-29 11:04:28.438 ThaliTest[1804:4613182] Resetting plugins due to page load.
,2016-03-29 11:04:30.840 ThaliTest[1804:4613182] Finished load of: file:///var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/index.html
,2016-03-29 11:04:31.040 ThaliTest[1804:4613182] JXcore Cordova plugin initializing
2016-03-29 11:04:31.045 ThaliTest[1804:4613328] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-29 11:04:45.100 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-29 11:04:45.102 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:04:45.102 ThaliTest[1804:4613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {,"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:04:45.105 ThaliTest[1804:4613328] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8397C19B-5FCF-4480-9026-B53486A59A5B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54295
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54297
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
DEBUG createNativeListener: listening 54300
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 54304
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
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54309
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54313
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 54317
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 54321
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,ok 22 native server is nulled out
,ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54325
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
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
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
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
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
DEBUG createNativeListener: listening 54377
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
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
DEBUG createNativeListener: listening 54381
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
ok 56 thirdPromise result
ok 57 thirdPromise testValue
# teardown
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
ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises
# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
# teardown
,# setup
,# 21. basic
,ok 75 sane
,# teardown
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
,ok 81 test participant has uuid
,ok 82 participant data matches
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
,# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54393
,2016-03-29 11:07:29.498 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:07:29.501 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,ok 89 error should be null
,ok 90 error should be null
,2016-03-29 11:07:29.504 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:07:29.507 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,# teardown
,2016-03-29 11:07:29.703 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:07:29.703 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:07:29.703 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:07:29.704 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:29.705 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
,ok 94 error should be null
,# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54395
2016-03-29 11:07:29.931 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
,2016-03-29 11:07:29.933 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:07:29.934 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-29 11:07:29.945 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-29 11:07:29.947 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
# teardown
,2016-03-29 11:07:30.718 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:07:30.719 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:07:30.719 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:07:30.719 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
2016-03-29 11:07:30.719 ThaliTest[1804:4613328] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:30.720 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 99 error should be null
ok 100 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54397
,2016-03-29 11:07:37.584 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:07:37.584 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:1
2016-03-29 11:07:37.585 ThaliTest[1804:4613328] multipeer m,anager: start client restart timer: 0x14e85e90
2016-03-29 11:07:37.585 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:1
2016-03-29 11:07:37.585 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
2016-03-29 11:07:37.599 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:07:37.599 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:07:37.599, ThaliTest[1804:4613328] multipeer manager: stop client timer
2016-03-29 11:07:37.600 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
,2016-03-29 11:07:37.600 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
2016-03-29 11:07:37.607 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:07:37.608 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
# teardown
,2016-03-29 11:07:38.675 ThaliTest[1804:4613182] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
,2016-03-29 11:07:41.373 ThaliTest[1804:4613182] client: found new peer: F067257C-7084-41CC-A4B5-8A232A1C6437:2
,2016-03-29 11:07:57.608 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:07:57.626 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
,2016-03-29 11:08:07.473 ThaliTest[1804:4613182] client: lost peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:08:07.473 ThaliTest[1804:4613182] client session: onPeerLost: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
,2016-03-29 11:08:08.617 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
,2016-03-29 11:08:17.608 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:08:17.626 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
,2016-03-29 11:08:25.395 ThaliTest[1804:4613182] client: lost peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:08:25.396 ThaliTest[1804:4613182] client session: onPeerLost: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
,2016-03-29 11:08:28.170 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
,2016-03-29 11:08:37.608 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:08:37.643 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
,2016-03-29 11:08:42.393 ThaliTest[1804:4613182] client: lost peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:08:42.393 ThaliTest[1804:4613182] client session: onPeerLost: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
,2016-03-29 11:08:45.575 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:45.575 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:08:45.576 ThaliTest[1804:4613328] multipeer manager: stop client timer
20,16-03-29 11:08:45.576 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:08:45.576 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 11:08:45.577 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 105 error should be null
ok 106 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54402
2016-03-29 11:08:46.332 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.332 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:08:46.332 ThaliTest[1804:4613,328] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
2016-03-29 11:08:46.335 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.335 ThaliTest[1804:4613328] THEMultipeerMa,nager stopping peer
2016-03-29 11:08:46.335 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
# teardown
,2016-03-29 11:08:46.593 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.594 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:08:46.594 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:08:46.594 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:08:46.595 ThaliTest[1804,:4613328] jxcore: stopListeningForAdvertisements: success
,ok 111 error should be null
ok 112 error should be null
,# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54404
,ok 113 first call should succeed
,ok 114 first call should succeed
,ok 115 specific error should be returned
,# teardown
,2016-03-29 11:08:46.986 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.986 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:08:46.986 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:08:46.986 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:08:46.987 ThaliTest[1804,:4613328] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
,ok 117 error should be null
,# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54406
2016-03-29 11:08:47.217 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
2016-03-29 11:08:47.218 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:08:47.219 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
,2016-03-29 11:08:47.233 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:08:47.234 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:3
2016-03-29 11:08:47.234 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:3
2016-03-29 11:08:47.235 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening: success
,ok 118 called only once
,ok 119 discovery state matches
,ok 120 advertising state matches
,# teardown
,2016-03-29 11:08:47.411 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:47.412 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:08:47.412 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:08:47.412 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
2016-03-29 11:08:47.412 ThaliTest[1804:4613328] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 11:08:47.414 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 121 error should be null
ok 122 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 123 should be called once
ok 124 should not have been called more than once
# teardown
,ok 125 error should be null
ok 126 error should be null
# setup
,# 33. can get the network status
,ok 127 network status should have certain non-empty properties
# teardown
,ok 128 error should be null
ok 129 error should be null
# setup
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
,2016-03-29 11:09:40.373 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
2016-03-29 11:09:40.373 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:09:40.374 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-29 11:09:40.376 ThaliTes,t[1804:4613328] jxcore: stopListeningForAdvertisements
2016-03-29 11:09:40.376 ThaliTest[1804:4613328] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-29 11:09:40.377 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 11:09:40.636 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:09:40.637 ThaliTest[1804:46133,28] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:09:40.638 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:09:40.638 ThaliTest[1804:461332,8] THEMultipeerManager stopping peer
2016-03-29 11:09:40.638 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-29 11:09:51.164 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
2016-03-29 11:09:51.164 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:09:51.165 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-29 11:09:51.166 ThaliTes,t[1804:4613328] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:09:51.167 ThaliTest[1804:4613328] jxcore: startListeningForAdv,ertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-29 11:10:05.139 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
2016-03-29 11:10:05.140 ThaliTest[1804:4613328] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-29 11:10:05.141 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:10:05.141 ThaliTest[1804:46133,28] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:05.142 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:10:05.142 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-29 11:10:25.310 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:25.310 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:4
2016-03-29 11:10:25.311 ThaliTest[1804:4613328] multipeer m,anager: start client restart timer: 0x14e85e90
2016-03-29 11:10:25.311 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:4
2016-03-29 11:10:25.311 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 144 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:10:25.312 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:25.313 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
,2016-03-29 11:10:25.313 ThaliTest[1804:4613328] multipeer manager: stop client timer
2016-03-29 11:10:25.318 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
ok 145 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-29 11:10:28.558 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:10:28.559 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
ok 146 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:10:28.560 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:28.560 ThaliTest[1804:461332,8] THEMultipeerManager stopping peer
2016-03-29 11:10:28.560 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
ok 147 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-29 11:10:55.308 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:55.309 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:5
2016-03-29 11:10:55.309 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
2016-03-29 11:10:55.309 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:5
2016-03-29 11:10:55.310 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 148 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:10:55.311 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:55.311 ThaliTest[1804:4613328] THEMultipeerManager stopping pee,r
,2016-03-29 11:10:55.311 ThaliTest[1804:4613328] multipeer manager: stop client timer
2016-03-29 11:10:55.318 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:6
2016-03-29 11:10:55.318 ThaliTest[1804:4613328] multipeer manager,: start client restart timer: 0x14e85e90
2016-03-29 11:10:55.319 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:6
2016-03-29 11:10:55.319 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 149 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-29 11:10:55.584 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 11:10:55.585 ThaliTest[1804:461332,8] jxcore: stopListeningForAdvertisements: success
ok 150 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:10:55.586 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:55.586 ThaliTest[1804:4613328,] THEMultipeerManager stopping peer
2016-03-29 11:10:55.586 ThaliTest[1804:4613328] multipeer manager: stop client timer
2016-03-29 11:10:55.587 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
ok 151 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-29 11:10:55.797 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:55.797 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:7
2016-03-29 11:10:55.798 ThaliTest[1804:4613328] multipeer m,anager: start client restart timer: 0x14e85e90
2016-03-29 11:10:55.798 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:7
2016-03-29 11:10:55.798 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 152 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-29 11:10:55.799 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-29 11:10:55.801 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
ok 153 Can call startListeningForAdvertisements without error
,2016-03-29 11:10:57.021 ThaliTest[1804:4613182] client: found new peer: F067257C-7084-41CC-A4B5-8A232A1C6437:7
ok 154 peers must be an array
ok 155 peers must not be zero-length
ok 156 peer must have peerIdentifier
ok 157 peerIdentifier must be a string
ok 158 peer must have peerAvailable
ok 159 peer must have pleaseConnect
,# teardown
,2016-03-29 11:10:58.029 ThaliTest[1804:4613182] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
,2016-03-29 11:10:58.824 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 11:10:58.825 ThaliTest[1804:461332,8] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:10:58.826 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:58.827 ThaliTest[1804:4613328,] THEMultipeerManager stopping peer
2016-03-29 11:10:58.828 ThaliTest[1804:4613328] multipeer manager: stop client timer
2016-03-29 11:10:58.828 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 40. Can connect to a remote peer
,2016-03-29 11:11:33.291 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:11:33.291 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:11:33.292 ThaliTest[1804:4613328] multipeer m,anager: start client restart timer: 0x14e85e90
2016-03-29 11:11:33.292 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:11:33.292 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 162 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:11:33.293 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-29 11:11:33.294 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
ok 163 Can call startListeningForAdvertisements without error
,2016-03-29 11:11:33.314 ThaliTest[1804:4613182] client: found new peer: F067257C-7084-41CC-A4B5-8A232A1C6437:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F067257C-7084-41CC-A4B5-8A232A1C6,437:7","pleaseConnect":0}]
2016-03-29 11:11:33.317 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:11:33.317 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:11:33.318 ThaliTest[1804:4613328], client session: reverseConnect
2016-03-29 11:11:33.318 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:7
,2016-03-29 11:11:35.709 ThaliTest[1804:4614142] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:11:35.710 ThaliTest[1804:4614142] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:11:35.7,11 ThaliTest[1804:4614142] client session: disconnect
2016-03-29 11:11:35.711 ThaliTest[1804:4614142] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:11:35.711 ThaliTest[1804:4614142] client session: no connect callback (server initiated)
,2016-03-29 11:11:36.096 ThaliTest[1804:4613182] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8","pleaseConnect":0}]
,2016-03-29 11:11:36.429 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:11:36.430 ThaliTest[1804:4613182] server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:8 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:2)
,2016-03-29 11:11:43.319 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 11:11:46.329 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:11:46.329 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:11:46.329 ThaliTest[1804:4613328] client session: reverseConn,ect
2016-03-29 11:11:46.329 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:7
,2016-03-29 11:11:46.580 ThaliTest[1804:4614141] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:11:46.582 ThaliTest[1804:4614141] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:11:46.5,82 ThaliTest[1804:4614141] client session: disconnect
2016-03-29 11:11:46.582 ThaliTest[1804:4614141] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:11:46.582 ThaliTest[1804:4614141] client session: no connect callback (server initiated)
,2016-03-29 11:11:48.088 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:11:48.088 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:11:48.088 ThaliTest[1804:4613182], server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:8 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:2)
,2016-03-29 11:11:53.293 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:11:53.323 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8
,2016-03-29 11:11:53.330 ThaliTest[1804:4613182] client: found updated peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F067257C-7084-41CC-A4B5-8A232A1C6437:8","pleaseConnect":0}]
,2016-03-29 11:11:56.330 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 11:11:59.342 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:11:59.342 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:11:59.343 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:11:59.343 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:11:59.636 ThaliTest[1804:4614182] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:11:59.636 ThaliTest[1804:4614182] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:11:59.6,36 ThaliTest[1804:4614182] client session: disconnect
2016-03-29 11:11:59.637 ThaliTest[1804:4614182] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:11:59.638 ThaliTest[1804:4614182] client session: no connect callback (server initiated)
,2016-03-29 11:12:00.861 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:12:00.862 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:12:00.862 ThaliTest[1804:4613182] server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:8 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:2)
,2016-03-29 11:12:09.344 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 7
,2016-03-29 11:12:12.351 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:12:12.352 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:12:12.352 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:12:12.352 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:12:12.756 ThaliTest[1804:4614296] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:12:12.756 ThaliTest[1804:4614296] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:12:12.7,57 ThaliTest[1804:4614296] client session: disconnect
2016-03-29 11:12:12.757 ThaliTest[1804:4614296] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:12:12.760 ThaliTest[1804:4614296] client session: no connect callback (server initiated)
,2016-03-29 11:12:13.293 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:12:13.312 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8
2016-03-29 11:12:13.313 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:12:13.809 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:12:13.809 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:12:13.809 ThaliTest[1804:4613182] server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:8 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:2)
,2016-03-29 11:12:22.353 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 11:12:25.360 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:12:25.360 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:12:25.360 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:12:25.360 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:12:26.890 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:12:26.890 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:12:26.890 ThaliTest[1804:4613182], server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:8 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:2)
,2016-03-29 11:12:27.786 ThaliTest[1804:4614345] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:12:27.788 ThaliTest[1804:4614345] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:12:27.789 ThaliTest[1804:4614345] client session: disconnect
2016-03-29 11:12:27.789 ThaliTest[1804:4614345] client session:, stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:12:27.790 ThaliTest[1804:4614345] client session: no connect callback (server initiated)
,2016-03-29 11:12:33.293 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:12:33.317 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:12:33.317 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8
,2016-03-29 11:12:35.361 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 11:12:38.369 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:12:38.370 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:12:38.370 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:12:38.370 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:12:39.879 ThaliTest[1804:4614345] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:12:39.880 ThaliTest[1804:4614345] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:12:39.8,80 ThaliTest[1804:4614345] client session: disconnect
2016-03-29 11:12:39.882 ThaliTest[1804:4614345] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:12:39.882 ThaliTest[1804:4614345] client session: no connect callback (server initiated)
,2016-03-29 11:12:40.049 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:12:40.049 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:12:40.049 ThaliTest[1804:4613182] server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:8 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:2)
,2016-03-29 11:12:48.371 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 11:12:51.382 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:12:51.383 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:12:51.383 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:12:51.383 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:12:51.521 ThaliTest[1804:4614419] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:12:51.523 ThaliTest[1804:4614419] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:12:51.5,24 ThaliTest[1804:4614419] client session: disconnect
2016-03-29 11:12:51.524 ThaliTest[1804:4614419] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:12:51.524 ThaliTest[1804:4614419] client session: no connect callback (server initiated)
,2016-03-29 11:12:53.084 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:12:53.084 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:12:53.085 ThaliTest[1804:4613182] server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:8 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:2)
,2016-03-29 11:12:53.293 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:12:53.317 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:12:53.319 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8
,2016-03-29 11:13:01.384 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 11:13:04.394 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:13:04.394 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:13:04.394 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:13:04.394 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:13:06.197 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:13:06.197 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:13:06.197 ThaliTest[1804:4613182] server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:8 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:2)
,2016-03-29 11:13:06.892 ThaliTest[1804:4614421] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:06.892 ThaliTest[1804:4614421] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:13:06.8,93 ThaliTest[1804:4614421] client session: disconnect
2016-03-29 11:13:06.894 ThaliTest[1804:4614421] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:06.894 ThaliTest[1804:4614421] client session: no connect callback (server initiated)
,2016-03-29 11:13:13.293 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:13:13.311 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:13:13.315 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8
,2016-03-29 11:13:14.395 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 11:13:17.399 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:13:17.400 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:13:17.400 ThaliTest[1804:4613328] client session: reverseConn,ect
2016-03-29 11:13:17.400 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:13:17.935 ThaliTest[1804:4614421] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:17.936 ThaliTest[1804:4614421] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:13:17.9,36 ThaliTest[1804:4614421] client session: disconnect
2016-03-29 11:13:17.937 ThaliTest[1804:4614421] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:17.937 ThaliTest[1804:4614421] client session: no connect callback (server initiated)
,2016-03-29 11:13:18.914 ThaliTest[1804:4613182] multipeer session: reset timer
,2016-03-29 11:13:18.914 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:13:18.917 ThaliTest[1804:4613182] server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:8 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:2)
,2016-03-29 11:13:27.400 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 11:13:30.407 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:13:30.408 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:13:30.408 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:13:30.408 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:13:30.796 ThaliTest[1804:4614511] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:30.796 ThaliTest[1804:4614511] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:13:30.7,97 ThaliTest[1804:4614511] client session: disconnect
2016-03-29 11:13:30.797 ThaliTest[1804:4614511] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:30.798 ThaliTest[1804:4614511] client session: no connect callb,ack (server initiated)
,2016-03-29 11:13:32.411 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:13:32.411 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:13:32.411 ThaliTest[1804:4613182] server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:8 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:2)
,2016-03-29 11:13:33.293 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:13:33.316 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:33.317 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8
,2016-03-29 11:13:40.409 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
WARN testThaliMobileNative: Too many connect retries,!
not ok 164 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-03-29 11:13:42.104 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-29 11:13:42.105 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,ok 165 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-29 11:13:42.107 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
,2016-03-29 11:13:42.107 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
,2016-03-29 11:13:42.108 ThaliTest[1804:4613328] multipeer manager: stop client timer
2016-03-29 11:13:42.108 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
ok 166 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. Can shift large amounts of data
,2016-03-29 11:13:43.067 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:13:43.067 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:13:43.068 ThaliTest[1804:4613328] multipeer m,anager: start client restart timer: 0x14e85e90
2016-03-29 11:13:43.068 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:13:43.068 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 167 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:13:43.069 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-29 11:13:43.070 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
ok 168 Can call startListeningForAdvertisements without error
,2016-03-29 11:13:44.799 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:13:44.799 ThaliTest[1804:4613182] server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:13:44.904 ThaliTest[1804:4613182] client: found new peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:44.905 ThaliTest[1804:4613182] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8
2016-03-29 11:13:44.906 ThaliTes,t[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:44.906 ThaliTest[1804:4613328] client: server will connect
,2016-03-29 11:13:44.907 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:13:44.907 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:13:45.848 ThaliTest[1804:4614555] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:45.850 ThaliTest[1804:4614555] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:13:45.850 ThaliTest[1804:4614555] client session: disconnect
2016-03-29 11:13:45.850 ThaliTest[1804:4614555] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:45.851 ThaliTest[1804:4614555] client session: no connect callb,ack (server initiated)
,2016-03-29 11:13:45.964 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:13:45.965 ThaliTest[1804:4613182] server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:13:48.007 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:13:48.008 ThaliTest[1804:4613182] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:13:48.008 ThaliTest[1804:4613182], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:13:51.195 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:13:51.196 ThaliTest[1804:4613182] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:13:51.196 ThaliTest[1804:4613182], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:13:54.297 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:13:54.298 ThaliTest[1804:4613182] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:13:54.298 ThaliTest[1804:4613182], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:13:54.908 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 11:13:57.031 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:13:57.031 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:13:57.032 ThaliTest[1804:4613182] server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:13:57.443 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:13:57.444 ThaliTest[1804:4613182] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:13:57.444 ThaliTest[1804:4613182], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:13:57.915 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:57.915 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:13:57.915 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:13:57.916 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:13:57.975 ThaliTest[1804:4614580] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:57.975 ThaliTest[1804:4614580] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:13:57.9,75 ThaliTest[1804:4614580] client session: disconnect
2016-03-29 11:13:57.975 ThaliTest[1804:4614580] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:13:57.980 ThaliTest[1804:4614580] client session: no connect callback (server initiated)
,2016-03-29 11:14:00.589 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:14:00.589 ThaliTest[1804:4613182] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:14:00.589 ThaliTest[1804:4613182] server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:14:03.069 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:14:03.095 ThaliTest[1804:4613182] client: found updated peer: F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:14:03.095 ThaliTest[1804:4613182] client: found updated peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:14:03.782 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:14:03.782 ThaliTest[1804:4613182] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:14:03.783 ThaliTest[1804:4613182], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:14:06.936 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:14:06.936 ThaliTest[1804:4613182] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:14:06.936 ThaliTest[1804:4613182] server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:14:07.916 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 8
,2016-03-29 11:14:10.023 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:14:10.023 ThaliTest[1804:4613182] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:14:10.024 ThaliTest[1804:4613182] server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:14:10.213 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:14:10.215 ThaliTest[1804:4613182] server: disconnecting to refresh session (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB)
2016-03-29 11:14:10.215 ThaliTest[1804:4613182], server: rejecting invitation from AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:14:10.919 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:14:10.919 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:14:10.919 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:14:10.919 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:14:11.059 ThaliTest[1804:4614555] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:14:11.060 ThaliTest[1804:4614555] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:14:11.0,60 ThaliTest[1804:4614555] client session: disconnect
2016-03-29 11:14:11.060 ThaliTest[1804:4614555] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:14:11.061 ThaliTest[1804:4614555] client session: no connect callback (server initiated)
,2016-03-29 11:14:13.284 ThaliTest[1804:4613182] multipeer session: reset timer
2016-03-29 11:14:13.285 ThaliTest[1804:4613182] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:14:13.285 ThaliTest[1804:4613182], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (CF5927A1-42FA-4DDF-8112-8BFA72204E68:9 != CF5927A1-42FA-4DDF-8112-8BFA72204E68:8)
,2016-03-29 11:14:20.920 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 11:14:23.069 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:14:23.923 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:14:23.923 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:14:23.923 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:14:23.924 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:14:23.936 ThaliTest[1804:4613182] client: lost peer: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:14:23.936 ThaliTest[1804:4613182] client session: onPeerLost: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:14:23.936 ThaliTest[1804:4613182] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:14:23.937 ThaliTest[1804:4613182] client session: disconnect
2016-03-29 11:14:23.937 ThaliTest[1804:4613182] client session: stateChange:1->0 F067257C-7084-41CC-,A4B5-8A232A1C6437:9
2016-03-29 11:14:23.937 ThaliTest[1804:4613182] client session: no connect callback (server initiated)
,2016-03-29 11:14:33.924 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 11:14:36.934 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:14:36.934 ThaliTest[1804:4613328] client: connect: unreachable F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:14:36.934 ThaliTest[180,4:4613328] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 11:14:39.946 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:14:39.947 ThaliTest[1804:4613328] client: connect: unreachable F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:14:39.947 ThaliTest[180,4:4613328] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 11:14:42.962 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:14:42.963 ThaliTest[1804:4613328] client: connect: unreachable F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:14:42.963 ThaliTest[1804:4613328] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 11:14:43.069 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:14:43.084 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:14:43.084 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:14:45.974 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:14:45.974 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:14:45.975 ThaliTest[1804:4613328] client session: reverseConn,ect
2016-03-29 11:14:45.975 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:14:47.419 ThaliTest[1804:4614631] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:14:47.419 ThaliTest[1804:4614631] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:14:47.4,19 ThaliTest[1804:4614631] client session: disconnect
2016-03-29 11:14:47.419 ThaliTest[1804:4614631] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:14:47.420 ThaliTest[1804:4614631] client session: no connect callback (server initiated)
,2016-03-29 11:14:55.975 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 2
,2016-03-29 11:14:58.979 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:14:58.979 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:14:58.980 ThaliTest[1804:4613328] client session: reverseConnect
2016-03-29 11:14:58.980 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:15:00.122 ThaliTest[1804:4614631] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:15:00.122 ThaliTest[1804:4614631] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:15:00.1,23 ThaliTest[1804:4614631] client session: disconnect
2016-03-29 11:15:00.123 ThaliTest[1804:4614631] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:15:00.124 ThaliTest[1804:4614631] client session: no connect callback (server initiated)
,2016-03-29 11:15:03.069 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:15:03.086 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:15:03.086 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:15:08.981 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 11:15:11.985 ThaliTest[1804:4613328] jxcore: connect F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:15:11.985 ThaliTest[1804:4613328] client: server will connect
2016-03-29 11:15:11.986 ThaliTest[1804:4613328] client session: reverseConn,ect
2016-03-29 11:15:11.986 ThaliTest[1804:4613328] client session: stateChange:0->1 F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:15:13.484 ThaliTest[1804:4614717] client session: not connected F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:15:13.484 ThaliTest[1804:4614717] client session: onLinkFailure: F067257C-7084-41CC-A4B5-8A232A1C6437
2016-03-29 11:15:13.484 ThaliTest[1804:4614717] client session: disconnect
,2016-03-29 11:15:13.484 ThaliTest[1804:4614717] client session: stateChange:1->0 F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:15:13.485 ThaliTest[1804:4614717] client session: no connect callback (server initiated)
,2016-03-29 11:15:21.987 ThaliTest[1804:4613182] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
WARN testThaliMobileNative: Too many connect retries!
,not ok 169 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-29 11:15:22.354 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 11:15:22.355 ThaliTest[1804:461332,8] jxcore: stopListeningForAdvertisements: success
ok 170 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:15:22.356 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:22.357 ThaliTest[1804:4613328,] THEMultipeerManager stopping peer
2016-03-29 11:15:22.357 ThaliTest[1804:4613328] multipeer manager: stop client timer
2016-03-29 11:15:22.357 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
ok 171 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,2016-03-29 11:15:24.084 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:24.084 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:24.085 ThaliTest[1804:4613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:24.086 ThaliTest[1804:4613328] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-29 11:15:24.461 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:24.462 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:24.462 ThaliTest[1804:4613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:15:24.463 ThaliTest[1804:4613328] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 173 specific error should be returned
# teardown
,# setup
,2016-03-29 11:15:25.521 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:25.521 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:25.522 ThaliTest[1804:4613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:15:25.523 ThaliTest[1804:4613328] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54443
2016-03-29 11:15:25.946 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:15:25.947 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
ok 174 no errors
2016-03-29 11:15:25.948 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:15:25.949 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
ok 175 still no errors
# teardown,
,2016-03-29 11:15:26.141 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:26.141 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:15:26.141 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:15:26.142 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:15:26.142 ThaliTest[1804,:4613328] jxcore: stopListeningForAdvertisements: success
# setup
,2016-03-29 11:15:26.309 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:26.309 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:26.310 ThaliTest[1804:4,613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:15:26.311 ThaliTest[1804:4613328] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54445
,2016-03-29 11:15:26.548 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
2016-03-29 11:15:26.549 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:15:26.550 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
ok 176 no errors
,2016-03-29 11:15:26.551 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:15:26.553 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
ok 177 still no errors
,# teardown
,2016-03-29 11:15:26.560 ThaliTest[1804:4613182] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,2016-03-29 11:15:26.830 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:26.831 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:15:26.831 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:15:26.831 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
2016-03-29 11:15:26.831 ThaliTest[1804:4613328] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 11:15:26.832 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
# setup
,2016-03-29 11:15:26.991 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:26.992 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:26.992 ThaliTest[1804:4613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:15:26.993 ThaliTest[1804:4613328] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 46. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54448
,2016-03-29 11:15:27.152 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:15:27.153 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:10
2016-03-29 11:15:27.153 ThaliTest[1804:4613328] multipeer ,manager: start client restart timer: 0x14e85e90
2016-03-29 11:15:27.153 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:10
2016-03-29 11:15:27.154 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 178 no errors
2016-03-29 11:15:27.155 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:15:27.155 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:15:27.156 ThaliTest[1804:4613,328] multipeer manager: stop client timer
2016-03-29 11:15:27.158 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:11
2016-03-29 11:15:27.158 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
,2016-03-29 11:15:27.158 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:11
2016-03-29 11:15:27.163 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening: success
ok 179 still no errors
# teardown
,2016-03-29 11:15:27.199 ThaliTest[1804:4613182] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:15:27.279 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
,2016-03-29 11:15:27.280 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
,2016-03-29 11:15:27.283 ThaliTest[1804:4613328] multipeer manager: stop client timer
,2016-03-29 11:15:27.284 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
,2016-03-29 11:15:27.285 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:15:27.287 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:15:27.429 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-29 11:15:27.430 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-29 11:15:27.431 ThaliTest[1804:4613328] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:27.433 ThaliTest[1804:4613328] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54452
,2016-03-29 11:15:28.299 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
,2016-03-29 11:15:28.300 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
,2016-03-29 11:15:28.301 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
,ok 180 no errors
,2016-03-29 11:15:28.303 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
,2016-03-29 11:15:28.304 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
,2016-03-29 11:15:28.304 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
,ok 181 still no errors
,# teardown
,2016-03-29 11:15:28.407 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
,2016-03-29 11:15:28.407 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
,2016-03-29 11:15:28.408 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
,2016-03-29 11:15:28.409 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:15:28.411 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:15:31.371 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:31.371 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:31.372 ThaliTest[1804:4,613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:15:31.373 ThaliTest[1804:4613328] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 48. can get the network status before starting
,ok 182 network status should have certain non-empty properties
# teardown
,# setup
,2016-03-29 11:16:14.760 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:14.760 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:14.761 ThaliTest[1804:4,613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:16:14.762 ThaliTest[1804:4613328] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 49. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 183 specific error expected
# teardown
,# setup
,2016-03-29 11:16:15.725 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:15.726 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:15.726 ThaliTest[1804:4,613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:16:15.727 ThaliTest[1804:4613328] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 50. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54454
,2016-03-29 11:16:16.117 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
,2016-03-29 11:16:16.118 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-29 11:16:16.121 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements: success
,2016-03-29 11:16:16.122 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
,2016-03-29 11:16:16.123 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:12
,2016-03-29 11:16:16.124 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:12
,2016-03-29 11:16:16.125 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 184 connection to servers manager should succeed after starting
,ok 185 connection to router server should succeed after starting
,2016-03-29 11:16:16.173 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
,2016-03-29 11:16:16.174 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
,2016-03-29 11:16:16.174 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
,2016-03-29 11:16:16.176 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
,2016-03-29 11:16:16.177 ThaliTest[1804:4613328] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:16:16.180 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 186 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 187 connection to servers manager should fail after stopping
,ok 188 connection to router server should fail after stopping
,# teardown
,# setup
,2016-03-29 11:16:19.999 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:20.000 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:20.000 ThaliTest[1804:4613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:16:20.001 ThaliTest[1804:4613328] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure terminateConnection is properly hooked up
,ok 189 called with right arguments
# teardown
,# setup
,2016-03-29 11:16:58.817 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:58.818 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:58.818 ThaliTest[1804:4613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:16:58.820 ThaliTest[1804:4613328] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. make sure terminateListener is properly hooked up
,ok 190 called with right arguments
# teardown
,# setup
,2016-03-29 11:17:01.117 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:01.117 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:01.118 ThaliTest[1804:4,613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:17:01.119 ThaliTest[1804:4613328] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 53. make sure we actually call kill connections properly
,2016-03-29 11:17:01.335 ThaliTest[1804:4613328] jxcore: killConnections
2016-03-29 11:17:01.335 ThaliTest[1804:4613328] jxcore: killConnections: badParam
not ok 191 should not fail on iOS
  ---
    operator: fail
  ...
# teardown
,# setup
,2016-03-29 11:17:02.373 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:02.373 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:02.374 ThaliTest[1804:4,613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:17:02.375 ThaliTest[1804:4613328] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54461
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":54460,"error":{}}
2016-03-29 11:17:02.641 ThaliTest[1804:4613328] jxcore: stopAdvert,isingAndListening
2016-03-29 11:17:02.641 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:17:02.641 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:17:02.641 ThaliTest[1804:4613328] jxcore: stop,ListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:17:02.642 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,ok 192 failure reason is as expected
ok 193 error description is as expected
ok 194 must be stopped
# teardown
,# setup
,2016-03-29 11:17:06.039 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:06.039 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:06.040 ThaliTest[1804:4,613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:17:06.041 ThaliTest[1804:4613328] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 55. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54463
,ok 195 peerIdentifier matches
ok 196 error description matches
# teardown
,2016-03-29 11:17:13.315 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:17:13.315 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:17:13.315 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:17:13.316 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:17:13.317 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:17:14.757 ThaliTest[1804:4613328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:14.758 ThaliTest[1804:4613328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:14.758 ThaliTest[1804:4,613328] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:17:14.759 ThaliTest[1804:4613328] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 56. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54465
2016-03-29 11:17:14.898 ThaliTest[1804:4613328] jxcore: startListeningForAdvertisements
2016-03-29 11:17:14.898 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
ok 197 discoveryActive matches
ok 198 advertisingActive matches
2016-03-29 11:17:14.901 ThaliTest[1804:4613328] jxcore: startListeningForAdvertise,ments: success
2016-03-29 11:17:14.902 ThaliTest[1804:4613328] jxcore: stopAdvertisingAndListening
2016-03-29 11:17:14.902 ThaliTest[1804:4613328] THEMultipeerManager stopping peer
2016-03-29 11:17:14.902 ThaliTest[1804:4613328] jxcore: stopAdvertisingA,ndListening: success
2016-03-29 11:17:14.903 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements
,2016-03-29 11:17:14.903 ThaliTest[1804:4613328] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
ok 199 discoveryActive matches
ok 200 adverti,singActive matches
2016-03-29 11:17:14.910 ThaliTest[1804:4613328] jxcore: stopListeningForAdvertisements: success
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54467
,2016-03-29 11:17:14.921 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:17:14.922 ThaliTest[1804:4613328] server: starting CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:17:14.925 ThaliTest[1804:4613328] multipeer manager: start client restart timer: 0x14e85e90
2016-03-29 11:17:14.925 ThaliTest[1804:4613328] THEMultipeerManager initialized peer CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:17:14.925 ThaliTest[1804:4613328] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-29 11:17:16.907 ThaliTest[1804:4613182] client: found new peer: F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:17:17.141 ThaliTest[1804:4613182] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:17:34.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:17:34.942 ThaliTest[1804:4613182] client: found updated peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:17:34.942 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:17:54.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:17:54.941 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:17:54.942 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:18:14.925 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:18:14.938 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:18:14.940 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:18:34.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:18:34.939 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:18:34.940 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:18:54.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:18:54.942 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
2016-03-29 11:18:54.943 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:19:14.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:19:14.942 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:19:14.943 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:19:34.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:19:34.941 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:19:34.942 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:19:54.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:19:54.941 ThaliTest[1804:4613182] client: found updated peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:19:54.942 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:20:14.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:20:14.943 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:20:14.944 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:20:34.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:20:34.943 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:20:34.943 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:20:54.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:20:54.939 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:20:54.939 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:21:14.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:21:14.939 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:21:14.939 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:21:34.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:21:34.942 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:21:34.942 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:21:54.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:21:54.941 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:21:54.941 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:22:14.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:22:14.944 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:22:14.944 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:22:34.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:22:34.941 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:22:34.942 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:22:54.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:22:54.944 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:22:54.944 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:23:14.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:23:14.943 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:23:14.944 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:23:34.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:23:34.943 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:23:34.944 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:23:54.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:23:54.942 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:23:54.943 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:24:14.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:24:14.939 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:24:14.939 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:24:34.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:24:34.940 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:24:34.941 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:24:54.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:24:54.943 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:24:54.943 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:25:14.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:25:14.941 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:25:14.944 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:25:34.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:25:34.938 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:25:34.938 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:25:54.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:25:54.940 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:25:54.941 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:26:14.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:26:14.938 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:26:14.939 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:26:34.926 ThaliTest[1804:4613182] multipeer manager: restart client
,2016-03-29 11:26:34.938 ThaliTest[1804:4613182] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:26:34.939 ThaliTest[1804:4613182] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13

```
