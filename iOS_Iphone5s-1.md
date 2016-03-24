#### Test 639808773799dbd_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639808773799dbd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/79814800-C7A2-4DB5-B49E-D5406B0AAA46/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/79814800-C7A2-4DB5-B49E-D5406B0AAA46/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639808773799dbd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639808773799dbd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56024"
,(lldb)     command script import "/tmp/79814800-C7A2-4DB5-B49E-D5406B0AAA46/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-24 22:48:03.138 ThaliTest[2216:3799290] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/44467FC8-E1F2-43A1-A207-1771717E1FD6/Library/Cookies/Cookies.binarycookies
,2016-03-24 22:48:03.393 ThaliTest[2216:3799290] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 22:48:03.395 ThaliTest[2216:3799290] Multi-tasking -> Device: YES, App: YES
,2016-03-24 22:48:03.414 ThaliTest[2216:3799290] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 22:48:04.231 ThaliTest[2216:3799290] Using UIWebView
,2016-03-24 22:48:04.235 ThaliTest[2216:3799290] [CDVTimer][handleopenurl] 0.166953ms
,2016-03-24 22:48:04.238 ThaliTest[2216:3799290] [CDVTimer][intentandnavigationfilter] 2.864957ms
2016-03-24 22:48:04.238 ThaliTest[2216:3799290] [CDVTimer][gesturehandler] 0.138998ms
2016-03-24 22:48:04.239 ThaliTest[2216:3799290] [CDVTimer][TotalPluginS,tartup] 3.875971ms
,2016-03-24 22:48:07.485 ThaliTest[2216:3799290] Resetting plugins due to page load.
,2016-03-24 22:48:08.970 ThaliTest[2216:3799290] Finished load of: file:///var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/index.html
,2016-03-24 22:48:09.155 ThaliTest[2216:3799290] JXcore Cordova plugin initializing
,2016-03-24 22:48:09.157 ThaliTest[2216:3799460] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 22:48:17.470 ThaliTest[2216:3799460] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 22:48:17.471 ThaliTest[2216:3799460] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-24 22:48:17.472 ThaliTest[2216:3799460] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 22:48:17.475 ThaliTest[2216:3799460] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/72F3A254-9EA9-4330-955A-1A65FA282C61/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53403
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53405
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53408
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
DEBUG createNativeListener: listening 53412
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
,DEBUG createNativeListener: listening 53417
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53421
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
DEBUG createNativeListener: listening 53425
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
DEBUG createNativeListener: listening 53429
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
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53433
,DEBUG createNativeListener: new incoming socket
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
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
D,EBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 53485
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
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
DEBUG createNativeListener: listening 53489
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
ok 43 The mux object should be c,losed
ok 44 The mux stream should be closed
,# teardown
,# setup
,# 12. closeAll can close even when connections open
,ok 45 not possible to connect to the server anymore
,# teardown
,# setup
,# 13. closeAll with promise
,ok 46 not possible to connect to the server anymore
,# teardown
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
# teardown
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
,# teardown
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
# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 83 specific error should be returned
# teardown
,ok 84 error should be null
ok 85 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 86 specific error should be returned
# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53501
2016-03-24 22:50:52.587 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:52.588 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements: success
ok 89 error should be null
ok 90 error should be null
2016-03-24 22:50:52.590 ThaliTest[2216:3799460] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:52.590 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
# teardown
,2016-03-24 22:50:52.696 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:52.696 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:50:52.696 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:50:52.696 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:52.697 ThaliTest[2216,:3799460] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53503
2016-03-24 22:50:52.924 ThaliTest[2216:3799460] jxcore: startListeningForAdvertisements
,2016-03-24 22:50:52.926 ThaliTest[2216:3799460] multipeer manager: start client restart timer: 0x17d9f5f0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:50:52.927 ThaliTest[2216:3799460] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,2016-03-24 22:50:52.967 ThaliTest[2216:3799460] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:50:52.968 ThaliTest[2216:3799460] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,# teardown
,2016-03-24 22:50:53.278 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:53.278 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:50:53.278 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:50:53.278 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements
2016-03-24 22:50:53.279 ThaliTest[2216:3799460] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:53.279 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 99 error should be null
,ok 100 error should be null
,# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53505
,2016-03-24 22:50:53.901 ThaliTest[2216:3799460] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:50:53.902 ThaliTest[2216:3799460] server: starting D1CCE0D6-CC62-4A73-AA58-0307202126AA:1
2016-03-24 22:50:53.902 ThaliTest[2216:3799460] multipeer m,anager: start client restart timer: 0x17d9f5f0
2016-03-24 22:50:53.902 ThaliTest[2216:3799460] THEMultipeerManager initialized peer D1CCE0D6-CC62-4A73-AA58-0307202126AA:1
2016-03-24 22:50:53.902 ThaliTest[2216:3799460] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 101 error should be null
ok 102 error should be null
2016-03-24 22:50:53.934 ThaliTest[2216:3799460] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:50:53.935 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:50:53.935 ThaliTest[2216:3799460] multipeer manager: stop client timer
2016-03-24 22:50:53.935 ThaliTest[2216:3799460] server: starting D1CCE0D6-CC62-4A73-AA58-0307202126AA:2
2016-03-24 22:50:53.936 ThaliTest[2216:3799460] multipeer manager: start client restart ,timer: 0x17d9f5f0
2016-03-24 22:50:53.936 ThaliTest[2216:3799460] THEMultipeerManager initialized peer D1CCE0D6-CC62-4A73-AA58-0307202126AA:2
2016-03-24 22:50:53.936 ThaliTest[2216:3799460] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,# teardown
,2016-03-24 22:50:54.374 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:54.374 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:50:54.374 ThaliTest[2216:3799460] multipeer manager: stop client timer
20,16-03-24 22:50:54.374 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:50:54.374 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 22:50:54.375 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 105 error should be null
,ok 106 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53510
2016-03-24 22:50:55.220 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:55.220 ThaliTest[2216:3799460] THEMultipeerManager stoppi,ng peer
2016-03-24 22:50:55.220 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
,2016-03-24 22:50:55.223 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:55.223 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:50:55.223 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
# teardown
,2016-03-24 22:50:55.447 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:55.448 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:50:55.448 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:50:55.448 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:55.449 ThaliTest[2216,:3799460] jxcore: stopListeningForAdvertisements: success
ok 111 error should be null
ok 112 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53512
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
# teardown
,2016-03-24 22:50:56.295 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:56.295 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:50:56.296 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:50:56.296 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:56.297 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements: success
,ok 116 error should be null
ok 117 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53514
2016-03-24 22:50:56.796 ThaliTest[2216:3799460] jxcore: startListeningForAdvertisements
2016-03-24 22:50:56.797 ThaliTest[2216:3799460] multipeer manager: start client restart timer: 0x17d9f5f0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:50:56.798 ThaliTest[2216:3799460] jxcore: startListeningForAdvertisements: success
,2016-03-24 22:50:56.809 ThaliTest[2216:3799460] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:50:56.809 ThaliTest[2216:3799460] server: starting D1CCE0D6-CC62-4A73-AA58-0307202126AA:3
2016-03-24 22:50:56.810 ThaliTest[2216:3799460] THEMultipeerManager initialized peer D1CCE0D6-CC62-4A73-AA58-0307202126AA:3
2016-03-24 22:50:56.810 ThaliTest[2216:3799460] jxcore: startUpdateAdvertisingAndListening: success
ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
# teardown
,2016-03-24 22:50:56.920 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:56.920 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:50:56.921 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 22:50:56.921 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements
2016-03-24 22:50:56.921 ThaliTest[2216:3799460] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:56.922 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 121 error should be null
ok 122 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 123 should be called once
,ok 124 should not have been called more than once
,# teardown
,ok 125 error should be null
ok 126 error should be null
,# setup
,# 33. can get the network status
,ok 127 network status should have certain non-empty properties
# teardown
,ok 128 error should be null
ok 129 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 130 host address should match
ok 131 port should match
,ok 132 host address should be null
ok 133 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-24 22:51:32.527 ThaliTest[2216:3799460] jxcore: startListeningForAdvertisements
2016-03-24 22:51:32.527 ThaliTest[2216:3799460] multipeer manager: start client restart timer: 0x17d9f5f0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:51:32.528 ThaliTest[2216:3799460] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-24 22:51:32.529 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements
2016-03-24 22:51:32.529 ThaliTest[2216:3799460] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-24 22:51:32.530 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-24 22:51:32.660 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:51:32.660 ThaliTest[2216:37994,60] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 22:51:32.661 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016-03-24 22:51:32.661 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:51:32.661 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 22:51:33.307 ThaliTest[2216:3799460] jxcore: startListeningForAdvertisements
2016-03-24 22:51:33.307 ThaliTest[2216:3799460] multipeer manager: start client restart timer: 0x17d9f5f0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:51:33.308 ThaliTest[2216:3799460] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-24 22:51:33.309 ThaliTes,t[2216:3799460] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:51:33.310 ThaliTest[2216:3799460] jxcore: startListeningForAdv,ertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 22:51:33.459 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements
2016-03-24 22:51:33.460 ThaliTest[2216:3799460] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 22:51:33.461 ThaliTest[2216:3799460] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 22:51:33.462 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016-03-24 22:51:33.462 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:51:33.462 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 22:51:52.345 ThaliTest[2216:3799460] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:51:52.345 ThaliTest[2216:3799460] server: starting D1CCE0D6-CC62-4A73-AA58-0307202126AA:4
2016-03-24 22:51:52.345 ThaliTest[2216:3799460] multipeer manager: start client restart timer: 0x17d9f5f0
2016-03-24 22:51:52.346 ThaliTest[2216:3799460] THEMultipeerManager initialized peer D1CCE0D6-CC62-4A73-AA58-0307202126AA:4
,2016-03-24 22:51:52.349 ThaliTest[2216:3799460] jxcore: startUpdateAdvertisingAndListening: success
ok 144 Can call startUpdateAdvertisingAndListening without error
2016-03-24 22:51:52.350 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening
2016,-03-24 22:51:52.350 ThaliTest[2216:3799460] THEMultipeerManager stopping peer
2016-03-24 22:51:52.350 ThaliTest[2216:3799460] multipeer manager: stop client timer
2016-03-24 22:51:52.350 ThaliTest[2216:3799460] jxcore: stopAdvertisingAndListening: success
ok 145 Can call stopAdvertisingAndListening without error
# teardown

```
