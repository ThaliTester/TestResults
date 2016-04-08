#### Test 65745020fc66909_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/65745020fc66909/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/085A2D76-8B31-458B-9059-E36ABD7435A2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/085A2D76-8B31-458B-9059-E36ABD7435A2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/65745020fc66909/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/65745020fc66909/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52046"
,(lldb)     command script import "/tmp/085A2D76-8B31-458B-9059-E36ABD7435A2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-04-08 10:08:47.056 ThaliTest[2966:5867827] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AB5CC550-8AC6-4F0A-BADB-9EBAE2E91654/Library/Cookies/Cookies.binarycookies
,2016-04-08 10:08:47.283 ThaliTest[2966:5867827] Apache Cordova native platform version 4.1.1 is starting.
2016-04-08 10:08:47.284 ThaliTest[2966:5867827] Multi-tasking -> Device: YES, App: YES
,2016-04-08 10:08:47.296 ThaliTest[2966:5867827] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-08 10:08:48.060 ThaliTest[2966:5867827] Using UIWebView
2016-04-08 10:08:48.062 ThaliTest[2966:5867827] [CDVTimer][handleopenurl] 0.142038ms
2016-04-08 10:08:48.064 ThaliTest[2966:5867827] [CDVTimer][intentandnavigationfilter] 2.139986ms
2016-04-08 10:08:48.064 ThaliTest[2966:5867827] [CDVTimer][gesturehandler] 0.099003ms
,2016-04-08 10:08:48.066 ThaliTest[2966:5867827] [CDVTimer][TotalPluginStartup] 2.808988ms
,2016-04-08 10:08:51.087 ThaliTest[2966:5867827] Resetting plugins due to page load.
,2016-04-08 10:08:52.442 ThaliTest[2966:5867827] Finished load of: file:///var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/index.html
,2016-04-08 10:08:52.599 ThaliTest[2966:5867827] JXcore Cordova plugin initializing
,2016-04-08 10:08:52.601 ThaliTest[2966:5867986] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-08 10:08:59.701 ThaliTest[2966:5867986] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-08 10:08:59.703 ThaliTest[2966:5867986] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-08 10:08:59.703 ThaliTest[2966:5867986] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-08 10:08:59.705 ThaliTest[2966:5867986] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0C85FF81-74C5-484B-B48A-6B807916214F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58658
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58660
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58663
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
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58667
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 58672
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
DEBUG createNativeListener: listening 58676
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
DEBUG createNativeListener: listening 58680
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
,# setup
,DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58684
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
DEBUG createNativeListener: listening 58688
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
DEBUG createNativeListener: listening 58740
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
DEBUG createNativeListener: listening 58744
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
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
,# 16. enqueue and run in order
,ok 48 firstPromise setTimeout
ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue
,# teardown
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
,ok 66 second
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
,[{"uuid":"954a9fdb-faef-45fa-8c4a-e2bfb48a901a","data":"custom data"},{"uuid":"310bd762-5c41-4013-ba98-1cdb5e69f42c","data":"custom data"},{"uuid":"81db905b-3019-4407-af41-b12970730dfa","data":"custom data"},{"uuid":"11a5596c-0abf-49aa-b899-484cc8fc4f8f","data":"custom data"}]
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
DEBUG createNativeListener: listening 58754
2016-04-08 10:11:51.007 ThaliTest[2966:5867986] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 10:11:51.008 ThaliTest[2966:5867986] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-08 10:11:51.009 ThaliTest[2966:5867986] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 10:11:51.010 ThaliTest[2966:5867986] jxcore: stopListeningForAdvertisements: succes,s
ok 93 error should be null
ok 94 error should be null
,# teardown
,2016-04-08 10:11:52.051 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening
2016-04-08 10:11:52.051 ThaliTest[2966:5867986] THEMultipeerManager stopping peer
2016-04-08 10:11:52.051 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening: success
2016-04-08 10:11:52.051 ThaliTest[2966:5867986] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 10:11:52.052 ThaliTest[2966,:5867986] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58756
,2016-04-08 10:11:55.009 ThaliTest[2966:5867986] jxcore: startListeningForAdvertisements
,2016-04-08 10:11:55.010 ThaliTest[2966:5867986] multipeer manager: start client restart timer: 0x14e82130
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 10:11:55.011 ThaliTest[2966:5867986] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-08 10:11:55.016 ThaliTest[2966:5867986] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-04-08 10:11:55.017 ThaliTest[2966:5867986] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-08 10:11:56.458 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening
2016-04-08 10:11:56.458 ThaliTest[2966:5867986] THEMultipeerManager stopping peer
2016-04-08 10:11:56.459 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening: success
2016-04-08 10:11:56.459 ThaliTest[2966:5867986] jxcore: stopListeningForAdvertisements
2016-04-08 10:11:56.459 ThaliTest[2966:5867986] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-08 10:11:56.459 ThaliTest[2966:5867986] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58758
2016-04-08 10:13:54.617 ThaliTest[2966:5867986] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 10:13:54.617 ThaliTest[2966:5867986] server: starting 33B8A67F-CB3A-4E1D-BE92-04CE29FBE967:1
2016-04-08 10:13:54.618 ThaliTest[2966:5867986] multipeer manager: start client restart timer: 0x14e82130
2016-04-08 10:13:54.618 ThaliTest[2966:58679,86] THEMultipeerManager initialized peer 33B8A67F-CB3A-4E1D-BE92-04CE29FBE967:1
2016-04-08 10:13:54.618 ThaliTest[2966:5867986] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-08 10:13:54.629 ThaliTest[2966:5867986] jxcore: startUpdateAdvertisingAndListening
2016-04-08 10:13:54.629 ThaliTest[2966:5867986] THEMultipeerManager stopping peer
2016-04-08 10:13:54.629, ThaliTest[2966:5867986] multipeer manager: stop client timer
2016-04-08 10:13:54.629 ThaliTest[2966:5867986] server: starting 33B8A67F-CB3A-4E1D-BE92-04CE29FBE967:2
2016-04-08 10:13:54.629 ThaliTest[2966:5867986] multipeer manager: start client restart ,timer: 0x14e82130
2016-04-08 10:13:54.630 ThaliTest[2966:5867986] THEMultipeerManager initialized peer 33B8A67F-CB3A-4E1D-BE92-04CE29FBE967:2
2016-04-08 10:13:54.630 ThaliTest[2966:5867986] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
# teardown
,2016-04-08 10:13:55.312 ThaliTest[2966:5867827] client: found new peer: D7A405A0-6B0E-4696-A696-C7D19D46F92C:2
,2016-04-08 10:13:56.324 ThaliTest[2966:5867827] client: found new peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:2
,2016-04-08 10:13:58.076 ThaliTest[2966:5867827] client: found new peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 10:14:04.836 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening
2016-04-08 10:14:04.836 ThaliTest[2966:5867986] THEMultipeerManager stopping peer
2016-04-08 10:14:04.836 ThaliTest[2966:5867986] multipeer manager: stop client timer
20,16-04-08 10:14:04.836 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening: success
2016-04-08 10:14:04.836 ThaliTest[2966:5867986] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-08 10:14:04.837 ThaliTest[2966:5867986] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58763
2016-04-08 10:14:28.299 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening
2016-04-08 10:14:28.299 ThaliTest[2966:5867986] THEMultipeerManager stoppi,ng peer
2016-04-08 10:14:28.299 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
2016-04-08 10:14:28.300 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening
2016-04-08, 10:14:28.301 ThaliTest[2966:5867986] THEMultipeerManager stopping peer
2016-04-08 10:14:28.301 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
,# teardown
,2016-04-08 10:14:28.426 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening
2016-04-08 10:14:28.427 ThaliTest[2966:5867986] THEMultipeerManager stopping peer
2016-04-08 10:14:28.427 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 10:14:28.427 ThaliTest[2966:5867986] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 10:14:28.427 ThaliTest[2966,:5867986] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58765
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-08 10:14:28.873 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening
2016-04-08 10:14:28.873 ThaliTest[2966:5867986] THEMultipeerManager stopping peer
2016-04-08 10:14:28.873 ThaliTest[2966:5867986] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 10:14:28.874 ThaliTest[2966:5867986] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 10:14:28.874 ThaliTest[2966,:5867986] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58767
,2016-04-08 10:14:29.095 ThaliTest[2966:5867986] jxcore: startListeningForAdvertisements
2016-04-08 10:14:29.096 ThaliTest[2966:5867986] multipeer manager: start client restart timer: 0x14e82130
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 10:14:29.096 ThaliTest[2966:5867986] jxcore: startListeningForAdvertisements: success
,2016-04-08 10:14:29.103 ThaliTest[2966:5867986] jxcore: startUpdateAdvertisingAndListening
2016-04-08 10:14:29.103 ThaliTest[2966:5867986] server: starting 33B8A67F-CB3A-4E1D-BE92-04CE29FBE967:3
2016-04-08 10:14:29.104 ThaliTest[2966:5867986] THEMultipee,rManager initialized peer 33B8A67F-CB3A-4E1D-BE92-04CE29FBE967:3
2016-04-08 10:14:29.104 ThaliTest[2966:5867986] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-08 10:14:29.800 ThaliTest[2966:5867827] client: found new peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:2
,DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= 0
,2016-04-08 10:14:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:14:49.107 ThaliTest[2966:5867827] client: found updated peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= 0
,2016-04-08 10:15:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:15:09.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:15:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:15:29.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:15:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:15:49.107 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:16:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:16:09.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:16:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:16:29.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:16:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:16:49.103 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:17:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:17:09.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:17:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:17:29.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:17:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:17:49.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:18:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:18:09.107 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:18:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:18:29.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:18:49.096 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:18:49.104 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:19:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:19:09.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:19:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:19:29.103 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:19:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:19:49.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:20:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:20:09.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:20:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:20:29.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:20:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:20:49.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:21:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:21:09.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:21:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:21:29.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:21:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:21:49.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:22:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:22:09.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:22:29.096 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:22:29.104 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:22:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:22:49.108 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:23:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:23:09.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:23:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:23:29.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:23:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:23:49.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:24:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:24:09.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:24:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:24:29.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:24:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:24:49.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:25:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:25:09.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:25:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:25:29.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:25:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:25:49.107 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:26:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:26:09.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:26:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:26:29.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:26:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:26:49.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:27:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:27:09.104 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:27:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:27:29.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:27:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:27:49.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:28:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:28:09.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:28:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:28:29.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:28:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:28:49.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:29:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:29:09.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:29:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:29:29.105 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:29:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:29:49.107 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:30:09.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:30:09.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:30:29.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:30:29.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-08 10:30:49.097 ThaliTest[2966:5867827] multipeer manager: restart client
,2016-04-08 10:30:49.106 ThaliTest[2966:5867827] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3

```
