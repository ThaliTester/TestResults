#### Test 648099369ce4518_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/A763C1FD-A54D-41BE-AB55-0B2628BD78A0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/A763C1FD-A54D-41BE-AB55-0B2628BD78A0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/648099369ce4518/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49968"
,(lldb)     command script import "/tmp/A763C1FD-A54D-41BE-AB55-0B2628BD78A0/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 18:03:10.113 ThaliTest[1962:4968099] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F921EF1F-8FAF-44F9-92D2-07A9D6CA859A/Library/Cookies/Cookies.binarycookies
,2016-03-31 18:03:10.473 ThaliTest[1962:4968099] Apache Cordova native platform version 4.1.0 is starting.
2016-03-31 18:03:10.474 ThaliTest[1962:4968099] Multi-tasking -> Device: YES, App: YES
,2016-03-31 18:03:10.491 ThaliTest[1962:4968099] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 18:03:11.680 ThaliTest[1962:4968099] Using UIWebView
,2016-03-31 18:03:11.686 ThaliTest[1962:4968099] [CDVTimer][handleopenurl] 0.265002ms
,2016-03-31 18:03:11.692 ThaliTest[1962:4968099] [CDVTimer][intentandnavigationfilter] 4.402041ms
2016-03-31 18:03:11.692 ThaliTest[1962:4968099] [CDVTimer][gesturehandler] 0.211000ms
2016-03-31 18:03:11.692 ThaliTest[1962:4968099] [CDVTimer][TotalPluginS,tartup] 6.900966ms
,2016-03-31 18:03:16.685 ThaliTest[1962:4968099] Resetting plugins due to page load.
,2016-03-31 18:03:18.481 ThaliTest[1962:4968099] Finished load of: file:///var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/index.html
,2016-03-31 18:03:18.725 ThaliTest[1962:4968099] JXcore Cordova plugin initializing
,2016-03-31 18:03:18.848 ThaliTest[1962:4968220] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-31 18:03:32.816 ThaliTest[1962:4968220] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 18:03:32.817 ThaliTest[1962:4968220] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 18:03:32.817 ThaliTest[1962:4968220] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 18:03:32.820 ThaliTest[1962:4968220] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20AA820A-2314-4F44-B46C-4902D2DD90AB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56697
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56699
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56702
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 56706
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 56711
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
DEBUG createNativeListener: listening 56715
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56719
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
DEBUG createNativeListener: listening 56723
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
,ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56727
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new, incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creat,ing incoming mux
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
,DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 56779
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
,ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56783
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
ok 42 incomi,ng has been removed
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
,ok 86 error should be null
,# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 87 specific error should be returned
# teardown
,ok 88 error should be null
ok 89 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56795
2016-03-31 18:06:25.448 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.450 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
,ok 91 error should be null
,2016-03-31 18:06:25.455 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.456 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
# teardown
,2016-03-31 18:06:25.586 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:25.586 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
2016-03-31 18:06:25.586 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: success
2016-03-31 18:06:25.587 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.588 ThaliTest[1962,:4968220] jxcore: stopListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
,# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56797
2016-03-31 18:06:25.816 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements
,2016-03-31 18:06:25.818 ThaliTest[1962:4968220] multipeer manager: start client restart timer: 0x155a0880
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:06:25.819 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
ok 97 error should be null
2016-03-31 18:06:25.837 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-31 18:06:25.839 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements: success
ok 98 error should be null
ok 99 error should be null
,# teardown
,2016-03-31 18:06:25.960 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:25.960 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
2016-03-31 18:06:25.960 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 18:06:25.961 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
2016-03-31 18:06:25.961 ThaliTest[1962:4968220] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:25.962 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 100 error should be null
,ok 101 error should be null
,# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56799
,2016-03-31 18:06:26.294 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:06:26.295 ThaliTest[1962:4968220] server: starting F11AAA28-318B-4CE4-B684-469230DD4996:1
2016-03-31 18:06:26.295 ThaliTest[1962:4968220] multipeer m,anager: start client restart timer: 0x155a0880
2016-03-31 18:06:26.296 ThaliTest[1962:4968220] THEMultipeerManager initialized peer F11AAA28-318B-4CE4-B684-469230DD4996:1
2016-03-31 18:06:26.296 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
2016-03-31 18:06:26.312 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:06:26.312 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
2016-03-31 18:06:26.313, ThaliTest[1962:4968220] multipeer manager: stop client timer
2016-03-31 18:06:26.313 ThaliTest[1962:4968220] server: starting F11AAA28-318B-4CE4-B684-469230DD4996:2
2016-03-31 18:06:26.313 ThaliTest[1962:4968220] multipeer manager: start client restart timer: 0x155a0880
,2016-03-31 18:06:26.322 ThaliTest[1962:4968220] THEMultipeerManager initialized peer F11AAA28-318B-4CE4-B684-469230DD4996:2
2016-03-31 18:06:26.322 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
ok 105 error should be null
,# teardown
,2016-03-31 18:06:26.803 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:26.803 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
2016-03-31 18:06:26.803 ThaliTest[1962:4968220] multipeer manager: stop client timer
20,16-03-31 18:06:26.804 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: success
2016-03-31 18:06:26.804 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 18:06:26.805 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 106 error should be null
ok 107 error should be null
# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56804
2016-03-31 18:06:41.469 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:06:41.469 ThaliTest[1962:4968220] THEMultipeerManager stoppi,ng peer
2016-03-31 18:06:41.469 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
ok 109 error should be null
2016-03-31 18:06:41.472 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31, 18:06:41.472 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
2016-03-31 18:06:41.472 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: success
ok 110 error should be null
ok 111 error should be null
,# teardown
,2016-03-31 18:07:00.291 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:07:00.291 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
2016-03-31 18:07:00.292 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 18:07:00.292 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:00.293 ThaliTest[1962,:4968220] jxcore: stopListeningForAdvertisements: success
,ok 112 error should be null
,ok 113 error should be null
,# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56806
,ok 114 first call should succeed
,ok 115 first call should succeed
,ok 116 specific error should be returned
,# teardown
,2016-03-31 18:07:03.780 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:07:03.780 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
2016-03-31 18:07:03.780 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 18:07:03.780 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:03.781 ThaliTest[1962,:4968220] jxcore: stopListeningForAdvertisements: success
ok 117 error should be null
ok 118 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56808
,2016-03-31 18:07:05.725 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements
,2016-03-31 18:07:05.726 ThaliTest[1962:4968220] multipeer manager: start client restart timer: 0x155a0880
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:07:05.727 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements: success
,2016-03-31 18:07:05.768 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:07:05.768 ThaliTest[1962:4968220] server: starting F11AAA28-318B-4CE4-B684-469230DD4996:3
2016-03-31 18:07:05.769 ThaliTest[1962:4968220] THEMultipeerManager initialized peer F11AAA28-318B-4CE4-B684-469230DD4996:3
2016-03-31 18:07:05.769 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening: success
,ok 119 called only once
ok 120 discovery state matches
ok 121 advertising state matches
# teardown
,2016-03-31 18:07:05.981 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:07:05.982 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
2016-03-31 18:07:05.982 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 18:07:05.982 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
2016-03-31 18:07:05.982 ThaliTest[1962:4968220] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:05.983 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).
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
,ok 135 error should be null
ok 136 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-31 18:07:41.697 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements
2016-03-31 18:07:41.697 ThaliTest[1962:4968220] multipeer manager: start client restart timer: 0x155a0880
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:07:41.698 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
,2016-03-31 18:07:41.700 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
2016-03-31 18:07:41.700 ThaliTest[1962:4968220] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:41.702 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements: success
ok 138 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-31 18:07:41.873 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:07:41.874 ThaliTest[1962:49682,20] jxcore: stopListeningForAdvertisements: success
ok 139 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:07:41.875 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:07:41.876 ThaliTest[1962:496822,0] THEMultipeerManager stopping peer
2016-03-31 18:07:41.876 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 18:08:00.777 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements
2016-03-31 18:08:00.778 ThaliTest[1962:4968220] multipeer manager: start client restart timer: 0x155a0880
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:08:00.779 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements without error
2016-03-31 18:08:00.780 ThaliTes,t[1962:4968220] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 18:08:00.781 ThaliTest[1962:4968220] jxcore: startListeningForAdv,ertisements: success
ok 142 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-31 18:08:01.034 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
2016-03-31 18:08:01.035 ThaliTest[1962:4968220] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-31 18:08:01.036 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements: success
ok 143 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:08:01.037 ThaliTest[1962:49682,20] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:01.037 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
2016-03-31 18:08:01.037 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 18:08:01.564 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:01.565 ThaliTest[1962:4968220] server: starting F11AAA28-318B-4CE4-B684-469230DD4996:4
2016-03-31 18:08:01.565 ThaliTest[1962:4968220] multipeer m,anager: start client restart timer: 0x155a0880
2016-03-31 18:08:01.565 ThaliTest[1962:4968220] THEMultipeerManager initialized peer F11AAA28-318B-4CE4-B684-469230DD4996:4
2016-03-31 18:08:01.565 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListening without error
2016-03-31 18:08:01.566 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:01.567 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
,2016-03-31 18:08:01.567 ThaliTest[1962:4968220] multipeer manager: stop client timer
2016-03-31 18:08:01.572 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: success
ok 146 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 18:08:01.703 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 18:08:01.704 ThaliTest[1962:49682,20] jxcore: stopListeningForAdvertisements: success
ok 147 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:08:01.705 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:01.705 ThaliTest[1962:496822,0] THEMultipeerManager stopping peer
2016-03-31 18:08:01.705 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 18:08:02.254 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:02.254 ThaliTest[1962:4968220] server: starting F11AAA28-318B-4CE4-B684-469230DD4996:5
2016-03-31 18:08:02.255 ThaliTest[1962:4968220] multipeer manager: start client restart timer: 0x155a0880
,2016-03-31 18:08:02.255 ThaliTest[1962:4968220] THEMultipeerManager initialized peer F11AAA28-318B-4CE4-B684-469230DD4996:5
2016-03-31 18:08:02.259 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening: success
ok 149 Can call startUpdateAdv,ertisingAndListening without error
2016-03-31 18:08:02.260 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:02.260 ThaliTest[1962:4968220] THEMultipeerManager stopping peer
2016-03-31 18:08:02.261 ThaliTest[1962:496822,0] multipeer manager: stop client timer
2016-03-31 18:08:02.261 ThaliTest[1962:4968220] server: starting F11AAA28-318B-4CE4-B684-469230DD4996:6
2016-03-31 18:08:02.261 ThaliTest[1962:4968220] multipeer manager: start client restart timer: 0x155a0880
,2016-03-31 18:08:02.262 ThaliTest[1962:4968220] THEMultipeerManager initialized peer F11AAA28-318B-4CE4-B684-469230DD4996:6
2016-03-31 18:08:02.268 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 18:08:02.608 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 18:08:02.609 ThaliTest[1962:496822,0] jxcore: stopListeningForAdvertisements: success
ok 151 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:08:02.610 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:02.610 ThaliTest[1962:4968220,] THEMultipeerManager stopping peer
2016-03-31 18:08:02.611 ThaliTest[1962:4968220] multipeer manager: stop client timer
2016-03-31 18:08:02.611 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-31 18:08:03.136 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:03.136 ThaliTest[1962:4968220] server: starting F11AAA28-318B-4CE4-B684-469230DD4996:7
2016-03-31 18:08:03.136 ThaliTest[1962:4968220] multipeer m,anager: start client restart timer: 0x155a0880
2016-03-31 18:08:03.137 ThaliTest[1962:4968220] THEMultipeerManager initialized peer F11AAA28-318B-4CE4-B684-469230DD4996:7
2016-03-31 18:08:03.137 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 153 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 18:08:03.138 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-31 18:08:03.139 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error
,2016-03-31 18:08:07.073 ThaliTest[1962:4968099] client: found new peer: 2467FBFF-8374-4C28-A08D-056504009757:7
ok 155 peers must be an array
ok 156 peers must not be zero-length
ok 157 peer must have peerIdentifier
ok 158 peerIdentifier must be a strin,g
ok 159 peer must have peerAvailable
ok 160 peer must have pleaseConnect
,# teardown
,2016-03-31 18:08:08.074 ThaliTest[1962:4968220] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 18:08:08.075 ThaliTest[1962:496822,0] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 18:08:08.076 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening
2016-03-31 18:08:08.077 ThaliTest[1962:4968220,] THEMultipeerManager stopping peer
2016-03-31 18:08:08.077 ThaliTest[1962:4968220] multipeer manager: stop client timer
2016-03-31 18:08:08.077 ThaliTest[1962:4968220] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. Can connect to a remote peer
,2016-03-31 18:08:09.509 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening
2016-03-31 18:08:09.510 ThaliTest[1962:4968220] server: starting F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:08:09.510 ThaliTest[1962:4968220] multipeer manager: start client restart timer: 0x155a0880
,2016-03-31 18:08:09.510 ThaliTest[1962:4968220] THEMultipeerManager initialized peer F11AAA28-318B-4CE4-B684-469230DD4996:8
2016-03-31 18:08:09.523 ThaliTest[1962:4968220] jxcore: startUpdateAdvertisingAndListening: success
ok 163 Can call startUpdateAdvertisingAndListening without error
2016-03-31 18:08:09.524 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-3,1 18:08:09.525 ThaliTest[1962:4968220] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-31 18:08:10.279 ThaliTest[1962:4968099] client: found new peer: 2467FBFF-8374-4C28-A08D-056504009757:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2467FBFF-8374-4C28-A08D-056504009,757:7","pleaseConnect":0}]
2016-03-31 18:08:10.281 ThaliTest[1962:4968220] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:10.282 ThaliTest[1962:4968220] client session: connect
2016-03-31 18:08:10.282 ThaliTest[1962:4968220] client session: stateChange:0->1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:10.796 ThaliTest[1962:4969574] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:10.797 ThaliTest[1962:4969574] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:10.7,97 ThaliTest[1962:4969574] client session: disconnect
2016-03-31 18:08:10.797 ThaliTest[1962:4969574] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:10.799 ThaliTest[1962:4969574] client session: fireConnectCallb,ack: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:10.800 ThaliTest[1962:4969574] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 18:08:11.702 ThaliTest[1962:4968099] client: found new peer: C1217920-C4F0-4779-A4B2-BE1967CE79BC:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C1217920-C4F0-4779-A4B2-BE1967CE7,9BC:8","pleaseConnect":0}]
,2016-03-31 18:08:13.807 ThaliTest[1962:4968220] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:13.808 ThaliTest[1962:4968220] client session: connect
2016-03-31 18:08:13.808 ThaliTest[1962:4968220] client session: stateChange:0->,1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:13.942 ThaliTest[1962:4969573] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:13.944 ThaliTest[1962:4969573] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:13.9,44 ThaliTest[1962:4969573] client session: disconnect
2016-03-31 18:08:13.944 ThaliTest[1962:4969573] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:13.945 ThaliTest[1962:4969573] client session: fireConnectCallb,ack: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:13.945 ThaliTest[1962:4969573] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 8
,2016-03-31 18:08:16.956 ThaliTest[1962:4968220] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:16.956 ThaliTest[1962:4968220] client session: connect
2016-03-31 18:08:16.956 ThaliTest[1962:4968220] client session: stateChange:0->1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:17.038 ThaliTest[1962:4969573] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:17.039 ThaliTest[1962:4969573] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:17.0,40 ThaliTest[1962:4969573] client session: disconnect
2016-03-31 18:08:17.040 ThaliTest[1962:4969573] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:17.040 ThaliTest[1962:4969573] client session: fireConnectCallb,ack: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:17.041 ThaliTest[1962:4969573] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 18:08:20.053 ThaliTest[1962:4968220] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:20.053 ThaliTest[1962:4968220] client session: connect
2016-03-31 18:08:20.053 ThaliTest[1962:4968220] client session: stateChange:0->1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:20.238 ThaliTest[1962:4969573] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:20.238 ThaliTest[1962:4969573] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:20.2,38 ThaliTest[1962:4969573] client session: disconnect
2016-03-31 18:08:20.238 ThaliTest[1962:4969573] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:20.239 ThaliTest[1962:4969573] client session: fireConnectCallb,ack: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:20.239 ThaliTest[1962:4969573] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 18:08:23.250 ThaliTest[1962:4968220] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:23.250 ThaliTest[1962:4968220] client session: connect
2016-03-31 18:08:23.250 ThaliTest[1962:4968220] client session: stateChange:0->1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:23.417 ThaliTest[1962:4969575] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:23.418 ThaliTest[1962:4969575] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:23.419 ThaliTest[1962:4969575] client session: disconnect
2016-03-31 18:08:23.419 ThaliTest[1962:4969575] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:23.420 ThaliTest[1962:4969575] client session: fireConnectCallb,ack: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:23.420 ThaliTest[1962:4969575] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 18:08:26.432 ThaliTest[1962:4968220] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7
2016-03-31 18:08:26.433 ThaliTest[1962:4968220] client session: connect
2016-03-31 18:08:26.433 ThaliTest[1962:4968220] client session: stateChange:0->,1 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:26.523 ThaliTest[1962:4969598] client session: not connected 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:26.524 ThaliTest[1962:4969598] client session: onLinkFailure: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:26.524 ThaliTest[1962:4969598] client session: disconnect
2016-03-31 18:08:26.525 ThaliTest[1962:4969598] client session: stateChange:1->0 2467FBFF-8374-4C28-A08D-056504009757:7
,2016-03-31 18:08:26.527 ThaliTest[1962:4969598] client session: fireConnectCallback: 2467FBFF-8374-4C28-A08D-056504009757
2016-03-31 18:08:26.527 ThaliTest[1962:4969598] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 18:08:29.511 ThaliTest[1962:4968099] multipeer manager: restart client
,2016-03-31 18:08:29.529 ThaliTest[1962:4968099] client: found updated peer: 2467FBFF-8374-4C28-A08D-056504009757:8
2016-03-31 18:08:29.530 ThaliTest[1962:4968220] jxcore: connect 2467FBFF-8374-4C28-A08D-056504009757:7

```
