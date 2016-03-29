#### Test 64531254841497d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E8F54589-F730-4968-9B6A-9EC1EC84A2AE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E8F54589-F730-4968-9B6A-9EC1EC84A2AE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56565"
,(lldb)     command script import "/tmp/E8F54589-F730-4968-9B6A-9EC1EC84A2AE/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-29 23:40:18.050 ThaliTest[2395:4444410] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2C1A6091-A218-434A-821B-518D882A867A/Library/Cookies/Cookies.binarycookies
,2016-03-29 23:40:18.276 ThaliTest[2395:4444410] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-29 23:40:18.277 ThaliTest[2395:4444410] Multi-tasking -> Device: YES, App: YES
,2016-03-29 23:40:18.292 ThaliTest[2395:4444410] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 23:40:19.077 ThaliTest[2395:4444410] Using UIWebView
,2016-03-29 23:40:19.081 ThaliTest[2395:4444410] [CDVTimer][handleopenurl] 0.129998ms
,2016-03-29 23:40:19.084 ThaliTest[2395:4444410] [CDVTimer][intentandnavigationfilter] 3.017008ms
2016-03-29 23:40:19.084 ThaliTest[2395:4444410] [CDVTimer][gesturehandler] 0.109017ms
2016-03-29 23:40:19.084 ThaliTest[2395:4444410] [CDVTimer][TotalPluginStartup] 3.754973ms
,2016-03-29 23:40:22.202 ThaliTest[2395:4444410] Resetting plugins due to page load.
,2016-03-29 23:40:23.443 ThaliTest[2395:4444410] Finished load of: file:///var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/index.html
,2016-03-29 23:40:23.608 ThaliTest[2395:4444410] JXcore Cordova plugin initializing
,2016-03-29 23:40:23.609 ThaliTest[2395:4444601] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-29 23:40:30.654 ThaliTest[2395:4444601] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 23:40:30.655 ThaliTest[2395:4444601] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 23:40:30.655 ThaliTest[2395:4,444601] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 23:40:30.657 ThaliTest[2395:4444601] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0DB788C8-D4AA-4781-8A84-384A95EC47A8/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54110
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54112
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54115
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
,ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54119
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
DEBUG createNativeListener: listening 54124
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
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54128
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 54132
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
,DEBUG createNativeListener: listening 54136
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
DEBUG createNativeListener: listening 54140
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
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
ok 29 native server should be closed
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
DEBUG createNativeListener: listening 54192
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
,ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54196
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
,# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
,ok 47 Got the right error
,# teardown
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
# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
# teardown
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
,ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 own UUID is found from the participants list
,# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 83 specific error should be returned
# teardown
,ok 84 error should be null
ok 85 error should be null
# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 86 specific error should be returned
# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54206
,2016-03-29 23:43:11.822 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:11.823 ThaliTest[2395:44446,01] jxcore: stopListeningForAdvertisements: success
ok 89 error should be null
ok 90 error should be null
2016-03-29 23:43:11.824 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 23:43:11.827 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,# teardown
,2016-03-29 23:43:11.978 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:11.978 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:43:11.978 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 23:43:11.978 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:11.979 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
ok 94 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54208
,2016-03-29 23:43:12.255 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
,2016-03-29 23:43:12.256 ThaliTest[2395:4444601] multipeer manager: start client restart timer: 0x15e99c50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:43:12.257 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
,2016-03-29 23:43:12.277 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-29 23:43:12.278 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,# teardown
,2016-03-29 23:43:12.580 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:12.580 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:43:12.580 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
2016-03-29 23:43:12.580 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
2016-03-29 23:43:12.581 ThaliTest[2395:4444601] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:12.581 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 99 error should be null
,ok 100 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54210
,2016-03-29 23:43:13.030 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:43:13.030 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:1
2016-03-29 23:43:13.031 ThaliTest[2395:4444601] multipeer manager: start client restart timer: 0x15e99c50
2016-03-29 23:43:13.031 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:1
2016-03-29 23:43:13.031 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
,2016-03-29 23:43:13.045 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:43:13.046 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:43:13.046 ThaliTest[2395:4444601] multipeer manager: stop client timer
2016-03-29 23:43:13.046 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:2
2016-03-29 23:43:13.046 ThaliTest[2395:4444601] multipeer manager: start client restart timer: 0x15e99c50
2016-03-29 23:43:13.046 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:2
2016-03-29 23:43:13.046 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,# teardown
,2016-03-29 23:43:13.599 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:13.599 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:43:13.599 ThaliTest[2395:4444601] multipeer manager: stop client timer
20,16-03-29 23:43:13.599 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
2016-03-29 23:43:13.600 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:13.600 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 105 error should be null
ok 106 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54215
2016-03-29 23:43:35.212 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:35.212 ThaliTest[2395:4444601] THEMultipeerManager stoppi,ng peer
2016-03-29 23:43:35.212 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
2016-03-29 23:43:35.213 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:35.214 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:43:35.214 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
,ok 110 error should be null
# teardown
,2016-03-29 23:43:35.413 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:35.413 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:43:35.413 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 23:43:35.413 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:35.414 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
ok 111 error should be null
ok 112 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54217
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
# teardown
,2016-03-29 23:43:42.894 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:42.894 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:43:42.894 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
2016-03-29 23:43:42.894 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:42.895 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54219
2016-03-29 23:43:43.176 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
2016-03-29 23:43:43.176 ThaliTest[2395:4444601] multipeer manager: sta,rt client restart timer: 0x15e99c50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:43:43.177 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
,2016-03-29 23:43:43.186 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:43:43.186 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:3
2016-03-29 23:43:43.186 ThaliTest[2395:4444601] THEMultipee,rManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:3
2016-03-29 23:43:43.186 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
# teardown
,2016-03-29 23:43:43.546 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:43.547 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:43:43.547 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
2016-03-29 23:43:43.547 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
2016-03-29 23:43:43.547 ThaliTest[2395:4444601] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:43.548 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 121 error should be null
ok 122 error should be null
# setup
,# 31. does not send duplicate availability changes
,ok 123 should be called once
ok 124 should not have been called more than once
,# teardown
,ok 125 error should be null
,ok 126 error should be null
# setup
,# 32. can get the network status
,ok 127 network status should have certain non-empty properties
# teardown
,ok 128 error should be null
ok 129 error should be null
# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 130 host address should match
,ok 131 port should match
,ok 132 host address should be null
ok 133 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-03-29 23:44:25.288 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
2016-03-29 23:44:25.288 ThaliTest[2395:4444601] multipeer manager: start client restart timer: 0x15e99c50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:44:25.289 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-29 23:44:25.290 ThaliTes,t[2395:4444601] jxcore: stopListeningForAdvertisements
2016-03-29 23:44:25.290 ThaliTest[2395:4444601] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:25.290 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 23:44:25.531 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:25.531 ThaliTest[2395:44446,01] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:44:25.532 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:44:25.532 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:44:25.532 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-29 23:44:26.263 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
2016-03-29 23:44:26.263 ThaliTest[2395:4444601] multipeer manager: start client restart timer: 0x15e99c50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:44:26.264 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-29 23:44:26.265 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:44:26.265 ThaliTest[2395:4444601] jxcore: startListeningForAdv,ertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-29 23:44:29.733 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
2016-03-29 23:44:29.734 ThaliTest[2395:4444601] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-29 23:44:29.734 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:44:29.735 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:44:29.735 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:44:29.735 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-03-29 23:44:54.124 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:54.124 ThaliTest[2395:44446,01] jxcore: stopListeningForAdvertisements: success
ok 144 Can call stopListeningForAdvertisements without error
2016-03-29 23:44:54.125 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:54.126 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
ok 145 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 23:44:54.400 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:54.401 ThaliTest[2395:44446,01] jxcore: stopListeningForAdvertisements: success
ok 146 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:44:54.402 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:44:54.402 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:44:54.402 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 147 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-29 23:45:03.168 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:45:03.168 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:4
2016-03-29 23:45:03.168 ThaliTest[2395:4444601] multipeer m,anager: start client restart timer: 0x15e99c50
2016-03-29 23:45:03.169 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:4
2016-03-29 23:45:03.169 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:45:03.170 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:03.170 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
,2016-03-29 23:45:03.170 ThaliTest[2395:4444601] multipeer manager: stop client timer
2016-03-29 23:45:03.173 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 149 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-29 23:45:03.490 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:45:03.491 ThaliTest[2395:44446,01] jxcore: stopListeningForAdvertisements: success
ok 150 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:45:03.492 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:03.492 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:45:03.492 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 151 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-29 23:45:07.360 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:45:07.360 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:5
2016-03-29 23:45:07.360 ThaliTest[2395:4444601] multipeer m,anager: start client restart timer: 0x15e99c50
2016-03-29 23:45:07.361 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:5
2016-03-29 23:45:07.361 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
ok 152 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:45:07.361 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:45:07.362 ThaliTest[2395:4444601] THEMultipeerManager stopping pee,r
2016-03-29 23:45:07.362 ThaliTest[2395:4444601] multipeer manager: stop client timer
2016-03-29 23:45:07.362 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:6
2016-03-29 23:45:07.362 ThaliTest[2395:4444601] multipeer mana,ger: start client restart timer: 0x15e99c50
2016-03-29 23:45:07.363 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:6
2016-03-29 23:45:07.363 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
,ok 153 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-29 23:45:07.711 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:45:07.712 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:45:07.713 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:07.713 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
,2016-03-29 23:45:07.713 ThaliTest[2395:4444601] multipeer manager: stop client timer
,2016-03-29 23:45:07.720 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
,ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-03-29 23:45:46.288 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:46.288 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:45:46.288 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 156 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:45:46.289 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:46.289 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:45:46.289 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 157 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-29 23:45:59.496 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:45:59.496 ThaliTest[2395:44446,01] jxcore: stopListeningForAdvertisements: success
ok 158 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:45:59.497 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:59.497 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:45:59.497 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-03-29 23:45:59.905 ThaliTest[2395:4444601] jxcore: connect foo
2016-03-29 23:45:59.905 ThaliTest[2395:4444601] jxcore: connect: fail: Start browsing first
,not ok 160 got right error
  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-03-29 23:46:00.074 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 23:46:00.075 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
