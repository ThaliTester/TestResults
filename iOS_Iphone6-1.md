#### Test 64613803d18c8d9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B2B555ED-AAFA-4E26-A79D-62ED2235A5D7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B2B555ED-AAFA-4E26-A79D-62ED2235A5D7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50046"
,(lldb)     command script import "/tmp/B2B555ED-AAFA-4E26-A79D-62ED2235A5D7/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 07:17:18.761 ThaliTest[2582:4801765] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/787BECB6-1A96-4EDC-9485-8DC91D340B17/Library/Cookies/Cookies.binarycookies
,2016-04-01 07:17:18.993 ThaliTest[2582:4801765] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 07:17:18.994 ThaliTest[2582:4801765] Multi-tasking -> Device: YES, App: YES
,2016-04-01 07:17:19.009 ThaliTest[2582:4801765] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 07:17:19.784 ThaliTest[2582:4801765] Using UIWebView
2016-04-01 07:17:19.786 ThaliTest[2582:4801765] [CDVTimer][handleopenurl] 0.128031ms
2016-04-01 07:17:19.788 ThaliTest[2582:4801765] [CDVTimer][intentandnavigationfilter] 2.286971ms
2016-04-01 07:17:19.789 ThaliTest[2582:4801765] [CDVTimer][gesturehandler] 0.104010ms
2016-04-01 07:17:19.789 ThaliTest[2582:4801765] [CDVTimer][TotalPluginStartup] 2.972960ms
,2016-04-01 07:17:22.920 ThaliTest[2582:4801765] Resetting plugins due to page load.
,2016-04-01 07:17:24.170 ThaliTest[2582:4801765] Finished load of: file:///var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/index.html
,2016-04-01 07:17:24.331 ThaliTest[2582:4801765] JXcore Cordova plugin initializing
2016-04-01 07:17:24.331 ThaliTest[2582:4801919] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 07:17:31.346 ThaliTest[2582:4801919] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 07:17:31.347 ThaliTest[2582:4801919] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 07:17:31.347 ThaliTest[2582:4,801919] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 07:17:31.348 ThaliTest[2582:4801919] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB937F1-BEA5-4EC1-B428-AF35041AC73F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-01 07:17:36.930 ThaliTest[2582:4801765] THREAD WARNING: ['JXcore'] took '5276.937012' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56116
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56118
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
DEBUG createNativeListener: listening 56121
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
,ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56125
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
DEBUG createNativeListener: listening 56130
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
DEBUG createNativeListener: listening 56134
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56138
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
DEBUG createNativeListener: listening 56142
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
,ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56146
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
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG cr,eateNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 56198
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
DEBUG createNativeListener: listening 56202
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
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
,ok 52 secondPromise result
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
,[{"uuid":"fb907fa7-6bbb-4685-a83b-630e712f1cec","data":"custom data"},{"uuid":"2116515a-89f8-4ac6-81c4-f1910b261345","data":"custom data"},{"uuid":"0aa21398-7b4c-4999-b9cc-207fff665ddf","data":"custom data"},{"uuid":"096b47f0-b3ca-42e2-86de-efb223a755a4",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83 participant data matches
ok 84 own UUID is found from the participants list
,# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 85 specific error should be returned
,# teardown
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
DEBUG createNativeListener: listening 56212
2016-04-01 07:20:43.505 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:43.506 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-01 07:20:43.507 ThaliTest[2582:4801919] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:43.508 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-01 07:20:43.659 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:43.659 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:20:43.659 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:20:43.659 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:43.660 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56214
,2016-04-01 07:20:44.030 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements
,2016-04-01 07:20:44.032 ThaliTest[2582:4801919] multipeer manager: start client restart timer: 0x165bcb50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:20:44.033 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-01 07:20:44.038 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:20:44.038 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-01 07:20:44.371 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:44.371 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:20:44.371 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
2016-04-01 07:20:44.371 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
2016-04-01 07:20:44.371 ThaliTest[2582:4801919] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:44.372 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56216
2016-04-01 07:20:44.912 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:20:44.912 ThaliTest[2582:4801919] server: starting 444A455A-C80E-416D-9E03-5D6FFDE7B60A:1
2016-04-01 07:20:44.912 ThaliTest[2582:4801919] multipeer manager: start client restart timer: 0x165bcb50
2016-04-01 07:20:44.913 ThaliTest[2582:4801919] THEMultipeerManager initialized peer 444A455A-C80E-416D-9E03-5D6FFDE7B60A:1
2016-04-01 07:20:44.913 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-01 07:20:44.919 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:20:44.919 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:20:44.919, ThaliTest[2582:4801919] multipeer manager: stop client timer
2016-04-01 07:20:44.919 ThaliTest[2582:4801919] server: starting 444A455A-C80E-416D-9E03-5D6FFDE7B60A:2
2016-04-01 07:20:44.920 ThaliTest[2582:4801919] multipeer manager: start client restart ,timer: 0x165bcb50
2016-04-01 07:20:44.920 ThaliTest[2582:4801919] THEMultipeerManager initialized peer 444A455A-C80E-416D-9E03-5D6FFDE7B60A:2
2016-04-01 07:20:44.920 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
# teardown
,2016-04-01 07:20:45.037 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:45.037 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:20:45.037 ThaliTest[2582:4801919] multipeer manager: stop client timer
2016-04-01 07:20:45.037 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
2016-04-01 07:20:45.038 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:45.038 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56221
2016-04-01 07:21:02.736 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:02.736 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:02.736 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
2016-04-01 07:21:02.737 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:02.738 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:02.738 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-01 07:21:03.000 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:03.000 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:03.000 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:21:03.001 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:03.001 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56223
ok 115 first call should succeed
,ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-01 07:21:05.372 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:05.373 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:05.373 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
2016-04-01 07:21:05.373 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:05.373 ThaliTest[2582,:4801919] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56225
2016-04-01 07:21:05.630 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements
2016-04-01 07:21:05.631 ThaliTest[2582:4801919] multipeer manager: sta,rt client restart timer: 0x165bcb50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:05.631 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements: success
,2016-04-01 07:21:05.638 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:05.638 ThaliTest[2582:4801919] server: starting 444A455A-C80E-416D-9E03-5D6FFDE7B60A:3
2016-04-01 07:21:05.638 ThaliTest[2582:4801919] THEMultipeerManager initialized peer 444A455A-C80E-416D-9E03-5D6FFDE7B60A:3
2016-04-01 07:21:05.638 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches,
# teardown
,2016-04-01 07:21:06.071 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:06.071 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:06.072 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:21:06.072 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:06.072 ThaliTest[2582:4801919] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:06.072 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 123 error should be null
ok 124 error should be null
# setup
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
ok 133 port should match
,ok 134 host address should be null
ok 135 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-01 07:21:41.107 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements
2016-04-01 07:21:41.108 ThaliTest[2582:4801919] multipeer manager: start client restart timer: 0x165bcb50
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:41.110 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAd,vertisements without error
2016-04-01 07:21:41.111 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:41.111 ThaliTest[2582:4801919] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:41.111 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 07:21:41.417 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:41.418 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:41.419 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:41.419 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:41.419 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-01 07:21:42.074 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements
2016-04-01 07:21:42.075 ThaliTest[2582:4801919] multipeer manager: start client restart timer: 0x165bcb50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:42.075 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-01 07:21:42.076 ThaliTes,t[2582:4801919] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:42.076 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-01 07:21:43.046 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:43.047 ThaliTest[2582:4801919] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:43.047 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:43.048 ThaliTest[2582:4801,919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:43.048 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:43.048 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-01 07:21:44.070 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:44.071 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-01 07:21:44.072 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:44.072 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 07:21:44.199 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:44.200 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:44.200 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:44.200 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:44.200 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-01 07:21:44.586 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:44.587 ThaliTest[2582:4801919] server: starting 444A455A-C80E-416D-9E03-5D6FFDE7B60A:4
2016-04-01 07:21:44.587 ThaliTest[2582:4801919] multipeer manager: start client restart timer: 0x165bcb50
2016-04-01 07:21:44.587 ThaliTest[2582:4801919] THEMultipeerManager initialized peer 444A455A-C80E-416D-9E03-5D6FFDE7B60A:4
2016-04-01 07:21:44.587 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:21:44.588 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:44.588 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
,2016-04-01 07:21:44.588 ThaliTest[2582:4801919] multipeer manager: stop client timer
2016-04-01 07:21:44.590 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-01 07:21:44.678 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:44.678 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:44.679 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:44.679 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:44.679 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-01 07:21:45.074 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:45.075 ThaliTest[2582:4801919] server: starting 444A455A-C80E-416D-9E03-5D6FFDE7B60A:5
2016-04-01 07:21:45.075 ThaliTest[2582:4801919] multipeer m,anager: start client restart timer: 0x165bcb50
2016-04-01 07:21:45.075 ThaliTest[2582:4801919] THEMultipeerManager initialized peer 444A455A-C80E-416D-9E03-5D6FFDE7B60A:5
2016-04-01 07:21:45.075 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:21:45.076 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:45.076 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
,2016-04-01 07:21:45.076 ThaliTest[2582:4801919] multipeer manager: stop client timer
2016-04-01 07:21:45.079 ThaliTest[2582:4801919] server: starting 444A455A-C80E-416D-9E03-5D6FFDE7B60A:6
2016-04-01 07:21:45.080 ThaliTest[2582:4801919] multipeer manager: start client restart timer: 0x165bcb50
2016-04-01 07:21:45.080 ThaliTest[2582:4801919] THEMultipeerManager initialized peer 444A455A-C80E-416D-9E03-5D6FFDE7B60A:6
2016-04-01 07:21:45.080 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-01 07:21:45.193 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 07:21:45.194 ThaliTest[2582:480191,9] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:45.194 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:45.195 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:45.195 ThaliTest[2582:4801919] multipeer manager: stop client timer
2016-04-01 07:21:45.195 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-01 07:21:45.597 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:45.597 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:45.597 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:21:45.598 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:45.598 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:21:45.598 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-01 07:22:08.671 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:22:08.672 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:22:08.673 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:22:08.673 ThaliTest[2582:48019,19] THEMultipeerManager stopping peer
2016-04-01 07:22:08.673 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-01 07:22:19.422 ThaliTest[2582:4801919] jxcore: connect foo
2016-04-01 07:22:19.423 ThaliTest[2582:4801919] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-01 07:22:19.637 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:22:19.637 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
2016-04-01 07:22:19.635 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:22:19.636 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:22:19.637 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-01 07:22:20.374 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:22:20.374 ThaliTest[2582:4801919] server: starting 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:22:20.375 ThaliTest[2582:4801919] multipeer m,anager: start client restart timer: 0x165bcb50
2016-04-01 07:22:20.375 ThaliTest[2582:4801919] THEMultipeerManager initialized peer 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:22:20.375 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-01 07:22:20.376 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 07:22:20.376 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-01 07:22:21.377 ThaliTest[2582:4801765] client: found new peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:21.377 ThaliTest[2582:4801765] client: found new peer: A956A86E-53B4-4DBF-B193-1271D200C497:7
,ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-01 07:22:21.490 ThaliTest[2582:4801765] client: found new peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:7
,2016-04-01 07:22:23.402 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 07:22:23.402 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:22:23.403 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:22:23.403 ThaliTest[2582:4801919] THEMultipeerManager stopping peer
2016-04-01 07:22:23.404 ThaliTest[2582:4801919] multipeer manager: stop client timer
20,16-04-01 07:22:23.404 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-01 07:22:24.515 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:22:24.516 ThaliTest[2582:4801919] server: starting 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:22:24.516 ThaliTest[2582:4801919] multipeer manager: start client restart timer: 0x165bcb50
2016-04-01 07:22:24.516 ThaliTest[2582:4801919] THEMultipeerManager initialized peer 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:22:24.516 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:22:24.517 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 07:22:24.517 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-01 07:22:25.341 ThaliTest[2582:4801765] client: found new peer: A956A86E-53B4-4DBF-B193-1271D200C497:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"A956A86E-53B4-4DBF-B193-1271D200C,497:7","pleaseConnect":0}]
2016-04-01 07:22:25.342 ThaliTest[2582:4801919] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:25.342 ThaliTest[2582:4801919] client: server will connect
2016-04-01 07:22:25.342 ThaliTest[2582:4801919], client session: reverseConnect
2016-04-01 07:22:25.343 ThaliTest[2582:4801919] client session: stateChange:0->1 A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:22:25.349 ThaliTest[2582:4801765] client: found new peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"15037E99-B9A2-4986-82B2-3AB5B64E2,CE2:7","pleaseConnect":0}]
,2016-04-01 07:22:26.574 ThaliTest[2582:4801765] client: found new peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"775127D1-BE71-46C7-B433-2FA7873DB,B8C:7","pleaseConnect":0}]
,2016-04-01 07:22:26.793 ThaliTest[2582:4802590] client session: not connected A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:26.794 ThaliTest[2582:4802590] client session: onLinkFailure: A956A86E-53B4-4DBF-B193-1271D200C497
2016-04-01 07:22:26.794 ThaliTest[2582:4802590] client session: disconnect
2016-04-01 07:22:26.795 ThaliTest[2582:4802590] client session: stateChange:1->0 A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:22:26.795 ThaliTest[2582:4802590] client session: no connect callback (server initiated)
,2016-04-01 07:22:26.859 ThaliTest[2582:4801765] multipeer session: reset timer
2016-04-01 07:22:26.859 ThaliTest[2582:4801765] server: rejecting invitation from 15037E99-B9A2-4986-82B2-3AB5B64E2CE2 due to previous generation (444A455A-C80E-416D-9E03-5D6FFDE7B60A:8 != 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7)
,2016-04-01 07:22:35.343 ThaliTest[2582:4801765] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 07:22:38.349 ThaliTest[2582:4801919] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:38.349 ThaliTest[2582:4801919] client: server will connect
2016-04-01 07:22:38.349 ThaliTest[2582:4801919] client session: reverseConnect
2016-04-01 07:22:38.349 ThaliTest[2582:4801919] client session: stateChange:0->1 A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:22:38.543 ThaliTest[2582:4802673] client session: not connected A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:38.543 ThaliTest[2582:4802673] client session: onLinkFailure: A956A86E-53B4-4DBF-B193-1271D200C497
2016-04-01 07:22:38.543 ThaliTest[2582:4802673] client session: disconnect
2016-04-01 07:22:38.543 ThaliTest[2582:4802673] client session: stateChange:1->0 A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:38.543 ThaliTest[2582:4802673] client session: no connect callback (server initiated)
,2016-04-01 07:22:39.834 ThaliTest[2582:4801765] multipeer session: reset timer
2016-04-01 07:22:39.835 ThaliTest[2582:4801765] server: disconnecting to refresh session (15037E99-B9A2-4986-82B2-3AB5B64E2CE2)
2016-04-01 07:22:39.835 ThaliTest[2582:4801765], server: rejecting invitation from 15037E99-B9A2-4986-82B2-3AB5B64E2CE2 due to previous generation (444A455A-C80E-416D-9E03-5D6FFDE7B60A:8 != 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7)
,2016-04-01 07:22:44.517 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:22:44.532 ThaliTest[2582:4801765] client: found updated peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:22:44.533 ThaliTest[2582:4801765] client: found updated peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:22:44.533 ThaliTest[2582:4801765] client: found updated peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8","pleaseConnec,t":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"A956A86E-53B4-4DBF-B193-1271D200C497:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"775127D1-BE71-46C7-B433-2FA7873DBB8C:8","pleaseConnect":0}]
,2016-04-01 07:22:48.350 ThaliTest[2582:4801765] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-04-01 07:22:51.356 ThaliTest[2582:4801919] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:51.357 ThaliTest[2582:4801919] client: server will connect
2016-04-01 07:22:51.357 ThaliTest[2582:4801919] client session: reverseConnect
2016-04-01 07:22:51.357 ThaliTest[2582:4801919] client session: stateChange:0->1 A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:22:51.465 ThaliTest[2582:4802666] client session: not connected A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:22:51.467 ThaliTest[2582:4802666] client session: onLinkFailure: A956A86E-53B4-4DBF-B193-1271D200C497
2016-04-01 07:22:51.4,67 ThaliTest[2582:4802666] client session: disconnect
2016-04-01 07:22:51.468 ThaliTest[2582:4802666] client session: stateChange:1->0 A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:22:51.468 ThaliTest[2582:4802666] client session: no connect callb,ack (server initiated)
,2016-04-01 07:22:52.668 ThaliTest[2582:4801765] multipeer session: reset timer
2016-04-01 07:22:52.669 ThaliTest[2582:4801765] server: disconnecting to refresh session (15037E99-B9A2-4986-82B2-3AB5B64E2CE2)
2016-04-01 07:22:52.669 ThaliTest[2582:4801765] server: rejecting invitation from 15037E99-B9A2-4986-82B2-3AB5B64E2CE2 due to previous generation (444A455A-C80E-416D-9E03-5D6FFDE7B60A:8 != 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7)
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-01 07:23:01.358 ThaliTest[2582:4801765] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 07:23:04.373 ThaliTest[2582:4801919] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:04.373 ThaliTest[2582:4801919] client: server will connect
2016-04-01 07:23:04.373 ThaliTest[2582:4801919] client session: reverseConnect
2016-04-01 07:23:04.373 ThaliTest[2582:4801919] client session: stateChange:0->1 A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:23:04.517 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:23:04.529 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:23:04.529 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:23:04.540 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:23:05.602 ThaliTest[2582:4801765] multipeer session: reset timer
2016-04-01 07:23:05.603 ThaliTest[2582:4801765] server: disconnecting to refresh session (15037E99-B9A2-4986-82B2-3AB5B64E2CE2)
2016-04-01 07:23:05.603 ThaliTest[2582:4801765] server: rejecting invitation from 15037E99-B9A2-4986-82B2-3AB5B64E2CE2 due to previous generation (444A455A-C80E-416D-9E03-5D6FFDE7B60A:8 != 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7)
,2016-04-01 07:23:14.374 ThaliTest[2582:4801765] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-01 07:23:17.381 ThaliTest[2582:4801919] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:17.381 ThaliTest[2582:4801919] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:17.381 Thali,Test[2582:4801919] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 07:23:18.743 ThaliTest[2582:4801765] multipeer session: reset timer
2016-04-01 07:23:18.743 ThaliTest[2582:4801765] server: disconnecting to refresh session (15037E99-B9A2-4986-82B2-3AB5B64E2CE2)
2016-04-01 07:23:18.743 ThaliTest[2582:4801765], server: rejecting invitation from 15037E99-B9A2-4986-82B2-3AB5B64E2CE2 due to previous generation (444A455A-C80E-416D-9E03-5D6FFDE7B60A:8 != 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7)
,2016-04-01 07:23:20.385 ThaliTest[2582:4801919] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:20.386 ThaliTest[2582:4801919] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:20.386 ThaliTest[2582:4801919] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 07:23:23.390 ThaliTest[2582:4801919] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:23.390 ThaliTest[2582:4801919] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:23.390 ThaliTest[2582:4801919] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 07:23:24.517 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:23:24.532 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:23:24.533 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:23:24.533 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:23:26.394 ThaliTest[2582:4801919] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:26.394 ThaliTest[2582:4801919] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:26.395 ThaliTest[2582:4801919] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 07:23:29.405 ThaliTest[2582:4801919] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:29.405 ThaliTest[2582:4801919] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:29.405 ThaliTest[2582:4801919] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 07:23:32.372 ThaliTest[2582:4801765] multipeer session: reset timer
2016-04-01 07:23:32.372 ThaliTest[2582:4801765] server: disconnecting to refresh session (15037E99-B9A2-4986-82B2-3AB5B64E2CE2)
2016-04-01 07:23:32.372 ThaliTest[2582:4801765] server: rejecting invitation from 15037E99-B9A2-4986-82B2-3AB5B64E2CE2 due to previous generation (444A455A-C80E-416D-9E03-5D6FFDE7B60A:8 != 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7)
,2016-04-01 07:23:32.413 ThaliTest[2582:4801919] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:32.413 ThaliTest[2582:4801919] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:32.413 ThaliTest[2582:4801919] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
    operator: fail
