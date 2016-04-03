#### Test 64809936d936b9e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/2533689F-05E7-4893-806C-31BEA4D25244/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2533689F-05E7-4893-806C-31BEA4D25244/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50518"
,(lldb)     command script import "/tmp/2533689F-05E7-4893-806C-31BEA4D25244/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-03 21:07:02.918 ThaliTest[2737:5186287] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/65FCE1E3-DD0D-470D-90DA-BEE8E03C6885/Library/Cookies/Cookies.binarycookies
,2016-04-03 21:07:03.152 ThaliTest[2737:5186287] Apache Cordova native platform version 4.1.0 is starting.
2016-04-03 21:07:03.152 ThaliTest[2737:5186287] Multi-tasking -> Device: YES, App: YES
,2016-04-03 21:07:03.170 ThaliTest[2737:5186287] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-03 21:07:03.949 ThaliTest[2737:5186287] Using UIWebView
,2016-04-03 21:07:03.952 ThaliTest[2737:5186287] [CDVTimer][handleopenurl] 0.133991ms
2016-04-03 21:07:03.954 ThaliTest[2737:5186287] [CDVTimer][intentandnavigationfilter] 2.140999ms
2016-04-03 21:07:03.955 ThaliTest[2737:5186287] [CDVTimer][gesturehandle,r] 0.105023ms
2016-04-03 21:07:03.955 ThaliTest[2737:5186287] [CDVTimer][TotalPluginStartup] 2.828002ms
,2016-04-03 21:07:07.055 ThaliTest[2737:5186287] Resetting plugins due to page load.
,2016-04-03 21:07:08.449 ThaliTest[2737:5186287] Finished load of: file:///var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/index.html
,2016-04-03 21:07:08.617 ThaliTest[2737:5186287] JXcore Cordova plugin initializing
2016-04-03 21:07:08.618 ThaliTest[2737:5186478] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-03 21:07:15.595 ThaliTest[2737:5186478] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-03 21:07:15.595 ThaliTest[2737:5186478] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-03 21:07:15.595 ThaliTest[2737:5186478] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-03 21:07:15.597 ThaliTest[2737:5186478] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A86FA45C-110F-47B8-9C60-DE8FBC4625DB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57271
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57273
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57276
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57280
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
DEBUG createNativeListener: listening 57285
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
DEBUG createNativeListener: listening 57289
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 57293
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
DEBUG createNativeListener: listening 57297
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
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57301
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
,DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 57353
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
DEBUG createNativeListener: listening 57357
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
,# teardown
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
,[{"uuid":"f6d73446-5000-4d78-b1ff-7f7cf59b2a18","data":"custom data"},{"uuid":"09cac296-ea8d-47c3-aafb-b2ba98d948de","data":"custom data"},{"uuid":"7f465dac-b5fc-4fa0-aece-e506c38feb66","data":"custom data"},{"uuid":"24de18a5-460b-493f-8720-a0ac5fddea1c",",data":"custom data"}]
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
DEBUG createNativeListener: listening 57367
2016-04-03 21:10:42.306 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:42.307 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-03 21:10:42.308 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:42.309 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-03 21:10:42.555 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:42.555 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:10:42.555 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
2016-04-03 21:10:42.555 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:42.556 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57369
2016-04-03 21:10:42.845 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements
,2016-04-03 21:10:42.847 ThaliTest[2737:5186478] multipeer manager: start client restart timer: 0x15ecfed0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:10:42.847 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-03 21:10:42.852 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-04-03 21:10:42.853 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-03 21:10:43.303 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:43.304 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:10:43.304 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:43.304 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
2016-04-03 21:10:43.304 ThaliTest[2737:5186478] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:43.305 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be ,null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57371
2016-04-03 21:10:43.865 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:10:43.865 ThaliTest[2737:5186478] server: starting CD,9AB027-E5E1-43D4-A70E-56CE01144BF3:1
2016-04-03 21:10:43.866 ThaliTest[2737:5186478] multipeer manager: start client restart timer: 0x15ecfed0
2016-04-03 21:10:43.866 ThaliTest[2737:5186478] THEMultipeerManager initialized peer CD9AB027-E5E1-43D4-A70E-56CE01144BF3:1
2016-04-03 21:10:43.866 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-03 21:10:43.872 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:10:43.872 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:10:43.872 ThaliTest[2737:5186478] multipeer manager: stop client timer
2016-04-03 21:10:43.872 ThaliTest[2737:5186478] server: starting CD9AB027-E5E1-43D4-A70E-56CE01144BF3:2
2016-04-03 21:10:43.872 ThaliTest[2737:5186478] multipeer manager: start client restart ,timer: 0x15ecfed0
2016-04-03 21:10:43.872 ThaliTest[2737:5186478] THEMultipeerManager initialized peer CD9AB027-E5E1-43D4-A70E-56CE01144BF3:2
2016-04-03 21:10:43.872 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
,# teardown
,2016-04-03 21:10:44.330 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.330 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:10:44.330 ThaliTest[2737:5186478] multipeer manager: stop client timer
2016-04-03 21:10:44.331 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
2016-04-03 21:10:44.331 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:44.331 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57376
,2016-04-03 21:10:44.768 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.768 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:10:44.768 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
,2016-04-03 21:10:44.770 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.770 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:10:44.770 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-03 21:10:44.917 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.917 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:10:44.917 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:44.917 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:44.918 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57378
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-03 21:10:45.823 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:45.823 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:10:45.823 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
2016-04-03 21:10:45.823 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:45.824 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57380
2016-04-03 21:10:46.911 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements
2016-04-03 21:10:46.912 ThaliTest[2737:5186478] multipeer manager: start client restart timer: 0x15ecfed0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:10:46.912 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements: success
,2016-04-03 21:10:46.920 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:10:46.920 ThaliTest[2737:5186478] server: starting CD9AB027-E5E1-43D4-A70E-56CE01144BF3:3
2016-04-03 21:10:46.920 ThaliTest[2737:5186478] THEMultipeerManager initialized peer CD9AB027-E5E1-43D4-A70E-56CE01144BF3:3
2016-04-03 21:10:46.920 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-03 21:10:47.013 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:47.013 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:10:47.013 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:47.013 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
2016-04-03 21:10:47.013 ThaliTest[2737:5186478] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:47.014 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
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
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
,ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-03 21:11:48.956 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements
2016-04-03 21:11:48.956 ThaliTest[2737:5186478] multipeer manager: start client restart timer: 0x15ecfed0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:11:48.957 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-03 21:11:48.957 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
2016-04-03 21:11:48.957 ThaliTest[2737:5186478] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:11:48.958 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-03 21:11:49.215 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:11:49.216 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:11:49.216 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:11:49.217 ThaliTest[2737:51864,78] THEMultipeerManager stopping peer
2016-04-03 21:11:49.217 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-03 21:11:49.402 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements
2016-04-03 21:11:49.402 ThaliTest[2737:5186478] multipeer manager: start client restart timer: 0x15ecfed0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:11:49.403 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-03 21:11:49.404 ThaliTes,t[2737:5186478] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:11:49.404 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-03 21:11:49.781 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
2016-04-03 21:11:49.781 ThaliTest[2737:5186478] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-03 21:11:49.782 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:11:49.782 ThaliTest[2737:5186,478] jxcore: stopAdvertisingAndListening
2016-04-03 21:11:49.782 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:11:49.783 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-03 21:12:17.941 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:17.941 ThaliTest[2737:51864,78] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-03 21:12:17.942 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:17.942 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-03 21:12:19.780 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:19.781 ThaliTest[2737:51864,78] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:12:19.782 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:12:19.782 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:12:19.782 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-03 21:12:20.043 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:12:20.043 ThaliTest[2737:5186478] server: starting CD9AB027-E5E1-43D4-A70E-56CE01144BF3:4
2016-04-03 21:12:20.043 ThaliTest[2737:5186478] multipeer manager: start client restart timer: 0x15ecfed0
2016-04-03 21:12:20.044 ThaliTest[2737:5186478] THEMultipeerManager initialized peer CD9AB027-E5E1-43D4-A70E-56CE01144BF3:4
2016-04-03 21:12:20.044 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:12:20.045 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:12:20.046 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
,2016-04-03 21:12:20.046 ThaliTest[2737:5186478] multipeer manager: stop client timer
2016-04-03 21:12:20.048 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-03 21:12:20.370 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:12:20.371 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:12:20.372 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:12:20.372 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:12:20.372 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-03 21:13:46.950 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:13:46.951 ThaliTest[2737:5186478] server: starting CD9AB027-E5E1-43D4-A70E-56CE01144BF3:5
2016-04-03 21:13:46.951 ThaliTest[2737:5186478] multipeer m,anager: start client restart timer: 0x15ecfed0
2016-04-03 21:13:46.951 ThaliTest[2737:5186478] THEMultipeerManager initialized peer CD9AB027-E5E1-43D4-A70E-56CE01144BF3:5
2016-04-03 21:13:46.951 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:13:46.953 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:13:46.953 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
,2016-04-03 21:13:46.953 ThaliTest[2737:5186478] multipeer manager: stop client timer
2016-04-03 21:13:46.955 ThaliTest[2737:5186478] server: starting CD9AB027-E5E1-43D4-A70E-56CE01144BF3:6
2016-04-03 21:13:46.956 ThaliTest[2737:5186478] multipeer manager: start client restart timer: 0x15ecfed0
2016-04-03 21:13:46.956 ThaliTest[2737:5186478] THEMultipeerManager initialized peer CD9AB027-E5E1-43D4-A70E-56CE01144BF3:6
2016-04-03 21:13:46.956 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-03 21:13:47.310 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-03 21:13:47.311 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:13:47.311 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.311 ThaliTest[2737:518647,8] THEMultipeerManager stopping peer
2016-04-03 21:13:47.311 ThaliTest[2737:5186478] multipeer manager: stop client timer
2016-04-03 21:13:47.311 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-03 21:13:47.752 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.752 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:13:47.752 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:13:47.753 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.753 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:13:47.753 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-03 21:13:47.878 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:13:47.879 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:13:47.879 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.880 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:13:47.880 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-03 21:14:07.403 ThaliTest[2737:5186478] jxcore: connect foo
2016-04-03 21:14:07.403 ThaliTest[2737:5186478] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
,  ---
,    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
,# teardown
,2016-04-03 21:14:31.892 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:14:31.893 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:14:31.893 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:14:31.894 ThaliTest[2737:51864,78] THEMultipeerManager stopping peer
2016-04-03 21:14:31.894 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-03 21:14:32.470 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:14:32.471 ThaliTest[2737:5186478] server: starting CD9AB027-E5E1-43D4-A70E-56CE01144BF3:7
2016-04-03 21:14:32.471 ThaliTest[2737:5186478] multipeer manager: start client restart timer: 0x15ecfed0
2016-04-03 21:14:32.471 ThaliTest[2737:5186478] THEMultipeerManager initialized peer CD9AB027-E5E1-43D4-A70E-56CE01144BF3:7
2016-04-03 21:14:32.471 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-03 21:14:32.472 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-03 21:14:32.472 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-03 21:14:33.110 ThaliTest[2737:5186287] client: found new peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-03 21:14:33.642 ThaliTest[2737:5186287] client: found new peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:14:33.993 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-03 21:14:33.993 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:14:33.994 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:14:33.994 ThaliTest[2737:518647,8] THEMultipeerManager stopping peer
2016-04-03 21:14:33.994 ThaliTest[2737:5186478] multipeer manager: stop client timer
2016-04-03 21:14:33.994 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-03 21:14:35.010 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:14:35.011 ThaliTest[2737:5186478] server: starting CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:14:35.011 ThaliTest[2737:5186478] multipeer manager: start client restart timer: 0x15ecfed0
2016-04-03 21:14:35.011 ThaliTest[2737:5186478] THEMultipeerManager initialized peer CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:14:35.011 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:14:35.012 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-03 21:14:35.012 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-03 21:14:35.547 ThaliTest[2737:5186287] client: found new peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"569AF1E0-EE92-40BF-918A-581DB52F2,2D0:7","pleaseConnect":0}]
2016-04-03 21:14:35.548 ThaliTest[2737:5186478] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:35.548 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:14:35.548 ThaliTest[2737:5186478] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:36.089 ThaliTest[2737:5186287] client: found new peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9C9DAABD-80A6-487A-AC19-4D6E0668D813:7","pleaseConnect":0}]
,2016-04-03 21:14:36.320 ThaliTest[2737:5187406] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:36.321 ThaliTest[2737:5187406] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:36.3,21 ThaliTest[2737:5187406] client session: disconnect
2016-04-03 21:14:36.321 ThaliTest[2737:5187406] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:36.322 ThaliTest[2737:5187406] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:36.322 ThaliTest[2737:5187406] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 9
,2016-04-03 21:14:37.682 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
2016-04-03 21:14:37.682 ThaliTest[2737:5186287] client: found new peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4C7015DA-AE07-4F33-B74F-C43FFD219895:8","pleaseConnect":0}]
,2016-04-03 21:14:39.330 ThaliTest[2737:5186478] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:39.330 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:14:39.331 ThaliTest[2737:5186478] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:39.401 ThaliTest[2737:5187406] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:39.401 ThaliTest[2737:5187406] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:39.4,02 ThaliTest[2737:5187406] client session: disconnect
2016-04-03 21:14:39.402 ThaliTest[2737:5187406] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:39.402 ThaliTest[2737:5187406] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:39.402 ThaliTest[2737:5187406] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 8
,2016-04-03 21:14:42.406 ThaliTest[2737:5186478] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:42.407 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:14:42.407 ThaliTest[2737:5186478] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:42.472 ThaliTest[2737:5187404] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:42.473 ThaliTest[2737:5187404] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:42.474 ThaliTest[2737:5187404] client session: disconnect
2016-04-03 21:14:42.474 ThaliTest[2737:5187404] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:42.474 ThaliTest[2737:5187404] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:42.474 ThaliTest[2737:5187404] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-03 21:14:45.484 ThaliTest[2737:5186478] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:45.484 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:14:45.485 ThaliTest[2737:5186478] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:45.598 ThaliTest[2737:5187430] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:45.598 ThaliTest[2737:5187430] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:45.598 ThaliTest[2737:5187430] client session: disconnect
2016-04-03 21:14:45.598 ThaliTest[2737:5187430] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:45.599 ThaliTest[2737:5187430] client session: fireConnectCallb,ack: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:45.599 ThaliTest[2737:5187430] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-03 21:14:48.603 ThaliTest[2737:5186478] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:48.603 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:14:48.603 ThaliTest[2737:5186478] client session: stateChange:0->,1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:48.796 ThaliTest[2737:5187430] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:48.797 ThaliTest[2737:5187430] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:48.797 ThaliTest[2737:5187430] client session: disconnect
2016-04-03 21:14:48.797 ThaliTest[2737:5187430] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:48.797 ThaliTest[2737:5187430] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:48.797 ThaliTest[2737:5187430] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-03 21:14:51.807 ThaliTest[2737:5186478] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:51.807 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:14:51.808 ThaliTest[2737:5186478] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:51.958 ThaliTest[2737:5187406] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:51.960 ThaliTest[2737:5187406] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:51.9,60 ThaliTest[2737:5187406] client session: disconnect
2016-04-03 21:14:51.960 ThaliTest[2737:5187406] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:51.960 ThaliTest[2737:5187406] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:51.960 ThaliTest[2737:5187406] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-03 21:14:54.971 ThaliTest[2737:5186478] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:54.971 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:14:54.971 ThaliTest[2737:5186478] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:55.012 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:14:55.039 ThaliTest[2737:5186287] client: found updated peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:14:55.039 ThaliTest[2737:5186287] client: found updated peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
INFO testThaliMobileNati,ve: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"569AF1E0-EE92-40BF-918A-581DB52F22D0:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9C9DAABD-80A6-487A-AC19-4D6E0668D813:8","pleaseConnect":0}]
,2016-04-03 21:14:55.051 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:15:15.012 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:15:15.022 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:15.023 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:15:15.02,3 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:15:27.901 ThaliTest[2737:5187404] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:27.901 ThaliTest[2737:5187404] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:27.9,01 ThaliTest[2737:5187404] client session: disconnect
2016-04-03 21:15:27.901 ThaliTest[2737:5187404] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:27.901 ThaliTest[2737:5187404] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:27.901 ThaliTest[2737:5187404] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-03 21:15:30.906 ThaliTest[2737:5186478] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:30.907 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:15:30.907 ThaliTest[2737:5186478] client session: stateChange:0->,1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:31.284 ThaliTest[2737:5187547] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:31.285 ThaliTest[2737:5187547] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:31.285 ThaliTest[2737:5187547] client session: disconnect
2016-04-03 21:15:31.285 ThaliTest[2737:5187547] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:31.285 ThaliTest[2737:5187547] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:31.285 ThaliTest[2737:5187547] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-03 21:15:34.292 ThaliTest[2737:5186478] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:34.293 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:15:34.293 ThaliTest[2737:5186478] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:34.366 ThaliTest[2737:5187541] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:34.367 ThaliTest[2737:5187541] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:34.3,67 ThaliTest[2737:5187541] client session: disconnect
2016-04-03 21:15:34.368 ThaliTest[2737:5187541] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:34.368 ThaliTest[2737:5187541] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:34.368 ThaliTest[2737:5187541] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-03 21:15:35.012 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:15:35.022 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:35.023 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:15:35.024 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:15:37.381 ThaliTest[2737:5186478] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:37.381 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:15:37.381 ThaliTest[2737:5186478] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:37.476 ThaliTest[2737:5187610] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:37.476 ThaliTest[2737:5187610] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:37.476 ThaliTest[2737:5187610] client session: disconnect
2016-04-03 21:15:37.476 ThaliTest[2737:5187610] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:37.477 ThaliTest[2737:5187610] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:37.477 ThaliTest[2737:5187610] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
,  ---
    operator: fail
