#### Test 6539483973f7970_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/29902FD7-83A0-469E-B8E6-C54617B591B7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/29902FD7-83A0-469E-B8E6-C54617B591B7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51002"
,(lldb)     command script import "/tmp/29902FD7-83A0-469E-B8E6-C54617B591B7/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-06 03:09:28.522 ThaliTest[2169:5781774] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/37299F03-2800-4862-9F6A-1D07346BC7DF/Library/Cookies/Cookies.binarycookies
,2016-04-06 03:09:28.633 ThaliTest[2169:5781774] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-06 03:09:28.635 ThaliTest[2169:5781774] Multi-tasking -> Device: YES, App: YES
,2016-04-06 03:09:28.655 ThaliTest[2169:5781774] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-06 03:09:29.867 ThaliTest[2169:5781774] Using UIWebView
,2016-04-06 03:09:29.873 ThaliTest[2169:5781774] [CDVTimer][handleopenurl] 0.279009ms
,2016-04-06 03:09:29.877 ThaliTest[2169:5781774] [CDVTimer][intentandnavigationfilter] 4.392982ms
2016-04-06 03:09:29.878 ThaliTest[2169:5781774] [CDVTimer][gesturehandler] 0.235021ms
2016-04-06 03:09:29.878 ThaliTest[2169:5781774] [CDVTimer][TotalPluginS,tartup] 5.795002ms
,2016-04-06 03:09:34.931 ThaliTest[2169:5781774] Resetting plugins due to page load.
,2016-04-06 03:09:37.147 ThaliTest[2169:5781774] Finished load of: file:///var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/index.html
,2016-04-06 03:09:37.350 ThaliTest[2169:5781774] JXcore Cordova plugin initializing
,2016-04-06 03:09:37.352 ThaliTest[2169:5781916] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-04-06 03:09:51.512 ThaliTest[2169:5781916] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-06 03:09:51.514 ThaliTest[2169:5781916] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-06 03:09:51.515 ThaliTest[2169:5781916] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {,"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-06 03:09:51.517 ThaliTest[2169:5781916] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66745922-5B14-4A93-8097-05FF92F4D2DB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58502
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58504
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58507
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
,# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58511
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
,ok 9 Send/recvd #2 should be equal length
,ok 10 Send/recvd #2 should be same
,ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58516
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
DEBUG createNativeListener: listening 58520
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
,ok 16 incoming is cleaned up
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58524
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
DEBUG createNativeListener: listening 58528
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed,
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58532
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
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListene,r: new stream: 
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
,DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
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
DEBUG ,createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 nati,ve server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
D,EBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58584
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
,ok 33 server should be fine
,ok 34 server should be open
,ok 35 incoming has been removed
,ok 36 The mux object should be closed
,ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58588
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
ok 43 The mux object should be c,losed
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
,ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
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
,[{"uuid":"23004744-777a-4286-80e8-7c39ced52031","data":"custom data"},{"uuid":"b9648362-bd7c-4ccf-8c9e-e657f2368bf5","data":"custom data"},{"uuid":"1e708892-c95f-4713-9eb4-ebedb0ff7757","data":"custom data"},{"uuid":"c99173ba-aafb-407b-a44f-72a198cb56d8",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83 participant data matches
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
DEBUG createNativeListener: listening 58598
2016-04-06 03:13:22.213 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:22.215 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-06 03:13:22.217 ThaliTest[2169:5781916] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:13:22.218 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-06 03:13:22.304 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:22.304 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:13:22.304 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-06 03:13:22.305 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:22.306 ThaliTest[2169,:5781916] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
,ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58600
,2016-04-06 03:13:22.483 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements
,2016-04-06 03:13:22.485 ThaliTest[2169:5781916] multipeer manager: start client restart timer: 0x175a5670
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-06 03:13:22.486 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-06 03:13:22.500 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-06 03:13:22.501 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-06 03:13:22.836 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:22.836 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:13:22.836 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-06 03:13:22.836 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
2016-04-06 03:13:22.837 ThaliTest[2169:5781916] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:22.838 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58602
2016-04-06 03:13:23.278 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:13:23.278 ThaliTest[2169:5781916] server: starting C5E616F6-311E-4AAE-ABEF-071095D8F02C:1
2016-04-06 03:,13:23.278 ThaliTest[2169:5781916] multipeer manager: start client restart timer: 0x175a5670
2016-04-06 03:13:23.279 ThaliTest[2169:5781916] THEMultipeerManager initialized peer C5E616F6-311E-4AAE-ABEF-071095D8F02C:1
2016-04-06 03:13:23.279 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-06 03:13:23.291 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:13:23.291 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:13:23.291, ThaliTest[2169:5781916] multipeer manager: stop client timer
2016-04-06 03:13:23.292 ThaliTest[2169:5781916] server: starting C5E616F6-311E-4AAE-ABEF-071095D8F02C:2
2016-04-06 03:13:23.292 ThaliTest[2169:5781916] multipeer manager: start client restart ,timer: 0x175a5670
2016-04-06 03:13:23.292 ThaliTest[2169:5781916] THEMultipeerManager initialized peer C5E616F6-311E-4AAE-ABEF-071095D8F02C:2
,2016-04-06 03:13:23.292 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
,# teardown
,2016-04-06 03:13:23.451 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:23.451 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:13:23.451 ThaliTest[2169:5781916] multipeer manager: stop client timer
20,16-04-06 03:13:23.451 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:23.452 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:23.453 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58607
,2016-04-06 03:13:44.941 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:44.941 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:13:44.942 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: suc,cess
ok 109 error should be null
ok 110 error should be null
2016-04-06 03:13:44.944 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:44.945 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:13:44.945 ,ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-06 03:13:57.072 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:57.072 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:13:57.073 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-06 03:13:57.073 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:57.074 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58609
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-06 03:13:59.027 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:59.028 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:13:59.028 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-06 03:13:59.028 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:59.029 ThaliTest[2169,:5781916] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58611
2016-04-06 03:13:59.223 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements
2016-04-06 03:13:59.223 ThaliTest[2169:5781916] multipeer manager: start client restart timer: 0x175a5670
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:13:59.224 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements: success
,2016-04-06 03:13:59.241 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:13:59.242 ThaliTest[2169:5781916] server: starting C5E616F6-311E-4AAE-ABEF-071095D8F02C:3
2016-04-06 03:13:59.242 ThaliTest[2169:5781916] THEMultipee,rManager initialized peer C5E616F6-311E-4AAE-ABEF-071095D8F02C:3
2016-04-06 03:13:59.242 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-06 03:13:59.358 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:59.359 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:13:59.359 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-06 03:13:59.359 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
2016-04-06 03:13:59.359 ThaliTest[2169:5781916] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:59.360 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 123 error should be null
ok 124 error should be null
# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
ok 126 should not have been called more than once
,# teardown
,ok 127 error should be null
ok 128 error should be null
,# setup
,# 32. can get the network status
,ok 129 network status should have certain non-empty properties
,# teardown
,ok 130 error should be null
ok 131 error should be null
# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
,ok 133 port should match
,ok 134 host address should be null
ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-06 03:14:46.121 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements
2016-04-06 03:14:46.121 ThaliTest[2169:5781916] multipeer manager: start client restart timer: 0x175a5670
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:14:46.122 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-06 03:14:46.124 ThaliTes,t[2169:5781916] jxcore: stopListeningForAdvertisements
2016-04-06 03:14:46.124 ThaliTest[2169:5781916] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-04-06 03:14:46.125 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-06 03:14:46.220 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:46.221 ThaliTest[2169:57819,16] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:14:46.222 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:14:46.222 ThaliTest[2169:57819,16] THEMultipeerManager stopping peer
2016-04-06 03:14:46.222 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-06 03:14:46.546 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements
2016-04-06 03:14:46.547 ThaliTest[2169:5781916] multipeer manager: start client restart timer: 0x175a5670
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:14:46.548 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-06 03:14:46.549 ThaliTes,t[2169:5781916] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:14:46.549 ThaliTest[2169:5781916] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-06 03:14:46.908 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
2016-04-06 03:14:46.908 ThaliTest[2169:5781916] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-06 03:14:46.909 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:14:46.910 ThaliTest[2169:5781,916] jxcore: stopAdvertisingAndListening
2016-04-06 03:14:46.910 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:14:46.910 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-06 03:14:47.095 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:47.096 ThaliTest[2169:57819,16] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-06 03:14:47.097 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:47.098 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-06 03:14:49.738 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:49.739 ThaliTest[2169:57819,16] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:14:49.740 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:14:49.740 ThaliTest[2169:57819,16] THEMultipeerManager stopping peer
2016-04-06 03:14:49.741 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-06 03:15:33.205 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:15:33.205 ThaliTest[2169:5781916] server: starting C5E616F6-311E-4AAE-ABEF-071095D8F02C:4
2016-04-06 03:15:33.206 ThaliTest[2169:5781916] multipeer m,anager: start client restart timer: 0x175a5670
2016-04-06 03:15:33.206 ThaliTest[2169:5781916] THEMultipeerManager initialized peer C5E616F6-311E-4AAE-ABEF-071095D8F02C:4
2016-04-06 03:15:33.206 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:15:33.207 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:33.208 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
,2016-04-06 03:15:33.208 ThaliTest[2169:5781916] multipeer manager: stop client timer
2016-04-06 03:15:33.214 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-06 03:15:33.992 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:15:33.993 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:15:33.994 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:33.995 ThaliTest[2169:57819,16] THEMultipeerManager stopping peer
2016-04-06 03:15:33.995 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-06 03:15:37.634 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:15:37.634 ThaliTest[2169:5781916] server: starting C5E616F6-311E-4AAE-ABEF-071095D8F02C:5
2016-04-06 03:15:37.635 ThaliTest[2169:5781916] multipeer m,anager: start client restart timer: 0x175a5670
2016-04-06 03:15:37.635 ThaliTest[2169:5781916] THEMultipeerManager initialized peer C5E616F6-311E-4AAE-ABEF-071095D8F02C:5
2016-04-06 03:15:37.635 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:15:37.637 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:15:37.637 ThaliTest[2169:5781916] THEMultipeerManager stopping pee,r
2016-04-06 03:15:37.637 ThaliTest[2169:5781916] multipeer manager: stop client timer
2016-04-06 03:15:37.637 ThaliTest[2169:5781916] server: starting C5E616F6-311E-4AAE-ABEF-071095D8F02C:6
2016-04-06 03:15:37.638 ThaliTest[2169:5781916] multipeer man,ager: start client restart timer: 0x175a5670
2016-04-06 03:15:37.639 ThaliTest[2169:5781916] THEMultipeerManager initialized peer C5E616F6-311E-4AAE-ABEF-071095D8F02C:6
2016-04-06 03:15:37.639 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndList,ening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-04-06 03:15:37.656 ThaliTest[2169:5781774] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:6
,2016-04-06 03:15:38.149 ThaliTest[2169:5781774] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:6
,2016-04-06 03:15:41.405 ThaliTest[2169:5781774] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:6
,2016-04-06 03:15:43.175 ThaliTest[2169:5781774] client: lost peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:15:43.176 ThaliTest[2169:5781774] client session: onPeerLost: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:15:43.288 ThaliTest[2169:5781774] client: lost peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:15:43.288 ThaliTest[2169:5781774] client session: onPeerLost: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
,2016-04-06 03:15:50.276 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-06 03:15:50.277 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:15:50.278 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:50.279 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:15:50.279 ThaliTest[2169:5781916] multipeer manager: stop client timer
2016-04-06 03:15:50.279 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-06 03:16:38.056 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.056 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:16:38.056 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:16:38.057 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.058 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:16,:38.058 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-06 03:16:38.161 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:16:38.162 ThaliTest[2169:57819,16] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:16:38.163 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.163 ThaliTest[2169:57819,16] THEMultipeerManager stopping peer
2016-04-06 03:16:38.163 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-06 03:16:38.374 ThaliTest[2169:5781916] jxcore: connect foo
2016-04-06 03:16:38.374 ThaliTest[2169:5781916] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvert,isements is not active'
    actual:   'Start browsing first'
  ...
,# teardown
,2016-04-06 03:16:38.512 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:16:38.514 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:16:38.516 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.516 ThaliTest[2169:5781916] THEMultipeerManager stopping peer
2016-04-06 03:16:38.516 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-06 03:16:38.678 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening
,2016-04-06 03:16:38.679 ThaliTest[2169:5781916] server: starting C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:16:38.681 ThaliTest[2169:5781916] multipeer manager: start client restart timer: 0x175a5670
,2016-04-06 03:16:38.688 ThaliTest[2169:5781916] THEMultipeerManager initialized peer C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:16:38.691 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening: success
,ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-06 03:16:38.693 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-06 03:16:38.696 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-06 03:16:39.716 ThaliTest[2169:5781774] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-06 03:16:39.786 ThaliTest[2169:5781774] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
,2016-04-06 03:16:39.874 ThaliTest[2169:5781774] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,2016-04-06 03:16:46.350 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-06 03:16:46.351 ThaliTest[2169:578191,6] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:16:46.351 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:46.352 ThaliTest[2169:578191,6] THEMultipeerManager stopping peer
2016-04-06 03:16:46.352 ThaliTest[2169:5781916] multipeer manager: stop client timer
2016-04-06 03:16:46.352 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-06 03:16:47.156 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:16:47.156 ThaliTest[2169:5781916] server: starting C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:16:47.156 ThaliTest[2169:5781916] multipeer manager: start client restart timer: 0x175a5670
2016-04-06 03:16:47.157 ThaliTest[2169:5781916] THEMultipeerManager initialized peer C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:16:47.157 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:16:47.158 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-06 03:16:47.159 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-06 03:16:48.077 ThaliTest[2169:5781774] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:48.077 ThaliTest[2169:5781774] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7","pleaseConnect":0}]
2016-04-06 03:16:48.079 ThaliTest[2169:5781916] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
,2016-04-06 03:16:48.080 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:16:48.081 ThaliTest[2169:5781916] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7","pleaseConnect":0}]
,2016-04-06 03:16:48.195 ThaliTest[2169:5781774] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"8C5B19F5-9879-44C8-A20C-4970704F4B6A:7","pleaseConnect":0}]
,2016-04-06 03:16:48.313 ThaliTest[2169:5782733] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:48.314 ThaliTest[2169:5782733] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:16:48.314 ThaliTest[2169:5782733] client session: disconnect
2016-04-06 03:16:48.315 ThaliTest[2169:5782733] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
,2016-04-06 03:16:48.315 ThaliTest[2169:5782733] client session: fireConnectCallback: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:16:48.315 ThaliTest[2169:5782733] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-06 03:16:49.426 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:16:49.426 ThaliTest[2169:5781774] server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (C5E616F6-311E-4AAE-ABEF-07109,5D8F02C:8 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:7)
,2016-04-06 03:16:51.326 ThaliTest[2169:5781916] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:51.326 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:16:51.327 ThaliTest[2169:5781916] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
,2016-04-06 03:16:51.783 ThaliTest[2169:5782768] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:51.784 ThaliTest[2169:5782768] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:16:51.7,85 ThaliTest[2169:5782768] client session: disconnect
2016-04-06 03:16:51.786 ThaliTest[2169:5782768] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:51.786 ThaliTest[2169:5782768] client session: fireConnectCallb,ack: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:16:51.786 ThaliTest[2169:5782768] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-06 03:16:54.793 ThaliTest[2169:5781916] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:54.793 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:16:54.793 ThaliTest[2169:5781916] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
,2016-04-06 03:16:54.991 ThaliTest[2169:5782781] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:54.992 ThaliTest[2169:5782781] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:16:54.9,93 ThaliTest[2169:5782781] client session: disconnect
2016-04-06 03:16:54.993 ThaliTest[2169:5782781] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:54.993 ThaliTest[2169:5782781] client session: fireConnectCallb,ack: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:16:54.994 ThaliTest[2169:5782781] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-06 03:16:57.995 ThaliTest[2169:5781916] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:57.996 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:16:57.996 ThaliTest[2169:5781916] client session: stateChange:0->,1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
,2016-04-06 03:16:58.139 ThaliTest[2169:5782769] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:58.140 ThaliTest[2169:5782769] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:16:58.140 ThaliTest[2169:5782769] client session: disconnect
2016-04-06 03:16:58.140 ThaliTest[2169:5782769] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:58.143 ThaliTest[2169:5782769] client session: fireConnectCallb,ack: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:16:58.143 ThaliTest[2169:5782769] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-06 03:17:01.156 ThaliTest[2169:5781916] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:17:01.156 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:17:01.157 ThaliTest[2169:5781916] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
,2016-04-06 03:17:01.290 ThaliTest[2169:5782733] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:17:01.290 ThaliTest[2169:5782733] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:01.2,91 ThaliTest[2169:5782733] client session: disconnect
2016-04-06 03:17:01.291 ThaliTest[2169:5782733] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:17:01.292 ThaliTest[2169:5782733] client session: fireConnectCallb,ack: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:01.292 ThaliTest[2169:5782733] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-06 03:17:01.347 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:17:01.348 ThaliTest[2169:5781774] server: disconnecting to refresh session (8C5B19F5-9879-44C8-A20C-4970704F4B6A)
2016-04-06 03:17:01.348 ThaliTest[2169:5781774], server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:8 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:7)
,2016-04-06 03:17:04.297 ThaliTest[2169:5781916] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:17:04.297 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:17:04.297 ThaliTest[2169:5781916] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
,2016-04-06 03:17:04.383 ThaliTest[2169:5782781] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:17:04.385 ThaliTest[2169:5782781] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:04.3,86 ThaliTest[2169:5782781] client session: disconnect
2016-04-06 03:17:04.386 ThaliTest[2169:5782781] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:17:04.386 ThaliTest[2169:5782781] client session: fireConnectCallb,ack: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:04.386 ThaliTest[2169:5782781] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 4
,2016-04-06 03:17:07.158 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:17:07.184 ThaliTest[2169:5781774] client: found updated peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:07.185 ThaliTest[2169:5781774] client: found updated peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
INFO testThaliMobileNati,ve: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier,":"8C5B19F5-9879-44C8-A20C-4970704F4B6A:8","pleaseConnect":0}]
2016-04-06 03:17:07.186 ThaliTest[2169:5781774] client: found updated peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8","pleaseConnect":0}]
,2016-04-06 03:17:07.398 ThaliTest[2169:5781916] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:17:07.398 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:17:07.398 ThaliTest[2169:5781916] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:17:07.576 ThaliTest[2169:5782781] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:07.577 ThaliTest[2169:5782781] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:07.5,77 ThaliTest[2169:5782781] client session: disconnect
2016-04-06 03:17:07.577 ThaliTest[2169:5782781] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:07.578 ThaliTest[2169:5782781] client session: fireConnectCallb,ack: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:07.578 ThaliTest[2169:5782781] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-06 03:17:10.590 ThaliTest[2169:5781916] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:17:10.590 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:17:10.591 ThaliTest[2169:5781916] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:17:10.716 ThaliTest[2169:5782781] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:10.717 ThaliTest[2169:5782781] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:10.7,17 ThaliTest[2169:5782781] client session: disconnect
2016-04-06 03:17:10.718 ThaliTest[2169:5782781] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:10.718 ThaliTest[2169:5782781] client session: fireConnectCallb,ack: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:10.719 ThaliTest[2169:5782781] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-06 03:17:13.725 ThaliTest[2169:5781916] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:17:13.725 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:17:13.725 ThaliTest[2169:5781916] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:17:13.928 ThaliTest[2169:5782782] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:13.929 ThaliTest[2169:5782782] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
,2016-04-06 03:17:13.931 ThaliTest[2169:5782782] client session: disconnect
,2016-04-06 03:17:13.931 ThaliTest[2169:5782782] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:17:13.932 ThaliTest[2169:5782782] client session: fireConnectCallback: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:13.932 ThaliTest[2169:5782782] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-06 03:17:14.254 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:17:14.255 ThaliTest[2169:5781774] server: disconnecting to refresh session (8C5B19F5-9879-44C8-A20C-4970704F4B6A)
2016-04-06 03:17:14.255 ThaliTest[2169:5781774] server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:8 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:7)
,2016-04-06 03:17:16.935 ThaliTest[2169:5781916] jxcore: connect BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:17:16.936 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:17:16.936 ThaliTest[2169:5781916] client session: stateChange:0->1 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:17:17.073 ThaliTest[2169:5782782] client session: not connected BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:17.074 ThaliTest[2169:5782782] client session: onLinkFailure: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:17.0,74 ThaliTest[2169:5782782] client session: disconnect
2016-04-06 03:17:17.074 ThaliTest[2169:5782782] client session: stateChange:1->0 BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:17.074 ThaliTest[2169:5782782] client session: fireConnectCallb,ack: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
2016-04-06 03:17:17.076 ThaliTest[2169:5782782] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
not ok 177 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-04-06 03:17:20.516 ThaliTest[2169:5781774] client: lost peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:20.517 ThaliTest[2169:5781774] client session: onPeerLost: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:17:27.158 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:17:27.179 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:27.179 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:17:27.18,0 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8","pleaseConnect":0}]
,2016-04-06 03:17:40.271 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:17:40.271 ThaliTest[2169:5781774] server: disconnecting to refresh session (8C5B19F5-9879-44C8-A20C-4970704F4B6A)
2016-04-06 03:17:40.271 ThaliTest[2169:5781774] server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:8 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:7)
,2016-04-06 03:17:47.158 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:17:47.188 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:47.188 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
,2016-04-06 03:17:47.199 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:17:53.143 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:17:53.143 ThaliTest[2169:5781774] server: disconnecting to refresh session (8C5B19F5-9879-44C8-A20C-4970704F4B6A)
2016-04-06 03:17:53.143 ThaliTest[2169:5781774], server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:8 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:7)
,2016-04-06 03:17:55.373 ThaliTest[2169:5781774] client: lost peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:55.374 ThaliTest[2169:5781774] client session: onPeerLost: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:18:01.660 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8","pleaseConnect":0}]
,2016-04-06 03:18:06.337 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:18:06.338 ThaliTest[2169:5781774] server: disconnecting to refresh session (8C5B19F5-9879-44C8-A20C-4970704F4B6A)
2016-04-06 03:18:06.338 ThaliTest[2169:5781774] server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:8 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:7)
,2016-04-06 03:18:07.158 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:18:07.191 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:07.192 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:18:07.19,2 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
,2016-04-06 03:18:19.447 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:18:19.447 ThaliTest[2169:5781774] server: disconnecting to refresh session (8C5B19F5-9879-44C8-A20C-4970704F4B6A)
2016-04-06 03:18:19.448 ThaliTest[2169:5781774], server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:8 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:7)
,2016-04-06 03:18:27.158 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:18:27.183 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:18:27.183 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:18:27.195 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:18:32.604 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:18:32.604 ThaliTest[2169:5781774] server: disconnecting to refresh session (8C5B19F5-9879-44C8-A20C-4970704F4B6A)
2016-04-06 03:18:32.604 ThaliTest[2169:5781774], server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:8 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:7)
,2016-04-06 03:18:45.194 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:18:45.195 ThaliTest[2169:5781774] server: disconnecting to refresh session (8C5B19F5-9879-44C8-A20C-4970704F4B6A)
2016-04-06 03:18:45.195 ThaliTest[2169:5781774], server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:8 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:7)
,2016-04-06 03:18:47.158 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:18:47.183 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:18:47.195 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:18:47.197 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:18:55.748 ThaliTest[2169:5781916] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-06 03:18:55.749 ThaliTest[2169:578191,6] jxcore: stopListeningForAdvertisements: success
ok 178 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:18:55.750 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening
2016-04-06 03:18:55.750 ThaliTest[2169:578191,6] THEMultipeerManager stopping peer
2016-04-06 03:18:55.750 ThaliTest[2169:5781916] multipeer manager: stop client timer
2016-04-06 03:18:55.751 ThaliTest[2169:5781916] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-06 03:18:56.458 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:18:56.458 ThaliTest[2169:5781916] server: starting C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:18:56.458 ThaliTest[2169:5781916] multipeer m,anager: start client restart timer: 0x175a5670
2016-04-06 03:18:56.459 ThaliTest[2169:5781916] THEMultipeerManager initialized peer C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:18:56.459 ThaliTest[2169:5781916] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:18:56.460 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-06 03:18:56.461 ThaliTest[2169:5781916] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-06 03:18:57.368 ThaliTest[2169:5781774] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:57.368 ThaliTest[2169:5781774] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:18:57.370 ThaliTes,t[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:57.370 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:18:57.371 ThaliTest[2169:5781916] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:18:57.587 ThaliTest[2169:5781774] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
,2016-04-06 03:18:57.845 ThaliTest[2169:5783130] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:57.845 ThaliTest[2169:5783130] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:18:57.8,46 ThaliTest[2169:5783130] client session: disconnect
2016-04-06 03:18:57.847 ThaliTest[2169:5783130] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:57.849 ThaliTest[2169:5783130] client session: fireConnectCallb,ack: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:18:57.849 ThaliTest[2169:5783130] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-06 03:18:58.049 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:18:58.049 ThaliTest[2169:5781774] server: rejecting invitation from 7DE50CBF-CC92-4CD5-AA12-B28CD384766D due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:9 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:8)
,2016-04-06 03:19:00.858 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:00.859 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:19:00.859 ThaliTest[2169:5781916] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:01.186 ThaliTest[2169:5783130] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:01.187 ThaliTest[2169:5783130] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:01.1,87 ThaliTest[2169:5783130] client session: disconnect
2016-04-06 03:19:01.187 ThaliTest[2169:5783130] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:01.188 ThaliTest[2169:5783130] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:19:01.188 ThaliTest[2169:5783130] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-06 03:19:04.201 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:04.201 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:19:04.201 ThaliTest[2169:5781916] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:04.411 ThaliTest[2169:5783144] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:04.412 ThaliTest[2169:5783144] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:04.4,12 ThaliTest[2169:5783144] client session: disconnect
2016-04-06 03:19:04.412 ThaliTest[2169:5783144] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:04.413 ThaliTest[2169:5783144] client session: fireConnectCallb,ack: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:04.413 ThaliTest[2169:5783144] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-06 03:19:07.419 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:07.419 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:19:07.419 ThaliTest[2169:5781916] client session: stateChange:0->,1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:07.576 ThaliTest[2169:5783144] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:07.577 ThaliTest[2169:5783144] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:07.577 ThaliTest[2169:5783144] client session: disconnect
,2016-04-06 03:19:07.578 ThaliTest[2169:5783144] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:07.579 ThaliTest[2169:5783144] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 0,3:19:07.579 ThaliTest[2169:5783144] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-06 03:19:10.587 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:10.587 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:19:10.588 ThaliTest[2169:5781916] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:10.751 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:19:10.751 ThaliTest[2169:5781774] server: disconnecting to refresh session (7DE50CBF-CC92-4CD5-AA12-B28CD384766D)
2016-04-06 03:19:10.751 ThaliTest[2169:5781774], server: rejecting invitation from 7DE50CBF-CC92-4CD5-AA12-B28CD384766D due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:9 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:8)
,2016-04-06 03:19:10.761 ThaliTest[2169:5783131] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:10.763 ThaliTest[2169:5783131] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:19:10.764 ThaliTest[2169:5783131] client session: disconnect
2016-04-06 03:19:10.765 ThaliTest[2169:5783131] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:10.766 ThaliTest[2169:5783131] client sess,ion: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:10.766 ThaliTest[2169:5783131] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-06 03:19:13.775 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:13.775 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:19:13.775 ThaliTest[2169:5781916] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:13.883 ThaliTest[2169:5783130] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:13.884 ThaliTest[2169:5783130] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:13.8,84 ThaliTest[2169:5783130] client session: disconnect
2016-04-06 03:19:13.884 ThaliTest[2169:5783130] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:13.885 ThaliTest[2169:5783130] client session: fireConnectCallb,ack: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:13.885 ThaliTest[2169:5783130] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-06 03:19:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:19:16.485 ThaliTest[2169:5781774] client: found updated peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:19:16.485 ThaliTest[2169:5781774] client: found updated peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:19:16.494 ThaliTest[2169:5781774] client: found updated peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:16.895 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:16.895 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:19:16.895 ThaliTest[2169:5781916] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:17.048 ThaliTest[2169:5783131] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:17.049 ThaliTest[2169:5783131] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:17.0,49 ThaliTest[2169:5783131] client session: disconnect
2016-04-06 03:19:17.049 ThaliTest[2169:5783131] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:17.051 ThaliTest[2169:5783131] client session: fireConnectCallb,ack: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:17.051 ThaliTest[2169:5783131] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 3
,2016-04-06 03:19:20.056 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:20.056 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:19:20.056 ThaliTest[2169:5781916] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:20.151 ThaliTest[2169:5783131] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:20.151 ThaliTest[2169:5783131] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:19:20.151 ThaliTest[2169:5783131] client session: disconnect
2016-04-06 03:19:20.152 ThaliTest[2169:5783131] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:20.153 ThaliTest[2169:5783131] client sess,ion: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:20.153 ThaliTest[2169:5783131] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-06 03:19:23.167 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:23.168 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:19:23.168 ThaliTest[2169:5781916] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:23.328 ThaliTest[2169:5783131] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:23.328 ThaliTest[2169:5783131] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:19:23.329 ThaliTest[2169:5783131] client session: disconnect
,2016-04-06 03:19:23.330 ThaliTest[2169:5783131] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:23.331 ThaliTest[2169:5783131] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:19:23.331 ThaliTest[2169:5783131] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-06 03:19:23.792 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:19:23.792 ThaliTest[2169:5781774] server: disconnecting to refresh session (7DE50CBF-CC92-4CD5-AA12-B28CD384766D)
2016-04-06 03:19:23.792 ThaliTest[2169:5781774], server: rejecting invitation from 7DE50CBF-CC92-4CD5-AA12-B28CD384766D due to previous generation (C5E616F6-311E-4AAE-ABEF-071095D8F02C:9 != C5E616F6-311E-4AAE-ABEF-071095D8F02C:8)
,2016-04-06 03:19:26.341 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:26.342 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:19:26.342 ThaliTest[2169:5781916] client session: stateChange:0->,1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:26.480 ThaliTest[2169:5783145] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:26.480 ThaliTest[2169:5783145] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:26.480 ThaliTest[2169:5783145] client session: disconnect
2016-04-06 03:19:26.481 ThaliTest[2169:5783145] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:26.481 ThaliTest[2169:5783145] client session: fireConnectCallb,ack: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:26.481 ThaliTest[2169:5783145] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,2016-04-06 03:19:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:19:36.501 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:19:36.502 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:36.50,3 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:19:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:20:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:20:16.480 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:20:16.481 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:20:16.481 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:20:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:20:36.481 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:20:36.481 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:36.48,2 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:20:37.422 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:20:37.422 ThaliTest[2169:5781774] server: disconnecting to refresh session (7DE50CBF-CC92-4CD5-AA12-B28CD384766D)
2016-04-06 03:20:37.422 ThaliTest[2169:5781774] server: rejecting invitation for lexical ordering 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:20:37.428 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:37.429 ThaliTest[2169:5781916] client session: connect
2016-04-06 03:20:37.429 ThaliTest[2169:5781916] client session: stateChange:0->,1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:20:39.051 ThaliTest[2169:5783369] client session: p2p link connected
,2016-04-06 03:20:39.122 ThaliTest[2169:5783358] client session: stateChange:1->2 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:39.122 ThaliTest[2169:5783358] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:20:39.122 ThaliTest[2169:5783358] jxcore: connect: success
,2016-04-06 03:20:39.137 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:39.138 ThaliTest[2169:5781916] client: already connect(ing/ed) to 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:39.138 Thali,Test[2169:5781916] jxcore: connect: fail: Already connect(ing/ed)
ok 182 Expected error
2016-04-06 03:20:39.139 ThaliTest[2169:5781774] client: relay established
2016-04-06 03:20:39.139 ThaliTest[2169:5781774] client: new accepted socket: 0x1dc0ae70
ok, 183 Null connection as expected
2016-04-06 03:20:39.140 ThaliTest[2169:5781916] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:39.141 ThaliTest[2169:5781916] client: already connect(ing/ed) to 7DE50CBF-CC92-4CD5-AA12-B28CD384766,D:9
2016-04-06 03:20:39.141 ThaliTest[2169:5781916] jxcore: connect: fail: Already connect(ing/ed)
ok 184 Expected error
ok 185 Null connection as expected
,# teardown
,2016-04-06 03:20:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:20:56.479 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:56.479 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:20:56.480 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:21:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:21:16.484 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:21:16.484 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:21:16.484 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:21:36.459 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:21:36.481 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:21:36.484 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:21:36.485 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:21:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:21:56.480 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:21:56.480 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:21:56.481 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:22:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:22:16.484 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:22:16.485 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:22:16.48,5 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:22:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:22:36.480 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:22:36.482 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:22:36.482 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:22:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:22:56.484 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:22:56.484 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:22:56.484 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:23:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:23:16.481 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:23:16.482 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:23:16.483 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:23:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:23:36.481 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:23:36.482 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:23:36.483 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:23:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:23:56.484 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:23:56.485 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:23:56.486 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:24:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:24:16.479 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:24:16.479 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:24:16.479 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:24:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:24:36.486 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:24:36.487 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:24:36.487 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:24:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:24:56.481 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:24:56.481 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:24:56.481 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:25:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:25:16.482 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:25:16.482 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:25:16.482 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:25:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:25:36.481 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:25:36.482 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:25:36.482 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:25:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:25:56.481 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:25:56.483 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:25:56.483 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:26:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:26:16.482 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:26:16.482 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:26:16.482 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:26:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:26:36.482 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:26:36.483 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:26:36.483 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:26:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:26:56.481 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:26:56.482 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:26:56.482 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:27:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:27:36.459 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:27:36.482 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:27:36.482 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:27:36.48,2 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:27:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:27:56.485 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:27:56.485 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:27:56.48,5 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:28:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:28:16.482 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:28:16.482 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:28:16.48,3 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:28:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:28:36.480 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:28:36.480 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:28:36.485 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:28:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:28:56.482 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:28:56.482 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:28:56.482 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:29:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:29:16.480 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:29:16.482 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:29:16.48,4 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:29:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:29:36.484 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:29:36.485 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:29:36.485 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:29:56.459 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:29:56.478 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:29:56.479 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:29:56.48,0 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:30:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:30:16.480 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:30:16.481 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:30:16.482 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:30:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:30:36.481 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:30:36.484 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:30:36.484 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:30:56.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:30:56.476 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:30:56.479 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:30:56.47,9 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:30:57.476 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:30:57.477 ThaliTest[2169:5781774] server: rejecting invitation for lexical ordering BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
,2016-04-06 03:31:09.540 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:31:09.540 ThaliTest[2169:5781774] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:31:09.540 ThaliTest[2169:5781774], server: rejecting invitation for lexical ordering BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
,2016-04-06 03:31:16.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:31:22.636 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:31:22.637 ThaliTest[2169:5781774] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:31:22.637 ThaliTest[2169:5781774] server: rejecting invitation for lexical ordering BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
,2016-04-06 03:31:35.675 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:31:35.676 ThaliTest[2169:5781774] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:31:35.676 ThaliTest[2169:5781774], server: rejecting invitation for lexical ordering BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76
,2016-04-06 03:31:36.460 ThaliTest[2169:5781774] multipeer manager: restart client
,2016-04-06 03:31:36.484 ThaliTest[2169:5781774] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:31:36.484 ThaliTest[2169:5781774] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:31:36.48,4 ThaliTest[2169:5781774] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:31:48.843 ThaliTest[2169:5781774] multipeer session: reset timer
2016-04-06 03:31:48.844 ThaliTest[2169:5781774] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:31:48.844 ThaliTest[2169:5781774] server: rejecting invitation for lexical ordering BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76

```
