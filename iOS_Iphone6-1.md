#### Test 648099369ce4518_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0FD991B3-B72A-4AEA-8EE2-8AFE5A13F9AD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0FD991B3-B72A-4AEA-8EE2-8AFE5A13F9AD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49970"
,(lldb)     command script import "/tmp/0FD991B3-B72A-4AEA-8EE2-8AFE5A13F9AD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 18:03:36.825 ThaliTest[2554:4718631] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E528CE56-B506-4BBF-9799-11CFD885E14F/Library/Cookies/Cookies.binarycookies
,2016-03-31 18:03:37.057 ThaliTest[2554:4718631] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 18:03:37.058 ThaliTest[2554:4718631] Multi-tasking -> Device: YES, App: YES
,2016-03-31 18:03:37.075 ThaliTest[2554:4718631] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 18:03:37.857 ThaliTest[2554:4718631] Using UIWebView
,2016-03-31 18:03:37.861 ThaliTest[2554:4718631] [CDVTimer][handleopenurl] 0.142992ms
2016-03-31 18:03:37.863 ThaliTest[2554:4718631] [CDVTimer][intentandnavigationfilter] 2.135992ms
2016-03-31 18:03:37.864 ThaliTest[2554:4718631] [CDVTimer][gesturehandler] 0.093043ms
2016-03-31 18:03:37.864 ThaliTest[2554:4718631] [CDVTimer][TotalPluginStartup] 2.815962ms
,2016-03-31 18:03:41.019 ThaliTest[2554:4718631] Resetting plugins due to page load.
,2016-03-31 18:03:42.413 ThaliTest[2554:4718631] Finished load of: file:///var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/index.html
,2016-03-31 18:03:42.573 ThaliTest[2554:4718631] JXcore Cordova plugin initializing
,2016-03-31 18:03:42.574 ThaliTest[2554:4718801] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 18:03:49.468 ThaliTest[2554:4718801] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 18:03:49.469 ThaliTest[2554:4718801] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 18:03:49.469 ThaliTest[2554:4,718801] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 18:03:49.471 ThaliTest[2554:4718801] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9813A8C8-F10E-4091-B036-2C090BA8CECE/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55889
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55891
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
,DEBUG createNativeListener: listening 55894
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
DEBUG createNativeListener: listening 55898
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 55903
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
DEBUG createNativeListener: listening 55907
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
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
,DEBUG createNativeListener: listening 55911
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
DEBUG createNativeListener: listening 55915
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
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
DEBUG createNativeListener: listening 55919
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
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creati,ng incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
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
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 55971
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
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55975
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
ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises
,# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
# teardown
,# setup
,# 21. basic
,ok 75 sane
# teardown
,# setup
,# 22. another
,ok 76 sane
,# teardown
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
DEBUG createNativeListener: listening 55987
2016-03-31 18:06:25.336 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.336 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
,2016-03-31 18:06:25.338 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.339 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
# teardown
,2016-03-31 18:06:25.508 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:25.509 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:06:25.509 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
2016-03-31 18:06:25.509 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.509 ThaliTest[2554,:4718801] jxcore: stopListeningForAdvertisements: success
ok 94 error should be null
ok 95 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55989
2016-03-31 18:06:25.750 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements
,2016-03-31 18:06:25.752 ThaliTest[2554:4718801] multipeer manager: start client restart timer: 0x17d98f10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:06:25.752 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
ok 97 error should be null
2016-03-31 18:06:25.759 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-31 18:06:25.759 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements: success
ok 98 error should be null
ok 99 error should be null
# teardown
,2016-03-31 18:06:25.991 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:25.991 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:06:25.991 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
2016-03-31 18:06:25.991 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
2016-03-31 18:06:25.991 ThaliTest[2554:4718801] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.992 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 100 error should be null
ok 101 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55991
,2016-03-31 18:06:26.209 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:06:26.209 ThaliTest[2554:4718801] server: starting C1217920-C4F0-4779-A4B2-BE1967CE79BC:1
2016-03-31 18:06:26.209 ThaliTest[2554:4718801] multipeer manager: start client restart timer: 0x17d98f10
,2016-03-31 18:06:26.210 ThaliTest[2554:4718801] THEMultipeerManager initialized peer C1217920-C4F0-4779-A4B2-BE1967CE79BC:1
2016-03-31 18:06:26.210 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
,2016-03-31 18:06:26.237 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:06:26.237 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:06:26.237 ThaliTest[2554:4718801] multipeer manager: stop client timer
2016-03-31 18:06:26.238 ThaliTest[2554:4718801] server: starting C1217920-C4F0-4779-A4B2-BE1967CE79BC:2
2016-03-31 18:06:26.238 ThaliTest[2554:4718801] multipeer manager: start client restart timer: 0x17d98f10
2016-03-31 18:06:26.238 ThaliTest[2554:4718801] THEMultipeerManager initialized peer C1217920-C4F0-4779-A4B2-BE1967CE79BC:2
2016-03-31 18:06:26.238 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
ok 105 error should be null
,# teardown
,2016-03-31 18:06:26.723 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:26.723 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:06:26.723 ThaliTest[2554:4718801] multipeer manager: stop client timer
2016-03-31 18:06:26.723 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
2016-03-31 18:06:26.723 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:26.724 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 106 error should be null
,ok 107 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55996
2016-03-31 18:06:33.113 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:33.114 ThaliTest[2554:4718801] THEMultipeerManager stoppi,ng peer
2016-03-31 18:06:33.114 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
ok 109 error should be null
2016-03-31 18:06:33.115 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:33.115 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:06:33.115 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
ok 110 error should be null
ok 111 error should be null
# teardown
,2016-03-31 18:06:41.823 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:41.823 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:06:41.823 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 18:06:41.823 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:41.824 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
ok 112 error should be null
ok 113 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55998
ok 114 first call should succeed
ok 115 first call should succeed
,ok 116 specific error should be returned
# teardown
,2016-03-31 18:07:03.537 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:07:03.538 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:07:03.538 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 18:07:03.538 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:03.539 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
ok 117 error should be null
ok 118 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56000
2016-03-31 18:07:05.586 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements
2016-03-31 18:07:05.586 ThaliTest[2554:4718801] multipeer manager: start client restart timer: 0x17d98f10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:07:05.587 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements: success
,2016-03-31 18:07:05.592 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:07:05.592 ThaliTest[2554:4718801] server: starting C1217920-C4F0-4779-A4B2-BE1967CE79BC:3
2016-03-31 18:07:05.592 ThaliTest[2554:4718801] THEMultipee,rManager initialized peer C1217920-C4F0-4779-A4B2-BE1967CE79BC:3
2016-03-31 18:07:05.592 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening: success
ok 119 called only once
ok 120 discovery state matches
ok 121 advertising state matches
# teardown
,2016-03-31 18:07:05.891 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:07:05.891 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:07:05.891 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 18:07:05.891 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
2016-03-31 18:07:05.891 ThaliTest[2554:4718801] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:05.892 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 122 error should be null
ok 123 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 124 should be called once
,ok 125 should not have been called more than once
# teardown
,ok 126 error should be null
ok 127 error should be null
# setup
,# 33. can get the network status
,ok 128 network status should have certain non-empty properties
# teardown
,ok 129 error should be null
ok 130 error should be null
,# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 131 host address should match
ok 132 port should match
,ok 133 host address should be null
,ok 134 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 135 error should be null
ok 136 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-31 18:07:41.629 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements
2016-03-31 18:07:41.630 ThaliTest[2554:4718801] multipeer manager: start client restart timer: 0x17d98f10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:07:41.630 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
2016-03-31 18:07:41.631 ThaliTes,t[2554:4718801] jxcore: stopListeningForAdvertisements
2016-03-31 18:07:41.631 ThaliTest[2554:4718801] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:41.631 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
ok 138 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 18:07:41.872 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:41.873 ThaliTest[2554:47188,01] jxcore: stopListeningForAdvertisements: success
ok 139 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:07:41.873 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:07:41.873 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:07:41.873 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 18:07:59.926 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements
2016-03-31 18:07:59.926 ThaliTest[2554:4718801] multipeer manager: start client restart timer: 0x17d98f10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:07:59.927 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements without error
2016-03-31 18:07:59.927 ThaliTes,t[2554:4718801] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:07:59.928 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-31 18:08:00.860 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
2016-03-31 18:08:00.860 ThaliTest[2554:4718801] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-31 18:08:00.861 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
ok 143 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:08:00.862 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:00.862 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:08:00.862 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 18:08:01.317 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:01.318 ThaliTest[2554:4718801] server: starting C1217920-C4F0-4779-A4B2-BE1967CE79BC:4
2016-03-31 18:08:01.318 ThaliTest[2554:4718801] multipeer m,anager: start client restart timer: 0x17d98f10
2016-03-31 18:08:01.318 ThaliTest[2554:4718801] THEMultipeerManager initialized peer C1217920-C4F0-4779-A4B2-BE1967CE79BC:4
2016-03-31 18:08:01.318 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening: success
ok 145 Can call startUpdateAdvertisingAndListening without error
2016-03-31 18:08:01.319 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:01.319 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
,2016-03-31 18:08:01.319 ThaliTest[2554:4718801] multipeer manager: stop client timer
2016-03-31 18:08:01.322 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
ok 146 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 18:08:01.745 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 18:08:01.746 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
ok 147 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 18:08:01.747 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:01.747 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:08:01.747 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 18:08:02.259 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:02.259 ThaliTest[2554:4718801] server: starting C1217920-C4F0-4779-A4B2-BE1967CE79BC:5
2016-03-31 18:08:02.260 ThaliTest[2554:4718801] multipeer manager: start client restart timer: 0x17d98f10
2016-03-31 18:08:02.260 ThaliTest[2554:4718801] THEMultipeerManager initialized peer C1217920-C4F0-4779-A4B2-BE1967CE79BC:5
2016-03-31 18:08:02.260 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 149 Can call startUpdateAdvertisingAndListening without error
2016-03-31 18:08:02.261 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:02.261 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
,2016-03-31 18:08:02.261 ThaliTest[2554:4718801] multipeer manager: stop client timer
2016-03-31 18:08:02.264 ThaliTest[2554:4718801] server: starting C1217920-C4F0-4779-A4B2-BE1967CE79BC:6
2016-03-31 18:08:02.264 ThaliTest[2554:4718801] multipeer manager: start client restart timer: 0x17d98f10
2016-03-31 18:08:02.264 ThaliTest[2554:4718801] THEMultipeerManager initialized peer C1217920-C4F0-4779-A4B2-BE1967CE79BC:6
2016-03-31 18:08:02.265 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 18:08:02.374 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 18:08:02.375 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
ok 151 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:08:02.375 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:02.375 ThaliTest[2554:4718801,] THEMultipeerManager stopping peer
2016-03-31 18:08:02.375 ThaliTest[2554:4718801] multipeer manager: stop client timer
2016-03-31 18:08:02.375 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-31 18:08:02.830 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:02.830 ThaliTest[2554:4718801] server: starting C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:08:02.831 ThaliTest[2554:4718801] multipeer manager: start client restart timer: 0x17d98f10
2016-03-31 18:08:02.831 ThaliTest[2554:4718801] THEMultipeerManager initialized peer C1217920-C4F0-4779-A4B2-BE1967CE79BC:7
2016-03-31 18:08:02.831 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening: success
ok 153 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 18:08:02.832 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-31 18:08:02.832 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error
,2016-03-31 18:08:07.622 ThaliTest[2554:4718631] client: found new peer: 2467FBFF-8374-4C28-A08D-056504009757:7
,ok 155 peers must be an array
,ok 156 peers must not be zero-length
,ok 157 peer must have peerIdentifier
,ok 158 peerIdentifier must be a string
,ok 159 peer must have peerAvailable
,ok 160 peer must have pleaseConnect
,# teardown
,2016-03-31 18:08:08.065 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 18:08:08.066 ThaliTest[2554:4718801] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 18:08:08.067 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:08.067 ThaliTest[2554:4718801] THEMultipeerManager stopping peer
2016-03-31 18:08:08.067 ThaliTest[2554:4718801] multipeer manager: stop client timer
2016-03-31 18:08:08.067 ThaliTest[2554:4718801] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. Can connect to a remote peer
,2016-03-31 18:08:09.386 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:09.386 ThaliTest[2554:4718801] server: starting C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:08:09.386 ThaliTest[2554:4718801] multipeer m,anager: start client restart timer: 0x17d98f10
2016-03-31 18:08:09.386 ThaliTest[2554:4718801] THEMultipeerManager initialized peer C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
2016-03-31 18:08:09.386 ThaliTest[2554:4718801] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 163 Can call startUpdateAdvertisingAndListening without error
2016-03-31 18:08:09.387 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 18:08:09.388 ThaliTest[2554:4718801] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-31 18:08:10.207 ThaliTest[2554:4718631] client: found new peer: 2467FBFF-8374-4C28-A08D-056504009757:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2467FBFF-8374-4C28-A08D-056504009,757:7","pleaseConnect":0}]
2016-03-31 18:08:10.208 ThaliTest[2554:4718801] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:10.208 ThaliTest[2554:4718801] client session: connect
2016-03-31 18:08:10.208 ThaliTest[2554:4718801] client session: stateChange:0->1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:10.723 ThaliTest[2554:4718631] client: found new peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F11AAA28-318B-4CE4-B684-469230DD4996:8","pleaseConnect":0}]
,2016-03-31 18:08:11.316 ThaliTest[2554:4719331] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:11.317 ThaliTest[2554:4719331] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:11.317 ThaliTest[2554:4719331] client session: disconnect
2016-03-31 18:08:11.317 ThaliTest[2554:4719331] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:11.317 ThaliTest[2554:4719331] client session: fireConnectCallback: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:11.317 ThaliTest[2554:4719331] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 9
,2016-03-31 18:08:11.580 ThaliTest[2554:4718631] multipeer session: reset timer
2016-03-31 18:08:11.580 ThaliTest[2554:4718631] server: rejecting invitation from 2467FBFF-8374-4C28-A08D-056504009757 due to previous generation (C1217920-C4F0-4779-A4B2-BE196,7CE79BC:8 != C1217920-C4F0-4779-A4B2-BE1967CE79BC:7)
,2016-03-31 18:08:14.320 ThaliTest[2554:4718801] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:14.321 ThaliTest[2554:4718801] client session: connect
2016-03-31 18:08:14.321 ThaliTest[2554:4718801] client session: stateChange:0->1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:14.439 ThaliTest[2554:4719331] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:14.439 ThaliTest[2554:4719331] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
,2016-03-31 18:08:14.439 ThaliTest[2554:4719331] client session: disconnect
2016-03-31 18:08:14.439 ThaliTest[2554:4719331] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:14.440 ThaliTest[2554:4719331] client session: fireConnectCallback: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:14.440 ThaliTest[2554:4719331] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 18:08:17.453 ThaliTest[2554:4718801] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:17.453 ThaliTest[2554:4718801] client session: connect
2016-03-31 18:08:17.453 ThaliTest[2554:4718801] client session: stateChange:0->1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:18.390 ThaliTest[2554:4719352] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:18.391 ThaliTest[2554:4719352] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:18.391 ThaliTest[2554:4719352] client session: disconnect
2016-03-31 18:08:18.391 ThaliTest[2554:4719352] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:18.391 ThaliTest[2554:4719352] client session: fireConnectCallb,ack: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:18.391 ThaliTest[2554:4719352] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 18:08:21.396 ThaliTest[2554:4718801] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:21.396 ThaliTest[2554:4718801] client session: connect
2016-03-31 18:08:21.397 ThaliTest[2554:4718801] client session: stateChange:0->1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:21.680 ThaliTest[2554:4719351] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:21.680 ThaliTest[2554:4719351] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:21.6,80 ThaliTest[2554:4719351] client session: disconnect
2016-03-31 18:08:21.680 ThaliTest[2554:4719351] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:21.680 ThaliTest[2554:4719351] client session: fireConnectCallb,ack: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:21.680 ThaliTest[2554:4719351] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 18:08:23.511 ThaliTest[2554:4718631] multipeer session: reset timer
2016-03-31 18:08:23.511 ThaliTest[2554:4718631] server: disconnecting to refresh session (2467FBFF-8374-4C28-A08D-056504009757)
2016-03-31 18:08:23.511 ThaliTest[2554:4718631] server: rejecting invitation from 2467FBFF-8374-4C28-A08D-056504009757 due to previous generation (C1217920-C4F0-4779-A4B2-BE1967CE79BC:8 != C1217920-C4F0-4779-A4B2-BE1967CE79BC:7)
,2016-03-31 18:08:24.693 ThaliTest[2554:4718801] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:24.694 ThaliTest[2554:4718801] client session: connect
2016-03-31 18:08:24.694 ThaliTest[2554:4718801] client session: stateChange:0->1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:24.875 ThaliTest[2554:4719352] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:24.875 ThaliTest[2554:4719352] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:24.875 ThaliTest[2554:4719352] client session: disconnect
,2016-03-31 18:08:24.875 ThaliTest[2554:4719352] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:24.876 ThaliTest[2554:4719352] client session: fireConnectCallback: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:24.876 ThaliTest[2554:4719352] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 18:08:27.884 ThaliTest[2554:4718801] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:27.885 ThaliTest[2554:4718801] client session: connect
2016-03-31 18:08:27.885 ThaliTest[2554:4718801] client session: stateChange:0->,1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:28.003 ThaliTest[2554:4719347] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:28.003 ThaliTest[2554:4719347] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:28.003 ThaliTest[2554:4719347] client session: disconnect
2016-03-31 18:08:28.003 ThaliTest[2554:4719347] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:28.004 ThaliTest[2554:4719347] client session: fireConnectCallb,ack: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:28.004 ThaliTest[2554:4719347] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 18:08:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:08:29.397 ThaliTest[2554:4718631] client: found updated peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:29.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2467FBFF-8374-4C28-A08D-056504009757:8","pleaseConnect":0}]
,2016-03-31 18:08:31.018 ThaliTest[2554:4718801] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:31.019 ThaliTest[2554:4718801] client session: connect
2016-03-31 18:08:31.019 ThaliTest[2554:4718801] client session: stateChange:0->,1 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:08:31.163 ThaliTest[2554:4719352] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:31.163 ThaliTest[2554:4719352] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
,2016-03-31 18:08:31.163 ThaliTest[2554:4719352] client session: disconnect
,2016-03-31 18:08:31.164 ThaliTest[2554:4719352] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:31.164 ThaliTest[2554:4719352] client session: fireConnectCallback: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:31.164 ThaliTest[2554:4719352] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 18:08:34.173 ThaliTest[2554:4718801] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:34.174 ThaliTest[2554:4718801] client session: connect
2016-03-31 18:08:34.174 ThaliTest[2554:4718801] client session: stateChange:0->,1 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:08:34.311 ThaliTest[2554:4719352] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:08:34.312 ThaliTest[2554:4719352] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:34.313 ThaliTest[2554:4719352] client session: disconnect
2016-03-31 18:08:34.313 ThaliTest[2554:4719352] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:34.313 ThaliTest[2554:4719352] client session: fireConnectCallback: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:34.313 ThaliTest[2554:4719352] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 18:08:36.348 ThaliTest[2554:4718631] multipeer session: reset timer
2016-03-31 18:08:36.348 ThaliTest[2554:4718631] server: disconnecting to refresh session (2467FBFF-8374-4C28-A08D-056504009757)
2016-03-31 18:08:36.348 ThaliTest[2554:4718631] server: rejecting invitation from 2467FBFF-8374-4C28-A08D-056504009757 due to previous generation (C1217920-C4F0-4779-A4B2-BE1967CE79BC:8 != C1217920-C4F0-4779-A4B2-BE1967CE79BC:7)
,2016-03-31 18:08:37.315 ThaliTest[2554:4718801] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:37.316 ThaliTest[2554:4718801] client session: connect
2016-03-31 18:08:37.316 ThaliTest[2554:4718801] client session: stateChange:0->1 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:08:37.456 ThaliTest[2554:4719351] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:37.456 ThaliTest[2554:4719351] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:37.4,56 ThaliTest[2554:4719351] client session: disconnect
2016-03-31 18:08:37.456 ThaliTest[2554:4719351] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:37.457 ThaliTest[2554:4719351] client session: fireConnectCallback: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:37.457 ThaliTest[2554:4719351] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 1
,2016-03-31 18:08:40.469 ThaliTest[2554:4718801] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:40.469 ThaliTest[2554:4718801] client session: connect
2016-03-31 18:08:40.469 ThaliTest[2554:4718801] client session: stateChange:0->,1 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:08:40.571 ThaliTest[2554:4719385] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:40.573 ThaliTest[2554:4719385] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:40.5,73 ThaliTest[2554:4719385] client session: disconnect
2016-03-31 18:08:40.573 ThaliTest[2554:4719385] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:40.573 ThaliTest[2554:4719385] client session: fireConnectCallback: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:40.573 ThaliTest[2554:4719385] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 165 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-31 18:08:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:08:49.399 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:49.399 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:09:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:09:09.398 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:09:09.402 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:09:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:09:29.397 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:09:29.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:09:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:09:49.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:09:49.397 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:10:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:10:09.395 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:10:09.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:10:29.388 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:10:29.397 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:10:29.398 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:10:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:10:49.395 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:10:49.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:11:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:11:09.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:11:09.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:11:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:11:29.397 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:11:29.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:11:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:11:49.397 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:11:49.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:12:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:12:09.395 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:12:09.395 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:12:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:12:29.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:12:29.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:12:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:12:49.399 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:12:49.402 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:13:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:13:09.399 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:13:09.400 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:13:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:13:29.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:13:29.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:13:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:13:49.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:13:49.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:14:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:14:09.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:14:09.398 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:14:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:14:29.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:14:29.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:14:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:14:49.395 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:14:49.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:15:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:15:09.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:15:09.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:15:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:15:29.399 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:15:29.399 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:15:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:15:49.400 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:15:49.400 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:16:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:16:09.400 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:16:09.400 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:16:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:16:29.397 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:16:29.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:16:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:16:49.397 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:16:49.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:17:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:17:09.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:17:09.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:17:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:17:29.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:17:29.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:17:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:17:49.399 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:17:49.403 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:18:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:18:09.397 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:18:09.398 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:18:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:18:29.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:18:29.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:18:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:18:49.398 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:18:49.398 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:19:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:19:09.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:19:09.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:19:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:19:29.400 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:19:29.400 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:19:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:19:49.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:19:49.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:20:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:20:09.397 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:20:09.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:20:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:20:29.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:20:29.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:20:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:20:49.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:20:49.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:21:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:21:09.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:21:09.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:21:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:21:29.399 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:21:29.399 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:21:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:21:49.398 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:21:49.399 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:22:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:22:09.400 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:22:09.400 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:22:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:22:29.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:22:29.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:22:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:22:49.399 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:22:49.400 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:23:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:23:09.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:23:09.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:23:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:23:29.396 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:23:29.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:23:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:23:49.399 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
,2016-03-31 18:23:49.401 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:24:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:24:09.399 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:24:09.399 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:24:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:24:29.397 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:24:29.397 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:24:49.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:24:49.395 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:24:49.396 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:25:09.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:25:09.399 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:25:09.400 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
,2016-03-31 18:25:29.387 ThaliTest[2554:4718631] multipeer manager: restart client
,2016-03-31 18:25:29.399 ThaliTest[2554:4718631] client: found existing peer: F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:25:29.400 ThaliTest[2554:4718631] client: found existing peer: 2467FBFF-8374-4C28-A08D-056504009757:8

```
