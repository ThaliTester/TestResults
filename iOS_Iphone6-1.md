#### Test 64065450860dd96_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D6CE0015-C8A2-4B9F-917B-60FCD517280E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D6CE0015-C8A2-4B9F-917B-60FCD517280E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55809"
,(lldb)     command script import "/tmp/D6CE0015-C8A2-4B9F-917B-60FCD517280E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 18:23:40.367 ThaliTest[2128:3676893] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/48A249BD-F0E8-4B13-B20B-CF2CE262B103/Library/Cookies/Cookies.binarycookies
,2016-03-24 18:23:40.596 ThaliTest[2128:3676893] Apache Cordova native platform version 4.1.0 is starting.
2016-03-24 18:23:40.597 ThaliTest[2128:3676893] Multi-tasking -> Device: YES, App: YES
,2016-03-24 18:23:40.612 ThaliTest[2128:3676893] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 18:23:41.396 ThaliTest[2128:3676893] Using UIWebView
2016-03-24 18:23:41.398 ThaliTest[2128:3676893] [CDVTimer][handleopenurl] 0.117004ms
2016-03-24 18:23:41.401 ThaliTest[2128:3676893] [CDVTimer][intentandnavigationfilter] 2.231002ms
2016-03,-24 18:23:41.401 ThaliTest[2128:3676893] [CDVTimer][gesturehandler] 0.118017ms
2016-03-24 18:23:41.401 ThaliTest[2128:3676893] [CDVTimer][TotalPluginStartup] 2.946973ms
,2016-03-24 18:23:44.571 ThaliTest[2128:3676893] Resetting plugins due to page load.
,2016-03-24 18:23:45.983 ThaliTest[2128:3676893] Finished load of: file:///var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/index.html
,2016-03-24 18:23:46.149 ThaliTest[2128:3676893] JXcore Cordova plugin initializing
2016-03-24 18:23:46.151 ThaliTest[2128:3677054] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-24 18:23:53.157 ThaliTest[2128:3677054] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 18:23:53.158 ThaliTest[2128:3677054] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 18:23:53.159 ThaliTest[2128:3677054] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 18:23:53.160 ThaliTest[2128:3677054] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/576D1598-175D-46B2-B192-08FD71F9A07C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52052
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52054
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
DEBUG createNativeListener: listening 52057
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
DEBUG createNativeListener: listening 52061
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
,# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52066
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52070
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52074
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
,DEBUG createNativeListener: listening 52078
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
DEBUG createNativeListener: listening 52082
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
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 52134
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 52138
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,ok 62 firstPromise - in then
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
,ok 77 participant data matches
,ok 78 test participant has uuid
,ok 79 participant data matches
,ok 80 test participant has uuid
,ok 81 participant data matches
,# teardown
,# setup
,# 22. #startListeningForAdvertisements should fail if start not called
,ok 82 specific error should be returned
,# teardown
,ok 83 error should be null
ok 84 error should be null
,# setup
,# 23. #startUpdateAdvertisingAndListening should fail if start not called
,ok 85 specific error should be returned
# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52150
2016-03-24 18:26:30.172 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:30.172 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
ok 88 error should be null
ok 89 error should be null
2016-03-24 18:26:30.174 ThaliTest[2128:3677054] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:30.174 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
# teardown
,2016-03-24 18:26:30.324 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:30.325 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:30.325 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:30.325 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:30.326 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52152
2016-03-24 18:26:30.692 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements
,2016-03-24 18:26:30.694 ThaliTest[2128:3677054] multipeer manager: start client restart timer: 0x17e9c230
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:30.695 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
2016-03-24 18:26:30.702 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:30.703 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# teardown
,2016-03-24 18:26:31.066 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:31.066 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:31.067 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:31.067 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:31.067 ThaliTest[2128:3677054] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:31.067 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 98 error should be null
ok 99 error should be null
# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52154
2016-03-24 18:26:31.677 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:26:31.678 ThaliTest[2128:3677054] server: starting 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:1
2016-03-24 18:26:31.678 ThaliTest[2128:3677054] multipeer manager: start client restart timer: 0x17e9c230
2016-03-24 18:26:31.678 ThaliTest[2128:3677054] THEMultipeerManager initialized peer 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:1
2016-03-24 18:26:31.678 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
2016-03-24 18:26:31.684 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:26:31.684 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:31.685 ThaliTest[2128:3677054] multipeer manager: stop client timer
2016-03-24 18:26:31.685 ThaliTest[2128:3677054] server: starting 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:2
2016-03-24 18:26:31.685 ThaliTest[2128:3677054] multipeer manager: start client restart ,timer: 0x17e9c230
2016-03-24 18:26:31.685 ThaliTest[2128:3677054] THEMultipeerManager initialized peer 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:2
2016-03-24 18:26:31.686 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
# teardown
,2016-03-24 18:26:32.111 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:32.112 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:32.112 ThaliTest[2128:3677054] multipeer manager: stop client timer
20,16-03-24 18:26:32.112 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:32.112 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:32.113 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 104 error should be null
ok 105 error should be null
# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52159
2016-03-24 18:26:32.695 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:32.695 ThaliTest[2128:3677054] THEMultipeerManager stoppi,ng peer
2016-03-24 18:26:32.695 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
ok 106 error should be null
ok 107 error should be null
2016-03-24 18:26:32.697 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:32.697 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:32.697 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
ok 109 error should be null
# teardown
,2016-03-24 18:26:33.063 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:33.063 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:33.064 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:33.064 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:33.064 ThaliTest[2128,:3677054] jxcore: stopListeningForAdvertisements: success
ok 110 error should be null
ok 111 error should be null
# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52161
ok 112 first call should succeed
ok 113 first call should succeed
ok 114 specific error should be returned
# teardown
,2016-03-24 18:26:33.702 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:33.702 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:33.702 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 18:26:33.702 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:33.703 ThaliTest[2128,:3677054] jxcore: stopListeningForAdvertisements: success
ok 115 error should be null
ok 116 error should be null
# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52163
2016-03-24 18:26:34.546 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements
2016-03-24 18:26:34.546 ThaliTest[2128:3677054] multipeer manager: start client restart timer: 0x17e9c230
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:34.547 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements: success
,2016-03-24 18:26:34.551 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:26:34.552 ThaliTest[2128:3677054] server: starting 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:3
2016-03-24 18:26:34.552 ThaliTest[2128:3677054] THEMultipee,rManager initialized peer 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:3
2016-03-24 18:26:34.552 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening: success
ok 117 called only once
ok 118 discovery state matches
ok 119 advertising state matches
# teardown
,2016-03-24 18:26:34.750 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:34.751 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:34.751 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:34.751 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:34.751 ThaliTest[2128:3677054] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:34.752 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
# setup
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
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 133 error should be null
ok 134 error should be null
# setup
,# 33. Can call start/stopListeningForAdvertisements
,2016-03-24 18:26:56.822 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements
2016-03-24 18:26:56.823 ThaliTest[2128:3677054] multipeer manager: start client restart timer: 0x17e9c230
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:56.824 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements: success
ok 135 Can call startListeningForAdvertisements without error
2016-03-24 18:26:56.824 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:56.824 ThaliTest[2128:3677054] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-24 18:26:56.825 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
ok 136 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-24 18:26:57.067 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:57.068 ThaliTest[2128:36770,54] jxcore: stopListeningForAdvertisements: success
ok 137 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:26:57.068 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:57.068 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:57.068 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 18:26:57.594 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements
2016-03-24 18:26:57.594 ThaliTest[2128:3677054] multipeer manager: start client restart timer: 0x17e9c230
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:57.595 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-24 18:26:57.596 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:57.596 ThaliTest[2128:3677054] jxcore: startListeningForAdv,ertisements: success
ok 140 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 18:26:57.697 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:57.697 ThaliTest[2128:3677054] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:57.698 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:26:57.698 ThaliTest[2128:36770,54] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:57.698 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:57.698 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 18:26:58.742 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:26:58.742 ThaliTest[2128:3677054] server: starting 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:4
2016-03-24 18:26:58.742 ThaliTest[2128:3677054] multipeer manager: start client restart timer: 0x17e9c230
2016-03-24 18:26:58.742 ThaliTest[2128:3677054] THEMultipeerManager initialized peer 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:4
2016-03-24 18:26:58.742 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:26:58.743 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:58.743 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
,2016-03-24 18:26:58.744 ThaliTest[2128:3677054] multipeer manager: stop client timer
2016-03-24 18:26:58.746 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-24 18:26:59.878 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 18:26:59.879 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:26:59.880 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:59.880 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:26:59.880 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-24 18:27:00.266 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:00.266 ThaliTest[2128:3677054] server: starting 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:5
2016-03-24 18:27:00.266 ThaliTest[2128:3677054] multipeer manager: start client restart timer: 0x17e9c230
2016-03-24 18:27:00.267 ThaliTest[2128:3677054] THEMultipeerManager initialized peer 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:5
2016-03-24 18:27:00.267 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:27:00.267 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:00.267 ThaliTest[2128:3677054] THEMultipeerManager stopping pee,r
,2016-03-24 18:27:00.267 ThaliTest[2128:3677054] multipeer manager: stop client timer
2016-03-24 18:27:00.270 ThaliTest[2128:3677054] server: starting 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:6
2016-03-24 18:27:00.270 ThaliTest[2128:3677054] multipeer manager: start client restart timer: 0x17e9c230
2016-03-24 18:27:00.271 ThaliTest[2128:3677054] THEMultipeerManager initialized peer 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:6
2016-03-24 18:27:00.271 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-24 18:27:00.671 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 18:27:00.672 ThaliTest[2128:367705,4] jxcore: stopListeningForAdvertisements: success
ok 149 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:27:00.672 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:27:00.673 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:27:00.673 ThaliTest[2128:3677054] multipeer manager: stop client timer
2016-03-24 18:27:00.673 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. peerAvailabilityChange is called
,2016-03-24 18:27:00.908 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:00.909 ThaliTest[2128:3677054] server: starting 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:7
2016-03-24 18:27:00.909 ThaliTest[2128:3677054] multipeer manager: start client restart timer: 0x17e9c230
2016-03-24 18:27:00.909 ThaliTest[2128:3677054] THEMultipeerManager initialized peer 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:7
2016-03-24 18:27:00.909 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-24 18:27:00.910 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-24 18:27:00.911 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements: success
ok 152 Can call startListeningForAdvertisements without error
,2016-03-24 18:27:01.899 ThaliTest[2128:3676893] client: found new peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
,ok 153 peers must be an array
ok 154 peers must not be zero-length
ok 155 peer must have peerIdentifier
,ok 156 peerIdentifier must be a string
,ok 157 peer must have peerAvailable
,ok 158 peer must have pleaseConnect
,# teardown
,2016-03-24 18:27:02.120 ThaliTest[2128:3676893] client: found new peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:7
,2016-03-24 18:27:05.465 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 18:27:05.466 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
ok 159 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:27:05.467 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:27:05.467 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:27:05.467 ThaliTest[2128:3677054] multipeer manager: stop client timer
2016-03-24 18:27:05.467 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Can connect to a remote peer
,2016-03-24 18:27:40.849 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:40.849 ThaliTest[2128:3677054] server: starting 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8
2016-03-24 18:27:40.849 ThaliTest[2128:3677054] multipeer m,anager: start client restart timer: 0x17e9c230
2016-03-24 18:27:40.849 ThaliTest[2128:3677054] THEMultipeerManager initialized peer 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8
2016-03-24 18:27:40.849 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening: success
ok 161 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:27:40.850 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-24 18:27:40.851 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-24 18:27:41.878 ThaliTest[2128:3676893] client: found new peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"14C3A3B7-F65B-4CDF-8939-7B9ED734B,46B:8","pleaseConnect":0}]
2016-03-24 18:27:41.879 ThaliTest[2128:3677054] jxcore: connect 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
2016-03-24 18:27:41.879 ThaliTest[2128:3677054] client session: connect
2016-03-24 18:27:41.879 ThaliTest[2128:3677054] client session: stateChange:0->1 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
,2016-03-24 18:27:41.886 ThaliTest[2128:3676893] client: found new peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7","pleaseConnect":0}]
,2016-03-24 18:27:45.500 ThaliTest[2128:3677498] client session: p2p link connected
,2016-03-24 18:27:45.548 ThaliTest[2128:3677500] client session: stateChange:1->2 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
2016-03-24 18:27:45.548 ThaliTest[2128:3677500] client session: fireConnectCallback: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
2016-03-24 18:27:45.548 ThaliTest[2128:3677500] jxcore: connect: success
INFO testThaliMobileNative: 
,ok 163 Must have listeningPort
,ok 164 listeningPort must be a number
,ok 165 Connection must have clientPort
,ok 166 clientPort must be a number
,ok 167 Connection must have serverPort
,ok 168 serverPort must be a number
,ok 169 forward connection must have clientPort == 0
,ok 170 forward connection must have serverPort == 0
,# teardown
,2016-03-24 18:27:49.157 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 18:27:49.157 ThaliTest[2128:367705,4] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:27:49.158 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:27:49.158 ThaliTest[2128:3677054,] THEMultipeerManager stopping peer
2016-03-24 18:27:49.158 ThaliTest[2128:3677054] client session: disconnect
2016-03-24 18:27:49.159 ThaliTest[2128:3677054] client session: stateChange:2->0 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
2016-03-24 18:27:49.16,5 ThaliTest[2128:3677054] multipeer manager: stop client timer
2016-03-24 18:27:49.165 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can shift large amounts of data
,2016-03-24 18:27:50.691 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:50.692 ThaliTest[2128:3677054] server: starting 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
2016-03-24 18:27:50.692 ThaliTest[2128:3677054] multipeer m,anager: start client restart timer: 0x17e9c230
2016-03-24 18:27:50.692 ThaliTest[2128:3677054] THEMultipeerManager initialized peer 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
2016-03-24 18:27:50.692 ThaliTest[2128:3677054] jxcore: startUpdateAdvertisingAndListening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:27:50.693 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-24 18:27:50.693 ThaliTest[2128:3677054] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-24 18:27:51.277 ThaliTest[2128:3676893] client: found new peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:27:51.278 ThaliTest[2128:3677054] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:27:51.278 ThaliTest[2128:3677054] client: server will connect
2016-03-24 18:27:51.279 ThaliTest[2128:3677054] client session: reverseConnect
2016-03-24 18:27:51.279 ThaliTest[2128:3677054] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
,2016-03-24 18:27:52.906 ThaliTest[2128:3676893] client: found new peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,2016-03-24 18:27:56.308 ThaliTest[2128:3677500] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:27:56.309 ThaliTest[2128:3677500] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:27:56.309 ThaliTest[2128:3677500] client session: disconnect
2016-03-24 18:27:56.309 ThaliTest[2128:3677500] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:27:56.309 ThaliTest[2128:3677500] client session: no connect callback (server initiated)
,2016-03-24 18:28:01.279 ThaliTest[2128:3676893] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 9
,2016-03-24 18:28:04.282 ThaliTest[2128:3677054] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:28:04.282 ThaliTest[2128:3677054] client: server will connect
2016-03-24 18:28:04.282 ThaliTest[2128:3677054] client session: reverseConn,ect
2016-03-24 18:28:04.282 ThaliTest[2128:3677054] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
,2016-03-24 18:28:04.617 ThaliTest[2128:3677500] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:28:04.617 ThaliTest[2128:3677500] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:28:04.618 ThaliTest[2128:3677500] client session: disconnect
2016-03-24 18:28:04.618 ThaliTest[2128:3677500] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:28:04.618 ThaliTest[2128:3677500] client session: no connect callback (server initiated)
,2016-03-24 18:28:10.693 ThaliTest[2128:3676893] multipeer manager: restart client
,2016-03-24 18:28:10.751 ThaliTest[2128:3676893] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
2016-03-24 18:28:10.751 ThaliTest[2128:3676893] client: found updated peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:28:14.283 ThaliTest[2128:3676893] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-24 18:28:17.296 ThaliTest[2128:3677054] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:28:17.296 ThaliTest[2128:3677054] client: server will connect
2016-03-24 18:28:17.296 ThaliTest[2128:3677054] client session: reverseConn,ect
2016-03-24 18:28:17.297 ThaliTest[2128:3677054] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:28:17.470 ThaliTest[2128:3677552] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:28:17.470 ThaliTest[2128:3677552] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
,2016-03-24 18:28:17.471 ThaliTest[2128:3677552] client session: disconnect
2016-03-24 18:28:17.471 ThaliTest[2128:3677552] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:28:17.471 ThaliTest[2128:3677552] client session: no connect callback (server initiated)
,2016-03-24 18:28:27.297 ThaliTest[2128:3676893] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-24 18:28:30.300 ThaliTest[2128:3677054] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:28:30.300 ThaliTest[2128:3677054] client: server will connect
2016-03-24 18:28:30.300 ThaliTest[2128:3677054] client session: reverseConnect
2016-03-24 18:28:30.301 ThaliTest[2128:3677054] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:28:30.446 ThaliTest[2128:3677669] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:28:30.447 ThaliTest[2128:3677669] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:28:30.447 ThaliTest[2128:3677669] client session: disconnect
,2016-03-24 18:28:30.448 ThaliTest[2128:3677669] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:28:30.448 ThaliTest[2128:3677669] client session: no connect callback (server initiated)
,2016-03-24 18:28:30.693 ThaliTest[2128:3676893] multipeer manager: restart client
,2016-03-24 18:28:30.709 ThaliTest[2128:3676893] client: found existing peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:28:30.710 ThaliTest[2128:3676893] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,2016-03-24 18:28:40.301 ThaliTest[2128:3676893] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-24 18:28:43.306 ThaliTest[2128:3677054] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:28:43.307 ThaliTest[2128:3677054] client: server will connect
2016-03-24 18:28:43.307 ThaliTest[2128:3677054] client session: reverseConnect
2016-03-24 18:28:43.307 ThaliTest[2128:3677054] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:28:43.407 ThaliTest[2128:3677723] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:28:43.408 ThaliTest[2128:3677723] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:28:43.4,08 ThaliTest[2128:3677723] client session: disconnect
2016-03-24 18:28:43.408 ThaliTest[2128:3677723] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:28:43.408 ThaliTest[2128:3677723] client session: no connect callback (server initiated)
,2016-03-24 18:28:50.693 ThaliTest[2128:3676893] multipeer manager: restart client
,2016-03-24 18:28:50.714 ThaliTest[2128:3676893] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
2016-03-24 18:28:50.715 ThaliTest[2128:3676893] client: found existing peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:28:53.308 ThaliTest[2128:3676893] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-24 18:28:56.316 ThaliTest[2128:3677054] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:28:56.316 ThaliTest[2128:3677054] client: server will connect
2016-03-24 18:28:56.317 ThaliTest[2128:3677054] client session: reverseConnect
2016-03-24 18:28:56.317 ThaliTest[2128:3677054] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:28:56.519 ThaliTest[2128:3677779] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:28:56.519 ThaliTest[2128:3677779] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:28:56.519 ThaliTest[2128:3677779] client session: disconnect
2016-03-24 18:28:56.519 ThaliTest[2128:3677779] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:28:56.521 ThaliTest[2128:3677779] client session: no connect callback (server initiated)
,2016-03-24 18:29:06.318 ThaliTest[2128:3676893] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-24 18:29:09.322 ThaliTest[2128:3677054] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:29:09.323 ThaliTest[2128:3677054] client: server will connect
2016-03-24 18:29:09.323 ThaliTest[2128:3677054] client session: reverseConn,ect
2016-03-24 18:29:09.323 ThaliTest[2128:3677054] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:29:09.628 ThaliTest[2128:3677800] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:29:09.628 ThaliTest[2128:3677800] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:29:09.6,29 ThaliTest[2128:3677800] client session: disconnect
2016-03-24 18:29:09.629 ThaliTest[2128:3677800] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:29:09.629 ThaliTest[2128:3677800] client session: no connect callb,ack (server initiated)
,2016-03-24 18:29:10.693 ThaliTest[2128:3676893] multipeer manager: restart client
,2016-03-24 18:29:10.699 ThaliTest[2128:3676893] client: found existing peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:29:10.701 ThaliTest[2128:3676893] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,2016-03-24 18:29:19.324 ThaliTest[2128:3676893] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-24 18:29:22.326 ThaliTest[2128:3677054] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:29:22.326 ThaliTest[2128:3677054] client: server will connect
2016-03-24 18:29:22.326 ThaliTest[2128:3677054] client session: reverseConn,ect
2016-03-24 18:29:22.326 ThaliTest[2128:3677054] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:29:23.144 ThaliTest[2128:3677833] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:29:23.144 ThaliTest[2128:3677833] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:29:23.144 ThaliTest[2128:3677833] client session: disconnect
,2016-03-24 18:29:23.144 ThaliTest[2128:3677833] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:29:23.145 ThaliTest[2128:3677833] client session: no connect callback (server initiated)
,2016-03-24 18:29:30.693 ThaliTest[2128:3676893] multipeer manager: restart client
,2016-03-24 18:29:30.702 ThaliTest[2128:3676893] client: found existing peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:29:30.702 ThaliTest[2128:3676893] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,2016-03-24 18:29:32.327 ThaliTest[2128:3676893] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-24 18:29:35.336 ThaliTest[2128:3677054] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:29:35.336 ThaliTest[2128:3677054] client: server will connect
2016-03-24 18:29:35.337 ThaliTest[2128:3677054] client session: reverseConnect
2016-03-24 18:29:35.337 ThaliTest[2128:3677054] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:29:35.705 ThaliTest[2128:3677888] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:29:35.705 ThaliTest[2128:3677888] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:29:35.705 ThaliTest[2128:3677888] client session: disconnect
2016-03-24 18:29:35.706 ThaliTest[2128:3677888] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:29:35.707 ThaliTest[2128:3677888] client session: no connect callback (server initiated)
,2016-03-24 18:29:45.338 ThaliTest[2128:3676893] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-24 18:29:48.346 ThaliTest[2128:3677054] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:29:48.347 ThaliTest[2128:3677054] client: server will connect
2016-03-24 18:29:48.347 ThaliTest[2128:3677054] client session: reverseConnect
2016-03-24 18:29:48.347 ThaliTest[2128:3677054] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:29:48.873 ThaliTest[2128:3677960] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:29:48.875 ThaliTest[2128:3677960] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:29:48.8,75 ThaliTest[2128:3677960] client session: disconnect
2016-03-24 18:29:48.875 ThaliTest[2128:3677960] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:29:48.875 ThaliTest[2128:3677960] client session: no connect callback (server initiated)
,2016-03-24 18:29:50.693 ThaliTest[2128:3676893] multipeer manager: restart client
,2016-03-24 18:29:50.701 ThaliTest[2128:3676893] client: found existing peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:29:50.702 ThaliTest[2128:3676893] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,2016-03-24 18:29:58.348 ThaliTest[2128:3676893] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 175 Connect failed!
,  ---
    operator: fail
  ...
,# teardown
,2016-03-24 18:29:59.664 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-24 18:29:59.665 ThaliTest[2128:3677054] jxcore: stopListeningForAdvertisements: success
ok 176 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 18:29:59.666 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening
2016-03-24 18:29:59.666 ThaliTest[2128:3677054] THEMultipeerManager stopping peer
2016-03-24 18:29:59.666 ThaliTest[2128:3677054] multipeer manager: stop client timer
2016-03-24 18:29:59.666 ThaliTest[2128:3677054] jxcore: stopAdvertisingAndListening: success
ok 177 Should be able to call stopAdvertisingAndListening in teardown
,# setup

```