,ok 161 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:46:00.077 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:46:00.077 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:46:00.077 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-03-29 23:46:00.400 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:46:00.400 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:00.400 ThaliTest[2395:4444601] multipeer m,anager: start client restart timer: 0x15e99c50
2016-03-29 23:46:00.401 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:00.401 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
ok 163 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-29 23:46:00.402 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 23:46:00.403 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-29 23:46:01.595 ThaliTest[2395:4444410] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:7
ok 165 peers must be an array
ok 166 peers must not be zero-length
ok 167 peer must have peerIdentifier
ok 168 peerIdentifier must be a strin,g
ok 169 peer must have peerAvailable
ok 170 peer must have pleaseConnect
,# teardown
,2016-03-29 23:46:01.658 ThaliTest[2395:4444410] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:6
,2016-03-29 23:46:03.917 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:46:03.917 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:46:03.918 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:46:03.918 ThaliTest[2395:444460,1] THEMultipeerManager stopping peer
2016-03-29 23:46:03.918 ThaliTest[2395:4444601] multipeer manager: stop client timer
2016-03-29 23:46:03.918 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-03-29 23:46:05.392 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:46:05.392 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:05.392 ThaliTest[2395:4444601] multipeer m,anager: start client restart timer: 0x15e99c50
2016-03-29 23:46:05.392 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:05.392 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:46:05.393 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 23:46:05.394 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-29 23:46:06.246 ThaliTest[2395:4444410] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335E3B6:7","pleaseConnect":0}]
2016-03-29 23:46:06.248 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:06.248 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:46:06.248 ThaliTest[2395:4444601], client session: reverseConnect
2016-03-29 23:46:06.248 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:7
,2016-03-29 23:46:06.366 ThaliTest[2395:4444410] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:6
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E75333B-5CA8-4BAB-BD6C-23036DBD2655:6","pleaseConnect":0}]
,2016-03-29 23:46:06.807 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:06.808 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:07.928 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:07.928 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672,D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:07.987 ThaliTest[2395:4445337] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:07.988 ThaliTest[2395:4445337] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:46:07.988 ThaliTest[2395:4445337] client session: disconnect
2016-03-29 23:46:07.988 ThaliTest[2395:4445337] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:07.990 ThaliTest[2395:4445337] client session: no connect callb,ack (server initiated)
,2016-03-29 23:46:09.898 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:09.898 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:46:09.898 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:11.033 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:11.033 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:46:11.033 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:13.094 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:13.095 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:46:13.095 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:14.140 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:14.140 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:46:14.140 ThaliTest[2395:4444410], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:16.187 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:16.187 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:46:16.187 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:16.248 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:46:17.292 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:17.292 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:46:17.293 ThaliTest[2395:4444410], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:19.259 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:19.259 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:46:19.259 ThaliTest[2395:4444601] client session: reverseConn,ect
2016-03-29 23:46:19.260 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:7
,2016-03-29 23:46:19.389 ThaliTest[2395:4444410] multipeer session: reset timer
,2016-03-29 23:46:19.389 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:46:19.389 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:19.393 ThaliTest[2395:4445364] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:19.393 ThaliTest[2395:4445364] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:46:19.393 ThaliTest[2395:4445364] client session: disconnect
2016-03-29 23:46:19.393 ThaliTest[2395:4445364] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:7
,2016-03-29 23:46:19.394 ThaliTest[2395:4445364] client session: no connect callback (server initiated)
,2016-03-29 23:46:20.378 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:20.378 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:46:20.378 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:22.511 ThaliTest[2395:4444410] multipeer session: reset timer
,2016-03-29 23:46:22.511 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:46:22.511 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:23.546 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:23.547 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:46:23.547 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:25.393 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:46:25.401 ThaliTest[2395:4444410] client: found updated peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:46:25.402 ThaliTest[2395:4444410] client: found updated peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335E3B6:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8","pleaseConnect":0}]
,2016-03-29 23:46:25.638 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:25.638 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:46:25.638 ThaliTest[2395:4444410], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:26.691 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:26.691 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:46:26.691 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:28.827 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:28.828 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:46:28.828 ThaliTest[2395:4444410], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:29.261 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:46:29.817 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:29.818 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:46:29.818 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:31.915 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:31.915 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:46:31.915 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:32.271 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:32.271 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:46:32.271 ThaliTest[2395:4444601] client session: reverseConn,ect
2016-03-29 23:46:32.271 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:46:32.459 ThaliTest[2395:4445337] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:46:32.460 ThaliTest[2395:4445337] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:46:32.4,60 ThaliTest[2395:4445337] client session: disconnect
2016-03-29 23:46:32.460 ThaliTest[2395:4445337] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:46:32.460 ThaliTest[2395:4445337] client session: no connect callback (server initiated)
,2016-03-29 23:46:32.904 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:32.905 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:46:32.905 ThaliTest[2395:4444410], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:35.054 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:35.054 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:46:35.054 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:36.156 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:46:36.157 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:46:36.157 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7)
,2016-03-29 23:46:42.272 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:46:45.273 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:45.273 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:46:45.274 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:46:45.274 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:46:45.393 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:46:45.410 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:46:45.410 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
,2016-03-29 23:46:55.274 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:46:58.278 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:58.278 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:58.278 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:47:01.284 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:47:01.284 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:47:01.284 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:47:04.293 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:47:04.293 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:47:04.293 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:47:05.393 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:47:05.402 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:05.402 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
,2016-03-29 23:47:07.299 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:47:07.299 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:47:07.299 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:47:10.311 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:47:10.312 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:47:10.312 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:47:13.318 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:47:13.319 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:47:13.319 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 175 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-29 23:47:13.475 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:47:13.475 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
,ok 176 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:47:13.476 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:47:13.476 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:47:13.477 ThaliTest[2395:4444601] client session: disconnect
2016-03-29 23:47:13.477 ThaliTest[2395:4444601] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:13.477 ThaliTest[2395:4444601] multipeer manager: stop client timer
2016-03-29 23:47:13.477 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 177 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Can shift large amounts of data
,2016-03-29 23:47:15.188 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:47:15.189 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:15.189 ThaliTest[2395:4444601] multipeer m,anager: start client restart timer: 0x15e99c50
2016-03-29 23:47:15.189 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:15.189 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
ok 178 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:47:15.190 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-29 23:47:15.191 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
ok 179 Can call startListeningForAdvertisements without error
,2016-03-29 23:47:15.967 ThaliTest[2395:4444410] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:15.968 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:15.968 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:47:15.968 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:47:15.968 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:47:15.973 ThaliTest[2395:4444410] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
,2016-03-29 23:47:16.849 ThaliTest[2395:4445586] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:16.851 ThaliTest[2395:4445586] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:47:16.8,51 ThaliTest[2395:4445586] client session: disconnect
2016-03-29 23:47:16.851 ThaliTest[2395:4445586] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:16.851 ThaliTest[2395:4445586] client session: no connect callback (server initiated)
,2016-03-29 23:47:17.221 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:17.221 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:18.176 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:18.176 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:21.282 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:21.282 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:47:21.282 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:21.956 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:21.956 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:47:21.956 ThaliTest[2395:4444410], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:24.388 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:24.389 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:47:24.389 ThaliTest[2395:4444410], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:25.769 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:25.770 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:47:25.770 ThaliTest[2395:4444410], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:25.969 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:47:27.474 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:27.475 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:47:27.475 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:28.972 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:28.972 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:47:28.973 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:47:28.973 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:47:29.515 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:29.515 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:47:29.515 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:29.582 ThaliTest[2395:4445592] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:29.582 ThaliTest[2395:4445592] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:47:29.5,82 ThaliTest[2395:4445592] client session: disconnect
2016-03-29 23:47:29.582 ThaliTest[2395:4445592] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:29.582 ThaliTest[2395:4445592] client session: no connect callback (server initiated)
,2016-03-29 23:47:30.547 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:30.547 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:47:30.547 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:32.715 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:32.715 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:47:32.715 ThaliTest[2395:4444410], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:33.784 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:33.784 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:47:33.784 ThaliTest[2395:4444410], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:35.190 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:47:35.198 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:35.198 ThaliTest[2395:4444410] client: found updated peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
,2016-03-29 23:47:35.900 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:35.900 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:47:35.900 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:36.911 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:36.912 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:47:36.912 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:38.973 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:47:39.089 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:39.089 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:47:39.089 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:40.106 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:40.106 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:47:40.106 ThaliTest[2395:4444410], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:41.981 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:41.981 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:47:41.981 ThaliTest[2395:4444601] client session: reverseConn,ect
2016-03-29 23:47:41.982 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:47:42.168 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:42.169 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:47:42.169 ThaliTest[2395:4444410], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:42.214 ThaliTest[2395:4445581] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:42.215 ThaliTest[2395:4445581] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:47:42.215 ThaliTest[2395:4445581] client session: disconnect
2016-03-29 23:47:42.216 ThaliTest[2395:4445581] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:42.216 ThaliTest[2395:4445581] client session: no connect callback (server initiated)
,2016-03-29 23:47:43.235 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:43.235 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:47:43.236 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:45.296 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:45.296 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:47:45.296 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:46.363 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:46.363 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:47:46.363 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:48.440 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:47:48.441 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:47:48.441 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8)
,2016-03-29 23:47:51.983 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 7
,2016-03-29 23:47:54.993 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:47:54.993 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:47:54.993 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:47:54.993 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:47:55.190 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:47:55.205 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
,2016-03-29 23:47:55.208 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:48:04.995 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:48:08.004 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:08.004 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:08.004 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:48:11.011 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:11.011 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:11.012 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:48:14.016 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:14.016 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:14.017 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:48:15.190 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:48:15.199 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
2016-03-29 23:48:15.199 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:48:17.020 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:17.020 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:17.020 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:48:20.029 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:20.029 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:20.029 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:48:23.042 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:23.042 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:23.042 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 180 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-29 23:48:23.223 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-29 23:48:23.223 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
ok 181 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:48:23.224 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:48:23.225 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:48:23.225 ThaliTest[2395:4444601] client session: disconnect
2016-03-29 2,3:48:23.225 ThaliTest[2395:4444601] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:23.225 ThaliTest[2395:4444601] multipeer manager: stop client timer
2016-03-29 23:48:23.225 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 182 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 44. #startUpdateAdvertisingAndListening - killing remote peers connection kills the local connection
,2016-03-29 23:48:24.822 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:48:24.822 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:48:24.822 ThaliTest[2395:4444601] multipeer ,manager: start client restart timer: 0x15e99c50
2016-03-29 23:48:24.822 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:48:24.823 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
ok 183 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:48:24.823 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 23:48:24.824 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
ok 184 Can call startListeningForAdvertisements without error
,2016-03-29 23:48:25.735 ThaliTest[2395:4444410] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335E3B6:8","pleaseConnect":0}]
2016-03-29 23:48:25.737 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:25.737 ThaliTest[2395:4444410] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
2016-03-29 23:48:25.737 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:48:25.737 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:48:25.737 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIden,tifier":"7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9","pleaseConnect":0}]
,2016-03-29 23:48:27.544 ThaliTest[2395:4445744] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:27.545 ThaliTest[2395:4445744] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:48:27.545 ThaliTest[2395:4445744] client session: disconnect
2016-03-29 23:48:27.546 ThaliTest[2395:4445744] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:27.546 ThaliTest[2395:4445744] client session: no connect callback (server initiated)
,2016-03-29 23:48:27.820 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:48:27.821 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9)
,2016-03-29 23:48:31.428 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:48:31.428 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:48:31.428 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9)
,2016-03-29 23:48:34.586 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:48:34.587 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:48:34.587 ThaliTest[2395:4444410], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9)
,2016-03-29 23:48:35.742 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:48:38.227 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:48:38.227 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:48:38.227 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9)
,2016-03-29 23:48:38.752 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:38.752 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:48:38.752 ThaliTest[2395:4444601] client session: reverseConn,ect
2016-03-29 23:48:38.752 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:48:39.847 ThaliTest[2395:4445592] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:39.847 ThaliTest[2395:4445592] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:48:39.8,47 ThaliTest[2395:4445592] client session: disconnect
2016-03-29 23:48:39.848 ThaliTest[2395:4445592] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:39.848 ThaliTest[2395:4445592] client session: no connect callback (server initiated)
,2016-03-29 23:48:41.436 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:48:41.436 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:48:41.436 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9)
,2016-03-29 23:48:44.557 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:48:44.557 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:48:44.557 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9)
,2016-03-29 23:48:44.823 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:48:44.835 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:44.835 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
,2016-03-29 23:48:47.720 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:48:47.720 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:48:47.720 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9)
,2016-03-29 23:48:48.753 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:48:50.871 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:48:50.871 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:48:50.871 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9)
,2016-03-29 23:48:51.760 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:51.760 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:48:51.761 ThaliTest[2395:4444601] client session: reverseConn,ect
2016-03-29 23:48:51.761 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:48:52.117 ThaliTest[2395:4445827] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:52.118 ThaliTest[2395:4445827] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:48:52.118 ThaliTest[2395:4445827] client session: disconnect
2016-03-29 23:48:52.118 ThaliTest[2395:4445827] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:48:52.119 ThaliTest[2395:4445827] client session: no connect callback (server initiated)
,2016-03-29 23:48:53.980 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:48:53.980 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:48:53.980 ThaliTest[2395:4444410], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9)
,2016-03-29 23:48:57.127 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:48:57.127 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:48:57.127 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9)
,2016-03-29 23:49:01.762 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:49:04.764 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:04.765 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:49:04.765 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:49:04.765 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:49:04.823 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:49:04.838 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:04.839 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
,2016-03-29 23:49:14.766 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:49:17.777 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:17.777 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:17.777 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:49:20.788 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:20.789 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:20.789 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:49:23.796 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:23.796 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:23.796 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:49:24.823 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:49:24.833 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
2016-03-29 23:49:24.833 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:49:26.809 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:26.809 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:26.809 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:49:29.824 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:29.824 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:29.824 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:49:32.828 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:32.829 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:32.829 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 185 Connect failed
  ---
