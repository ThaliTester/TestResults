#### Test 657450204f13c43_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/AB911BF3-1E26-44F5-8C87-155290C68004/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AB911BF3-1E26-44F5-8C87-155290C68004/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51981"
,(lldb)     command script import "/tmp/AB911BF3-1E26-44F5-8C87-155290C68004/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-08 09:29:18.418 ThaliTest[2953:5862467] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C340AFD1-4902-4742-9A28-5857181ED16B/Library/Cookies/Cookies.binarycookies
,2016-04-08 09:29:18.642 ThaliTest[2953:5862467] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-08 09:29:18.643 ThaliTest[2953:5862467] Multi-tasking -> Device: YES, App: YES
,2016-04-08 09:29:18.659 ThaliTest[2953:5862467] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-08 09:29:19.410 ThaliTest[2953:5862467] Using UIWebView
2016-04-08 09:29:19.412 ThaliTest[2953:5862467] [CDVTimer][handleopenurl] 0.138998ms
2016-04-08 09:29:19.414 ThaliTest[2953:5862467] [CDVTimer][intentandnavigationfilter] 2.104044ms
2016-04-08 09:29:19.414 ThaliTest[2953:5862467] [CDVTimer][gesturehandler] 0.092983ms
2016-04-08 09:29:19.414 ThaliTest[2953:5862467] [CDVTimer][TotalPluginStartup] 2.776980ms
,2016-04-08 09:29:22.448 ThaliTest[2953:5862467] Resetting plugins due to page load.
,2016-04-08 09:29:23.783 ThaliTest[2953:5862467] Finished load of: file:///var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/index.html
,2016-04-08 09:29:23.938 ThaliTest[2953:5862467] JXcore Cordova plugin initializing
,2016-04-08 09:29:23.939 ThaliTest[2953:5862601] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-08 09:29:30.994 ThaliTest[2953:5862601] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-08 09:29:30.995 ThaliTest[2953:5862601] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-08 09:29:30.995 ThaliTest[2953:5862601] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-08 09:29:30.997 ThaliTest[2953:5862601] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C8D35B47-3011-4791-B7F0-7724EB3F60AC/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58444
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58446
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
DEBUG createNativeListener: listening 58449
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
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58453
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 58458
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
DEBUG createNativeListener: listening 58462
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
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
DEBUG createNativeListener: listening 58466
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
DEBUG createNativeListener: listening 58470
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 58474
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
DEBUG createNativeListener: creating incoming mux
D,EBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new, incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 58526
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
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
DEBUG createNativeListener: listening 58530
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
,DEBUG createNativeListener: incoming socket close
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
,# 16. enqueue and run in order
,ok 48 firstPromise setTimeout
ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
,ok 56 thirdPromise testValue
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
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
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
,[{"uuid":"6bac6588-a6e4-44a8-b2ac-e4b77439f88c","data":"custom data"},{"uuid":"281113d3-0e97-4786-a620-6936cd6b2a37","data":"custom data"},{"uuid":"981e6d0f-5d06-4f4c-bdce-22c4d8fdd816","data":"custom data"},{"uuid":"e825a612-6c5c-4d54-afc9-816449e93798",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83, participant data matches
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
DEBUG createNativeListener: listening 58540
2016-04-08 09:32:22.571 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:22.571 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-08 09:32:22.573 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:22.573 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-08 09:32:22.727 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:22.727 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:32:22.728 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
2016-04-08 09:32:22.728 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:22.728 ThaliTest[2953,:5862601] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58542
2016-04-08 09:32:22.901 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements
,2016-04-08 09:32:22.903 ThaliTest[2953:5862601] multipeer manager: start client restart timer: 0x15d97a70
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:32:22.904 Th,aliTest[2953:5862601] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-08 09:32:22.912 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:32:22.913 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-08 09:32:23.200 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:23.201 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:32:23.201 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:32:23.201 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
2016-04-08 09:32:23.201 ThaliTest[2953:5862601] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:32:23.202 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58544
,2016-04-08 09:32:23.680 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:32:23.680 ThaliTest[2953:5862601] server: starting B29A2A64-B1EF-4545-BC19-F0DD94E05227:1
2016-04-08 09:32:23.681 ThaliTest[2953:5862601] multipeer m,anager: start client restart timer: 0x15d97a70
2016-04-08 09:32:23.681 ThaliTest[2953:5862601] THEMultipeerManager initialized peer B29A2A64-B1EF-4545-BC19-F0DD94E05227:1
2016-04-08 09:32:23.681 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-08 09:32:23.687 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:32:23.688 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:32:23.688, ThaliTest[2953:5862601] multipeer manager: stop client timer
2016-04-08 09:32:23.688 ThaliTest[2953:5862601] server: starting B29A2A64-B1EF-4545-BC19-F0DD94E05227:2
2016-04-08 09:32:23.688 ThaliTest[2953:5862601] multipeer manager: start client restart ,timer: 0x15d97a70
2016-04-08 09:32:23.688 ThaliTest[2953:5862601] THEMultipeerManager initialized peer B29A2A64-B1EF-4545-BC19-F0DD94E05227:2
2016-04-08 09:32:23.688 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
# teardown
,2016-04-08 09:32:23.853 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:23.854 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:32:23.854 ThaliTest[2953:5862601] multipeer manager: stop client timer
2016-04-08 09:32:23.854 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
2016-04-08 09:32:23.854 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:23.855 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58549
,2016-04-08 09:32:36.782 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:36.782 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:32:36.782 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
,ok 110 error should be null
,2016-04-08 09:32:36.784 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:36.784 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:32:36.784 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-08 09:33:26.491 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:26.492 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:33:26.492 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:33:26.492 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:26.492 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58551
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-08 09:33:27.033 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:27.034 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:33:27.034 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:33:27.034 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:27.034 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58553
2016-04-08 09:33:27.277 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements
2016-04-08 09:33:27.278 ThaliTest[2953:5862601] multipeer manager: start client restart timer: 0x15d97a70
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:33:27.278 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements: success
,2016-04-08 09:33:27.284 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:33:27.284 ThaliTest[2953:5862601] server: starting B29A2A64-B1EF-4545-BC19-F0DD94E05227:3
2016-04-08 09:33:27.284 ThaliTest[2953:5862601] THEMultipee,rManager initialized peer B29A2A64-B1EF-4545-BC19-F0DD94E05227:3
2016-04-08 09:33:27.284 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches,
# teardown
,2016-04-08 09:33:27.550 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:27.550 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:33:27.550 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:33:27.550 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
2016-04-08 09:33:27.551 ThaliTest[2953:5862601] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:27.551 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 123 error should be null
,ok 124 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
ok 126 should not have been called more than once
# teardown
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
,2016-04-08 09:33:53.276 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements
2016-04-08 09:33:53.277 ThaliTest[2953:5862601] multipeer manager: start client restart timer: 0x15d97a70
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:33:53.277 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-08 09:33:53.278 ThaliTes,t[2953:5862601] jxcore: stopListeningForAdvertisements
2016-04-08 09:33:53.278 ThaliTest[2953:5862601] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-04-08 09:33:53.279 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-08 09:33:53.541 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:53.542 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:33:53.542 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:53.542 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:33:53.542 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-08 09:34:17.120 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements
2016-04-08 09:34:17.120 ThaliTest[2953:5862601] multipeer manager: start client restart timer: 0x15d97a70
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:34:17.120 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-08 09:34:17.121 ThaliTes,t[2953:5862601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:34:17.122 ThaliTest[2953:5862601] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-08 09:34:36.367 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
2016-04-08 09:34:36.368 ThaliTest[2953:5862601] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:36.369 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:34:36.371 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:36.371 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:34:36.372 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-08 09:34:52.474 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:52.475 ThaliTest[2953:58626,01] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-08 09:34:52.476 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:52.476 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-08 09:34:52.769 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:52.770 ThaliTest[2953:58626,01] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:34:52.770 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:52.770 ThaliTest[2953:58626,01] THEMultipeerManager stopping peer
2016-04-08 09:34:52.770 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-08 09:34:53.011 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:34:53.012 ThaliTest[2953:5862601] server: starting B29A2A64-B1EF-4545-BC19-F0DD94E05227:4
2016-04-08 09:34:53.012 ThaliTest[2953:5862601] multipeer m,anager: start client restart timer: 0x15d97a70
2016-04-08 09:34:53.012 ThaliTest[2953:5862601] THEMultipeerManager initialized peer B29A2A64-B1EF-4545-BC19-F0DD94E05227:4
,2016-04-08 09:34:53.012 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:34:53.015 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016,-04-08 09:34:53.015 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:34:53.016 ThaliTest[2953:5862601] multipeer manager: stop client timer
2016-04-08 09:34:53.016 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: succes,s
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-08 09:34:53.102 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:34:53.103 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:34:53.104 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:53.104 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:34:53.104 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-08 09:34:53.424 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:34:53.425 ThaliTest[2953:5862601] server: starting B29A2A64-B1EF-4545-BC19-F0DD94E05227:5
2016-04-08 09:34:53.425 ThaliTest[2953:5862601] multipeer manager: start client restart timer: 0x15d97a70
2016-04-08 09:34:53.425 ThaliTest[2953:5862601] THEMultipeerManager initialized peer B29A2A64-B1EF-4545-BC19-F0DD94E05227:5
2016-04-08 09:34:53.425 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:34:53.426 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:34:53.426 ThaliTest[2953:5862601] THEMultipeerManager stopping pee,r
2016-04-08 09:34:53.426 ThaliTest[2953:5862601] multipeer manager: stop client timer
2016-04-08 09:34:53.426 ThaliTest[2953:5862601] server: starting B29A2A64-B1EF-4545-BC19-F0DD94E05227:6
2016-04-08 09:34:53.427 ThaliTest[2953:5862601] multipeer mana,ger: start client restart timer: 0x15d97a70
2016-04-08 09:34:53.428 ThaliTest[2953:5862601] THEMultipeerManager initialized peer B29A2A64-B1EF-4545-BC19-F0DD94E05227:6
,2016-04-08 09:34:53.428 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-08 09:34:53.516 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-08 09:34:53.517 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:34:53.518 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:53.518 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:34:53.518 ThaliTest[2953:5862601] multipeer manager: stop client timer
2016-04-08 09:34:53.518 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-08 09:34:54.189 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:54.189 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:34:54.189 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:34:54.190 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:54.190 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:34,:54.190 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-08 09:35:00.550 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:35:00.551 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:35:00.551 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
,2016-04-08 09:35:00.552 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:35:00.552 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-08 09:35:16.666 ThaliTest[2953:5862601] jxcore: connect foo
2016-04-08 09:35:16.666 ThaliTest[2953:5862601] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
,# teardown
,2016-04-08 09:35:16.748 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:35:16.749 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:35:16.749 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
,2016-04-08 09:35:16.749 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:35:16.749 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-08 09:35:16.917 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:35:16.917 ThaliTest[2953:5862601] server: starting B29A2A64-B1EF-4545-BC19-F0DD94E05227:7
2016-04-08 09:35:16.917 ThaliTest[2953:5862601] multipeer m,anager: start client restart timer: 0x15d97a70
2016-04-08 09:35:16.917 ThaliTest[2953:5862601] THEMultipeerManager initialized peer B29A2A64-B1EF-4545-BC19-F0DD94E05227:7
2016-04-08 09:35:16.917 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-08 09:35:16.918 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-08 09:35:16.919 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-08 09:35:17.964 ThaliTest[2953:5862467] client: found new peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:17.965 ThaliTest[2953:5862467] client: found new peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-08 09:35:18.495 ThaliTest[2953:5862467] client: found new peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:7
,2016-04-08 09:35:20.250 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-08 09:35:20.251 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:35:20.252 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:35:20.252 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:35:20.253 ThaliTest[2953:5862601] multipeer manager: stop client timer
20,16-04-08 09:35:20.253 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-08 09:35:41.815 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:35:41.816 ThaliTest[2953:5862601] server: starting B29A2A64-B1EF-4545-BC19-F0DD94E05227:8
2016-04-08 09:35:41.816 ThaliTest[2953:5862601] multipeer m,anager: start client restart timer: 0x15d97a70
2016-04-08 09:35:41.816 ThaliTest[2953:5862601] THEMultipeerManager initialized peer B29A2A64-B1EF-4545-BC19-F0DD94E05227:8
2016-04-08 09:35:41.816 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:35:41.817 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-08 09:35:41.817 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-08 09:35:43.650 ThaliTest[2953:5862467] client: found new peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:43.650 ThaliTest[2953:5862467] client: found new peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:8
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7","pleaseConnect":0}]
2016-04-08 09:35:43.652 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 0,9:35:43.652 ThaliTest[2953:5862601] client session: connect
2016-04-08 09:35:43.653 ThaliTest[2953:5862601] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5401A4DE-2020-4411-800F-72E067EDFF0D:8","pleaseConnect":0}]
,2016-04-08 09:35:44.056 ThaliTest[2953:5862467] client: found new peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C76D48A2-6720-4997-B51C-ADA808AA0AC0:8","pleaseConnect":0}]
,2016-04-08 09:35:45.090 ThaliTest[2953:5863515] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:45.091 ThaliTest[2953:5863515] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:45.091 ThaliTest[2953:5863515] client session: disconnect
2016-04-08 09:35:45.091 ThaliTest[2953:5863515] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:45.091 ThaliTest[2953:5863515] client session: fireConnectCallb,ack: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:45.091 ThaliTest[2953:5863515] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 9
,2016-04-08 09:35:48.094 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:48.094 ThaliTest[2953:5862601] client session: connect
2016-04-08 09:35:48.094 ThaliTest[2953:5862601] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,2016-04-08 09:35:48.383 ThaliTest[2953:5863515] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:48.385 ThaliTest[2953:5863515] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:48.385 ThaliTest[2953:5863515] client session: disconnect
2016-04-08 09:35:48.385 ThaliTest[2953:5863515] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:48.385 ThaliTest[2953:5863515] client session: fireConnectCallb,ack: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:48.385 ThaliTest[2953:5863515] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 8
,2016-04-08 09:35:51.389 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:51.389 ThaliTest[2953:5862601] client session: connect
2016-04-08 09:35:51.389 ThaliTest[2953:5862601] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,2016-04-08 09:35:51.576 ThaliTest[2953:5863514] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:51.577 ThaliTest[2953:5863514] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:51.5,77 ThaliTest[2953:5863514] client session: disconnect
2016-04-08 09:35:51.577 ThaliTest[2953:5863514] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:51.578 ThaliTest[2953:5863514] client session: fireConnectCallb,ack: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:51.578 ThaliTest[2953:5863514] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-04-08 09:35:54.583 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:54.583 ThaliTest[2953:5862601] client session: connect
2016-04-08 09:35:54.583 ThaliTest[2953:5862601] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,2016-04-08 09:35:54.720 ThaliTest[2953:5863515] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:54.720 ThaliTest[2953:5863515] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:54.721 ThaliTest[2953:5863515] client session: disconnect
2016-04-08 09:35:54.721 ThaliTest[2953:5863515] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:54.721 ThaliTest[2953:5863515] client session: fireConnectCallb,ack: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:54.722 ThaliTest[2953:5863515] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 6
,2016-04-08 09:35:57.730 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:57.730 ThaliTest[2953:5862601] client session: connect
2016-04-08 09:35:57.730 ThaliTest[2953:5862601] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,2016-04-08 09:35:57.924 ThaliTest[2953:5863513] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:57.925 ThaliTest[2953:5863513] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:57.9,25 ThaliTest[2953:5863513] client session: disconnect
2016-04-08 09:35:57.925 ThaliTest[2953:5863513] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:57.925 ThaliTest[2953:5863513] client session: fireConnectCallb,ack: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:57.925 ThaliTest[2953:5863513] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-08 09:36:00.937 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:36:00.938 ThaliTest[2953:5862601] client session: connect
2016-04-08 09:36:00.938 ThaliTest[2953:5862601] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,2016-04-08 09:36:01.027 ThaliTest[2953:5863514] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:36:01.027 ThaliTest[2953:5863514] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:36:01.027 ThaliTest[2953:5863514] client session: disconnect
,2016-04-08 09:36:01.028 ThaliTest[2953:5863514] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:36:01.028 ThaliTest[2953:5863514] client session: fireConnectCallback: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 0,9:36:01.028 ThaliTest[2953:5863514] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-08 09:36:01.817 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:36:01.827 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:01.827 ThaliTest[2953:5862467] client: found updated peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:01.827, ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8","pleaseConn,ect":0}]
,2016-04-08 09:36:04.032 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:36:04.032 ThaliTest[2953:5862601] client session: connect
2016-04-08 09:36:04.033 ThaliTest[2953:5862601] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:36:04.126 ThaliTest[2953:5863515] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:04.127 ThaliTest[2953:5863515] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:36:04.127 ThaliTest[2953:5863515] client session: disconnect
2016-04-08 09:36:04.127 ThaliTest[2953:5863515] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:04.127 ThaliTest[2953:5863515] client session: fireConnectCallb,ack: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:36:04.127 ThaliTest[2953:5863515] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-08 09:36:07.135 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:36:07.135 ThaliTest[2953:5862601] client session: connect
2016-04-08 09:36:07.135 ThaliTest[2953:5862601] client session: stateChange:0->,1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:36:07.305 ThaliTest[2953:5863515] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:36:07.306 ThaliTest[2953:5863515] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:36:07.306 ThaliTest[2953:5863515] client session: disconnect
,2016-04-08 09:36:07.306 ThaliTest[2953:5863515] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:07.307 ThaliTest[2953:5863515] client session: fireConnectCallback: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:36:07.307 ThaliTest[2953:5863515] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-08 09:36:10.316 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:36:10.316 ThaliTest[2953:5862601] client session: connect
2016-04-08 09:36:10.317 ThaliTest[2953:5862601] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:36:10.395 ThaliTest[2953:5863513] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:10.395 ThaliTest[2953:5863513] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:36:10.396 ThaliTest[2953:5863513] client session: disconnect
2016-04-08 09:36:10.396 ThaliTest[2953:5863513] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:10.396 ThaliTest[2953:5863513] client session: fireConnectCallb,ack: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:36:10.396 ThaliTest[2953:5863513] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-08 09:36:13.407 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:36:13.407 ThaliTest[2953:5862601] client session: connect
2016-04-08 09:36:13.407 ThaliTest[2953:5862601] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:36:13.596 ThaliTest[2953:5863515] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:13.597 ThaliTest[2953:5863515] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:36:13.597 ThaliTest[2953:5863515] client session: disconnect
,2016-04-08 09:36:13.597 ThaliTest[2953:5863515] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:13.597 ThaliTest[2953:5863515] client session: fireConnectCallback: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:36:13.598 ThaliTest[2953:5863515] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-04-08 09:36:13.985 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-08 09:36:13.985 ThaliTest[2953:5862601] jxcore: stopListeningForAdvertisements: success
ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:36:13.986 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening
2016-04-08 09:36:13.986 ThaliTest[2953:5862601] THEMultipeerManager stopping peer
2016-04-08 09:36:13.987 ThaliTest[2953:5862601] multipeer manager: stop client timer
2016-04-08 09:36:13.987 ThaliTest[2953:5862601] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-08 09:36:17.483 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:36:17.483 ThaliTest[2953:5862601] server: starting B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:36:17.483 ThaliTest[2953:5862601] multipeer manager: start client restart timer: 0x15d97a70
2016-04-08 09:36:17.483 ThaliTest[2953:5862601] THEMultipeerManager initialized peer B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:36:17.483 ThaliTest[2953:5862601] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:36:17.486 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-08 09:36:17.487 ThaliTest[2953:5862601] jxcore: startListeningForAdvertisements: success
,ok 181 Can call startListeningForAdvertisements without error
,2016-04-08 09:36:18.509 ThaliTest[2953:5862467] client: found new peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:18.509 ThaliTest[2953:5862467] client: found new peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:18.510 ThaliTest[2953:5862467] client: found new peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:18.510 ThaliTest[2953:5862601] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
,2016-04-08 09:36:18.511 ThaliTest[2953:5862601] client: server will connect
,2016-04-08 09:36:18.511 ThaliTest[2953:5862601] client session: reverseConnect
2016-04-08 09:36:18.512 ThaliTest[2953:5862601] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
,2016-04-08 09:36:19.931 ThaliTest[2953:5863514] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:19.931 ThaliTest[2953:5863514] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:36:19.9,31 ThaliTest[2953:5863514] client session: disconnect
2016-04-08 09:36:19.931 ThaliTest[2953:5863514] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:19.931 ThaliTest[2953:5863514] client session: no connect callb,ack (server initiated)
,2016-04-08 09:36:28.512 ThaliTest[2953:5862467] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-08 09:36:31.522 ThaliTest[2953:5862601] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:31.522 ThaliTest[2953:5862601] client: server will connect
2016-04-08 09:36:31.522 ThaliTest[2953:5862601] client session: reverseConnect
2016-04-08 09:36:31.522 ThaliTest[2953:5862601] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
,2016-04-08 09:36:31.675 ThaliTest[2953:5863514] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
,2016-04-08 09:36:31.675 ThaliTest[2953:5863514] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:36:31.676 ThaliTest[2953:5863514] client session: disconnect
2016-04-08 09:36:31.677 ThaliTest[2953:5863514] client session:, stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:31.677 ThaliTest[2953:5863514] client session: no connect callback (server initiated)
,2016-04-08 09:36:37.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:36:37.495 ThaliTest[2953:5862467] client: found updated peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:37.496 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:37.496 ThaliTest[2953:5862467] client: found updated peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:36:41.523 ThaliTest[2953:5862467] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-08 09:36:44.530 ThaliTest[2953:5862601] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:44.530 ThaliTest[2953:5862601] client: server will connect
2016-04-08 09:36:44.531 ThaliTest[2953:5862601] client session: reverseConnect
2016-04-08 09:36:44.531 ThaliTest[2953:5862601] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:36:44.784 ThaliTest[2953:5863700] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:44.784 ThaliTest[2953:5863700] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:36:44.7,84 ThaliTest[2953:5863700] client session: disconnect
2016-04-08 09:36:44.784 ThaliTest[2953:5863700] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:44.785 ThaliTest[2953:5863700] client session: no connect callback (server initiated)
,2016-04-08 09:36:54.532 ThaliTest[2953:5862467] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-08 09:36:57.484 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:36:57.495 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:57.495 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:57.495 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:36:57.535 ThaliTest[2953:5862601] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:57.535 ThaliTest[2953:5862601] client: server will connect
2016-04-08 09:36:57.535 ThaliTest[2953:5862601] client session: reverseConnect
2016-04-08 09:36:57.535 ThaliTest[2953:5862601] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:36:58.537 ThaliTest[2953:5863759] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:58.537 ThaliTest[2953:5863759] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:36:58.5,37 ThaliTest[2953:5863759] client session: disconnect
2016-04-08 09:36:58.537 ThaliTest[2953:5863759] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:58.537 ThaliTest[2953:5863759] client session: no connect callb,ack (server initiated)
,2016-04-08 09:37:07.536 ThaliTest[2953:5862467] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-08 09:37:10.545 ThaliTest[2953:5862601] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:37:10.545 ThaliTest[2953:5862601] client: server will connect
2016-04-08 09:37:10.545 ThaliTest[2953:5862601] client session: reverseConnect
2016-04-08 09:37:10.545 ThaliTest[2953:5862601] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:10.857 ThaliTest[2953:5863786] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:10.859 ThaliTest[2953:5863786] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:37:10.860 ThaliTest[2953:5863786] client session: disconnect
2016-04-08 09:37:10.860 ThaliTest[2953:5863786] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:10.861 ThaliTest[2953:5863786] client session: no connect callback (server initiated)
,2016-04-08 09:37:17.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:37:17.495 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:37:17.497 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:17.498 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:37:20.547 ThaliTest[2953:5862467] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-08 09:37:23.554 ThaliTest[2953:5862601] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:37:23.555 ThaliTest[2953:5862601] client: server will connect
2016-04-08 09:37:23.555 ThaliTest[2953:5862601] client session: reverseConnect
2016-04-08 09:37:23.555 ThaliTest[2953:5862601] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:25.209 ThaliTest[2953:5863834] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:25.209 ThaliTest[2953:5863834] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:37:25.209 ThaliTest[2953:5863834] client session: disconnect
2016-04-08 09:37:25.209 ThaliTest[2953:5863834] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:25.209 ThaliTest[2953:5863834] client session: no connect callb,ack (server initiated)
,2016-04-08 09:37:33.556 ThaliTest[2953:5862467] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-08 09:37:35.942 ThaliTest[2953:5862467] multipeer session: reset timer
2016-04-08 09:37:35.943 ThaliTest[2953:5862467] server: rejecting invitation for lexical ordering 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:37:36.559 ThaliTest[2953:5862601] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:37:36.559 ThaliTest[2953:5862601] client: server will connect
2016-04-08 09:37:36.559 ThaliTest[2953:5862601] client session: reverseConnect
2016-04-08 09:37:36.559 ThaliTest[2953:5862601] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:37.326 ThaliTest[2953:5863908] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:37.327 ThaliTest[2953:5863908] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:37:37.327 ThaliTest[2953:5863908] client session: disconnect
,2016-04-08 09:37:37.327 ThaliTest[2953:5863908] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:37.328 ThaliTest[2953:5863908] client session: no connect callback (server initiated)
,2016-04-08 09:37:37.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:37:37.495 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:37:37.496 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:37.496 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:46.560 ThaliTest[2953:5862467] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-08 09:37:48.999 ThaliTest[2953:5862467] multipeer session: reset timer
2016-04-08 09:37:48.999 ThaliTest[2953:5862467] server: disconnecting to refresh session (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC)
2016-04-08 09:37:48.999 ThaliTest[2953:5862467] server: rejecting invitation for lexical ordering 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:37:49.570 ThaliTest[2953:5862601] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:37:49.570 ThaliTest[2953:5862601] client: server will connect
2016-04-08 09:37:49.570 ThaliTest[2953:5862601] client session: reverseConnect
2016-04-08 09:37:49.571 ThaliTest[2953:5862601] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:49.848 ThaliTest[2953:5863840] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:49.848 ThaliTest[2953:5863840] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:37:49.848 ThaliTest[2953:5863840] client session: disconnect
,2016-04-08 09:37:49.848 ThaliTest[2953:5863840] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:49.850 ThaliTest[2953:5863840] client session: no connect callback (server initiated)
,2016-04-08 09:37:57.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:37:57.496 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:37:57.496 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:57.496 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:59.572 ThaliTest[2953:5862467] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-08 09:38:01.769 ThaliTest[2953:5862467] multipeer session: reset timer
2016-04-08 09:38:01.769 ThaliTest[2953:5862467] server: disconnecting to refresh session (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC)
2016-04-08 09:38:01.769 ThaliTest[2953:5862467] server: rejecting invitation for lexical ordering 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:38:02.585 ThaliTest[2953:5862601] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:38:02.585 ThaliTest[2953:5862601] client: server will connect
2016-04-08 09:38:02.585 ThaliTest[2953:5862601] client session: reverseConnect
2016-04-08 09:38:02.585 ThaliTest[2953:5862601] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:38:02.815 ThaliTest[2953:5863834] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:38:02.816 ThaliTest[2953:5863834] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:38:02.8,16 ThaliTest[2953:5863834] client session: disconnect
2016-04-08 09:38:02.816 ThaliTest[2953:5863834] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:38:02.816 ThaliTest[2953:5863834] client session: no connect callback (server initiated)
,2016-04-08 09:38:12.586 ThaliTest[2953:5862467] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-08 09:38:14.812 ThaliTest[2953:5862467] multipeer session: reset timer
2016-04-08 09:38:14.812 ThaliTest[2953:5862467] server: disconnecting to refresh session (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC)
2016-04-08 09:38:14.812 ThaliTest[2953:5862467] server: rejecting invitation for lexical ordering 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:38:15.598 ThaliTest[2953:5862601] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:38:15.598 ThaliTest[2953:5862601] client: server will connect
,2016-04-08 09:38:15.598 ThaliTest[2953:5862601] client session: reverseConnect
2016-04-08 09:38:15.599 ThaliTest[2953:5862601] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:38:15.777 ThaliTest[2953:5864068] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:38:15.778 ThaliTest[2953:5864068] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:38:15.778 ThaliTest[2953:5864068] client session: disconnect
,2016-04-08 09:38:15.778 ThaliTest[2953:5864068] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:38:15.779 ThaliTest[2953:5864068] client session: no connect callback (server initiated)
,2016-04-08 09:38:17.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:38:17.495 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:38:17.495 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:38:17.496 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:38:25.599 ThaliTest[2953:5862467] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-08 09:38:27.778 ThaliTest[2953:5862467] multipeer session: reset timer
2016-04-08 09:38:27.778 ThaliTest[2953:5862467] server: disconnecting to refresh session (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC)
2016-04-08 09:38:27.778 ThaliTest[2953:5862467] server: rejecting invitation for lexical ordering 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:38:27.779 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:27.779 ThaliTest[2953:5862601] client session:, connect
2016-04-08 09:38:27.780 ThaliTest[2953:5862601] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:38:30.669 ThaliTest[2953:5864097] client session: p2p link connected
,2016-04-08 09:38:30.685 ThaliTest[2953:5864105] client session: stateChange:1->2 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:38:30.685 ThaliTest[2953:5864105] client session: fireConnectCallback: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:38:30.685 ThaliTest[2953:5864105] jxcore: connect: success
,2016-04-08 09:38:30.698 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:30.698 ThaliTest[2953:5862467] client: relay established
2016-04-08 09:38:30.698 ThaliTest[2953:5862467] client: new accepted socket: ,0x17741a80
2016-04-08 09:38:30.698 ThaliTest[2953:5862601] client: already connect(ing/ed) to 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:30.698 ThaliTest[2953:5862601] jxcore: connect: fail: Already connect(ing/ed)
,ok 182 Expected error
,ok 183 Null connection as expected
,2016-04-08 09:38:30.701 ThaliTest[2953:5862601] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:30.701 ThaliTest[2953:5862601] client: already connect(ing/ed) to 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:30.701 Thali,Test[2953:5862601] jxcore: connect: fail: Already connect(ing/ed)
ok 184 Expected error
ok 185 Null connection as expected
,# teardown
,2016-04-08 09:38:37.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:38:37.495 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:38:37.495 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:38:37.495 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:38:57.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:38:57.494 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:38:57.494 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:38:57.494 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:39:17.484 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:39:17.508 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:39:17.509 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:17.509 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:39:37.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:39:37.495 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:39:37.496 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:37.496 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:39:57.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:39:57.496 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:57.496 ThaliTest[2953:5862467] client: found updated peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:39:57.496 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:40:17.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:40:17.496 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:40:17.496 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:40:17.49,6 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:40:37.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:40:37.497 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:40:37.498 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:40:37.498 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:40:57.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:40:57.497 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:40:57.497 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:40:57.497 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:41:17.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:41:17.496 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:41:17.497 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:41:17.497 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:41:37.484 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:41:37.494 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:41:37.495 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:41:37.495 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:41:57.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:41:57.499 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:41:57.499 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:41:57.499 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:42:17.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:42:17.498 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:42:17.503 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:42:17.503 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:42:37.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:42:37.497 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:42:37.497 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:42:37.497 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:42:57.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:42:57.496 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:42:57.496 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:42:57.496 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:43:17.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:43:17.497 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:43:17.497 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:43:17.497 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:43:37.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:43:37.499 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:43:37.499 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:43:37.499 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:43:57.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:43:57.496 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:43:57.496 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:43:57.49,6 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:44:17.485 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:44:17.495 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:44:17.496 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:44:17.496 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:44:37.466 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:44:37.477 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:44:37.479 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:44:37.479 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:44:57.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:44:57.457 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:44:57.457 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:44:57.457 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:45:17.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:45:17.457 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:45:17.457 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:45:17.458 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:45:37.444 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:45:37.455 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:45:37.456 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:45:37.457 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:45:57.444 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:45:57.455 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:45:57.456 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:45:57.456 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:46:17.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:46:17.460 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:46:17.460 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:46:17.461 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:46:37.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:46:37.455 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:46:37.456 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:46:37.456 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:46:57.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:46:57.455 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:46:57.457 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:46:57.457 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:47:17.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:47:17.456 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:47:17.456 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:47:17.456 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:47:37.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:47:37.455 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:47:37.456 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:47:37.456 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:47:57.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:47:57.456 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:47:57.456 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:47:57.456 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:48:17.444 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:48:17.456 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:48:17.456 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:48:17.45,6 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:48:37.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:48:37.456 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:48:37.456 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:48:37.45,6 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:48:57.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:48:57.456 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:48:57.456 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:48:57.456 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:49:17.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:49:17.457 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:49:17.457 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:49:17.457 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:49:37.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:49:37.455 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:49:37.455 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:49:37.458 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:49:57.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:49:57.456 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:49:57.457 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:49:57.458 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:50:17.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:50:17.456 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:50:17.456 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:50:17.45,6 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:50:37.444 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:50:37.456 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:50:37.456 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:50:37.456 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:50:57.445 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:50:57.457 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:50:57.457 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:50:57.457 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:51:17.444 ThaliTest[2953:5862467] multipeer manager: restart client
,2016-04-08 09:51:17.454 ThaliTest[2953:5862467] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:51:17.457 ThaliTest[2953:5862467] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:51:17.457 ThaliTest[2953:5862467] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9

```