,  ...
,# teardown
,2016-04-03 21:15:55.012 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:15:55.024 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:55.024 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:15:55.025 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:16:15.012 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:16:15.027 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:16:15.031 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:15.031 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:16:35.012 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:16:35.023 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:35.023 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:35.023 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:16:43.370 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-03 21:16:43.371 ThaliTest[2737:5186478] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:16:43.372 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening
2016-04-03 21:16:43.372 ThaliTest[2737:5186478] THEMultipeerManager stopping peer
2016-04-03 21:16:43.372 ThaliTest[2737:5186478] multipeer manager: stop client timer
20,16-04-03 21:16:43.373 ThaliTest[2737:5186478] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-03 21:16:43.886 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:16:43.886 ThaliTest[2737:5186478] server: starting CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:16:43.886 ThaliTest[2737:5186478] multipeer m,anager: start client restart timer: 0x15ecfed0
2016-04-03 21:16:43.886 ThaliTest[2737:5186478] THEMultipeerManager initialized peer CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:16:43.886 ThaliTest[2737:5186478] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:16:43.887 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-03 21:16:43.888 ThaliTest[2737:5186478] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-03 21:16:44.802 ThaliTest[2737:5186287] client: found new peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:44.803 ThaliTest[2737:5186287] client: found new peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:44.803 ThaliTest[2737:5186287] client: found new peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:16:44.804 ThaliTest[2737:5186478] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:44.806 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:16:44.806 ThaliTest[2737:5186478] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:45.231 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:16:45.231 ThaliTest[2737:5186287] server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:16:45.590 ThaliTest[2737:5187769] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:45.591 ThaliTest[2737:5187769] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:45.5,91 ThaliTest[2737:5187769] client session: disconnect
2016-04-03 21:16:45.591 ThaliTest[2737:5187769] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:45.592 ThaliTest[2737:5187769] client session: fireConnectCallback: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:45.592 ThaliTest[2737:5187769] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-03 21:16:46.187 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:16:46.187 ThaliTest[2737:5186287] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:16:48.599 ThaliTest[2737:5186478] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:48.600 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:16:48.600 ThaliTest[2737:5186478] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:48.807 ThaliTest[2737:5187754] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:48.807 ThaliTest[2737:5187754] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:48.807 ThaliTest[2737:5187754] client session: disconnect
2016-04-03 21:16:48.807 ThaliTest[2737:5187754] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:48.807 ThaliTest[2737:5187754] client session: fireConnectCallb,ack: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:48.807 ThaliTest[2737:5187754] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-03 21:16:51.817 ThaliTest[2737:5186478] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:51.817 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:16:51.817 ThaliTest[2737:5186478] client session: stateChange:0->,1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:51.941 ThaliTest[2737:5187769] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:51.941 ThaliTest[2737:5187769] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:51.9,41 ThaliTest[2737:5187769] client session: disconnect
2016-04-03 21:16:51.941 ThaliTest[2737:5187769] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:51.941 ThaliTest[2737:5187769] client session: fireConnectCallback: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:51.941 ThaliTest[2737:5187769] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-03 21:16:54.948 ThaliTest[2737:5186478] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:54.948 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:16:54.948 ThaliTest[2737:5186478] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:55.081 ThaliTest[2737:5187753] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:55.082 ThaliTest[2737:5187753] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:55.0,82 ThaliTest[2737:5187753] client session: disconnect
2016-04-03 21:16:55.082 ThaliTest[2737:5187753] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:55.082 ThaliTest[2737:5187753] client session: fireConnectCallback: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:55.082 ThaliTest[2737:5187753] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-03 21:16:58.086 ThaliTest[2737:5186478] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:58.087 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:16:58.087 ThaliTest[2737:5186478] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:58.190 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:16:58.190 ThaliTest[2737:5186287] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:16:58.190 ThaliTest[2737:5186287] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:16:58.233 ThaliTest[2737:5187753] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:58.233 ThaliTest[2737:5187753] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:58.233 ThaliTest[2737:5187753] client session: disconnect
2016-04-03 21:16:58.233 ThaliTest[2737:5187753] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:58.235 ThaliTest[2737:5187753] client session: fireConnectCallback: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:58.235 ThaliTest[2737:5187753] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-03 21:16:58.632 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:16:58.632 ThaliTest[2737:5186287] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:16:58.632 ThaliTest[2737:5186287] server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:17:01.241 ThaliTest[2737:5186478] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:17:01.241 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:17:01.241 ThaliTest[2737:5186478] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:17:01.383 ThaliTest[2737:5187769] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:17:01.384 ThaliTest[2737:5187769] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:17:01.384 ThaliTest[2737:5187769] client session: disconnect
2016-04-03 21:17:01.384 ThaliTest[2737:5187769] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:17:01.384 ThaliTest[2737:5187769] client session: fireConnectCallb,ack: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:17:01.384 ThaliTest[2737:5187769] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-03 21:17:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:17:03.901 ThaliTest[2737:5186287] client: found updated peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:17:03.902 ThaliTest[2737:5186287] client: found updated peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:03.903 ThaliTest[2737:5186287] client: found updated peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:17:04.390 ThaliTest[2737:5186478] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:17:04.390 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:17:04.390 ThaliTest[2737:5186478] client session: stateChange:0->,1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:17:04.479 ThaliTest[2737:5187753] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:04.479 ThaliTest[2737:5187753] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:17:04.4,79 ThaliTest[2737:5187753] client session: disconnect
2016-04-03 21:17:04.479 ThaliTest[2737:5187753] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:04.479 ThaliTest[2737:5187753] client session: fireConnectCallb,ack: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:17:04.479 ThaliTest[2737:5187753] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 3
,2016-04-03 21:17:07.482 ThaliTest[2737:5186478] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:17:07.482 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:17:07.482 ThaliTest[2737:5186478] client session: stateChange:0->,1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:17:07.649 ThaliTest[2737:5187853] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:17:07.650 ThaliTest[2737:5187853] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:17:07.650 ThaliTest[2737:5187853] client session: disconnect
2016-04-03 21:17:07.650 ThaliTest[2737:5187853] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:07.650 ThaliTest[2737:5187853] client session: fireConnectCallback: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:17:07.650 ThaliTest[2737:5187853] jxcore: connect: fail: Peer, disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-03 21:17:10.660 ThaliTest[2737:5186478] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:17:10.660 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:17:10.660 ThaliTest[2737:5186478] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:17:10.781 ThaliTest[2737:5187577] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:10.781 ThaliTest[2737:5187577] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:17:10.7,81 ThaliTest[2737:5187577] client session: disconnect
2016-04-03 21:17:10.781 ThaliTest[2737:5187577] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:10.781 ThaliTest[2737:5187577] client session: fireConnectCallb,ack: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:17:10.781 ThaliTest[2737:5187577] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-03 21:17:10.943 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:17:10.943 ThaliTest[2737:5186287] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:17:10.943 ThaliTest[2737:5186287] server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:17:11.072 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:17:11.073 ThaliTest[2737:5186287] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:17:11.073 ThaliTest[2737:5186287] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:17:13.783 ThaliTest[2737:5186478] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:17:13.783 ThaliTest[2737:5186478] client session: connect
2016-04-03 21:17:13.784 ThaliTest[2737:5186478] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:17:13.916 ThaliTest[2737:5187843] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:13.917 ThaliTest[2737:5187843] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:17:13.917 ThaliTest[2737:5187843] client session: disconnect
2016-04-03 21:17:13.917 ThaliTest[2737:5187843] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:13.917 ThaliTest[2737:5187843] client session: fireConnectCallb,ack: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:17:13.917 ThaliTest[2737:5187843] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-03 21:17:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:17:23.897 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:17:23.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:23.898 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:17:24.191 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:17:24.191 ThaliTest[2737:5186287] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:17:24.191 ThaliTest[2737:5186287] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:17:37.626 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:17:37.626 ThaliTest[2737:5186287] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:17:37.626 ThaliTest[2737:5186287], server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:17:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:17:44.036 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:44.036 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:17:44.036 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:17:50.320 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:17:50.320 ThaliTest[2737:5186287] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:17:50.320 ThaliTest[2737:5186287] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:18:03.783 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:18:03.783 ThaliTest[2737:5186287] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:18:03.783 ThaliTest[2737:5186287] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:18:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:18:03.902 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:18:03.902 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:18:03.90,2 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:18:16.428 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:18:16.429 ThaliTest[2737:5186287] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:18:16.429 ThaliTest[2737:5186287] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:18:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:18:23.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:18:23.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:18:23.901 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:18:29.438 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:18:29.438 ThaliTest[2737:5186287] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:18:29.438 ThaliTest[2737:5186287], server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:18:42.640 ThaliTest[2737:5186287] multipeer session: reset timer
2016-04-03 21:18:42.640 ThaliTest[2737:5186287] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:18:42.641 ThaliTest[2737:5186287] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9 != CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8)
,2016-04-03 21:18:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:18:43.903 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:18:43.903 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:18:43.907 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:19:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:19:03.898 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:19:03.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:19:03.900 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:19:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:19:23.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:19:23.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:19:23.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:19:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:19:43.900 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:19:43.900 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:19:43.900 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:20:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:20:03.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:20:03.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:20:03.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:20:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:20:23.996 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:20:23.997 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:20:23.998 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:20:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:20:43.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:20:43.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:20:43.901 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:21:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:21:03.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:21:03.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:21:03.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:21:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:21:23.900 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:21:23.900 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:21:23.900 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:21:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:21:43.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:21:43.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:21:43.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:22:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:22:03.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:22:03.898 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:22:03.898 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:22:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:22:23.900 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:22:23.900 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:22:23.900 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:22:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:22:43.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:22:43.900 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:22:43.901 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:23:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:23:03.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:23:03.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:23:03.901 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:23:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:23:23.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:23:23.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:23:23.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:23:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:23:43.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:23:43.898 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:23:43.898 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:24:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:24:03.898 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:24:03.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:24:03.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:24:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:24:23.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:24:23.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:24:23.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:24:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:24:43.898 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:24:43.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:24:43.898 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:25:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:25:03.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:25:03.898 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:25:03.900 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:25:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:25:23.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:25:23.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:25:23.89,9 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:25:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:25:43.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:25:43.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:25:43.900 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:26:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:26:03.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:26:03.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:26:03.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:26:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:26:23.905 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:26:23.905 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:26:23.905 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:26:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:26:43.901 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:26:43.902 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:26:43.902 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:27:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:27:03.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:27:03.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:27:03.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:27:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:27:23.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:27:23.898 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:27:23.901 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:27:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:27:43.898 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:27:43.898 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:27:43.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:28:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:28:03.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:28:03.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:28:03.89,9 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:28:23.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:28:23.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:28:23.899 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:28:23.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:28:43.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:28:43.899 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:28:43.899 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:28:43.900 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:29:03.887 ThaliTest[2737:5186287] multipeer manager: restart client
,2016-04-03 21:29:03.898 ThaliTest[2737:5186287] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:29:03.898 ThaliTest[2737:5186287] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:29:03.900 ThaliTest[2737:5186287] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9

```
