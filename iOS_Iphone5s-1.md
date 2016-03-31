#### Test 648099369ce4518_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/018D56BA-DAEE-414E-8D4D-C6D30DAA5D39/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/018D56BA-DAEE-414E-8D4D-C6D30DAA5D39/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49972"
,(lldb)     command script import "/tmp/018D56BA-DAEE-414E-8D4D-C6D30DAA5D39/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 18:03:38.415 ThaliTest[2613:4754653] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/82664CD0-9241-4CC2-8B1A-5ABA5F4AB004/Library/Cookies/Cookies.binarycookies
,2016-03-31 18:03:38.668 ThaliTest[2613:4754653] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 18:03:38.669 ThaliTest[2613:4754653] Multi-tasking -> Device: YES, App: YES
,2016-03-31 18:03:38.688 ThaliTest[2613:4754653] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 18:03:39.503 ThaliTest[2613:4754653] Using UIWebView
,2016-03-31 18:03:39.506 ThaliTest[2613:4754653] [CDVTimer][handleopenurl] 0.186026ms
,2016-03-31 18:03:39.510 ThaliTest[2613:4754653] [CDVTimer][intentandnavigationfilter] 2.929986ms
2016-03-31 18:03:39.510 ThaliTest[2613:4754653] [CDVTimer][gesturehandler] 0.132024ms
2016-03-31 18:03:39.510 ThaliTest[2613:4754653] [CDVTimer][TotalPluginS,tartup] 3.935993ms
,2016-03-31 18:03:42.737 ThaliTest[2613:4754653] Resetting plugins due to page load.
,2016-03-31 18:03:44.213 ThaliTest[2613:4754653] Finished load of: file:///var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/index.html
,2016-03-31 18:03:44.412 ThaliTest[2613:4754653] JXcore Cordova plugin initializing
,2016-03-31 18:03:44.414 ThaliTest[2613:4754824] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 18:03:52.784 ThaliTest[2613:4754824] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 18:03:52.785 ThaliTest[2613:4754824] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 18:03:52.786 ThaliTest[2613:4754824] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 18:03:52.789 ThaliTest[2613:4754824] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE24FF68-C380-47B6-826B-F945292E1870/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57351
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57353
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
DEBUG createNativeListener: listening 57356
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
DEBUG createNativeListener: listening 57360
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 57365
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
DEBUG createNativeListener: listening 57369
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
DEBUG createNativeListener: listening 57373
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
DEBUG createNativeListener: listening 57377
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 57381
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
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
DEBUG createNativeListener: listening 57433
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
DEBUG createNativeListener: listening 57437
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
,ok 50 firstPromise result
ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
,ok 53 secondPromise result
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
ok 83 own UUID is found from the participants list
# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 84 specific error should be returned
# teardown
,ok 85 error should be null
ok 86 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 87 specific error should be returned
# teardown
,ok 88 error should be null
ok 89 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57449
,2016-03-31 18:06:25.382 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.384 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
2016-03-31 18:06:25.385 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.386 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
,ok 93 error should be null
,# teardown
,2016-03-31 18:06:25.551 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:25.551 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:06:25.552 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
2016-03-31 18:06:25.552 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.552 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
ok 94 error should be null
ok 95 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57451
2016-03-31 18:06:25.795 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements
,2016-03-31 18:06:25.797 ThaliTest[2613:4754824] multipeer manager: start client restart timer: 0x146a7110
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:06:25.798 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
ok 97 error should be null
2016-03-31 18:06:25.839 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:06:25.840 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements: success
ok 98 error should be null
ok 99 error should be null
# teardown
,2016-03-31 18:06:25.934 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:25.934 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:06:25.934 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
2016-03-31 18:06:25.935 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
2016-03-31 18:06:25.935 ThaliTest[2613:4754824] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.935 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 100 error should be null
ok 101 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57453
,2016-03-31 18:06:26.268 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:06:26.268 ThaliTest[2613:4754824] server: starting 2467FBFF-8374-4C28-A08D-056504009757:1
,2016-03-31 18:06:26.270 ThaliTest[2613:4754824] multipeer manager: start client restart timer: 0x146a7110
2016-03-31 18:06:26.270 ThaliTest[2613:4754824] THEMultipeerManager initialized peer 2467FBFF-8374-4C28-A08D-056504009757:1
2016-03-31 18:06:26.271 ,ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
2016-03-31 18:06:26.330 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:06:26.330 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:06:26.331 ThaliTest[2613:4754824] multipeer manager: stop client timer
2016-03-31 18:06:26.331 ThaliTest[2613:4754824] server: starting 2467FBFF-8374-4C28-A08D-056504009757:2
2016-03-31 18:06:26.331 ThaliTest[2613:4754824] multipeer manager: start client restart ,timer: 0x146a7110
2016-03-31 18:06:26.331 ThaliTest[2613:4754824] THEMultipeerManager initialized peer 2467FBFF-8374-4C28-A08D-056504009757:2
2016-03-31 18:06:26.331 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
ok 105 error should be null
# teardown
,2016-03-31 18:06:26.774 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:26.774 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:06:26.774 ThaliTest[2613:4754824] multipeer manager: stop client timer
20,16-03-31 18:06:26.774 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
2016-03-31 18:06:26.775 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:26.775 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 106 error should be null
ok 107 error should be null
# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57458
2016-03-31 18:06:33.098 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:33.098 ThaliTest[2613:4754824] THEMultipeerManager stoppi,ng peer
2016-03-31 18:06:33.098 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
,ok 108 error should be null
ok 109 error should be null
,2016-03-31 18:06:33.102 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:33.102 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:06:33.102 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
,ok 110 error should be null
ok 111 error should be null
# teardown
,2016-03-31 18:06:43.546 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:43.546 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:06:43.546 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
2016-03-31 18:06:43.547 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:43.547 ThaliTest[2613,:4754824] jxcore: stopListeningForAdvertisements: success
ok 112 error should be null
ok 113 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57460
ok 114 first call should succeed
ok 115 first call should succeed
ok 116 specific error should be returned
# teardown
,2016-03-31 18:07:05.234 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:07:05.234 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:07:05.234 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 18:07:05.235 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:05.235 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
ok 117 error should be null
ok 118 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57462
2016-03-31 18:07:05.660 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements
2016-03-31 18:07:05.661 ThaliTest[2613:4754824] multipeer manager: start client restart timer: 0x146a7110
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:07:05.662 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements: success
,2016-03-31 18:07:05.673 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:07:05.673 ThaliTest[2613:4754824] server: starting 2467FBFF-8374-4C28-A08D-056504009757:3
2016-03-31 18:07:05.673 ThaliTest[2613:4754824] THEMultipee,rManager initialized peer 2467FBFF-8374-4C28-A08D-056504009757:3
2016-03-31 18:07:05.674 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening: success
ok 119 called only once
ok 120 discovery state matches
ok 121 advertising state matches
# teardown
,2016-03-31 18:07:05.937 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:07:05.937 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:07:05.937 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 18:07:05.938 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
2016-03-31 18:07:05.938 ThaliTest[2613:4754824] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:05.939 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 122 error should be null
ok 123 error should be null
# setup
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
,ok 130 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 131 host address should match
ok 132 port should match
,ok 133 host address should be null
ok 134 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 135 error should be null
ok 136 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-31 18:07:41.713 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements
2016-03-31 18:07:41.714 ThaliTest[2613:4754824] multipeer manager: start client restart timer: 0x146a7110
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:07:41.714 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
2016-03-31 18:07:41.716 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
2016-03-31 18:07:41.716 ThaliTest[2613:4754824] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-31 18:07:41.716 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
ok 138 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 18:07:45.882 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 18:07:45.884 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 18:07:45.885 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:07:45.885 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:07:45.885 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 18:08:00.751 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements
2016-03-31 18:08:00.752 ThaliTest[2613:4754824] multipeer manager: start client restart timer: 0x146a7110
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:08:00.753 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements without error
2016-03-31 18:08:00.753 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:08:00.755 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAd,vertisements twice without error
,# teardown
,2016-03-31 18:08:01.008 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
2016-03-31 18:08:01.007 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
2016-03-31 18:08:01.007 ThaliTest[2613:4754824] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:08:01.009 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:01.009 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
,2016-03-31 18:08:01.011 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 18:08:01.526 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:01.526 ThaliTest[2613:4754824] server: starting 2467FBFF-8374-4C28-A08D-056504009757:4
2016-03-31 18:08:01.527 ThaliTest[2613:4754824] multipeer m,anager: start client restart timer: 0x146a7110
2016-03-31 18:08:01.527 ThaliTest[2613:4754824] THEMultipeerManager initialized peer 2467FBFF-8374-4C28-A08D-056504009757:4
,2016-03-31 18:08:01.527 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening: success
ok 145 Can call startUpdateAdvertisingAndListening without error
2016-03-31 18:08:01.530 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:01.530 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:08:01.530 ThaliTest[2613:4754824] multipeer manager: stop client timer
2016-03-31 18:08:01.531 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
ok 146 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-31 18:08:01.668 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:08:01.669 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
ok 147 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:08:01.670 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:01.670 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:08:01.670 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 18:08:02.218 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:02.219 ThaliTest[2613:4754824] server: starting 2467FBFF-8374-4C28-A08D-056504009757:5
2016-03-31 18:08:02.219 ThaliTest[2613:4754824] multipeer m,anager: start client restart timer: 0x146a7110
2016-03-31 18:08:02.219 ThaliTest[2613:4754824] THEMultipeerManager initialized peer 2467FBFF-8374-4C28-A08D-056504009757:5
2016-03-31 18:08:02.219 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening: success
ok 149 Can call startUpdateAdvertisingAndListening without error
2016-03-31 18:08:02.220 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:02.220 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
,2016-03-31 18:08:02.220 ThaliTest[2613:4754824] multipeer manager: stop client timer
2016-03-31 18:08:02.223 ThaliTest[2613:4754824] server: starting 2467FBFF-8374-4C28-A08D-056504009757:6
2016-03-31 18:08:02.224 ThaliTest[2613:4754824] multipeer manager,: start client restart timer: 0x146a7110
2016-03-31 18:08:02.224 ThaliTest[2613:4754824] THEMultipeerManager initialized peer 2467FBFF-8374-4C28-A08D-056504009757:6
2016-03-31 18:08:02.224 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 18:08:02.571 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 18:08:02.572 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements: success
ok 151 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:08:02.573 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:02.573 ThaliTest[2613:4754824,] THEMultipeerManager stopping peer
2016-03-31 18:08:02.573 ThaliTest[2613:4754824] multipeer manager: stop client timer
2016-03-31 18:08:02.573 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-31 18:08:03.102 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:03.102 ThaliTest[2613:4754824] server: starting 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:03.102 ThaliTest[2613:4754824] multipeer manager: start client restart timer: 0x146a7110
2016-03-31 18:08:03.103 ThaliTest[2613:4754824] THEMultipeerManager initialized peer 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:03.103 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening: success
ok 153 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 18:08:03.103 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-31 18:08:03.104 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error
,2016-03-31 18:08:04.598 ThaliTest[2613:4754653] client: found new peer: F11AAA28-318B-4CE4-B684-469230DD4996:7
,ok 155 peers must be an array
ok 156 peers must not be zero-length
ok 157 peer must have peerIdentifier
,ok 158 peerIdentifier must be a string
,ok 159 peer must have peerAvailable
,ok 160 peer must have pleaseConnect
,# teardown
,2016-03-31 18:08:07.778 ThaliTest[2613:4754824] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 18:08:07.779 ThaliTest[2613:475482,4] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:08:07.780 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:07.780 ThaliTest[2613:4754824] THEMultipeerManager stopping peer
2016-03-31 18:08:07.780 ThaliTest[2613:4754824] multipeer manager: stop client timer
2016-03-31 18:08:07.780 ThaliTest[2613:4754824] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. Can connect to a remote peer
,2016-03-31 18:08:09.430 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:09.430 ThaliTest[2613:4754824] server: starting 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:09.430 ThaliTest[2613:4754824] multipeer manager: start client restart timer: 0x146a7110
2016-03-31 18:08:09.431 ThaliTest[2613:4754824] THEMultipeerManager initialized peer 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:09.431 ThaliTest[2613:4754824] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 163 Can call startUpdateAdvertisingAndListening without error
2016-03-31 18:08:09.432 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 18:08:09.432 ThaliTest[2613:4754824] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-31 18:08:10.089 ThaliTest[2613:4754653] client: found new peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C1217920-C4F0-4779-A4B2-BE1967CE7,9BC:7","pleaseConnect":0}]
2016-03-31 18:08:10.090 ThaliTest[2613:4754824] jxcore: connect C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:08:10.091 ThaliTest[2613:4754824] client: server will connect
2016-03-31 18:08:10.091 ThaliTest[2613:4754824] client session: reverseConnect
2016-03-31 18:08:10.091 ThaliTest[2613:4754824] client session: stateChange:0->1 C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
,2016-03-31 18:08:10.764 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:10.764 ThaliTest[2613:4754653] server: rejecting invitation from F11AAA28-318B-4CE4-B684-469230DD4996 due to previous generation (2467FBFF-8374-4C28-A08D-05650,4009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:11.356 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:11.356 ThaliTest[2613:4754653] server: rejecting invitation from C1217920-C4F0-4779-A4B2-BE1967CE79BC due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:11.517 ThaliTest[2613:4754653] client: found new peer: F11AAA28-318B-4CE4-B684-469230DD4996:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F11AAA28-318B-4CE4-B684-469230DD4,996:7","pleaseConnect":0}]
,2016-03-31 18:08:11.629 ThaliTest[2613:4755354] client session: not connected C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:08:11.630 ThaliTest[2613:4755354] client session: onLinkFailure: C1217920-C4F0-4779-A4B2-BE1967CE79BC
2016-03-31 18:08:11.631 ThaliTest[2613:4755354] client session: disconnect
2016-03-31 18:08:11.631 ThaliTest[2613:4755354] client session: stateChange:1->0 C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:08:11.631 ThaliTest[2613:4755354] client session: no connect callback (server initiated)
,2016-03-31 18:08:13.874 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:13.874 ThaliTest[2613:4754653] server: disconnecting to refresh session (F11AAA28-318B-4CE4-B684-469230DD4996)
2016-03-31 18:08:13.874 ThaliTest[2613:4754653], server: rejecting invitation from F11AAA28-318B-4CE4-B684-469230DD4996 due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:14.445 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:14.446 ThaliTest[2613:4754653] server: disconnecting to refresh session (C1217920-C4F0-4779-A4B2-BE1967CE79BC)
2016-03-31 18:08:14.446 ThaliTest[2613:4754653], server: rejecting invitation from C1217920-C4F0-4779-A4B2-BE1967CE79BC due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:17.005 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:17.006 ThaliTest[2613:4754653] server: disconnecting to refresh session (F11AAA28-318B-4CE4-B684-469230DD4996)
2016-03-31 18:08:17.006 ThaliTest[2613:4754653] server: rejecting invitation from F11AAA28-318B-4CE4-B684-469230DD4996 due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:18.430 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:18.430 ThaliTest[2613:4754653] server: disconnecting to refresh session (C1217920-C4F0-4779-A4B2-BE1967CE79BC)
2016-03-31 18:08:18.430 ThaliTest[2613:4754653] server: rejecting invitation from C1217920-C4F0-4779-A4B2-BE1967CE79BC due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:20.092 ThaliTest[2613:4754653] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 18:08:20.204 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:20.204 ThaliTest[2613:4754653] server: disconnecting to refresh session (F11AAA28-318B-4CE4-B684-469230DD4996)
2016-03-31 18:08:20.204 ThaliTest[2613:4754653] server: rejecting invitation from F11AAA28-318B-4CE4-B684-469230DD4996 due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:21.720 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:21.720 ThaliTest[2613:4754653] server: disconnecting to refresh session (C1217920-C4F0-4779-A4B2-BE1967CE79BC)
2016-03-31 18:08:21.721 ThaliTest[2613:4754653] server: rejecting invitation from C1217920-C4F0-4779-A4B2-BE1967CE79BC due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:23.095 ThaliTest[2613:4754824] jxcore: connect C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:08:23.095 ThaliTest[2613:4754824] client: server will connect
2016-03-31 18:08:23.096 ThaliTest[2613:4754824] client session: reverseConn,ect
2016-03-31 18:08:23.096 ThaliTest[2613:4754824] client session: stateChange:0->1 C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
,2016-03-31 18:08:23.351 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:23.351 ThaliTest[2613:4754653] server: disconnecting to refresh session (F11AAA28-318B-4CE4-B684-469230DD4996)
2016-03-31 18:08:23.351 ThaliTest[2613:4754653] server: rejecting invitation from F11AAA28-318B-4CE4-B684-469230DD4996 due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:23.563 ThaliTest[2613:4755439] client session: not connected C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:08:23.563 ThaliTest[2613:4755439] client session: onLinkFailure: C1217920-C4F0-4779-A4B2-BE1967CE79BC
2016-03-31 18:08:23.563 ThaliTest[2613:4755439] client session: disconnect
2016-03-31 18:08:23.564 ThaliTest[2613:4755439] client session: stateChange:1->0 C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
,2016-03-31 18:08:23.564 ThaliTest[2613:4755439] client session: no connect callback (server initiated)
,2016-03-31 18:08:24.864 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:24.864 ThaliTest[2613:4754653] server: disconnecting to refresh session (C1217920-C4F0-4779-A4B2-BE1967CE79BC)
2016-03-31 18:08:24.864 ThaliTest[2613:4754653] server: rejecting invitation from C1217920-C4F0-4779-A4B2-BE1967CE79BC due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:26.492 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:26.492 ThaliTest[2613:4754653] server: disconnecting to refresh session (F11AAA28-318B-4CE4-B684-469230DD4996)
2016-03-31 18:08:26.492 ThaliTest[2613:4754653], server: rejecting invitation from F11AAA28-318B-4CE4-B684-469230DD4996 due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:28.008 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:28.008 ThaliTest[2613:4754653] server: disconnecting to refresh session (C1217920-C4F0-4779-A4B2-BE1967CE79BC)
2016-03-31 18:08:28.009 ThaliTest[2613:4754653] server: rejecting invitation from C1217920-C4F0-4779-A4B2-BE1967CE79BC due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:08:29.449 ThaliTest[2613:4754653] client: found updated peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:08:29.450 ThaliTest[2613:4754653] client: found updated peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F11AAA28-318B-4CE4-B684-469230DD4996:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C1217920-C4F0-4779-A4B2-BE1967CE79BC:8","pleaseConnect":0}]
,2016-03-31 18:08:31.203 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:31.203 ThaliTest[2613:4754653] server: disconnecting to refresh session (C1217920-C4F0-4779-A4B2-BE1967CE79BC)
2016-03-31 18:08:31.203 ThaliTest[2613:4754653], server: rejecting invitation from C1217920-C4F0-4779-A4B2-BE1967CE79BC due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:33.096 ThaliTest[2613:4754653] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 18:08:34.351 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:34.351 ThaliTest[2613:4754653] server: disconnecting to refresh session (C1217920-C4F0-4779-A4B2-BE1967CE79BC)
2016-03-31 18:08:34.352 ThaliTest[2613:4754653] server: rejecting invitation from C1217920-C4F0-4779-A4B2-BE1967CE79BC due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:36.108 ThaliTest[2613:4754824] jxcore: connect C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:08:36.108 ThaliTest[2613:4754824] client: server will connect
2016-03-31 18:08:36.109 ThaliTest[2613:4754824] client session: reverseConnect
2016-03-31 18:08:36.109 ThaliTest[2613:4754824] client session: stateChange:0->1 C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:08:36.434 ThaliTest[2613:4755440] client session: not connected C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:08:36.434 ThaliTest[2613:4755440] client session: onLinkFailure: C1217920-C4F0-4779-A4B2-BE1967CE79BC
2016-03-31 18:08:36.435 ThaliTest[2613:4755440] client session: disconnect
2016-03-31 18:08:36.435 ThaliTest[2613:4755440] client session:, stateChange:1->0 C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:08:36.436 ThaliTest[2613:4755440] client session: no connect callback (server initiated)
,2016-03-31 18:08:37.496 ThaliTest[2613:4754653] multipeer session: reset timer
2016-03-31 18:08:37.497 ThaliTest[2613:4754653] server: disconnecting to refresh session (C1217920-C4F0-4779-A4B2-BE1967CE79BC)
2016-03-31 18:08:37.497 ThaliTest[2613:4754653] server: rejecting invitation from C1217920-C4F0-4779-A4B2-BE1967CE79BC due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:40.595 ThaliTest[2613:4754653] multipeer session: reset timer
,2016-03-31 18:08:40.596 ThaliTest[2613:4754653] server: disconnecting to refresh session (C1217920-C4F0-4779-A4B2-BE1967CE79BC)
2016-03-31 18:08:40.596 ThaliTest[2613:4754653] server: rejecting invitation from C1217920-C4F0-4779-A4B2-BE1967CE79BC due to previous generation (2467FBFF-8374-4C28-A08D-056504009757:8 != 2467FBFF-8374-4C28-A08D-056504009757:7)
,2016-03-31 18:08:46.110 ThaliTest[2613:4754653] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 18:08:49.114 ThaliTest[2613:4754824] jxcore: connect C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:08:49.114 ThaliTest[2613:4754824] client: server will connect
2016-03-31 18:08:49.114 ThaliTest[2613:4754824] client session: reverseConnect
2016-03-31 18:08:49.114 ThaliTest[2613:4754824] client session: stateChange:0->1 C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:08:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:08:49.447 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:08:49.448 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:08:59.115 ThaliTest[2613:4754653] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 18:09:02.123 ThaliTest[2613:4754824] jxcore: connect C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:02.124 ThaliTest[2613:4754824] client: already connect(ing/ed) to C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:02.124 Thali,Test[2613:4754824] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 18:09:05.136 ThaliTest[2613:4754824] jxcore: connect C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:05.136 ThaliTest[2613:4754824] client: already connect(ing/ed) to C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:05.137 ThaliTest[2613:4754824] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 18:09:08.146 ThaliTest[2613:4754824] jxcore: connect C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:08.146 ThaliTest[2613:4754824] client: already connect(ing/ed) to C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:08.147 Thali,Test[2613:4754824] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 18:09:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:09:09.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:09:09.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:09:11.159 ThaliTest[2613:4754824] jxcore: connect C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:11.159 ThaliTest[2613:4754824] client: already connect(ing/ed) to C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:11.159 ThaliTest[2613:4754824] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 18:09:14.169 ThaliTest[2613:4754824] jxcore: connect C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:14.169 ThaliTest[2613:4754824] client: already connect(ing/ed) to C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:14.169 Thali,Test[2613:4754824] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 18:09:17.173 ThaliTest[2613:4754824] jxcore: connect C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:17.174 ThaliTest[2613:4754824] client: already connect(ing/ed) to C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:09:17.174 Thali,Test[2613:4754824] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 165 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-31 18:09:22.116 ThaliTest[2613:4755620] client session: not connected C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:09:22.116 ThaliTest[2613:4755620] client session: onLinkFailure: C1217920-C4F0-4779-A4B2-BE1967CE79BC
2016-03-31 18:09:22.1,16 ThaliTest[2613:4755620] client session: disconnect
2016-03-31 18:09:22.117 ThaliTest[2613:4755620] client session: stateChange:1->0 C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:09:22.119 ThaliTest[2613:4755620] client session: no connect callback (server initiated)
,2016-03-31 18:09:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:09:29.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:09:29.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:09:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:09:49.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:09:49.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:10:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:10:09.449 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:10:09.451 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:10:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:10:29.447 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:10:29.447 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:10:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:10:49.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:10:49.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:11:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:11:09.445 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:11:09.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:11:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:11:29.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:11:29.446 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:11:49.431 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:11:49.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:11:49.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:12:09.431 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:12:09.443 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:12:09.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:12:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:12:29.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:12:29.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:12:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:12:49.443 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:12:49.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:13:09.431 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:13:09.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:13:09.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:13:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:13:29.445 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:13:29.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:13:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:13:49.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:13:49.445 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:14:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:14:09.448 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:14:09.448 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:14:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:14:29.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:14:29.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:14:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:14:49.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:14:49.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:15:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:15:09.448 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:15:09.448 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:15:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:15:29.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:15:29.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:15:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:15:49.446 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:15:49.447 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:16:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:16:09.445 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:16:09.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:16:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:16:29.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:16:29.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:16:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:16:49.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:16:49.446 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:17:09.431 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:17:09.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:17:09.443 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:17:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:17:29.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:17:29.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:17:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:17:49.445 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:17:49.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:18:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:18:09.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:18:09.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:18:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:18:29.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:18:29.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:18:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:18:49.443 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:18:49.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:19:09.431 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:19:09.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:19:09.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:19:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:19:29.448 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:19:29.449 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:19:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:19:49.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:19:49.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:20:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:20:09.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:20:09.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:20:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:20:29.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:20:29.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:20:49.431 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:20:49.448 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:20:49.449 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:21:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:21:09.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:21:09.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:21:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:21:29.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:21:29.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:21:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:22:00.013 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:22:00.013 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:22:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:22:09.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:22:09.445 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:22:29.431 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:22:29.445 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:22:29.446 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:22:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:22:49.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:22:49.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:23:09.431 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:23:09.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:23:09.443 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:23:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:23:29.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:23:29.445 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:23:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:23:49.443 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:23:49.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:24:09.431 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:24:09.447 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:24:09.448 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:24:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:24:29.448 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:24:29.449 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:24:49.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:24:49.448 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:24:49.449 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:25:09.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:25:09.450 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:25:09.450 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
,2016-03-31 18:25:29.432 ThaliTest[2613:4754653] multipeer manager: restart client
,2016-03-31 18:25:29.444 ThaliTest[2613:4754653] client: found existing peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:25:29.444 ThaliTest[2613:4754653] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8

```
