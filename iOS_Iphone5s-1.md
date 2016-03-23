#### Test 63848581358a1d8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63848581358a1d8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/2525C111-7A37-4DE2-9BA1-96A9948CDC00/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2525C111-7A37-4DE2-9BA1-96A9948CDC00/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63848581358a1d8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63848581358a1d8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55184"
,(lldb)     command script import "/tmp/2525C111-7A37-4DE2-9BA1-96A9948CDC00/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-23 11:45:41.020 ThaliTest[2042:3566770] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1C3F3093-9FBA-4689-8F02-153D98D3D063/Library/Cookies/Cookies.binarycookies
,2016-03-23 11:45:41.387 ThaliTest[2042:3566770] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-23 11:45:41.388 ThaliTest[2042:3566770] Multi-tasking -> Device: YES, App: YES
,2016-03-23 11:45:41.414 ThaliTest[2042:3566770] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-23 11:45:43.317 ThaliTest[2042:3566770] Using UIWebView
,2016-03-23 11:45:43.325 ThaliTest[2042:3566770] [CDVTimer][handleopenurl] 0.478983ms
,2016-03-23 11:45:43.334 ThaliTest[2042:3566770] [CDVTimer][intentandnavigationfilter] 8.050978ms
2016-03-23 11:45:43.335 ThaliTest[2042:3566770] [CDVTimer][gesturehandler] 0.393987ms
2016-03-23 11:45:43.336 ThaliTest[2042:3566770] [CDVTimer][TotalPluginS,tartup] 10.797024ms
,2016-03-23 11:45:50.606 ThaliTest[2042:3566770] Resetting plugins due to page load.
,2016-03-23 11:45:54.633 ThaliTest[2042:3566770] Finished load of: file:///var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/index.html
,2016-03-23 11:45:54.886 ThaliTest[2042:3566770] JXcore Cordova plugin initializing
,2016-03-23 11:45:54.888 ThaliTest[2042:3566972] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-23 11:46:03.565 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:46:03.565 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:46:03.566 ThaliTest[2042:3,566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:46:03.568 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1866EF8C-D710-49CB-A02F-C516C4503411/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-23 11:46:10.590 ThaliTest[2042:3566770] THREAD WARNING: ['JXcore'] took '6642.361084' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51040
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51042
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
,DEBUG createNativeListener: listening 51045
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
,DEBUG createNativeListener: listening 51049
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
,DEBUG createNativeListener: listening 51054
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 51058
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
,ok 16 incoming is cleaned up
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51062
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51066
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
,DEBUG createNativeListener: listening 51070
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 51122
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
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
,DEBUG createNativeListener: listening 51126
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
,ok 40 server should be fine
,ok 41 server should be open
,ok 42 incoming has been removed
,ok 43 The mux object should be closed
,ok 44 The mux stream should be closed
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
,# 14. multiplex can send data
,ok 47 String should be length:200
,# teardown
,# setup
,# 15. enqueue and run in order
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# teardown
,# setup
,# 16. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# teardown
,# setup
,# 17. mix enqueue and enqueueAtTop
,ok 64 fourth
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# teardown
,# setup
,# 18. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
,# setup
,# 19. basic
,ok 74 sane
,# teardown
,# setup
,# 20. another
,ok 75 sane
,# teardown
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
,ok 84 error should be null
,# setup
,# 23. #startUpdateAdvertisingAndListening should fail if start not called
,ok 85 specific error should be returned
,# teardown
,ok 86 error should be null
,ok 87 error should be null
,# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51138
,2016-03-23 11:48:04.479 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:04.483 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-23 11:48:04.490 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:04.493 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-23 11:48:04.611 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:04.612 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:04.613 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:48:04.614 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:04.616 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51140
,2016-03-23 11:48:04.943 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
,2016-03-23 11:48:04.946 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:04.948 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-23 11:48:05.002 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:05.006 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-23 11:48:06.266 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:06.267 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:06.267 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:48:06.269 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
2016-03-23 11:48:06.270 ThaliTest[2042:3566972] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:48:06.273 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51142
,2016-03-23 11:48:10.258 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:10.259 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:1
2016-03-23 11:48:10.260 ThaliTest[2042:3566972] multipeer m,anager: start client restart timer: 0x16e81900
2016-03-23 11:48:10.261 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:1
2016-03-23 11:48:10.261 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-23 11:48:10.301 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:10.301 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:10.302 ThaliTest[2042:3566972] multipeer manager: stop client ti,mer
2016-03-23 11:48:10.303 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:2
2016-03-23 11:48:10.304 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
2016-03-23 11:48:10.305 ThaliTest[2042:,3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:2
2016-03-23 11:48:10.311 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-23 11:48:10.624 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:10.625 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:10.626 ThaliTest[2042:3566972] multipeer manager: stop client timer
2016-03-23 11:48:10.627 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: su,ccess
2016-03-23 11:48:10.627 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:10.629 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51147
,2016-03-23 11:48:29.297 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:29.298 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:29.298 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: suc,cess
,ok 106 error should be null
,ok 107 error should be null
,2016-03-23 11:48:29.306 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:29.306 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:29.307 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: suc,cess
ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-23 11:48:29.502 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:29.503 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:29.503 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:48:29.506 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:29.508 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51149
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-23 11:48:34.295 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:34.296 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:34.296 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: suc,cess
,2016-03-23 11:48:34.298 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:34.301 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51151
,2016-03-23 11:48:35.231 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
,2016-03-23 11:48:35.233 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:35.235 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
,2016-03-23 11:48:35.288 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:48:35.289 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:3
,2016-03-23 11:48:35.291 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:3
,2016-03-23 11:48:35.299 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
,ok 118 discovery state matches
,ok 119 advertising state matches
,# teardown
,2016-03-23 11:48:35.509 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:35.511 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
,2016-03-23 11:48:35.512 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:48:35.516 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,2016-03-23 11:48:35.518 ThaliTest[2042:3566972] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:35.526 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 120 error should be null
,ok 121 error should be null
,# setup
,# 30. does not send duplicate availability changes
,ok 122 should be called once
,ok 123 should not have been called more than once
,# teardown
,ok 124 error should be null
,ok 125 error should be null
,# setup
,# 31. can get the network status
,ok 126 network status should have certain non-empty properties
,# teardown
,ok 127 error should be null
,ok 128 error should be null
,# setup
,# 32. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 129 host address should match
,ok 130 port should match
,ok 131 host address should be null
,ok 132 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 133 error should be null
,ok 134 error should be null
,# setup
,# 33. Can call start/stopListeningForAdvertisements
,2016-03-23 11:48:44.266 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
,2016-03-23 11:48:44.268 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:44.271 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
,ok 135 Can call startListeningForAdvertisements without error
,2016-03-23 11:48:44.275 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
2016-03-23 11:48:44.276 ThaliTest[2042:3566972] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-23 11:48:44.279 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-23 11:48:44.620 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:44.623 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:44.627 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:44.627 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:44.628 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-23 11:48:45.206 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
2016-03-23 11:48:45.207 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 11:48:45.209 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
,ok 139 Can call startListeningForAdvertisements without error
2016-03-23 11:48:45.214 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:45.218 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
,ok 140 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-23 11:48:45.775 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
2016-03-23 11:48:45.776 ThaliTest[2042:3566972] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:45.779 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-23 11:48:45.783 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2,016-03-23 11:48:45.783 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:45.783 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-23 11:48:47.329 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:47.330 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:4
2016-03-23 11:48:47.331 ThaliTest[2042:3566972] multipeer m,anager: start client restart timer: 0x16e81900
2016-03-23 11:48:47.331 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:4
2016-03-23 11:48:47.332 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 11:48:47.335 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:47.336 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
,2016-03-23 11:48:47.337 ThaliTest[2042:3566972] multipeer manager: stop client timer
,2016-03-23 11:48:47.337 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
,ok 144 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-23 11:48:47.600 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:47.603 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:47.606 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:47.607 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:47.607 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: suc,cess
ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-23 11:48:48.126 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:48.127 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:5
2016-03-23 11:48:48.128 ThaliTest[2042:3566972] multipeer m,anager: start client restart timer: 0x16e81900
2016-03-23 11:48:48.128 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:5
2016-03-23 11:48:48.130 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 11:48:48.143 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:48:48.145 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
,2016-03-23 11:48:48.150 ThaliTest[2042:3566972] multipeer manager: stop client timer
,2016-03-23 11:48:48.157 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:6
,2016-03-23 11:48:48.162 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
,2016-03-23 11:48:48.174 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:6
,2016-03-23 11:48:48.177 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening: success
,ok 148 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-03-23 11:48:48.350 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:48:48.354 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:48.358 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:48.358 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:48.359 ThaliTest[2042:3566972] multipeer manager: stop client timer
20,16-03-23 11:48:48.359 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. peerAvailabilityChange is called
,2016-03-23 11:48:48.750 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:48.750 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:48:48.751 ThaliTest[2042:3566972] multipeer m,anager: start client restart timer: 0x16e81900
2016-03-23 11:48:48.752 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:48:48.752 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-23 11:48:48.755 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-23 11:48:48.758 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
ok 152 Can call startListeningForAdvertisements without error
,2016-03-23 11:48:50.082 ThaliTest[2042:3566770] client: found new peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:7
,2016-03-23 11:48:50.088 ThaliTest[2042:3566770] client: found new peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
ok 153 peers must be an array
ok 154 peers must not be zero-length
ok 155 peer must have peerIdentifier
ok 156 peerIdentifier must be a strin,g
,ok 157 peer must have peerAvailable
ok 158 peer must have pleaseConnect
,# teardown
,2016-03-23 11:48:51.803 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:48:51.806 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 159 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:51.809 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:51.810 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:48:51.810 ThaliTest[2042:3566972] multipeer manager: stop client timer
20,16-03-23 11:48:51.811 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Can connect to a remote peer
,2016-03-23 11:49:15.462 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:49:15.463 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:49:15.464 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
,2016-03-23 11:49:15.467 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:15.467 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening: success
ok 161 Can call startUpdateAdv,ertisingAndListening without error
,2016-03-23 11:49:15.470 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-23 11:49:15.473 ThaliTest[2042:356697,2] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-23 11:49:15.495 ThaliTest[2042:3566770] client: found new peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"71AA62C9-76E6-4355-A877-ED5FEA587,FD9:7","pleaseConnect":0}]
2016-03-23 11:49:15.501 ThaliTest[2042:3566972] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:49:15.503 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:49:15.503 ThaliTest[2042:3566972], client session: reverseConnect
2016-03-23 11:49:15.504 ThaliTest[2042:3566972] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
,2016-03-23 11:49:16.391 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:49:16.392 ThaliTest[2042:3566770] server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697,E6BF5F0:8 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7)
,2016-03-23 11:49:16.826 ThaliTest[2042:3567406] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:49:16.826 ThaliTest[2042:3567406] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:49:16.8,27 ThaliTest[2042:3567406] client session: disconnect
2016-03-23 11:49:16.827 ThaliTest[2042:3567406] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:49:16.828 ThaliTest[2042:3567406] client session: no connect callb,ack (server initiated)
,2016-03-23 11:49:19.564 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:49:19.565 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:49:19.565 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7)
,2016-03-23 11:49:23.217 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:49:23.217 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:49:23.217 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7)
,2016-03-23 11:49:24.176 ThaliTest[2042:3566770] client: found new peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"D95DAC2A-FB09-4A72-B9F2-B5180B076E64:7","pleaseConnect":0}]
,2016-03-23 11:49:25.504 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-23 11:49:26.772 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:49:26.772 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:49:26.772 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7)
,2016-03-23 11:49:28.515 ThaliTest[2042:3566972] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:49:28.516 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:49:28.516 ThaliTest[2042:3566972] client session: reverseConnect
2016-03-23 11:49:28.516 ThaliTest[2042:3566972] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
,2016-03-23 11:49:28.885 ThaliTest[2042:3567408] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:49:28.886 ThaliTest[2042:3567408] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:49:28.8,86 ThaliTest[2042:3567408] client session: disconnect
,2016-03-23 11:49:28.887 ThaliTest[2042:3567408] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:49:28.891 ThaliTest[2042:3567408] client session: no connect callback (server initiated)
,2016-03-23 11:49:30.974 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:49:30.975 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:49:30.976 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7)
,2016-03-23 11:49:34.178 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:49:34.179 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:49:34.179 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7)
,2016-03-23 11:49:35.467 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:49:35.498 ThaliTest[2042:3566770] client: found updated peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:49:35.500 ThaliTest[2042:3566770] client: found updated peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"71AA62C9-76E6-4355-A877-ED5FEA587FD9:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8","pleaseConnect":0}]
,2016-03-23 11:49:37.329 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:49:37.329 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:49:37.330 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7)
,2016-03-23 11:49:38.517 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 11:49:40.477 ThaliTest[2042:3566770] multipeer session: reset timer
,2016-03-23 11:49:40.479 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:49:40.479 ThaliTest[2042:3566770] server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to p,revious generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7)
,2016-03-23 11:49:41.533 ThaliTest[2042:3566972] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:49:41.533 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:49:41.534 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:49:41.534 ThaliTest[2042:3566972] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:49:41.860 ThaliTest[2042:3567526] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:49:41.860 ThaliTest[2042:3567526] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:49:41.8,61 ThaliTest[2042:3567526] client session: disconnect
2016-03-23 11:49:41.861 ThaliTest[2042:3567526] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:49:41.865 ThaliTest[2042:3567526] client session: no connect callback (server initiated)
,2016-03-23 11:49:43.692 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:49:43.693 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:49:43.693 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7)
,2016-03-23 11:49:47.226 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:49:47.227 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:49:47.227 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7)
,2016-03-23 11:49:51.535 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-23 11:49:54.545 ThaliTest[2042:3566972] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:49:54.546 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:49:54.547 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:49:54.547 ThaliTest[2042:3566972] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:49:55.026 ThaliTest[2042:3567427] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:49:55.026 ThaliTest[2042:3567427] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:49:55.0,27 ThaliTest[2042:3567427] client session: disconnect
,2016-03-23 11:49:55.028 ThaliTest[2042:3567427] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:49:55.030 ThaliTest[2042:3567427] client session: no connect callback (server initiated)
,2016-03-23 11:49:55.467 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:49:55.499 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:49:55.500 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:50:04.547 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-23 11:50:07.563 ThaliTest[2042:3566972] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:50:07.564 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:50:07.565 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:50:07.565 ThaliTest[2042:3566972] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:50:07.854 ThaliTest[2042:3567427] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:50:07.855 ThaliTest[2042:3567427] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:50:07.8,55 ThaliTest[2042:3567427] client session: disconnect
2016-03-23 11:50:07.855 ThaliTest[2042:3567427] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:50:07.856 ThaliTest[2042:3567427] client session: no connect callback (server initiated)
,2016-03-23 11:50:15.467 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:50:15.503 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:50:15.504 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:50:17.566 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 11:50:20.571 ThaliTest[2042:3566972] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:50:20.571 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:50:20.572 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:50:20.572 ThaliTest[2042:3566972] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:50:20.959 ThaliTest[2042:3567658] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:50:20.959 ThaliTest[2042:3567658] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:50:20.960 ThaliTest[2042:3567658] client session: disconnect
,2016-03-23 11:50:20.960 ThaliTest[2042:3567658] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:50:20.965 ThaliTest[2042:3567658] client session: no connect callback (server initiated)
,2016-03-23 11:50:30.573 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 11:50:33.578 ThaliTest[2042:3566972] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:50:33.579 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:50:33.580 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:50:33.580 ThaliTest[2042:3566972] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:50:33.942 ThaliTest[2042:3567656] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:50:33.943 ThaliTest[2042:3567656] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:50:33.943 ThaliTest[2042:3567656] client session: disconnect
,2016-03-23 11:50:33.944 ThaliTest[2042:3567656] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:50:33.949 ThaliTest[2042:3567656] client session: no connect callback (server initiated)
,2016-03-23 11:50:35.467 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:50:35.503 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:50:35.504 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:50:43.581 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-23 11:50:46.591 ThaliTest[2042:3566972] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:50:46.592 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:50:46.593 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:50:46.593 ThaliTest[2042:3566972] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:50:47.035 ThaliTest[2042:3567808] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:50:47.036 ThaliTest[2042:3567808] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:50:47.0,36 ThaliTest[2042:3567808] client session: disconnect
,2016-03-23 11:50:47.037 ThaliTest[2042:3567808] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:50:47.041 ThaliTest[2042:3567808] client session: no connect callback (server initiated)
,2016-03-23 11:50:55.467 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:50:55.504 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:50:55.505 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:50:56.594 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-23 11:50:59.609 ThaliTest[2042:3566972] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:50:59.610 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:50:59.610 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:50:59.611 ThaliTest[2042:3566972] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:00.338 ThaliTest[2042:3567811] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:00.340 ThaliTest[2042:3567811] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:00.3,40 ThaliTest[2042:3567811] client session: disconnect
2016-03-23 11:51:00.341 ThaliTest[2042:3567811] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:00.342 ThaliTest[2042:3567811] client session: no connect callback (server initiated)
,2016-03-23 11:51:09.612 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-23 11:51:12.618 ThaliTest[2042:3566972] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:51:12.619 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:51:12.619 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:51:12.619 ThaliTest[2042:3566972] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:12.780 ThaliTest[2042:3567811] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:12.784 ThaliTest[2042:3567811] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:12.784 ThaliTest[2042:3567811] client session: disconnect
,2016-03-23 11:51:12.785 ThaliTest[2042:3567811] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:12.787 ThaliTest[2042:3567811] client session: no connect callback (server initiated)
,2016-03-23 11:51:15.467 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:51:15.500 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:15.503 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:51:22.620 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 163 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-23 11:51:22.846 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:51:22.849 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
ok 164 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:51:22.852 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:51:22.853 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:51:22.853 ThaliTest[2042:3566972] multipeer manager: stop client timer
20,16-03-23 11:51:22.854 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
ok 165 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can shift large amounts of data
,2016-03-23 11:51:25.456 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:51:25.457 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:51:25.458 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
2016-03-23 11:51:25.459 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:51:25.459 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening: success
ok 166 Can call startUpdateAdvertisingAndListening without error
2016-03-,23 11:51:25.462 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-23 11:51:25.463 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
ok 167 Can call startListeningForAdvertisements without error
,2016-03-23 11:51:25.473 ThaliTest[2042:3566770] client: found new peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:51:25.474 ThaliTest[2042:3566770] client: found new peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:25.475 ThaliTest[2042:3566972] jxcore: connect D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:51:25.476 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:51:25.476 ThaliTest[2042:3566972] client session: reverseConnect
2016-03-23 11:51:25.476 ThaliTest[2042:3566972] client session: stateChange:0->1 D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:51:28.359 ThaliTest[2042:3567895] client session: not connected D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:51:28.360 ThaliTest[2042:3567895] client session: onLinkFailure: D95DAC2A-FB09-4A72-B9F2-B5180B076E64
2016-03-23 11:51:28.3,61 ThaliTest[2042:3567895] client session: disconnect
,2016-03-23 11:51:28.361 ThaliTest[2042:3567895] client session: stateChange:1->0 D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:51:28.368 ThaliTest[2042:3567895] client session: no connect callback (server initiated)
,2016-03-23 11:51:28.431 ThaliTest[2042:3566770] multipeer session: reset timer
,2016-03-23 11:51:28.432 ThaliTest[2042:3566770] server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8)
,2016-03-23 11:51:32.392 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:51:32.393 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:51:32.393 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8)
,2016-03-23 11:51:35.477 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-23 11:51:36.818 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:51:36.819 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:51:36.819 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8)
,2016-03-23 11:51:38.499 ThaliTest[2042:3566972] jxcore: connect D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:51:38.500 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:51:38.501 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:51:38.501 ThaliTest[2042:3566972] client session: stateChange:0->1 D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:51:38.920 ThaliTest[2042:3567914] client session: not connected D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:51:38.922 ThaliTest[2042:3567914] client session: onLinkFailure: D95DAC2A-FB09-4A72-B9F2-B5180B076E64
2016-03-23 11:51:38.9,22 ThaliTest[2042:3567914] client session: disconnect
,2016-03-23 11:51:38.922 ThaliTest[2042:3567914] client session: stateChange:1->0 D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:51:38.928 ThaliTest[2042:3567914] client session: no connect callback (server initiated)
,2016-03-23 11:51:42.215 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:51:42.216 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:51:42.216 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8)
,2016-03-23 11:51:45.460 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:51:45.496 ThaliTest[2042:3566770] client: found updated peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
2016-03-23 11:51:45.498 ThaliTest[2042:3566770] client: found updated peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
,2016-03-23 11:51:48.502 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 11:51:48.996 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:51:48.998 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:51:48.998 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8)
,2016-03-23 11:51:51.514 ThaliTest[2042:3566972] jxcore: connect D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:51:51.515 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:51:51.516 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:51:51.516 ThaliTest[2042:3566972] client session: stateChange:0->1 D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
,2016-03-23 11:51:52.177 ThaliTest[2042:3567914] client session: not connected D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
2016-03-23 11:51:52.177 ThaliTest[2042:3567914] client session: onLinkFailure: D95DAC2A-FB09-4A72-B9F2-B5180B076E64
2016-03-23 11:51:52.178 ThaliTest[2042:3567914] client session: disconnect
,2016-03-23 11:51:52.178 ThaliTest[2042:3567914] client session: stateChange:1->0 D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
,2016-03-23 11:51:52.182 ThaliTest[2042:3567914] client session: no connect callback (server initiated)
,2016-03-23 11:51:53.682 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:51:53.683 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:51:53.683 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8)
,2016-03-23 11:51:57.752 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:51:57.753 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:51:57.753 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8)
,2016-03-23 11:52:01.408 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:52:01.408 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:52:01.408 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8)
,2016-03-23 11:52:01.517 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 7
,2016-03-23 11:52:04.529 ThaliTest[2042:3566972] jxcore: connect D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:04.529 ThaliTest[2042:3566972] client: server will connect
2016-03-23 11:52:04.530 ThaliTest[2042:3566972] client session: reverseConn,ect
2016-03-23 11:52:04.530 ThaliTest[2042:3566972] client session: stateChange:0->1 D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
,2016-03-23 11:52:05.083 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:52:05.084 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:52:05.084 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8)
,2016-03-23 11:52:05.460 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:52:05.498 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
2016-03-23 11:52:05.499 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
,2016-03-23 11:52:08.748 ThaliTest[2042:3566770] multipeer session: reset timer
2016-03-23 11:52:08.749 ThaliTest[2042:3566770] server: disconnecting to refresh session (71AA62C9-76E6-4355-A877-ED5FEA587FD9)
2016-03-23 11:52:08.750 ThaliTest[2042:3566770], server: rejecting invitation from 71AA62C9-76E6-4355-A877-ED5FEA587FD9 due to previous generation (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9 != 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8)
,2016-03-23 11:52:14.531 ThaliTest[2042:3566770] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-23 11:52:17.545 ThaliTest[2042:3566972] jxcore: connect D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:17.545 ThaliTest[2042:3566972] client: already connect(ing/ed) to D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:17.546 Thali,Test[2042:3566972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 11:52:20.566 ThaliTest[2042:3566972] jxcore: connect D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:20.567 ThaliTest[2042:3566972] client: already connect(ing/ed) to D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:20.567 Thali,Test[2042:3566972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 11:52:23.582 ThaliTest[2042:3566972] jxcore: connect D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:23.583 ThaliTest[2042:3566972] client: already connect(ing/ed) to D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:23.583 Thali,Test[2042:3566972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-23 11:52:25.460 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:52:25.485 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
2016-03-23 11:52:25.486 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:52:26.595 ThaliTest[2042:3566972] jxcore: connect D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:26.596 ThaliTest[2042:3566972] client: already connect(ing/ed) to D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:26.596 Thali,Test[2042:3566972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-23 11:52:29.607 ThaliTest[2042:3566972] jxcore: connect D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:29.608 ThaliTest[2042:3566972] client: already connect(ing/ed) to D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:29.608 Thali,Test[2042:3566972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-23 11:52:32.620 ThaliTest[2042:3566972] jxcore: connect D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:32.621 ThaliTest[2042:3566972] client: already connect(ing/ed) to D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:52:32.621 Thali,Test[2042:3566972] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 168 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-23 11:52:33.949 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:52:33.953 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 169 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:52:33.956 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:33.957 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:52:33.958 ThaliTest[2042:3566972] client session: disconnect
2016-03-23 1,1:52:33.958 ThaliTest[2042:3566972] client session: stateChange:1->0 D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
2016-03-23 11:52:33.960 ThaliTest[2042:3566972] multipeer manager: stop client timer
,2016-03-23 11:52:33.963 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
# setup
,2016-03-23 11:52:34.565 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:34.566 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:34.567 ThaliTest[2042:3,566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:34.571 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 40. #startListeningForAdvertisements should fail if start not called
,ok 171 specific error should be returned
,# teardown
,# setup
,2016-03-23 11:52:40.573 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:40.576 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:40.579 ThaliTest[2042:3566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:40.583 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-23 11:52:41.434 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:41.435 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:41.436 ThaliTest[2042:3,566972] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:41.439 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51187
,2016-03-23 11:52:41.602 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:41.605 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 173 no errors
,2016-03-23 11:52:41.608 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:41.610 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 174 still no errors
,# teardown
,2016-03-23 11:52:41.753 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:41.756 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
,2016-03-23 11:52:41.757 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:52:41.759 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:41.762 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:41.992 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:41.995 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:41.997 ThaliTest[2042:3566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:42.001 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51189
,2016-03-23 11:52:42.200 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
,2016-03-23 11:52:42.202 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:52:42.217 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
,ok 175 no errors
,2016-03-23 11:52:42.224 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:52:42.230 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
,ok 176 still no errors
,# teardown
,2016-03-23 11:52:42.373 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:42.373 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:52:42.374 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 11:52:42.375 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
2016-03-23 11:52:42.375 ThaliTest[2042:3566972] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:52:42.379 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:42.507 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:42.510 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:42.512 ThaliTest[2042:3566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:42.517 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51191
,2016-03-23 11:52:42.689 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:52:42.691 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:10
,2016-03-23 11:52:42.695 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
,2016-03-23 11:52:42.706 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:10
,2016-03-23 11:52:42.708 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening: success
,ok 177 no errors
,2016-03-23 11:52:42.716 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:52:42.719 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
,2016-03-23 11:52:42.728 ThaliTest[2042:3566972] multipeer manager: stop client timer
,2016-03-23 11:52:42.734 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:11
,2016-03-23 11:52:42.740 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
,2016-03-23 11:52:42.755 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:11
,2016-03-23 11:52:42.757 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening: success
,ok 178 still no errors
,# teardown
,2016-03-23 11:52:42.956 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:42.958 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
,2016-03-23 11:52:42.961 ThaliTest[2042:3566972] multipeer manager: stop client timer
,2016-03-23 11:52:42.963 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:52:42.970 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:42.973 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:43.116 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:43.119 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:43.121 ThaliTest[2042:3566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:43.125 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51195
,2016-03-23 11:52:45.957 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:45.957 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:52:45.958 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: suc,cess
ok 179 no errors
,2016-03-23 11:52:45.961 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:45.962 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:52:45.962 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: suc,cess
ok 180 still no errors
,# teardown
,2016-03-23 11:52:47.151 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:47.151 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:52:47.153 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:52:47.154 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:47.156 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:47.822 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:47.823 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:47.824 ThaliTest[2042:3,566972] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:47.828 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. can get the network status before starting
,ok 181 network status should have certain non-empty properties
,# teardown
,# setup
,2016-03-23 11:52:48.609 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:48.611 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:48.612 ThaliTest[2042:3566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:48.621 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 182 specific error expected
,# teardown
,# setup
,2016-03-23 11:52:48.984 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:48.986 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:48.988 ThaliTest[2042:3566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:48.993 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 48. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51197
,2016-03-23 11:52:49.257 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
,2016-03-23 11:52:49.258 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:52:49.262 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
2016-03-23 11:52:49.269 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:52:49.270 ThaliTest[2042:3566972] server: starting 5,3D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:12
2016-03-23 11:52:49.271 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:12
2016-03-23 11:52:49.272 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening,: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 183 connection to servers manager should succeed after starting
,ok 184 connection to router server should succeed after starting
,2016-03-23 11:52:49.339 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:49.339 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
2016-03-23 11:52:49.340 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 11:52:49.340 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,2016-03-23 11:52:49.344 ThaliTest[2042:3566972] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:52:49.348 ThaliTest[2042:3566972,] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 185 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 186 connection to servers manager should fail after stopping
,ok 187 connection to router server should fail after stopping
,# teardown
,# setup
,2016-03-23 11:52:49.698 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:49.699 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:49.700 ThaliTest[2042:3,566972] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:49.703 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 49. make sure terminateConnection is properly hooked up
,ok 188 called with right arguments
,# teardown
,# setup
,2016-03-23 11:52:50.304 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:50.307 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:50.309 ThaliTest[2042:3566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:50.313 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 50. make sure terminateListener is properly hooked up
,ok 189 called with right arguments
,# teardown
,# setup
,2016-03-23 11:52:56.670 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:56.671 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:56.672 ThaliTest[2042:3,566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:56.677 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure we actually call kill connections properly
,2016-03-23 11:52:56.805 ThaliTest[2042:3566972] jxcore: killConnections
2016-03-23 11:52:56.805 ThaliTest[2042:3566972] jxcore: killConnections: badParam
,not ok 190 should not fail on iOS
,  ---
,    operator: fail
,  ...
,# teardown
,# setup
,2016-03-23 11:52:57.246 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:57.247 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:57.248 ThaliTest[2042:3566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:57.253 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51204
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51203,"error":{}}
,2016-03-23 11:52:57.386 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:57.387 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
,2016-03-23 11:52:57.389 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:52:57.391 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:57.394 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,ok 191 failure reason is as expected
,ok 192 error description is as expected
,ok 193 must be stopped
,# teardown
,# setup
,2016-03-23 11:52:57.803 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:57.804 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:57.805 ThaliTest[2042:3,566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:57.810 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 53. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51206
,ok 194 peerIdentifier matches
,ok 195 error description matches
,# teardown
,2016-03-23 11:52:58.164 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:58.166 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
,2016-03-23 11:52:58.167 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:52:58.169 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:58.173 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:58.278 ThaliTest[2042:3566972] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:58.280 ThaliTest[2042:3566972] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:58.282 ThaliTest[2042:3566972] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:58.286 ThaliTest[2042:3566972] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51208
,2016-03-23 11:52:58.435 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements
,2016-03-23 11:52:58.439 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,ok 196 discoveryActive matches
,ok 197 advertisingActive matches
,2016-03-23 11:52:58.466 ThaliTest[2042:3566972] jxcore: startListeningForAdvertisements: success
,2016-03-23 11:52:58.468 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:58.470 ThaliTest[2042:3566972] THEMultipeerManager stopping peer
,2016-03-23 11:52:58.473 ThaliTest[2042:3566972] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:52:58.475 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements
,2016-03-23 11:52:58.478 ThaliTest[2042:3566972] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,ok 198 discoveryActive matches
,ok 199 advertisingActive matches
,2016-03-23 11:52:58.491 ThaliTest[2042:3566972] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51210
,2016-03-23 11:52:58.507 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:52:58.509 ThaliTest[2042:3566972] server: starting 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:52:58.513 ThaliTest[2042:3566972] multipeer manager: start client restart timer: 0x16e81900
2016-03-23 11:52:58.517 ThaliTest[2042:3566972] THEMultipeerManager initialized peer 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:52:58.521 ThaliTest[2042:3566972] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-23 11:53:00.366 ThaliTest[2042:3566770] client: found new peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
2016-03-23 11:53:00.368 ThaliTest[2042:3566770] client: found new peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:53:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:53:18.550 ThaliTest[2042:3566770] client: found updated peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:53:18.556 ThaliTest[2042:3566770] client: found updated peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:53:38.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:53:38.552 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:53:38.553 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:53:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:53:58.552 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:53:58.553 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:54:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:54:18.548 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:54:18.555 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:54:38.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:54:38.550 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:54:38.551 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:54:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:54:58.551 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:54:58.552 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:55:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:55:38.517 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:55:38.538 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:55:38.540 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:55:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:55:58.538 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:55:58.539 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:56:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:56:18.535 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:56:18.537 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:56:38.517 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:56:38.539 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:56:38.539 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:56:58.517 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:56:58.548 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:56:58.549 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:57:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:57:18.538 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:57:18.541 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:57:38.517 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:57:38.536 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:57:38.538 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:57:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:57:58.538 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:57:58.539 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:58:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:58:18.535 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:58:18.538 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:58:38.517 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:58:38.535 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:58:38.541 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:58:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:58:58.537 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:58:58.540 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:59:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:59:18.539 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:59:18.541 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:59:38.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:59:58.517 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 11:59:58.534 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:59:58.541 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:00:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:00:18.538 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:00:18.540 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:00:38.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:00:38.538 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:00:38.538 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:00:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:01:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:01:18.535 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:01:18.539 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:01:38.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:01:38.540 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:01:38.545 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:01:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:01:58.539 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:01:58.539 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:02:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:02:18.540 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:02:18.541 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:02:38.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:02:38.537 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:02:38.538 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:02:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:02:58.549 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:02:58.558 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:03:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:03:18.539 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:03:18.540 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:03:38.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:03:38.537 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:03:38.541 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:03:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:03:58.539 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:03:58.542 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:04:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:04:18.538 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:04:18.543 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:04:38.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:04:38.536 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:04:38.541 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:04:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:04:58.536 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:04:58.543 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:05:18.517 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:05:18.540 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:05:18.540 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:05:38.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:05:38.537 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:05:38.544 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:05:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:06:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:06:18.544 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:06:18.545 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:06:38.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:06:38.537 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:06:38.539 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:06:58.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:06:58.537 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:06:58.538 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:07:18.518 ThaliTest[2042:3566770] multipeer manager: restart client
,2016-03-23 12:07:18.536 ThaliTest[2042:3566770] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:07:18.537 ThaliTest[2042:3566770] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13

```
