#### Test 64613803d18c8d9_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/CE9D85A5-4391-4521-9859-C1F0C9BC6FF5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/CE9D85A5-4391-4521-9859-C1F0C9BC6FF5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50044"
,(lldb)     command script import "/tmp/CE9D85A5-4391-4521-9859-C1F0C9BC6FF5/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 07:16:56.456 ThaliTest[1983:5051437] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DFD8CFAD-A239-4516-B3DD-200C9D43ADAA/Library/Cookies/Cookies.binarycookies
,2016-04-01 07:16:56.568 ThaliTest[1983:5051437] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 07:16:56.570 ThaliTest[1983:5051437] Multi-tasking -> Device: YES, App: YES
,2016-04-01 07:16:56.589 ThaliTest[1983:5051437] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 07:16:57.769 ThaliTest[1983:5051437] Using UIWebView
2016-04-01 07:16:57.773 ThaliTest[1983:5051437] [CDVTimer][handleopenurl] 0.276983ms
,2016-04-01 07:16:57.778 ThaliTest[1983:5051437] [CDVTimer][intentandnavigationfilter] 5.514979ms
2016-04-01 07:16:57.779 ThaliTest[1983:5051437] [CDVTimer][gesturehandler] 0.222027ms
2016-04-01 07:16:57.779 ThaliTest[1983:5051437] [CDVTimer][TotalPluginStartup] 6.838977ms
,2016-04-01 07:17:03.094 ThaliTest[1983:5051437] Resetting plugins due to page load.
,2016-04-01 07:17:05.228 ThaliTest[1983:5051437] Finished load of: file:///var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/index.html
,2016-04-01 07:17:05.423 ThaliTest[1983:5051437] JXcore Cordova plugin initializing
2016-04-01 07:17:05.424 ThaliTest[1983:5051583] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-04-01 07:17:19.495 ThaliTest[1983:5051583] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 07:17:19.495 ThaliTest[1983:5051583] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 07:17:19.495 ThaliTest[1983:5,051583] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 07:17:19.499 ThaliTest[1983:5051583] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D13F1F2C-2EA6-4CB3-9848-C7AF890DF8C4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56921
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56923
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
DEBUG createNativeListener: listening 56926
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
,ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56930
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
,ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56935
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56939
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
,DEBUG createNativeListener: listening 56943
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
DEBUG createNativeListener: listening 56947
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
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
DEBUG createNativeListener: listening 56951
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new, incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
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
DEBUG createNativeListener: listening 57003
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
DEBUG createNativeListener: listening 57007
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
,ok 53 secondPromise testValue
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
,DEBUG createNativeListener: listening 57017
,2016-04-01 07:20:43.505 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:20:43.508 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-01 07:20:43.512 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:20:43.515 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-01 07:20:43.600 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:43.600 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:20:43.600 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:20:43.601 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:43.602 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57019
2016-04-01 07:20:43.983 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements
,2016-04-01 07:20:43.985 ThaliTest[1983:5051583] multipeer manager: start client restart timer: 0x155b3210
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:20:43.986 Th,aliTest[1983:5051583] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-01 07:20:44.029 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-04-01 07:20:44.030 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-01 07:20:44.396 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:44.396 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:20:44.396 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:20:44.396 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
2016-04-01 07:20:44.397 ThaliTest[1983:5051583] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:44.397 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57021
2016-04-01 07:20:44.863 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:20:44.863 ThaliTest[1983:5051583] server: starting 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:1
2016-04-01 07:20:44.864 ThaliTest[1983:5051583] multipeer manager: start client restart timer: 0x155b3210
2016-04-01 07:20:44.864 ThaliTest[1983:5051583] THEMultipeerManager initialized peer 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:1
2016-04-01 07:20:44.864 ThaliTest[1983,:5051583] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-01 07:20:44.878 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:20:44.878 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:20:44.879, ThaliTest[1983:5051583] multipeer manager: stop client timer
2016-04-01 07:20:44.880 ThaliTest[1983:5051583] server: starting 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:2
2016-04-01 07:20:44.880 ThaliTest[1983:5051583] multipeer manager: start client restart ,timer: 0x155b3210
2016-04-01 07:20:44.880 ThaliTest[1983:5051583] THEMultipeerManager initialized peer 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:2
,2016-04-01 07:20:44.881 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-01 07:20:44.988 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:44.988 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:20:44.989 ThaliTest[1983:5051583] multipeer manager: stop client timer
20,16-04-01 07:20:44.989 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
2016-04-01 07:20:44.989 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:44.990 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57026
,2016-04-01 07:20:47.510 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:47.510 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:20:47.510 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: suc,cess
ok 109 error should be null
ok 110 error should be null
2016-04-01 07:20:47.513 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:47.513 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:20:47.513 ,ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
,# teardown
,2016-04-01 07:21:02.861 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:02.862 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:21:02.862 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:21:02.862 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:02.863 ThaliTest[1983,:5051583] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57028
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
,# teardown
,2016-04-01 07:21:05.328 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:05.329 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:21:05.329 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:21:05.329 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:05.331 ThaliTest[1983,:5051583] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57030
,2016-04-01 07:21:05.578 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements
2016-04-01 07:21:05.578 ThaliTest[1983:5051583] multipeer manager: start client restart timer: 0x155b3210
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:05.579 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements: success
,2016-04-01 07:21:05.591 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:05.591 ThaliTest[1983:5051583] server: starting 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:3
2016-04-01 07:21:05.592 ThaliTest[1983:5051583] THEMultipee,rManager initialized peer 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:3
2016-04-01 07:21:05.592 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-01 07:21:06.020 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:06.021 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:21:06.021 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:21:06.021 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:06.021 ThaliTest[1983:5051583] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:06.022 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).
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
,# setup
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
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-01 07:21:41.056 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements
2016-04-01 07:21:41.057 ThaliTest[1983:5051583] multipeer manager: start client restart timer: 0x155b3210
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:41.058 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-01 07:21:41.059 ThaliTes,t[1983:5051583] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:41.059 ThaliTest[1983:5051583] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-04-01 07:21:41.060 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 07:21:41.442 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:41.443 ThaliTest[1983:50515,83] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:41.445 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:41.445 ThaliTest[1983:50515,83] THEMultipeerManager stopping peer
2016-04-01 07:21:41.445 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-01 07:21:42.023 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements
2016-04-01 07:21:42.024 ThaliTest[1983:5051583] multipeer manager: start client restart timer: 0x155b3210
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:42.025 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-01 07:21:42.026 ThaliTes,t[1983:5051583] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:42.027 ThaliTest[1983:5051583] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-01 07:21:43.092 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:43.093 ThaliTest[1983:5051583] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:43.094 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:43.095 ThaliTest[1983:5051,583] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:43.095 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:21:43.095 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-01 07:21:44.015 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:44.016 ThaliTest[1983:50515,83] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-01 07:21:44.017 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:44.017 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 07:21:44.139 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:44.140 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:44.141 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:44.141 ThaliTest[1983:50515,83] THEMultipeerManager stopping peer
2016-04-01 07:21:44.141 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-01 07:21:44.515 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:44.515 ThaliTest[1983:5051583] server: starting 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:4
2016-04-01 07:21:44.515 ThaliTest[1983:5051583] multipeer m,anager: start client restart timer: 0x155b3210
2016-04-01 07:21:44.516 ThaliTest[1983:5051583] THEMultipeerManager initialized peer 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:4
2016-04-01 07:21:44.516 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:21:44.517 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:44.517 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
,2016-04-01 07:21:44.518 ThaliTest[1983:5051583] multipeer manager: stop client timer
2016-04-01 07:21:44.525 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-01 07:21:44.634 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:44.635 ThaliTest[1983:50515,83] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:44.636 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:44.636 ThaliTest[1983:50515,83] THEMultipeerManager stopping peer
2016-04-01 07:21:44.636 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-01 07:21:45.015 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:45.015 ThaliTest[1983:5051583] server: starting 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:5
2016-04-01 07:21:45.015 ThaliTest[1983:5051583] multipeer m,anager: start client restart timer: 0x155b3210
2016-04-01 07:21:45.016 ThaliTest[1983:5051583] THEMultipeerManager initialized peer 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:5
2016-04-01 07:21:45.016 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:21:45.017 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:45.017 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
,2016-04-01 07:21:45.017 ThaliTest[1983:5051583] multipeer manager: stop client timer
2016-04-01 07:21:45.023 ThaliTest[1983:5051583] server: starting 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:6
2016-04-01 07:21:45.024 ThaliTest[1983:5051583] multipeer manager,: start client restart timer: 0x155b3210
2016-04-01 07:21:45.024 ThaliTest[1983:5051583] THEMultipeerManager initialized peer 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:6
,2016-04-01 07:21:45.025 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-04-01 07:21:45.142 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 07:21:45.143 ThaliTest[1983:505158,3] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:45.144 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:45.144 ThaliTest[1983:505158,3] THEMultipeerManager stopping peer
2016-04-01 07:21:45.144 ThaliTest[1983:5051583] multipeer manager: stop client timer
2016-04-01 07:21:45.144 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-01 07:21:56.271 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:56.272 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:21:56.272 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:21:56.273 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
,2016-04-01 07:21:56.273 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
2016-04-01 07:21:56.274 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-01 07:22:12.811 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:22:12.812 ThaliTest[1983:50515,83] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:22:12.813 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:22:12.813 ThaliTest[1983:50515,83] THEMultipeerManager stopping peer
2016-04-01 07:22:12.814 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-01 07:22:19.510 ThaliTest[1983:5051583] jxcore: connect foo
2016-04-01 07:22:19.510 ThaliTest[1983:5051583] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-01 07:22:19.588 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:22:19.589 ThaliTest[1983:50515,83] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:22:19.590 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:22:19.590 ThaliTest[1983:50515,83] THEMultipeerManager stopping peer
2016-04-01 07:22:19.590 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-01 07:22:20.323 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:22:20.323 ThaliTest[1983:5051583] server: starting 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:20.324 ThaliTest[1983:5051583] multipeer m,anager: start client restart timer: 0x155b3210
2016-04-01 07:22:20.324 ThaliTest[1983:5051583] THEMultipeerManager initialized peer 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:20.324 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-01 07:22:20.326 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-01 07:22:20.327 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-01 07:22:21.358 ThaliTest[1983:5051437] client: found new peer: A956A86E-53B4-4DBF-B193-1271D200C497:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-01 07:22:21.435 ThaliTest[1983:5051437] client: found new peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:7
,2016-04-01 07:22:22.404 ThaliTest[1983:5051437] client: found new peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
,2016-04-01 07:22:23.735 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 07:22:23.736 ThaliTest[1983:505158,3] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:22:23.737 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
2016-04-01 07:22:23.737 ThaliTest[1983:505158,3] THEMultipeerManager stopping peer
2016-04-01 07:22:23.737 ThaliTest[1983:5051583] multipeer manager: stop client timer
2016-04-01 07:22:23.737 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-01 07:22:24.471 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:22:24.471 ThaliTest[1983:5051583] server: starting 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:22:24.472 ThaliTest[1983:5051583] multipeer m,anager: start client restart timer: 0x155b3210
2016-04-01 07:22:24.472 ThaliTest[1983:5051583] THEMultipeerManager initialized peer 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:22:24.472 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:22:24.473 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-01 07:22:24.474 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-01 07:22:26.402 ThaliTest[1983:5051437] client: found new peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:22:26.403 ThaliTest[1983:5051437] client: found new peer: A956A86E-53B4-4DBF-B193-1271D200C497:7
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"444A455A-C80E-416D-9E03-5D6FFDE7B60A:7","pleaseConnect":0}]
2016-04-01 07:22:26.403 ThaliTest[1983:5051437] client: found new peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:7
2016-04-01 07:22:26.404 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
,2016-04-01 07:22:26.404 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:22:26.409 ThaliTest[1983:5051583] client session: reverseConnect
2016-04-01 07:22:26.409 ThaliTest[1983:5051583] client session: stateChange:0->1 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"A956A86E-53B4-4DBF-B193-1271D200C497:7","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"775127D1-BE71-46C7-B433-2FA7873DBB8C:7","pleaseConnect":0}]
,2016-04-01 07:22:26.864 ThaliTest[1983:5052202] client session: not connected 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:22:26.866 ThaliTest[1983:5052202] client session: onLinkFailure: 444A455A-C80E-416D-9E03-5D6FFDE7B60A
2016-04-01 07:22:26.8,66 ThaliTest[1983:5052202] client session: disconnect
2016-04-01 07:22:26.866 ThaliTest[1983:5052202] client session: stateChange:1->0 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:22:26.867 ThaliTest[1983:5052202] client session: no connect callback (server initiated)
,2016-04-01 07:22:26.938 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:22:26.938 ThaliTest[1983:5051437] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7)
,2016-04-01 07:22:30.302 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:22:30.302 ThaliTest[1983:5051437] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:22:30.302 ThaliTest[1983:5051437], server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7)
,2016-04-01 07:22:34.007 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:22:34.007 ThaliTest[1983:5051437] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:22:34.007 ThaliTest[1983:5051437] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7)
,2016-04-01 07:22:36.410 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 07:22:37.163 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:22:37.163 ThaliTest[1983:5051437] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:22:37.164 ThaliTest[1983:5051437] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7)
,2016-04-01 07:22:39.413 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:22:39.414 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:22:39.414 ThaliTest[1983:5051583] client session: reverseConnect
2016-04-01 07:22:39.414 ThaliTest[1983:5051583] client session: stateChange:0->1 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
,2016-04-01 07:22:39.836 ThaliTest[1983:5052204] client session: not connected 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:22:39.837 ThaliTest[1983:5052204] client session: onLinkFailure: 444A455A-C80E-416D-9E03-5D6FFDE7B60A
2016-04-01 07:22:39.8,37 ThaliTest[1983:5052204] client session: disconnect
2016-04-01 07:22:39.837 ThaliTest[1983:5052204] client session: stateChange:1->0 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:22:39.838 ThaliTest[1983:5052204] client session: no connect callback (server initiated)
,2016-04-01 07:22:40.826 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:22:40.826 ThaliTest[1983:5051437] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:22:40.827 ThaliTest[1983:5051437] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7)
,2016-04-01 07:22:44.038 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:22:44.039 ThaliTest[1983:5051437] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:22:44.039 ThaliTest[1983:5051437] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7)
,2016-04-01 07:22:44.473 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:22:44.504 ThaliTest[1983:5051437] client: found updated peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:22:44.504 ThaliTest[1983:5051437] client: found updated peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:22:44.507 ,ThaliTest[1983:5051437] client: found updated peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"444A455A-C80E-416D-9E03-5D6FFDE7B60A:8","pleaseConnec,t":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"775127D1-BE71-46C7-B433-2FA7873DBB8C:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{",peerAvailable":1,"peerIdentifier":"A956A86E-53B4-4DBF-B193-1271D200C497:8","pleaseConnect":0}]
,2016-04-01 07:22:45.409 ThaliTest[1983:5051437] client: lost peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A
2016-04-01 07:22:45.411 ThaliTest[1983:5051437] client session: onPeerLost: 444A455A-C80E-416D-9E03-5D6FFDE7B60A
,2016-04-01 07:22:47.305 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"444A455A-C80E-416D-9E03-5D6FFDE7B60A:8","pleaseConnect":0}]
,2016-04-01 07:22:47.582 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:22:47.583 ThaliTest[1983:5051437] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:22:47.583 ThaliTest[1983:5051437], server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7)
,2016-04-01 07:22:49.415 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 07:22:51.311 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:22:51.311 ThaliTest[1983:5051437] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:22:51.311 ThaliTest[1983:5051437], server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7)
,2016-04-01 07:22:52.420 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:22:52.420 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:22:52.421 ThaliTest[1983:5051583] client session: reverseConn,ect
2016-04-01 07:22:52.421 ThaliTest[1983:5051583] client session: stateChange:0->1 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:22:52.626 ThaliTest[1983:5052250] client session: not connected 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:22:52.626 ThaliTest[1983:5052250] client session: onLinkFailure: 444A455A-C80E-416D-9E03-5D6FFDE7B60A
2016-04-01 07:22:52.6,26 ThaliTest[1983:5052250] client session: disconnect
2016-04-01 07:22:52.626 ThaliTest[1983:5052250] client session: stateChange:1->0 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:22:52.628 ThaliTest[1983:5052250] client session: no connect callb,ack (server initiated)
,2016-04-01 07:22:54.530 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:22:54.530 ThaliTest[1983:5051437] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:22:54.530 ThaliTest[1983:5051437] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7)
,2016-04-01 07:22:58.067 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:22:58.067 ThaliTest[1983:5051437] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:22:58.067 ThaliTest[1983:5051437] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7)
,2016-04-01 07:23:02.422 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 07:23:04.473 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:23:04.501 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:23:04.502 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:23:04.517 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:23:05.433 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:23:05.433 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:23:05.433 ThaliTest[1983:5051583] client session: reverseConnect
2016-04-01 07:23:05.434 ThaliTest[1983:5051583] client session: stateChange:0->1 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:23:05.575 ThaliTest[1983:5052210] client session: not connected 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:05.575 ThaliTest[1983:5052210] client session: onLinkFailure: 444A455A-C80E-416D-9E03-5D6FFDE7B60A
2016-04-01 07:23:05.5,76 ThaliTest[1983:5052210] client session: disconnect
2016-04-01 07:23:05.576 ThaliTest[1983:5052210] client session: stateChange:1->0 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:05.576 ThaliTest[1983:5052210] client session: no connect callback (server initiated)
,2016-04-01 07:23:07.626 ThaliTest[1983:5051437] client: lost peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:23:07.626 ThaliTest[1983:5051437] client session: onPeerLost: 775127D1-BE71-46C7-B433-2FA7873DBB8C
,2016-04-01 07:23:09.899 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"775127D1-BE71-46C7-B433-2FA7873DBB8C:8","pleaseConnect":0}]
,2016-04-01 07:23:15.435 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 6
,2016-04-01 07:23:18.447 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:23:18.447 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:23:18.447 ThaliTest[1983:5051583] client session: reverseConnect
2016-04-01 07:23:18.448 ThaliTest[1983:5051583] client session: stateChange:0->1 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:23:18.699 ThaliTest[1983:5052210] client session: not connected 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:18.700 ThaliTest[1983:5052210] client session: onLinkFailure: 444A455A-C80E-416D-9E03-5D6FFDE7B60A
2016-04-01 07:23:18.7,00 ThaliTest[1983:5052210] client session: disconnect
2016-04-01 07:23:18.700 ThaliTest[1983:5052210] client session: stateChange:1->0 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:18.701 ThaliTest[1983:5052210] client session: no connect callback (server initiated)
,2016-04-01 07:23:24.473 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:23:24.496 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:23:24.503 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:23:24.505 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:23:28.448 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 07:23:31.452 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:23:31.452 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:23:31.453 ThaliTest[1983:5051583] client session: reverseConn,ect
2016-04-01 07:23:31.453 ThaliTest[1983:5051583] client session: stateChange:0->1 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:23:32.328 ThaliTest[1983:5052384] client session: not connected 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:32.328 ThaliTest[1983:5052384] client session: onLinkFailure: 444A455A-C80E-416D-9E03-5D6FFDE7B60A
2016-04-01 07:23:32.3,28 ThaliTest[1983:5052384] client session: disconnect
2016-04-01 07:23:32.329 ThaliTest[1983:5052384] client session: stateChange:1->0 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:32.329 ThaliTest[1983:5052384] client session: no connect callb,ack (server initiated)
,2016-04-01 07:23:41.454 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 07:23:44.457 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:23:44.457 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:23:44.458 ThaliTest[1983:5051583] client session: reverseConn,ect
2016-04-01 07:23:44.458 ThaliTest[1983:5051583] client session: stateChange:0->1 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:23:44.473 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:23:44.504 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:23:44.504 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:44.505 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:23:54.458 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 07:23:57.464 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:23:57.464 ThaliTest[1983:5051583] client: already connect(ing/ed) to 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:23:57.464 Thali,Test[1983:5051583] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 07:24:00.480 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:24:00.480 ThaliTest[1983:5051583] client: already connect(ing/ed) to 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:24:00.480 ThaliTest[1983:5051583] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 07:24:03.491 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:24:03.491 ThaliTest[1983:5051583] client: already connect(ing/ed) to 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
2016-04-01 07:24:03.491 Thali,Test[1983:5051583] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-04-01 07:24:04.473 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:24:04.871 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 07:24:04.872 ThaliTest[1983:5051583] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:24:04.874 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening
,2016-04-01 07:24:04.874 ThaliTest[1983:5051583] THEMultipeerManager stopping peer
,2016-04-01 07:24:04.875 ThaliTest[1983:5051583] client session: disconnect
2016-04-01 07:24:04.875 ThaliTest[1983:5051583] client session: stateChange:1->0 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:24:04.876 ThaliTest[1983:5051583] multipeer manager: stop client timer
2016-04-01 07:24:04.876 ThaliTest[1983:5051583] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-01 07:24:06.641 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:24:06.642 ThaliTest[1983:5051583] server: starting 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:06.642 ThaliTest[1983:5051583] multipeer m,anager: start client restart timer: 0x155b3210
2016-04-01 07:24:06.642 ThaliTest[1983:5051583] THEMultipeerManager initialized peer 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:06.643 ThaliTest[1983:5051583] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:24:06.644 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-01 07:24:06.645 ThaliTest[1983:5051583] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-01 07:24:06.783 ThaliTest[1983:5051437] client: found new peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:24:06.783 ThaliTest[1983:5051437] client: found new peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:06.784 ThaliTes,t[1983:5051437] client: found new peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:24:06.785 ThaliTest[1983:5051583] jxcore: connect 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:24:06.788 ThaliTest[1983:5051583] client: server will conn,ect
2016-04-01 07:24:06.788 ThaliTest[1983:5051583] client session: reverseConnect
2016-04-01 07:24:06.788 ThaliTest[1983:5051583] client session: stateChange:0->1 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:24:09.010 ThaliTest[1983:5052505] client session: not connected 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:24:09.010 ThaliTest[1983:5052505] client session: onLinkFailure: 444A455A-C80E-416D-9E03-5D6FFDE7B60A
2016-04-01 07:24:09.0,10 ThaliTest[1983:5052505] client session: disconnect
2016-04-01 07:24:09.010 ThaliTest[1983:5052505] client session: stateChange:1->0 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:24:09.012 ThaliTest[1983:5052505] client session: no connect callback (server initiated)
,2016-04-01 07:24:10.258 ThaliTest[1983:5051437] multipeer session: reset timer
,2016-04-01 07:24:10.259 ThaliTest[1983:5051437] server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8)
,2016-04-01 07:24:10.328 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:24:10.329 ThaliTest[1983:5051437] server session: connect
2016-04-01 07:24:10.329 ThaliTest[1983:5051437] server session: stateChange:0->1 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:24:10.336 ThaliTest[1983:5051437] server: accepting invitation 444A455A-C80E-416D-9E03-5D6FFDE7B60A
,2016-04-01 07:24:11.424 ThaliTest[1983:5052479] server session: p2p link connected
,2016-04-01 07:24:11.488 ThaliTest[1983:5051437] server relay: connected (to port: 57048)
2016-04-01 07:24:11.489 ThaliTest[1983:5051437] server session: stateChange:1->2 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:24:11.489 ThaliTest[1983:5051437] jxcore: connect: success
,2016-04-01 07:24:15.717 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:24:15.718 ThaliTest[1983:5051437] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:24:15.718 ThaliTest[1983:5051437], server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8)
,2016-04-01 07:24:22.122 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:24:22.122 ThaliTest[1983:5051437] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:24:22.123 ThaliTest[1983:5051437] server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8)
,2016-04-01 07:24:26.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:24:26.672 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:24:26.674 ThaliTest[1983:5051437] client: found updated peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:26.675, ThaliTest[1983:5051583] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:26.676 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:24:26.676 ThaliTest[1983:5051583] client session: reverseConnect
2016-04-01 07:24:2,6.676 ThaliTest[1983:5051583] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:24:26.687 ThaliTest[1983:5051437] client: found updated peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:24:27.169 ThaliTest[1983:5052509] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:24:27.170 ThaliTest[1983:5052509] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
,2016-04-01 07:24:27.171 ThaliTest[1983:5052509] client session: disconnect
,2016-04-01 07:24:27.172 ThaliTest[1983:5052509] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:27.173 ThaliTest[1983:5052509] client session: no connect callback (server initiated)
,2016-04-01 07:24:36.677 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 07:24:39.689 ThaliTest[1983:5051583] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:39.689 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:24:39.690 ThaliTest[1983:5051583] client session: reverseConnect
2016-04-01 07:24:39.690 ThaliTest[1983:5051583] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:24:40.996 ThaliTest[1983:5052572] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:40.998 ThaliTest[1983:5052572] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:40.9,98 ThaliTest[1983:5052572] client session: disconnect
2016-04-01 07:24:40.999 ThaliTest[1983:5052572] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:40.999 ThaliTest[1983:5052572] client session: no connect callback (server initiated)
,2016-04-01 07:24:46.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:24:46.671 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:24:46.671 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:24:46.675 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:24:49.691 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 07:24:52.705 ThaliTest[1983:5051583] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:52.705 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:24:52.705 ThaliTest[1983:5051583] client session: reverseConn,ect
2016-04-01 07:24:52.706 ThaliTest[1983:5051583] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:24:53.007 ThaliTest[1983:5052635] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:53.008 ThaliTest[1983:5052635] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:53.0,08 ThaliTest[1983:5052635] client session: disconnect
2016-04-01 07:24:53.009 ThaliTest[1983:5052635] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:53.009 ThaliTest[1983:5052635] client session: no connect callback (server initiated)
,2016-04-01 07:25:02.707 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 07:25:04.113 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:25:04.113 ThaliTest[1983:5051437] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:25:04.113 ThaliTest[1983:5051437], server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8)
,2016-04-01 07:25:05.710 ThaliTest[1983:5051583] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:05.710 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:25:05.710 ThaliTest[1983:5051583] client session: reverseConnect
2016-04-01 07:25:05.711 ThaliTest[1983:5051583] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:05.850 ThaliTest[1983:5052656] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:05.852 ThaliTest[1983:5052656] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:05.8,52 ThaliTest[1983:5052656] client session: disconnect
2016-04-01 07:25:05.852 ThaliTest[1983:5052656] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:05.854 ThaliTest[1983:5052656] client session: no connect callback (server initiated)
,2016-04-01 07:25:06.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:25:06.678 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:25:06.678 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:06.678 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:25:09.657 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:25:09.657 ThaliTest[1983:5051437] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:25:09.657 ThaliTest[1983:5051437] server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8)
,2016-04-01 07:25:15.465 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:25:15.465 ThaliTest[1983:5051437] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:25:15.465 ThaliTest[1983:5051437], server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8)
,2016-04-01 07:25:15.712 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 6
,2016-04-01 07:25:18.716 ThaliTest[1983:5051583] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:18.716 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:25:18.716 ThaliTest[1983:5051583] client session: reverseConnect
2016-04-01 07:25:18.717 ThaliTest[1983:5051583] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:19.189 ThaliTest[1983:5052639] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:19.189 ThaliTest[1983:5052639] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:19.1,89 ThaliTest[1983:5052639] client session: disconnect
2016-04-01 07:25:19.189 ThaliTest[1983:5052639] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:19.190 ThaliTest[1983:5052639] client session: no connect callb,ack (server initiated)
,2016-04-01 07:25:20.660 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:25:20.660 ThaliTest[1983:5051437] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:25:20.660 ThaliTest[1983:5051437] server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8)
,2016-04-01 07:25:25.939 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:25:25.940 ThaliTest[1983:5051437] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:25:25.940 ThaliTest[1983:5051437] server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8)
,2016-04-01 07:25:26.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:25:26.675 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:26.676 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:25:26.67,7 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:25:28.718 ThaliTest[1983:5051437] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 07:25:29.595 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:25:29.595 ThaliTest[1983:5051437] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:25:29.595 ThaliTest[1983:5051437], server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9 != 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8)
,2016-04-01 07:25:31.722 ThaliTest[1983:5051583] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:31.722 ThaliTest[1983:5051583] client: server will connect
2016-04-01 07:25:31.722 ThaliTest[1983:5051583] client session: reverseConnect
2016-04-01 07:25:31.722 ThaliTest[1983:5051583] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:32.238 ThaliTest[1983:5052668] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:32.239 ThaliTest[1983:5052668] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:32.239 ThaliTest[1983:5052668] client session: disconnect
,2016-04-01 07:25:32.239 ThaliTest[1983:5052668] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:32.242 ThaliTest[1983:5052668] client session: no connect callback (server initiated)
,2016-04-01 07:25:34.447 ThaliTest[1983:5051437] multipeer session: reset timer
2016-04-01 07:25:34.448 ThaliTest[1983:5051437] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:25:34.448 ThaliTest[1983:5051437] server session: connect
2016-04-01 07:25:34.448 ThaliTest[1983:5051437] server session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:34.455 ThaliTest[1983:5051437] server: accepting invitation 775127D1-BE71-46C7-B433-2FA7873DBB8C
,2016-04-01 07:25:37.798 ThaliTest[1983:5052735] server session: p2p link connected
,2016-04-01 07:25:37.805 ThaliTest[1983:5051437] server relay: connected (to port: 57048)
2016-04-01 07:25:37.806 ThaliTest[1983:5051437] server session: stateChange:1->2 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:37.806 ThaliTest[1983:5051437] jxcore: connect: success
,2016-04-01 07:25:46.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:25:46.670 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:46.670 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:25:46.671 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:26:06.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:26:06.676 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:26:06.679 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:26:06.67,9 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:26:26.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:26:26.675 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:26:26.679 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:26:26.681 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:26:46.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:26:46.675 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:26:46.677 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:26:46.677 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:27:06.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:27:06.677 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:27:06.677 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:27:06.685 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:27:26.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:27:26.676 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:27:26.677 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:27:26.684 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:27:46.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:27:46.668 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:27:46.670 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:27:46.671 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:28:06.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:28:06.676 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:28:06.678 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:28:06.678 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:28:26.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:28:26.679 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:28:26.679 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:28:26.679 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:28:46.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:28:46.677 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:28:46.677 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:28:46.679 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:29:06.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:29:06.674 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:29:06.674 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:29:06.679 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:29:26.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:29:26.670 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:29:26.670 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:29:26.67,2 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:29:46.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:29:46.675 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:29:46.677 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:29:46.677 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:30:06.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:30:06.670 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:30:06.670 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:30:06.671 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:30:26.642 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:30:26.669 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:30:26.669 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:30:26.670 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:30:46.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:30:46.676 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:30:46.676 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:30:46.682 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:31:06.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:31:06.669 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:31:06.672 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:31:06.672 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:31:26.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:31:26.668 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:31:26.671 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:31:26.672 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:31:46.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:31:46.676 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:31:46.678 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:31:46.679 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:32:06.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:32:06.679 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:32:06.679 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:32:06.680 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:32:26.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:32:26.671 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:32:26.671 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:32:26.671 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:32:46.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:32:46.673 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:32:46.673 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:32:46.674 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:33:06.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:33:06.676 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:33:06.676 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:33:06.683 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:33:26.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:33:26.673 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:33:26.673 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:33:26.67,5 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:33:46.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:33:46.678 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:33:46.678 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:33:46.678 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:34:06.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:34:06.677 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:34:06.678 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:34:06.678 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:34:26.643 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:34:26.667 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:34:26.668 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:34:26.673 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:34:46.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:34:46.613 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:34:46.614 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:34:46.615 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:35:06.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:35:06.611 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:35:06.612 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:35:06.614 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:35:26.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:35:26.611 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:35:26.612 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:35:26.619 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:35:46.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:35:46.611 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:35:46.611 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:35:46.613 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:36:06.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:36:06.606 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:36:06.607 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:36:06.609 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:36:26.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:36:26.607 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:36:26.610 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:36:26.610 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:36:46.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:36:46.605 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:36:46.605 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:36:46.608 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:37:06.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:37:06.606 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:37:06.609 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:37:06.609 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:37:26.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:37:26.611 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:37:26.612 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:37:26.613 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:37:46.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:37:46.605 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:37:46.605 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:37:46.612 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:38:06.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:38:06.609 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:38:06.611 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:38:06.614 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:38:26.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:38:26.608 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:38:26.609 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:38:26.610 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:38:46.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:38:46.610 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:38:46.611 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:38:46.616 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:39:06.578 ThaliTest[1983:5051437] multipeer manager: restart client
,2016-04-01 07:39:06.611 ThaliTest[1983:5051437] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:39:06.611 ThaliTest[1983:5051437] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:39:06.612 ThaliTest[1983:5051437] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9

```
