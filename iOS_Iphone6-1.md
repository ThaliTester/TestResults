#### Test 646862831c69957_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646862831c69957/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/1249D04A-01AF-4DF3-BF7E-3FFE6B6CA9DC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1249D04A-01AF-4DF3-BF7E-3FFE6B6CA9DC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/646862831c69957/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646862831c69957/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49423"
,(lldb)     command script import "/tmp/1249D04A-01AF-4DF3-BF7E-3FFE6B6CA9DC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-30 22:17:07.061 ThaliTest[2455:4585828] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4996CA8B-B674-4157-BB77-16BCA263DE52/Library/Cookies/Cookies.binarycookies
,2016-03-30 22:17:07.297 ThaliTest[2455:4585828] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-30 22:17:07.298 ThaliTest[2455:4585828] Multi-tasking -> Device: YES, App: YES
,2016-03-30 22:17:07.313 ThaliTest[2455:4585828] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-30 22:17:08.091 ThaliTest[2455:4585828] Using UIWebView
2016-03-30 22:17:08.093 ThaliTest[2455:4585828] [CDVTimer][handleopenurl] 0.120997ms
2016-03-30 22:17:08.095 ThaliTest[2455:4585828] [CDVTimer][intentandnavigationfilter] 2.121031ms
2016-03-30 22:17:08.096 ThaliTest[2455:4585828] [CDVTimer][gesturehandler] 0.095963ms
2016-03-30 22:17:08.096 ThaliTest[2455:4585828] [CDVTimer][TotalPluginStartup] 2.758980ms
,2016-03-30 22:17:11.223 ThaliTest[2455:4585828] Resetting plugins due to page load.
,2016-03-30 22:17:12.635 ThaliTest[2455:4585828] Finished load of: file:///var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/index.html
,2016-03-30 22:17:12.791 ThaliTest[2455:4585828] JXcore Cordova plugin initializing
,2016-03-30 22:17:12.874 ThaliTest[2455:4585999] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-30 22:17:19.840 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-30 22:17:19.841 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-30 22:17:19.842 ThaliTest[2455:4585999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:17:19.844 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E2C3DBAA-EA35-4810-ADE0-A318D5A0F65E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54488
,ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54490
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
,DEBUG createNativeListener: listening 54493
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
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54497
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
DEBUG createNativeListener: listening 54502
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
DEBUG createNativeListener: listening 54506
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
DEBUG createNativeListener: listening 54510
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54514
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,ok 22 native server is nulled out
,ok 23 native server should be closed
,ok 24 incoming has been removed
,ok 25 Incoming should be done
,ok 26 The mux object should be closed
,ok 27 The mux stream should be closed
,DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54518
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
,DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG cr,eateNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNat,iveListener: new outgoing socket
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNat,iveListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBU,G createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG cr removed
eateNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
D,EBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54570
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
DEBUG createNativeListener: listening 54574
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
,ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
,ok 53 secondPromise result
,ok 54 secondPromise testValue
,ok 55 thirdPromise in promise
,ok 56 thirdPromise result
,ok 57 thirdPromise testValue
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
,ok 71 third
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
,ok 81 test participant has uuid
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
,DEBUG createNativeListener: listening 54586
2016-03-30 22:19:45.410 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:45.411 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
2016-03-30 22:19:45.412 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMob,ileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:45.412 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
# teardown
,2016-03-30 22:19:45.600 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:45.600 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:19:45.600 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:19:45.600 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:45.601 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54588
2016-03-30 22:19:45.961 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
,2016-03-30 22:19:45.963 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:19:45.964 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
ok 97 error should be null
2016-03-30 22:19:45.969 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:19:45.969 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
ok 98 error should be null
ok 99 error should be null
,# teardown
,2016-03-30 22:19:46.292 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:46.293 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:19:46.293 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:19:46.293 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
2016-03-30 22:19:46.293 ThaliTest[2455:4585999] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:19:46.294 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 100 error should be null
,ok 101 error should be null
,# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54590
2016-03-30 22:19:46.932 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:19:46.933 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:1
2016-03-30 22:19:46.933 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
2016-03-30 22:19:46.933 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:1
2016-03-30 22:19:46.933 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
2016-03-30 22:19:46.940 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:19:46.940 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:19:46.940, ThaliTest[2455:4585999] multipeer manager: stop client timer
2016-03-30 22:19:46.940 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:2
2016-03-30 22:19:46.941 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
2016-03-30 22:19:46.941 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:2
2016-03-30 22:19:46.941 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
ok 105 error should be null
# teardown
,2016-03-30 22:19:47.918 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:47.919 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:19:47.919 ThaliTest[2455:4585999] multipeer manager: stop client timer
20,16-03-30 22:19:47.919 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:19:47.919 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:47.920 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 106 error should be null
ok 107 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54595
2016-03-30 22:19:49.528 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:49.528 ThaliTest[2455:4585999] THEMultipeerManager stoppi,ng peer
2016-03-30 22:19:49.528 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
ok 109 error should be null
2016-03-30 22:19:49.530 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:49.530 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:19:49.530 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 110 error should be null
ok 111 error should be null
# teardown
,2016-03-30 22:19:49.901 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:49.901 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:19:49.901 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:19:49.901 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:49.902 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
ok 112 error should be null
ok 113 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54597
ok 114 first call should succeed
ok 115 first call should succeed
ok 116 specific error should be returned
# teardown
,2016-03-30 22:19:50.472 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:50.472 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:19:50.472 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:19:50.472 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:50.473 ThaliTest[2455,:4585999] jxcore: stopListeningForAdvertisements: success
ok 117 error should be null
ok 118 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54599
2016-03-30 22:19:51.050 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
2016-03-30 22:19:51.051 ThaliTest[2455:4585999] multipeer manager: sta,rt client restart timer: 0x16db8fb0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:19:51.051 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
,2016-03-30 22:19:51.056 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:19:51.057 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:3
2016-03-30 22:19:51.057 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:3
2016-03-30 22:19:51.057 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening: success
ok 119 called only once
ok 120 discovery state matches
ok 121 advertising state matches
# teardown
,2016-03-30 22:19:51.615 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:51.615 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:19:51.615 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:19:51.616 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
2016-03-30 22:19:51.616 ThaliTest[2455:4585999] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:51.616 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
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
ok 130 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 131 host address should match
ok 132 port should match
,ok 133 host address should be null
ok 134 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 135 error should be null
ok 136 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-30 22:20:16.649 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
2016-03-30 22:20:16.649 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:20:16.650 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
2016-03-30 22:20:16.651 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
2016-03-30 22:20:16.651 ThaliTest[2455:4585999] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:20:16.651 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
ok 138 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-30 22:20:16.852 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:20:16.853 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
ok 139 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:16.853 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:16.853 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:20:16.853 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-30 22:20:17.259 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
2016-03-30 22:20:17.259 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:20:17.260 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements without error
2016-03-30 22:20:17.260 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:20:17.261 ThaliTest[2455:4585999] jxcore: startListeningForAdv,ertisements: success
ok 142 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-30 22:20:17.491 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
2016-03-30 22:20:17.491 ThaliTest[2455:4585999] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:20:17.492 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-30 22:20:17.493 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:17.494 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:20:17.494 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-30 22:20:18.565 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:18.565 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:4
2016-03-30 22:20:18.565 ThaliTest[2455:4585999] multipeer m,anager: start client restart timer: 0x16db8fb0
2016-03-30 22:20:18.566 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:4
2016-03-30 22:20:18.566 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening: success
ok 145 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:20:18.566 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:18.566 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
,2016-03-30 22:20:18.566 ThaliTest[2455:4585999] multipeer manager: stop client timer
2016-03-30 22:20:18.570 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 146 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-30 22:20:18.702 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:20:18.702 ThaliTest[2455:45859,99] jxcore: stopListeningForAdvertisements: success
ok 147 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:18.703 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:18.703 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:20:18.703 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-30 22:20:19.180 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:19.180 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:5
2016-03-30 22:20:19.180 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
2016-03-30 22:20:19.180 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:5
2016-03-30 22:20:19.180 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 149 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:20:19.181 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:19.181 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
,2016-03-30 22:20:19.181 ThaliTest[2455:4585999] multipeer manager: stop client timer
2016-03-30 22:20:19.184 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:6
2016-03-30 22:20:19.184 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
2016-03-30 22:20:19.184 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:6
2016-03-30 22:20:19.184 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-30 22:20:19.351 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-30 22:20:19.353 ThaliTest[2455:458599,9] jxcore: stopListeningForAdvertisements: success
ok 151 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:19.353 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:19.353 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:20:19.353 ThaliTest[2455:4585999] multipeer manager: stop client timer
2016-03-30 22:20:19.354 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-30 22:20:19.746 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:19.747 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:7
2016-03-30 22:20:19.747 ThaliTest[2455:4585999] multipeer m,anager: start client restart timer: 0x16db8fb0
2016-03-30 22:20:19.747 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:7
2016-03-30 22:20:19.747 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening: success
ok 153 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-30 22:20:19.748 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-30 22:20:19.748 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error
,2016-03-30 22:20:21.159 ThaliTest[2455:4585828] client: found new peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:21.159 ThaliTest[2455:4585828] client: found new peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:7
ok 155 peers must be an array
ok 156 peers must not be zero-length
ok 157 peer must have peerIdentifier
ok 158 peerIdentifier must be a string
ok 159 peer must have peerAvailable
,ok 160 peer must have pleaseConnect
,# teardown
,2016-03-30 22:20:21.836 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-30 22:20:21.837 ThaliTest[2455:458599,9] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:21.838 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:21.838 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:20:21.838 ThaliTest[2455:4585999] multipeer manager: stop client timer
2016-03-30 22:20:21.838 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 40. Can connect to a remote peer
,2016-03-30 22:20:22.744 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:22.744 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:22.744 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
2016-03-30 22:20:22.744 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:22.744 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 163 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:20:22.745 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-30 22:20:22.745 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-30 22:20:23.187 ThaliTest[2455:4585828] client: found new peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"A3E18F7B-F512-41AB-86C7-5683F62667F5:7","pleaseConnect":0}]
2016-03-30 22:20:23.188 ThaliTest[2455:4585999] jxcore: connect A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:20:23.188 ThaliTest[2455:4585999] client: server will connect
2016-03-30 22:20:23.188 ThaliTest[2455:4585999], client session: reverseConnect
2016-03-30 22:20:23.188 ThaliTest[2455:4585999] client session: stateChange:0->1 A3E18F7B-F512-41AB-86C7-5683F62667F5:7
,2016-03-30 22:20:23.194 ThaliTest[2455:4585828] client: found new peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7","pleaseConnect":0}]
,2016-03-30 22:20:24.866 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:20:24.866 ThaliTest[2455:4585828] server: rejecting invitation for lexical ordering 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":1}]
,2016-03-30 22:20:25.844 ThaliTest[2455:4586428] client session: not connected A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:20:25.845 ThaliTest[2455:4586428] client session: onLinkFailure: A3E18F7B-F512-41AB-86C7-5683F62667F5
2016-03-30 22:20:25.8,45 ThaliTest[2455:4586428] client session: disconnect
2016-03-30 22:20:25.845 ThaliTest[2455:4586428] client session: stateChange:1->0 A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:20:25.845 ThaliTest[2455:4586428] client session: no connect callback (server initiated)
,2016-03-30 22:20:33.189 ThaliTest[2455:4585828] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-30 22:20:36.198 ThaliTest[2455:4585999] jxcore: connect A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:20:36.198 ThaliTest[2455:4585999] client: server will connect
2016-03-30 22:20:36.198 ThaliTest[2455:4585999] client session: reverseConnect
2016-03-30 22:20:36.199 ThaliTest[2455:4585999] client session: stateChange:0->1 A3E18F7B-F512-41AB-86C7-5683F62667F5:7
,2016-03-30 22:20:36.390 ThaliTest[2455:4586477] client session: not connected A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:20:36.391 ThaliTest[2455:4586477] client session: onLinkFailure: A3E18F7B-F512-41AB-86C7-5683F62667F5
2016-03-30 22:20:36.3,91 ThaliTest[2455:4586477] client session: disconnect
2016-03-30 22:20:36.391 ThaliTest[2455:4586477] client session: stateChange:1->0 A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:20:36.391 ThaliTest[2455:4586477] client session: no connect callback (server initiated)
,2016-03-30 22:20:38.290 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:20:38.291 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:20:38.291 ThaliTest[2455:4585828], server: rejecting invitation for lexical ordering 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":1}]
,2016-03-30 22:20:42.745 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:20:42.756 ThaliTest[2455:4585828] client: found updated peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"A3E18F7B-F512-41AB-86C7-5683F62667F5:8","pleaseConnect":0}]
2016-03-30 22:20:42.758 ThaliTest[2455:4585828] client: found updated peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":0}]
,2016-03-30 22:20:46.200 ThaliTest[2455:4585828] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 8
,2016-03-30 22:20:49.212 ThaliTest[2455:4585999] jxcore: connect A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:20:49.212 ThaliTest[2455:4585999] client: server will connect
2016-03-30 22:20:49.212 ThaliTest[2455:4585999] client session: reverseConnect
2016-03-30 22:20:49.212 ThaliTest[2455:4585999] client session: stateChange:0->1 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:20:49.500 ThaliTest[2455:4586517] client session: not connected A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:20:49.501 ThaliTest[2455:4586517] client session: onLinkFailure: A3E18F7B-F512-41AB-86C7-5683F62667F5
2016-03-30 22:20:49.5,01 ThaliTest[2455:4586517] client session: disconnect
2016-03-30 22:20:49.501 ThaliTest[2455:4586517] client session: stateChange:1->0 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:20:49.501 ThaliTest[2455:4586517] client session: no connect callback (server initiated)
,2016-03-30 22:20:51.409 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:20:51.409 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:20:51.409 ThaliTest[2455:4585828], server: rejecting invitation for lexical ordering 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":1}]
,2016-03-30 22:20:59.213 ThaliTest[2455:4585828] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-30 22:21:02.217 ThaliTest[2455:4585999] jxcore: connect A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:21:02.218 ThaliTest[2455:4585999] client: server will connect
2016-03-30 22:21:02.218 ThaliTest[2455:4585999] client session: reverseConn,ect
2016-03-30 22:21:02.218 ThaliTest[2455:4585999] client session: stateChange:0->1 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:21:02.603 ThaliTest[2455:4586525] client session: not connected A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:02.604 ThaliTest[2455:4586525] client session: onLinkFailure: A3E18F7B-F512-41AB-86C7-5683F62667F5
2016-03-30 22:21:02.6,04 ThaliTest[2455:4586525] client session: disconnect
2016-03-30 22:21:02.604 ThaliTest[2455:4586525] client session: stateChange:1->0 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:02.604 ThaliTest[2455:4586525] client session: no connect callback (server initiated)
,2016-03-30 22:21:02.745 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:21:02.754 ThaliTest[2455:4585828] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:02.754 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:21:04.311 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:21:04.311 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:21:04.311 ThaliTest[2455:4585828], server: rejecting invitation for lexical ordering 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":1}]
,2016-03-30 22:21:12.219 ThaliTest[2455:4585828] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 6
,2016-03-30 22:21:15.227 ThaliTest[2455:4585999] jxcore: connect A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:21:15.228 ThaliTest[2455:4585999] client: server will connect
2016-03-30 22:21:15.228 ThaliTest[2455:4585999] client session: reverseConnect
2016-03-30 22:21:15.228 ThaliTest[2455:4585999] client session: stateChange:0->1 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:21:18.126 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:21:18.126 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:21:18.127 ThaliTest[2455:4585828], server: rejecting invitation for lexical ordering 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":1}]
,2016-03-30 22:21:20.424 ThaliTest[2455:4586635] client session: not connected A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:20.424 ThaliTest[2455:4586635] client session: onLinkFailure: A3E18F7B-F512-41AB-86C7-5683F62667F5
2016-03-30 22:21:20.424 ThaliTest[2455:4586635] client session: disconnect
2016-03-30 22:21:20.424 ThaliTest[2455:4586635] client session: stateChange:1->0 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:20.425 ThaliTest[2455:4586635] client session: no connect callback (server initiated)
,2016-03-30 22:21:22.745 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:21:22.753 ThaliTest[2455:4585828] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:22.755 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:21:25.229 ThaliTest[2455:4585828] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 5
,2016-03-30 22:21:28.234 ThaliTest[2455:4585999] jxcore: connect A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:21:28.234 ThaliTest[2455:4585999] client: server will connect
2016-03-30 22:21:28.234 ThaliTest[2455:4585999] client session: reverseConn,ect
2016-03-30 22:21:28.235 ThaliTest[2455:4585999] client session: stateChange:0->1 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:21:29.007 ThaliTest[2455:4586640] client session: not connected A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:29.007 ThaliTest[2455:4586640] client session: onLinkFailure: A3E18F7B-F512-41AB-86C7-5683F62667F5
2016-03-30 22:21:29.007 ThaliTest[2455:4586640] client session: disconnect
2016-03-30 22:21:29.007 ThaliTest[2455:4586640] client session: stateChange:1->0 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:21:29.008 ThaliTest[2455:4586640] client session: no connect callback (server initiated)
,2016-03-30 22:21:30.577 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:21:30.577 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:21:30.578 ThaliTest[2455:4585828], server: rejecting invitation for lexical ordering 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":1}]
,2016-03-30 22:21:38.236 ThaliTest[2455:4585828] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-30 22:21:41.240 ThaliTest[2455:4585999] jxcore: connect A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:21:41.240 ThaliTest[2455:4585999] client: server will connect
2016-03-30 22:21:41.240 ThaliTest[2455:4585999] client session: reverseConnect
2016-03-30 22:21:41.240 ThaliTest[2455:4585999] client session: stateChange:0->1 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:21:41.927 ThaliTest[2455:4586635] client session: not connected A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:41.927 ThaliTest[2455:4586635] client session: onLinkFailure: A3E18F7B-F512-41AB-86C7-5683F62667F5
2016-03-30 22:21:41.927 ThaliTest[2455:4586635] client session: disconnect
,2016-03-30 22:21:41.927 ThaliTest[2455:4586635] client session: stateChange:1->0 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:21:41.928 ThaliTest[2455:4586635] client session: no connect callback (server initiated)
,2016-03-30 22:21:42.745 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:21:42.753 ThaliTest[2455:4585828] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:42.753 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:21:43.035 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:21:43.035 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:21:43.035 ThaliTest[2455:4585828], server: rejecting invitation for lexical ordering 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":1}]
,2016-03-30 22:21:51.241 ThaliTest[2455:4585828] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-30 22:21:54.242 ThaliTest[2455:4585999] jxcore: connect A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:21:54.243 ThaliTest[2455:4585999] client: server will connect
2016-03-30 22:21:54.243 ThaliTest[2455:4585999] client session: reverseConn,ect
2016-03-30 22:21:54.243 ThaliTest[2455:4585999] client session: stateChange:0->1 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:21:54.701 ThaliTest[2455:4586635] client session: not connected A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:54.701 ThaliTest[2455:4586635] client session: onLinkFailure: A3E18F7B-F512-41AB-86C7-5683F62667F5
2016-03-30 22:21:54.7,01 ThaliTest[2455:4586635] client session: disconnect
2016-03-30 22:21:54.702 ThaliTest[2455:4586635] client session: stateChange:1->0 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:21:54.702 ThaliTest[2455:4586635] client session: no connect callback (server initiated)
,2016-03-30 22:21:56.012 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:21:56.012 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:21:56.012 ThaliTest[2455:4585828], server: rejecting invitation for lexical ordering 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":1}]
,2016-03-30 22:22:02.745 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:22:02.754 ThaliTest[2455:4585828] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:22:02.754 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:22:04.244 ThaliTest[2455:4585828] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-30 22:22:07.257 ThaliTest[2455:4585999] jxcore: connect A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:22:07.258 ThaliTest[2455:4585999] client: server will connect
2016-03-30 22:22:07.258 ThaliTest[2455:4585999] client session: reverseConnect
2016-03-30 22:22:07.258 ThaliTest[2455:4585999] client session: stateChange:0->1 A3E18F7B-F512-41AB,-86C7-5683F62667F5:8
,2016-03-30 22:22:07.539 ThaliTest[2455:4586731] client session: not connected A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:22:07.539 ThaliTest[2455:4586731] client session: onLinkFailure: A3E18F7B-F512-41AB-86C7-5683F62667F5
2016-03-30 22:22:07.5,39 ThaliTest[2455:4586731] client session: disconnect
2016-03-30 22:22:07.539 ThaliTest[2455:4586731] client session: stateChange:1->0 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:22:07.539 ThaliTest[2455:4586731] client session: no connect callback (server initiated)
,2016-03-30 22:22:09.120 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:22:09.120 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:22:09.120 ThaliTest[2455:4585828], server: rejecting invitation for lexical ordering 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":1}]
,2016-03-30 22:22:17.259 ThaliTest[2455:4585828] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 1
,2016-03-30 22:22:20.267 ThaliTest[2455:4585999] jxcore: connect A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:22:20.267 ThaliTest[2455:4585999] client: server will connect
2016-03-30 22:22:20.267 ThaliTest[2455:4585999] client session: reverseConn,ect
2016-03-30 22:22:20.267 ThaliTest[2455:4585999] client session: stateChange:0->1 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:22:20.706 ThaliTest[2455:4586798] client session: not connected A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:22:20.707 ThaliTest[2455:4586798] client session: onLinkFailure: A3E18F7B-F512-41AB-86C7-5683F62667F5
,2016-03-30 22:22:20.707 ThaliTest[2455:4586798] client session: disconnect
2016-03-30 22:22:20.707 ThaliTest[2455:4586798] client session: stateChange:1->0 A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:22:20.707 ThaliTest[2455:4586798] client session: no connect callback (server initiated)
,2016-03-30 22:22:22.274 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:22:22.275 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:22:22.275 ThaliTest[2455:4585828], server: rejecting invitation for lexical ordering 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8","pleaseConnect":1}]
,2016-03-30 22:22:22.745 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:22:22.753 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:22.753 ThaliTest[2455:4585828] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:22:30.268 ThaliTest[2455:4585828] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
WARN testThaliMobileNative: Too many connect retries!
,not ok 165 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-30 22:22:33.777 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-30 22:22:33.778 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,ok 166 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-30 22:22:33.779 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:22:33.779 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:22:33.780 ThaliTest[2455:4585999] multipeer manager: stop client timer
2016-03-30 22:22:33.780 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 167 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. Can shift large amounts of data
,2016-03-30 22:22:35.711 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
,2016-03-30 22:22:35.712 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:22:35.712 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
2016-03-30 22:22:35.713 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:22:35.713 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening: success
ok 168 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:22:35.714 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeW,rapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-30 22:22:35.714 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
ok 169 Can call startListeningForAdvertisements without error
,2016-03-30 22:22:35.809 ThaliTest[2455:4585828] client: found new peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:22:35.810 ThaliTest[2455:4585999] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:35.810 ThaliTest[2455:4585999] client session: connect
2016-03-30 22:22:35.810 ThaliTest[2455:4585999] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:22:36.370 ThaliTest[2455:4585828] client: found new peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:22:37.676 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:22:37.676 ThaliTest[2455:4585828] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:22:38.003 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:22:38.003 ThaliTest[2455:4585828] server: rejecting invitation from 0D4FB91C-5072-4219-BFC9-CC10DE895F2C due to previous generation (10864D2D-6C65-445D-AFFE-A77AB,0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:22:38.836 ThaliTest[2455:4586833] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:38.838 ThaliTest[2455:4586833] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:38.8,38 ThaliTest[2455:4586833] client session: disconnect
2016-03-30 22:22:38.838 ThaliTest[2455:4586833] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:38.838 ThaliTest[2455:4586833] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:38.838 ThaliTest[2455:4586833] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-30 22:22:41.025 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:22:41.025 ThaliTest[2455:4585828] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:22:41.026 ThaliTest[2455:4585828] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:22:41.845 ThaliTest[2455:4585999] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:41.845 ThaliTest[2455:4585999] client session: connect
2016-03-30 22:22:41.845 ThaliTest[2455:4585999] client session: stateChange:0->,1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:22:42.851 ThaliTest[2455:4586798] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:42.853 ThaliTest[2455:4586798] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:42.853 ThaliTest[2455:4586798] client session: disconnect
2016-03-30 22:22:42.853 ThaliTest[2455:4586798] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:22:42.853 ThaliTest[2455:4586798] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:42.854 ThaliTest[2455:4586798] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-30 22:22:44.171 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:22:44.172 ThaliTest[2455:4585828] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:22:44.172 ThaliTest[2455:4585828] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:22:45.858 ThaliTest[2455:4585999] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:45.858 ThaliTest[2455:4585999] client session: connect
2016-03-30 22:22:45.858 ThaliTest[2455:4585999] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:22:46.749 ThaliTest[2455:4586798] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:46.749 ThaliTest[2455:4586798] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:46.7,49 ThaliTest[2455:4586798] client session: disconnect
2016-03-30 22:22:46.749 ThaliTest[2455:4586798] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:46.749 ThaliTest[2455:4586798] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:46.749 ThaliTest[2455:4586798] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-30 22:22:47.368 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:22:47.368 ThaliTest[2455:4585828] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:22:47.368 ThaliTest[2455:4585828] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:22:49.014 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:22:49.014 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:22:49.014 ThaliTest[2455:4585828] server: rejecting invitation from 0D4FB91C-5072-4219-BFC9-CC10DE895F2C due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:22:49.760 ThaliTest[2455:4585999] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:49.760 ThaliTest[2455:4585999] client session: connect
2016-03-30 22:22:49.761 ThaliTest[2455:4585999] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:22:50.527 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:22:50.527 ThaliTest[2455:4585828] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:22:50.528 ThaliTest[2455:4585828] server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:22:50.699 ThaliTest[2455:4586905] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:50.700 ThaliTest[2455:4586905] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:50.700 ThaliTest[2455:4586905] client session: disconnect
2016-03-30 22:22:50.700 ThaliTest[2455:4586905] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:50.700 ThaliTest[2455:4586905] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:50.701 ThaliTest[2455:4586905] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-30 22:22:53.671 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:22:53.671 ThaliTest[2455:4585828] server: disconnecting to refresh session (A3E18F7B-F512-41AB-86C7-5683F62667F5)
2016-03-30 22:22:53.671 ThaliTest[2455:4585828], server: rejecting invitation from A3E18F7B-F512-41AB-86C7-5683F62667F5 due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:22:53.710 ThaliTest[2455:4585999] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:53.710 ThaliTest[2455:4585999] client session: connect
2016-03-30 22:22:53.710 ThaliTest[2455:4585999] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:22:54.585 ThaliTest[2455:4586844] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:54.586 ThaliTest[2455:4586844] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:54.5,86 ThaliTest[2455:4586844] client session: disconnect
2016-03-30 22:22:54.586 ThaliTest[2455:4586844] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:54.586 ThaliTest[2455:4586844] client session: fireConnectCallb,ack: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:54.586 ThaliTest[2455:4586844] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-30 22:22:55.713 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:22:55.723 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:55.723 ThaliTest[2455:4585828] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:22:57.588 ThaliTest[2455:4585999] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:57.588 ThaliTest[2455:4585999] client session: connect
2016-03-30 22:22:57.589 ThaliTest[2455:4585999] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:22:58.452 ThaliTest[2455:4586834] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:58.452 ThaliTest[2455:4586834] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:58.4,52 ThaliTest[2455:4586834] client session: disconnect
2016-03-30 22:22:58.452 ThaliTest[2455:4586834] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:22:58.452 ThaliTest[2455:4586834] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:22:58.452 ThaliTest[2455:4586834] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-30 22:23:01.455 ThaliTest[2455:4585999] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:01.455 ThaliTest[2455:4585999] client session: connect
2016-03-30 22:23:01.455 ThaliTest[2455:4585999] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:23:02.114 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:23:02.114 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:23:02.114 ThaliTest[2455:4585828] server: rejecting invitation from 0D4FB91C-5072-4219-BFC9-CC10DE895F2C due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:23:02.115 ThaliTest[2455:4586834] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:23:02.117 ThaliTest[2455:4586834] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:23:02.118 ThaliTest[2455:4586834] client session: disconnect
2016-03-30 22:23:02.118 ThaliTest[2455:4586834] client session:, stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:02.118 ThaliTest[2455:4586834] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:23:02.118 ThaliTest[2455:4586834] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-30 22:23:05.122 ThaliTest[2455:4585999] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:05.122 ThaliTest[2455:4585999] client session: connect
2016-03-30 22:23:05.122 ThaliTest[2455:4585999] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:23:05.698 ThaliTest[2455:4586905] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:05.699 ThaliTest[2455:4586905] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:23:05.6,99 ThaliTest[2455:4586905] client session: disconnect
2016-03-30 22:23:05.699 ThaliTest[2455:4586905] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:05.699 ThaliTest[2455:4586905] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:23:05.699 ThaliTest[2455:4586905] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-30 22:23:08.705 ThaliTest[2455:4585999] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:08.705 ThaliTest[2455:4585999] client session: connect
2016-03-30 22:23:08.705 ThaliTest[2455:4585999] client session: stateChange:0->,1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:23:09.346 ThaliTest[2455:4586834] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:09.346 ThaliTest[2455:4586834] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:23:09.346 ThaliTest[2455:4586834] client session: disconnect
2016-03-30 22:23:09.346 ThaliTest[2455:4586834] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:09.346 ThaliTest[2455:4586834] client session: fireConnectCallb,ack: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:23:09.346 ThaliTest[2455:4586834] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-30 22:23:12.360 ThaliTest[2455:4585999] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:12.360 ThaliTest[2455:4585999] client session: connect
2016-03-30 22:23:12.360 ThaliTest[2455:4585999] client session: stateChange:0->,1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:23:13.055 ThaliTest[2455:4586834] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:13.055 ThaliTest[2455:4586834] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:23:13.0,55 ThaliTest[2455:4586834] client session: disconnect
2016-03-30 22:23:13.056 ThaliTest[2455:4586834] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:13.056 ThaliTest[2455:4586834] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:23:13.056 ThaliTest[2455:4586834] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 170 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-30 22:23:15.103 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:23:15.103 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:23:15.103 ThaliTest[2455:4585828] server: rejecting invitation from 0D4FB91C-5072-4219-BFC9-CC10DE895F2C due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:23:15.714 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:23:15.722 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:15.722 ThaliTest[2455:4585828] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:23:28.269 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:23:28.269 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:23:28.269 ThaliTest[2455:4585828] server: rejecting invitation from 0D4FB91C-5072-4219-BFC9-CC10DE895F2C due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:23:35.714 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:23:35.722 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:23:35.723 ThaliTest[2455:4585828] client: found existing peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:23:41.488 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:23:41.488 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:23:41.489 ThaliTest[2455:4585828] server: rejecting invitation from 0D4FB91C-5072-4219-BFC9-CC10DE895F2C due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:23:54.018 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:23:54.019 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:23:54.019 ThaliTest[2455:4585828] server: rejecting invitation from 0D4FB91C-5072-4219-BFC9-CC10DE895F2C due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:23:55.714 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:23:55.723 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:23:55.723 ThaliTest[2455:4585828] client: found updated peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:9
,2016-03-30 22:24:07.639 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:24:07.639 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:24:07.639 ThaliTest[2455:4585828] server: rejecting invitation from 0D4FB91C-5072-4219-BFC9-CC10DE895F2C due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:24:15.714 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:24:15.722 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:24:15.723 ThaliTest[2455:4585828] client: found updated peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:24:20.283 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:24:20.283 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:24:20.283 ThaliTest[2455:4585828], server: rejecting invitation from 0D4FB91C-5072-4219-BFC9-CC10DE895F2C due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:24:33.855 ThaliTest[2455:4585828] multipeer session: reset timer
2016-03-30 22:24:33.855 ThaliTest[2455:4585828] server: disconnecting to refresh session (0D4FB91C-5072-4219-BFC9-CC10DE895F2C)
2016-03-30 22:24:33.855 ThaliTest[2455:4585828] server: rejecting invitation from 0D4FB91C-5072-4219-BFC9-CC10DE895F2C due to previous generation (10864D2D-6C65-445D-AFFE-A77AB0B7C823:9 != 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8)
,2016-03-30 22:24:35.714 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:24:35.722 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
2016-03-30 22:24:35.723 ThaliTest[2455:4585828] client: found updated peer: A3E18F7B-F512-41AB-86C7-5683F62667F5:9
,2016-03-30 22:24:44.544 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-30 22:24:44.545 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-30 22:24:44.546 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:24:44.546 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:24:44.546 ThaliTest[2455:4585999] multipeer manager: stop client timer
2016-03-30 22:24:44.547 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-30 22:24:55.595 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:24:55.595 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:24:55.595 ThaliTest[2455:4,585999] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:24:55.597 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 173 specific error should be returned
,# teardown
,ok 174 must be stopped
# setup
,2016-03-30 22:25:04.320 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:04.320 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:04.321 ThaliTest[2455:4585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:25:04.322 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 175 specific error should be returned
,# teardown
,ok 176 must be stopped
,# setup
,2016-03-30 22:25:24.082 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:24.082 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:24.083 ThaliTest[2455:4585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:25:24.083 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54646
,2016-03-30 22:25:25.491 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:25.492 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,ok 177 no errors
,2016-03-30 22:25:25.493 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:25:25.494 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
ok 178 still no errors
,# teardown
,2016-03-30 22:25:25.799 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:25.799 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:25:25.800 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:25:25.800 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:25.800 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,ok 179 must be stopped
,# setup
,2016-03-30 22:25:26.000 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:26.000 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:26.000 ThaliTest[2455:4585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:25:26.001 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54648
,2016-03-30 22:25:26.361 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
2016-03-30 22:25:26.361 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:25:26.362 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
,ok 180 no errors
,2016-03-30 22:25:26.363 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:25:26.364 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
ok 181 still no errors
,# teardown
,2016-03-30 22:25:26.679 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:26.680 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:25:26.680 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:25:26.680 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
2016-03-30 22:25:26.680 ThaliTest[2455:4585999] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:26.681 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,ok 182 must be stopped
# setup
,2016-03-30 22:25:27.191 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:27.192 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:27.192 ThaliTest[2455:4585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:25:27.193 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 46. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54650
,2016-03-30 22:25:28.769 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:25:28.769 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:10
2016-03-30 22:25:28.769 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
2016-03-30 22:25:28.769 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:10
2016-03-30 22:25:28.769 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening: success
ok 183 no errors
2016-03-30 22:25:28.770 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:25:28.770 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:25:28.770 ThaliTest[2455:4585,999] multipeer manager: stop client timer
2016-03-30 22:25:28.771 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:11
2016-03-30 22:25:28.771 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
,2016-03-30 22:25:28.771 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:11
2016-03-30 22:25:28.773 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening: success
ok 184 still no errors
# teardown
,2016-03-30 22:25:29.182 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:29.182 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:25:29.183 ThaliTest[2455:4585999] multipeer manager: stop client timer
2016-03-30 22:25:29.183 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:25:29.183 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:25:29.184 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,ok 185 must be stopped
# setup
,2016-03-30 22:25:29.741 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:29.741 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:29.742 ThaliTest[2455:4,585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:25:29.743 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54654
,2016-03-30 22:25:29.939 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:29.939 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:25:29.939 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 186 no errors
2016-03-30 22:25:29.940 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
,2016-03-30 22:25:29.940 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
,2016-03-30 22:25:29.940 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
ok 187 still no errors
,# teardown
,2016-03-30 22:25:30.819 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:30.820 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:25:30.820 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:25:30.820 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:30.821 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,ok 188 must be stopped
,# setup
,2016-03-30 22:25:31.256 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:31.256 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:31.256 ThaliTest[2455:4,585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:25:31.257 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 48. can get the network status before starting
,ok 189 network status should have certain non-empty properties
,# teardown
,ok 190 must be stopped
,# setup
,2016-03-30 22:26:01.658 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:01.659 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:01.659 ThaliTest[2455:4,585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:26:01.659 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 49. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 191 specific error expected
,# teardown
,ok 192 must be stopped
,# setup
,2016-03-30 22:26:08.503 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:08.504 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:08.504 ThaliTest[2455:4,585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:08.505 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 50. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54656
,2016-03-30 22:26:08.751 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
2016-03-30 22:26:08.751 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-30 22:26:08.752 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
2016-03-30 22:26:08.753 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:26:08.753 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:12
2016-03-30 22:26:08.753 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:12
2016-03-30 22:26:08.753 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 193 connection to servers manager should succeed after starting
,ok 194 connection to router server should succeed after starting
,2016-03-30 22:26:08.785 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:26:08.785 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:26:08.785 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:26:08.786 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
2016-03-30 22:26:08.786 ThaliTest[2455:4585999] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:26:08.787 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
ok 195 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 196 connection to servers manager should fail after stopping
,ok 197 connection to router server should fail after stopping
,# teardown
,ok 198 must be stopped
,# setup
,2016-03-30 22:26:09.938 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:09.939 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:09.939 ThaliTest[2455:4585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:09.940 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure terminateConnection is properly hooked up
,ok 199 called with right arguments
,# teardown
,ok 200 must be stopped
,# setup
,2016-03-30 22:26:14.741 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:14.741 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:14.741 ThaliTest[2455:4585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:14.742 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. make sure terminateListener is properly hooked up
,ok 201 called with right arguments
,# teardown
,ok 202 must be stopped
,# setup
,2016-03-30 22:26:25.186 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:25.187 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:25.187 ThaliTest[2455:4585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:25.188 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 53. make sure we actually call kill connections properly
,2016-03-30 22:26:25.265 ThaliTest[2455:4585999] jxcore: killConnections
2016-03-30 22:26:25.265 ThaliTest[2455:4585999] jxcore: killConnections: badParam
,not ok 203 should not fail on iOS
,  ---
,    operator: fail
,  ...
,# teardown
,ok 204 must be stopped
,# setup
,2016-03-30 22:26:25.554 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:25.555 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:25.555 ThaliTest[2455:4585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:25.556 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54663
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":54662,"error":{}}
,2016-03-30 22:26:25.683 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:26:25.684 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:26:25.684 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:26:25.684 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:26:25.684 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,ok 205 failure reason is as expected
,ok 206 error description is as expected
,ok 207 must be stopped
,# teardown
,ok 208 must be stopped
,# setup
,2016-03-30 22:26:25.969 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:25.969 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:25.969 ThaliTest[2455:4585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:25.971 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 55. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54665
,ok 209 peerIdentifier matches
,ok 210 error description matches
,# teardown
,2016-03-30 22:26:26.339 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:26:26.339 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:26:26.339 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:26:26.340 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:26:26.340 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,ok 211 must be stopped
,# setup
,2016-03-30 22:26:26.536 ThaliTest[2455:4585999] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:26.537 ThaliTest[2455:4585999] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:26.537 ThaliTest[2455:4,585999] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:26.538 ThaliTest[2455:4585999] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 56. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54667
,2016-03-30 22:26:26.758 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements
2016-03-30 22:26:26.759 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
ok 212 discoveryActive matches
,ok 213 advertisingActive matches
2016-03-30 22:26:26.764 ThaliTest[2455:4585999] jxcore: startListeningForAdvertisements: success
,2016-03-30 22:26:26.764 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening
2016-03-30 22:26:26.764 ThaliTest[2455:4585999] THEMultipeerManager stopping peer
2016-03-30 22:26:26.764 ThaliTest[2455:4585999] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:26:26.765 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements
2016-03-30 22:26:26.765 ThaliTest[2455:4585999] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
ok 214 discoveryActive matches
,ok 215 advertisingActive matches
,2016-03-30 22:26:26.767 ThaliTest[2455:4585999] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54669
,2016-03-30 22:26:26.772 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:26:26.773 ThaliTest[2455:4585999] server: starting 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
2016-03-30 22:26:26.773 ThaliTest[2455:4585999] multipeer manager: start client restart timer: 0x16db8fb0
2016-03-30 22:26:26.774 ThaliTest[2455:4585999] THEMultipeerManager initialized peer 10864D2D-6C65-445D-AFFE-A77AB0B7C823:13
2016-03-30 22:26:26.774 ThaliTest[2455:4585999] jxcore: startUpdateAdvertisingAnd,Listening: success
,2016-03-30 22:26:27.791 ThaliTest[2455:4585828] client: found new peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:8
,2016-03-30 22:26:46.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:27:00.008 ThaliTest[2455:4585828] client: found updated peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:27:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:27:06.784 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:27:26.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:27:26.787 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:27:46.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:27:46.782 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:28:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:28:06.789 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:28:26.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:28:26.781 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:28:46.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:28:46.782 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:29:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:29:06.781 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:29:26.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:29:26.780 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:29:46.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:29:46.784 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:30:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:30:06.781 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:30:26.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:30:26.780 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:30:46.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:30:46.782 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:31:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:31:06.782 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:31:26.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:31:26.780 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:31:46.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:31:46.785 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:32:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:32:06.784 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:32:26.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:32:26.790 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:32:46.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:32:46.781 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:33:06.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:33:06.779 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:33:26.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:33:26.780 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:33:46.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:33:46.780 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:34:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:34:06.787 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:34:26.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:34:26.781 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:34:46.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:34:46.786 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:35:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:35:06.783 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:35:26.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:35:26.786 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:35:46.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:35:46.791 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:36:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:36:06.785 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:36:26.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:36:26.781 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:36:46.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:36:46.783 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:37:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:37:06.782 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:37:26.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:37:26.782 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:37:46.774 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:37:46.781 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:38:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:38:06.781 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:38:26.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:38:26.783 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:38:46.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:38:46.782 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13
,2016-03-30 22:39:06.775 ThaliTest[2455:4585828] multipeer manager: restart client
,2016-03-30 22:39:06.784 ThaliTest[2455:4585828] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:13

```