,    operator: fail
  ...
,# teardown
,2016-03-29 23:49:33.919 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-29 23:49:33.920 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
,ok 186 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:49:33.921 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:49:33.921 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:49:33.921 ThaliTest[2395:4444601] client session: disconnect
2016-03-29 2,3:49:33.921 ThaliTest[2395:4444601] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:33.922 ThaliTest[2395:4444601] multipeer manager: stop client timer
2016-03-29 23:49:33.922 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 187 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 45. #startUpdateAdvertisingAndListening - killing the local connection kills the connection to the remote peer
,2016-03-29 23:49:39.965 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:49:39.965 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:49:39.965 ThaliTest[2395:4444601] multipeer ,manager: start client restart timer: 0x15e99c50
2016-03-29 23:49:39.965 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:49:39.965 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 188 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:49:39.966 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertis,ingActive":true,"discoveryActive":true}
2016-03-29 23:49:39.967 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
ok 189 Can call startListeningForAdvertisements without error
,2016-03-29 23:49:40.625 ThaliTest[2395:4444410] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335E3B6:8","pleaseConnect":0}]
2016-03-29 23:49:40.626 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:40.627 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:49:40.627 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:49:40.627 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:49:40.791 ThaliTest[2395:4444410] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9","pleaseConnect":0}]
,2016-03-29 23:49:41.129 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:49:41.129 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672,D83BC4F:11 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10)
,2016-03-29 23:49:41.728 ThaliTest[2395:4445827] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:41.728 ThaliTest[2395:4445827] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:49:41.7,28 ThaliTest[2395:4445827] client session: disconnect
2016-03-29 23:49:41.729 ThaliTest[2395:4445827] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:41.729 ThaliTest[2395:4445827] client session: no connect callback (server initiated)
,2016-03-29 23:49:44.810 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:49:44.811 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:49:44.811 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10)
,2016-03-29 23:49:49.372 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:49:49.372 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:49:49.372 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10)
,2016-03-29 23:49:50.628 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 9
,2016-03-29 23:49:53.639 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:53.640 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:49:53.640 ThaliTest[2395:4444601] client session: reverseConn,ect
2016-03-29 23:49:53.640 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:49:53.773 ThaliTest[2395:4446054] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:53.773 ThaliTest[2395:4446054] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:49:53.7,73 ThaliTest[2395:4446054] client session: disconnect
2016-03-29 23:49:53.773 ThaliTest[2395:4446054] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:53.774 ThaliTest[2395:4446054] client session: no connect callback (server initiated)
,2016-03-29 23:49:53.901 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:49:53.901 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:49:53.901 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10)
,2016-03-29 23:49:57.442 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:49:57.442 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:49:57.442 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10)
,2016-03-29 23:49:59.966 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:49:59.978 ThaliTest[2395:4444410] client: found updated peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
2016-03-29 23:49:59.978 ThaliTest[2395:4444410] client: found updated peer: E4612A32-7792-490E-A387-1EC57335E3B6:11
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335E3B6:11","pleaseConnect":0}]
,2016-03-29 23:50:00.600 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:50:00.600 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:50:00.600 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10)
,2016-03-29 23:50:03.641 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:50:03.705 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:50:03.706 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:50:03.706 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10)
,2016-03-29 23:50:06.647 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:06.647 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:50:06.647 ThaliTest[2395:4444601] client session: reverseConn,ect
2016-03-29 23:50:06.647 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:11
,2016-03-29 23:50:06.876 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:50:06.877 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:50:06.877 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10)
,2016-03-29 23:50:06.940 ThaliTest[2395:4446057] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:11
2016-03-29 23:50:06.940 ThaliTest[2395:4446057] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:50:06.940 ThaliTest[2395:4446057] client session: disconnect
2016-03-29 23:50:06.940 ThaliTest[2395:4446057] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:11
2016-03-29 23:50:06.943 ThaliTest[2395:4446057] client session: no connect callback (server initiated)
,2016-03-29 23:50:09.972 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:50:09.972 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:50:09.972 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10)
,2016-03-29 23:50:13.174 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:50:13.174 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:50:13.174 ThaliTest[2395:4444410], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10)
,2016-03-29 23:50:16.648 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:50:19.662 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:19.662 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:50:19.662 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:50:19.662 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:11
,2016-03-29 23:50:19.966 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:50:19.975 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
2016-03-29 23:50:19.975 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:11
,2016-03-29 23:50:29.663 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:50:32.676 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:32.676 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:32.676 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:50:35.691 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:35.691 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:35.691 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:50:38.699 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:38.699 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:38.700 ThaliTest[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:50:39.966 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:50:39.978 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:11
,2016-03-29 23:50:39.980 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
,2016-03-29 23:50:41.715 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:41.715 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:41.715 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:50:44.721 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:44.722 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:44.722 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:50:47.733 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:47.733 ThaliTest[2395:4444601] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:50:47.733 Thali,Test[2395:4444601] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 190 Connect failed
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-29 23:50:52.529 ThaliTest[2395:4446119] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:11
2016-03-29 23:50:52.529 ThaliTest[2395:4446119] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:50:52.,529 ThaliTest[2395:4446119] client session: disconnect
2016-03-29 23:50:52.529 ThaliTest[2395:4446119] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:11
2016-03-29 23:50:52.529 ThaliTest[2395:4446119] client session: no connect callback (server initiated)
,2016-03-29 23:50:59.966 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:50:59.975 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
2016-03-29 23:50:59.975 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:11
,2016-03-29 23:51:17.791 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:51:17.792 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
,ok 191 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:51:17.793 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:51:17.793 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:51:17.793 ThaliTest[2395:4444601] multipeer manager: stop client timer
2016-03-29 23:51:17.794 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
ok 192 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 46. We do not emit peerAvailabilityChanged events until one of the start methods is called
,2016-03-29 23:51:19.868 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
2016-03-29 23:51:19.868 ThaliTest[2395:4444601] multipeer manager: start client restart timer: 0x15e99c50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:51:19.869 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
ok 193 We should start listening fine
,2016-03-29 23:51:19.870 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:51:19.870 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:19.870 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:19.870 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
ok 194 We should start updating fine
,# teardown
,2016-03-29 23:51:20.547 ThaliTest[2395:4444410] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E75333B-5CA8-4BAB-BD6C-23036DBD,2655:11","pleaseConnect":0}]
,2016-03-29 23:51:20.550 ThaliTest[2395:4444410] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:11
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335,E3B6:11","pleaseConnect":0}]
,2016-03-29 23:51:21.836 ThaliTest[2395:4444410] client: lost peer: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:51:21.836 ThaliTest[2395:4444410] client session: onPeerLost: E4612A32-7792-490E-A387-1EC57335E3B6
,2016-03-29 23:51:25.767 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-29 23:51:25.767 ThaliTest[2395:4444601] jxcore: stopListeningForAdvertisements: success
ok 195 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:51:25.768 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening
2016-03-29 23:51:25.768 ThaliTest[2395:4444601] THEMultipeerManager stopping peer
2016-03-29 23:51:25.769 ThaliTest[2395:4444601] multipeer manager: stop client timer
2016-03-29 23:51:25.769 ThaliTest[2395:4444601] jxcore: stopAdvertisingAndListening: success
,ok 196 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 47. Test updating advertising and parallel data transfer
,2016-03-29 23:51:28.235 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:51:28.235 ThaliTest[2395:4444601] server: starting 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:51:28.236 ThaliTest[2395:4444601] multipeer ,manager: start client restart timer: 0x15e99c50
2016-03-29 23:51:28.236 ThaliTest[2395:4444601] THEMultipeerManager initialized peer 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:51:28.236 ThaliTest[2395:4444601] jxcore: startUpdateAdvertisingAndListening: success
ok 197 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:51:28.236 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 23:51:28.237 ThaliTest[2395:4444601] jxcore: startListeningForAdvertisements: success
ok 198 Can call startListeningForAdvertisements without error
,2016-03-29 23:51:29.136 ThaliTest[2395:4444410] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:29.137 ThaliTest[2395:4444601] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:29.137 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:51:29.137 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:51:29.138 ThaliTest[2395:4444601] client session: stateChange:0->1 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:29.424 ThaliTest[2395:4446259] client session: not connected 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:29.425 ThaliTest[2395:4446259] client session: onLinkFailure: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:29.425 ThaliTest[2395:4446259] client session: disconnect
2016-03-29 23:51:29.425 ThaliTest[2395:4446259] client session: stateChange:1->0 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:29.425 ThaliTest[2395:4446259] client session: no connect callback (server initiated)
,2016-03-29 23:51:30.425 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:51:30.425 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672,D83BC4F:13 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11)
,2016-03-29 23:51:30.550 ThaliTest[2395:4444410] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:30.550 ThaliTest[2395:4444601] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:30.550 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:51:30.551 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:51:30.551 ThaliTest[2395:4444601] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:51:30.624 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:51:30.625 ThaliTest[2395:4444410] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12)
,2016-03-29 23:51:31.669 ThaliTest[2395:4446259] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:31.669 ThaliTest[2395:4446259] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:51:31.,669 ThaliTest[2395:4446259] client session: disconnect
2016-03-29 23:51:31.670 ThaliTest[2395:4446259] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:51:31.670 ThaliTest[2395:4446259] client session: no connect callback (server initiated)
,2016-03-29 23:51:31.790 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:51:31.790 ThaliTest[2395:4444410] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:51:31.791 ThaliTest[2395:4444410], server session: connect
2016-03-29 23:51:31.791 ThaliTest[2395:4444410] server session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:51:31.795 ThaliTest[2395:4444410] server: accepting invitation E4612A32-7792-490E-A387-1EC57335E3B6
,2016-03-29 23:51:34.489 ThaliTest[2395:4446260] server session: p2p link connected
,2016-03-29 23:51:34.772 ThaliTest[2395:4444410] server relay: connected (to port: 54271)
2016-03-29 23:51:34.773 ThaliTest[2395:4444410] server session: stateChange:1->2 E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:34.773 ThaliTest[2395:44444,10] jxcore: connect: success
,DEBUG testThaliMobileNative: Got recoverable client error Error: ListeningPort is 0
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,2016-03-29 23:51:34.911 ThaliTest[2395:4444410] server relay: socket disconnected
2016-03-29 23:51:34.911 ThaliTest[2395:4444410] server relay: 0x176dfbc0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,ok 199 At least one should fire before we hit close
,2016-03-29 23:51:36.308 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:51:36.308 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:51:36.308 ThaliTest[2395:4444410], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11)
,2016-03-29 23:51:39.138 ThaliTest[2395:4444410] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:51:39.668 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:51:39.668 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:51:39.668 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11)
,2016-03-29 23:51:42.148 ThaliTest[2395:4444601] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:42.148 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:51:42.148 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:51:42.149 ThaliTest[2395:4444601] client session: stateChange:0->1 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:42.268 ThaliTest[2395:4446259] client session: not connected 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:42.269 ThaliTest[2395:4446259] client session: onLinkFailure: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:42.269 ThaliTest[2395:4446259] client session: disconnect
2016-03-29 23:51:42.270 ThaliTest[2395:4446259] client session: stateChange:1->0 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:42.270 ThaliTest[2395:4446259] client session: no connect callback (server initiated)
,2016-03-29 23:51:42.746 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:51:42.746 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:51:42.746 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11)
,2016-03-29 23:51:45.930 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:51:45.930 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:51:45.930 ThaliTest[2395:4444410] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13 != 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11)
,2016-03-29 23:51:48.236 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:51:48.247 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:48.247 ThaliTest[2395:4444410] client: found updated peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:51:48.248 ThaliTest[2395:4444601] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:51:48.248 ThaliTest[2395:4444601] client: server will connect
2016-03-29 23:51:48.251 ThaliTest[2395:4444601] client session: reverseConnect
2016-03-29 23:51:48.251 ThaliTest[2395:4444601] client session: stateChange:0->1 7E75333B-5CA8-4BAB,-BD6C-23036DBD2655:13
,2016-03-29 23:51:48.525 ThaliTest[2395:4444410] multipeer session: reset timer
2016-03-29 23:51:48.525 ThaliTest[2395:4444410] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:51:48.525 ThaliTest[2395:4444410] server session: connect
2016-03-29 23:51:48.525 ThaliTest[2395:4444410] server session: stateChange:0->1 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:51:48.530 ThaliTest[2395:4444410] server: accepting invitation 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
,2016-03-29 23:51:48.533 ThaliTest[2395:4446291] client session: not connected 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:51:48.534 ThaliTest[2395:4446291] client session: onLinkFailure: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:48.535 ThaliTest[2395:4446291] client session: disconnect
2016-03-29 23:51:48.535 ThaliTest[2395:4446291] client session: stateChange:1->0 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:51:48.535 ThaliTest[2395:4446291] client session: no connect callback (server initiated)
,2016-03-29 23:51:50.044 ThaliTest[2395:4446119] server session: p2p link connected
,2016-03-29 23:51:50.057 ThaliTest[2395:4444410] server relay: connected (to port: 54271)
,2016-03-29 23:51:50.059 ThaliTest[2395:4444410] server session: stateChange:1->2 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:51:50.059 ThaliTest[2395:4444410] jxcore: connect: success
,DEBUG testThaliMobileNative: Got recoverable client error Error: ListeningPort is 0
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,2016-03-29 23:52:08.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:52:08.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:52:08.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:52:28.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:52:28.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:52:28.245 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:52:39.870 ThaliTest[2395:4446410] server session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:52:48.236 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:52:48.244 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:52:48.244 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:52:55.140 ThaliTest[2395:4446410] server session: not connected 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:53:08.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:53:08.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:53:08.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:53:28.236 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:53:28.245 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:53:28.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:53:48.236 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:53:48.244 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:53:48.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:54:08.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:54:08.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:54:08.247 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:54:28.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:54:28.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:54:28.245 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:54:48.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:54:48.248 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:54:48.248 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:55:08.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:55:08.247 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:55:08.247 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:55:28.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:55:28.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:55:28.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:55:48.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:55:48.245 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:55:48.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:56:08.236 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:56:08.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:56:08.245 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:56:28.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:56:28.247 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:56:28.247 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:56:48.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:56:48.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:56:48.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:57:08.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:57:08.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:57:08.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:57:28.236 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:57:28.245 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:57:28.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:57:48.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:57:48.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:57:48.245 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:58:08.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:58:08.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:58:08.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:58:28.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:58:28.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:58:28.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:58:48.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:58:48.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:58:48.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:59:08.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:59:08.244 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:59:08.245 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:59:28.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:59:28.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:59:28.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:59:48.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-29 23:59:48.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:59:48.247 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-30 00:00:08.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-30 00:00:08.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-30 00:00:08.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-30 00:00:28.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-30 00:00:28.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-30 00:00:28.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-30 00:00:48.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-30 00:00:48.247 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-30 00:00:48.247 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-30 00:01:08.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-30 00:01:08.251 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-30 00:01:08.251 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-30 00:01:28.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-30 00:01:28.247 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-30 00:01:28.247 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-30 00:01:48.237 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-30 00:01:48.246 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-30 00:01:48.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-30 00:02:08.236 ThaliTest[2395:4444410] multipeer manager: restart client
,2016-03-30 00:02:08.245 ThaliTest[2395:4444410] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-30 00:02:08.246 ThaliTest[2395:4444410] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13

```