,  ...
,# teardown
,2016-04-01 07:23:37.379 ThaliTest[2582:4803042] client session: not connected A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:23:37.379 ThaliTest[2582:4803042] client session: onLinkFailure: A956A86E-53B4-4DBF-B193-1271D200C497
2016-04-01 07:23:37.379 ThaliTest[2582:4803042] client session: disconnect
2016-04-01 07:23:37.379 ThaliTest[2582:4803042] client session: stateChange:1->0 A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:23:37.381 ThaliTest[2582:4803042] client session: no connect callback (server initiated)
,2016-04-01 07:23:44.516 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:23:44.528 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:23:44.528 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:23:44.529 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:03.874 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 07:24:03.875 ThaliTest[2582:4801919] jxcore: stopListeningForAdvertisements: success
ok 178 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:24:03.875 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening
2016-04-01 07:24:03.875 ThaliTest[2582:480191,9] THEMultipeerManager stopping peer
2016-04-01 07:24:03.876 ThaliTest[2582:4801919] multipeer manager: stop client timer
2016-04-01 07:24:03.876 ThaliTest[2582:4801919] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-01 07:24:07.728 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:24:07.728 ThaliTest[2582:4801919] server: starting 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:24:07.728 ThaliTest[2582:4801919] multipeer m,anager: start client restart timer: 0x165bcb50
2016-04-01 07:24:07.728 ThaliTest[2582:4801919] THEMultipeerManager initialized peer 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:24:07.729 ThaliTest[2582:4801919] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:24:07.729 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 07:24:07.730 ThaliTest[2582:4801919] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-01 07:24:08.907 ThaliTest[2582:4801765] client: found new peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:08.908 ThaliTest[2582:4801919] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:08.908 ThaliTest[2582:4801919] client session: connect
2016-04-01 07:24:08.908 ThaliTest[2582:4801919] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:24:08.912 ThaliTest[2582:4801765] client: found new peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:08.940 ThaliTest[2582:4801765] multipeer session: reset timer
2016-04-01 07:24:08.940 ThaliTest[2582:4801765] server: rejecting invitation from 15037E99-B9A2-4986-82B2-3AB5B64E2CE2 due to previous generation (444A455A-C80E-416D-9E03-5D6FFDE7B60A:9 != 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8)
,2016-04-01 07:24:09.840 ThaliTest[2582:4801765] client: found new peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:24:11.479 ThaliTest[2582:4803030] client session: p2p link connected
,2016-04-01 07:24:11.532 ThaliTest[2582:4803100] client session: stateChange:1->2 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:11.532 ThaliTest[2582:4803100] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:24:11.532 ThaliTest[2582:4803100] jxcore: connect: success
,2016-04-01 07:24:11.546 ThaliTest[2582:4801919] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:11.546 ThaliTest[2582:4801919] client: already connect(ing/ed) to 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:11.546 ThaliTest[2582:4801919] jxcore: connect: fail: Already connect(ing/ed)
ok 182 Expected error
ok 183 Null connection as expected
2016-04-01 07:24:11.547 ThaliTest[2582:4801919] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:11.547 ThaliTest[2582:4801919] client: already connect(ing/ed) to 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:11.547 ThaliTest[2582:4801919] jxcore: connect: fail: Already connect(ing/ed)
ok 184 Expected error
ok 185 Null connection as expected
# te,ardown
2016-04-01 07:24:11.550 ThaliTest[2582:4801765] client: relay established
2016-04-01 07:24:11.550 ThaliTest[2582:4801765] client: new accepted socket: 0x18460810
,2016-04-01 07:24:27.729 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:24:27.740 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:27.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:27.741 ThaliTest[2582:4801765] client: found updated peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:24:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:24:47.745 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:24:47.748 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:47.748 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:25:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:25:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:25:27.742 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:25:27.743 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:25:27.743 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:25:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:25:47.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:25:47.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:25:47.743 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:26:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:26:07.745 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:26:07.746 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:26:07.746 ThaliTest[2582:4801765] client: found updated peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:26:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:26:27.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:26:27.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:26:27.741 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:26:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:26:47.742 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:26:47.742 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:26:47.742 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:27:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:27:07.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:27:07.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:27:07.741 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:27:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:27:27.744 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:27:27.745 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:27:27.748 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:27:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:27:47.746 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:27:47.746 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:27:47.746 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:28:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:28:07.747 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:28:07.748 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:28:07.748 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:28:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:28:27.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:28:27.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:28:27.742 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:28:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:28:47.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:28:47.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:28:47.744 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:29:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:29:07.745 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:29:07.745 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:29:07.749 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:29:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:29:27.745 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:29:27.745 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:29:27.748 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:29:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:29:47.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:29:47.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:29:47.741 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:30:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:30:07.740 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:30:07.740 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:30:07.742 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:30:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:30:27.744 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:30:27.744 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:30:27.744 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:30:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:30:47.745 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:30:47.745 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:30:47.749 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:31:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:31:07.740 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:31:07.742 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:31:07.742 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:31:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:31:27.746 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:31:27.746 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:31:27.746 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:31:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:31:47.745 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:31:47.747 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:31:47.747 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:32:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:32:07.742 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:32:07.742 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:32:07.743 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:32:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:32:27.741 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:32:27.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:32:27.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:32:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:32:47.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:32:47.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:32:47.741 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:33:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:33:07.745 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:33:07.745 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:33:07.749 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:33:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:33:27.744 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:33:27.744 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:33:27.747 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:33:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:33:47.742 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:33:47.742 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:33:47.742 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:34:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:34:07.745 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:34:07.745 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:34:07.748 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:34:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:34:27.743 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:34:27.745 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:34:27.746 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:34:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:34:47.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:34:47.741 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:34:47.74,2 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:35:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:35:07.745 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:35:07.745 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:35:07.749 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:35:27.729 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:35:27.744 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:35:27.744 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:35:27.745 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:35:47.729 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:35:47.739 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:35:47.740 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:35:47.743 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:36:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:36:07.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:36:07.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:36:08.329 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:36:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:36:27.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:36:27.742 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:36:27.742 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:36:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:36:47.746 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:36:47.747 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:36:47.747 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:37:07.729 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:37:07.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:37:07.741 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:37:07.742 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:37:27.729 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:37:27.739 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:37:27.740 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:37:27.740 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:37:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:37:47.744 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:37:47.745 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:37:47.747 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:38:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:38:07.740 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:38:07.740 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:38:07.741 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:38:27.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:38:27.742 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:38:27.742 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:38:27.742 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:38:47.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:38:47.741 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:38:47.741 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:38:47.743 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:39:07.730 ThaliTest[2582:4801765] multipeer manager: restart client
,2016-04-01 07:39:07.742 ThaliTest[2582:4801765] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:39:07.742 ThaliTest[2582:4801765] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:39:07.742 ThaliTest[2582:4801765] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9

```
