#### Test 64746945aaa3c62_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64746945aaa3c62/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/BDEEA903-F3C6-4ACE-A004-5DE468EBFBA7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BDEEA903-F3C6-4ACE-A004-5DE468EBFBA7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64746945aaa3c62/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64746945aaa3c62/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49631"
,(lldb)     command script import "/tmp/BDEEA903-F3C6-4ACE-A004-5DE468EBFBA7/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 10:10:13.478 ThaliTest[2499:4662620] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9BACAD01-FB85-4294-8942-14F1C6D37B2C/Library/Cookies/Cookies.binarycookies
,2016-03-31 10:10:13.712 ThaliTest[2499:4662620] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 10:10:13.713 ThaliTest[2499:4662620] Multi-tasking -> Device: YES, App: YES
,2016-03-31 10:10:13.728 ThaliTest[2499:4662620] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 10:10:14.520 ThaliTest[2499:4662620] Using UIWebView
,2016-03-31 10:10:14.522 ThaliTest[2499:4662620] [CDVTimer][handleopenurl] 0.266016ms
,2016-03-31 10:10:14.525 ThaliTest[2499:4662620] [CDVTimer][intentandnavigationfilter] 2.344012ms
2016-03-31 10:10:14.525 ThaliTest[2499:4662620] [CDVTimer][gesturehandler] 0.113964ms
2016-03-31 10:10:14.525 ThaliTest[2499:4662620] [CDVTimer][TotalPluginS,tartup] 3.259003ms
,2016-03-31 10:10:17.640 ThaliTest[2499:4662620] Resetting plugins due to page load.
,2016-03-31 10:10:19.039 ThaliTest[2499:4662620] Finished load of: file:///var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/index.html
,2016-03-31 10:10:19.196 ThaliTest[2499:4662620] JXcore Cordova plugin initializing
,2016-03-31 10:10:19.198 ThaliTest[2499:4662781] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 10:10:26.222 ThaliTest[2499:4662781] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 10:10:26.223 ThaliTest[2499:4662781] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 10:10:26.224 ThaliTest[2499:4662781] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 10:10:26.226 ThaliTest[2499:4662781] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3B68B76A-CDDC-42D3-BCEE-F67B2A4BE36F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55045
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55047
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
,DEBUG createNativeListener: listening 55050
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
DEBUG createNativeListener: listening 55054
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 55059
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
DEBUG createNativeListener: listening 55063
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
DEBUG createNativeListener: listening 55067
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
DEBUG createNativeListener: listening 55071
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
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
DEBUG createNativeListener: listening 55075
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
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBU,G createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
D,EBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55127
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 55131
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
,# teardown
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
DEBUG createNativeListener: listening 55143
,2016-03-31 10:13:05.371 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:05.372 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
2016-03-31 10:13:05.374 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:05.374 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
# teardown
,2016-03-31 10:13:05.596 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:05.597 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:13:05.597 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:05.597 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:05.598 ThaliTest[2499,:4662781] jxcore: stopListeningForAdvertisements: success
ok 94 error should be null
ok 95 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55145
2016-03-31 10:13:05.928 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements
,2016-03-31 10:13:05.930 ThaliTest[2499:4662781] multipeer manager: start client restart timer: 0x14da5540
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:05.931 Th,aliTest[2499:4662781] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
ok 97 error should be null
,2016-03-31 10:13:05.939 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 10:13:05.940 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements: success
,ok 98 error should be null
,ok 99 error should be null
,# teardown
,2016-03-31 10:13:06.786 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:06.786 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:13:06.786 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
2016-03-31 10:13:06.787 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
2016-03-31 10:13:06.787 ThaliTest[2499:4662781] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:06.787 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 100 error should be null
ok 101 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55147
2016-03-31 10:13:07.278 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:13:07.279 ThaliTest[2499:4662781] server: starting 2F92EB85-432C-485C-AE1C-D018859FD29C:1
2016-03-31 10:13:07.279 ThaliTest[2499:4662781] multipeer manager: start client restart timer: 0x14da5540
2016-03-31 10:13:07.279 ThaliTest[2499:4662781] THEMultipeerManager initialized peer 2F92EB85-432C-485C-AE1C-D0,18859FD29C:1
2016-03-31 10:13:07.279 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
2016-03-31 10:13:07.285 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:13:07.285 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:13:07.285, ThaliTest[2499:4662781] multipeer manager: stop client timer
2016-03-31 10:13:07.286 ThaliTest[2499:4662781] server: starting 2F92EB85-432C-485C-AE1C-D018859FD29C:2
2016-03-31 10:13:07.286 ThaliTest[2499:4662781] multipeer manager: start client restart timer: 0x14da5540
2016-03-31 10:13:07.286 ThaliTest[2499:4662781] THEMultipeerManager initialized peer 2F92EB85-432C-485C-AE1C-D018859FD29C:2
2016-03-31 10:13:07.286 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
ok 105 error should be null
# teardown
,2016-03-31 10:13:08.206 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:08.206 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:13:08.206 ThaliTest[2499:4662781] multipeer manager: stop client timer
2016-03-31 10:13:08.206 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
2016-03-31 10:13:08.206 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:08.207 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 106 error should be null
,ok 107 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55152
,2016-03-31 10:13:08.472 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:08.472 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:13:08.472 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: suc,cess
ok 108 error should be null
ok 109 error should be null
,2016-03-31 10:13:08.474 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:08.474 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:13:08.474 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
ok 110 error should be null
ok 111 error should be null
,# teardown
,2016-03-31 10:13:08.734 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:08.735 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:13:08.735 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
2016-03-31 10:13:08.735 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:08.735 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
,ok 112 error should be null
ok 113 error should be null
,# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55154
ok 114 first call should succeed
ok 115 first call should succeed
ok 116 specific error should be returned
# teardown
,2016-03-31 10:13:09.429 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:09.429 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:13:09.429 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:09.429 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:09.430 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
ok 117 error should be null
ok 118 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55156
2016-03-31 10:13:09.876 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements
2016-03-31 10:13:09.877 ThaliTest[2499:4662781] multipeer manager: start client restart timer: 0x14da5540
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:09.877 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements: success
,2016-03-31 10:13:09.885 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:13:09.885 ThaliTest[2499:4662781] server: starting 2F92EB85-432C-485C-AE1C-D018859FD29C:3
2016-03-31 10:13:09.886 ThaliTest[2499:4662781] THEMultipee,rManager initialized peer 2F92EB85-432C-485C-AE1C-D018859FD29C:3
2016-03-31 10:13:09.886 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening: success
ok 119 called only once
ok 120 discovery state matches
ok 121 advertising state matches
# teardown
,2016-03-31 10:13:10.061 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:10.061 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:13:10.062 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:10.062 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
2016-03-31 10:13:10.062 ThaliTest[2499:4662781] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:10.062 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
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
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 135 error should be null
ok 136 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-31 10:13:44.548 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements
2016-03-31 10:13:44.548 ThaliTest[2499:4662781] multipeer manager: start client restart timer: 0x14da5540
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:44.549 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
2016-03-31 10:13:44.549 ThaliTes,t[2499:4662781] jxcore: stopListeningForAdvertisements
2016-03-31 10:13:44.549 ThaliTest[2499:4662781] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-31 10:13:44.550 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
ok 138 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 10:13:44.795 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:44.796 ThaliTest[2499:46627,81] jxcore: stopListeningForAdvertisements: success
ok 139 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:13:44.797 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:44.797 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:13:44.797 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 10:14:18.963 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements
2016-03-31 10:14:18.963 ThaliTest[2499:4662781] multipeer manager: start client restart timer: 0x14da5540
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:14:18.964 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements without error
2016-03-31 10:14:18.965 ThaliTes,t[2499:4662781] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:14:18.965 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-31 10:14:19.928 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
2016-03-31 10:14:19.929 ThaliTest[2499:4662781] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:14:19.929 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
ok 143 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:14:19.930 ThaliTest[2499:46627,81] jxcore: stopAdvertisingAndListening
2016-03-31 10:14:19.930 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:14:19.930 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 10:14:27.943 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:14:27.943 ThaliTest[2499:4662781] server: starting 2F92EB85-432C-485C-AE1C-D018859FD29C:4
2016-03-31 10:14:27.943 ThaliTest[2499:4662781] multipeer m,anager: start client restart timer: 0x14da5540
2016-03-31 10:14:27.943 ThaliTest[2499:4662781] THEMultipeerManager initialized peer 2F92EB85-432C-485C-AE1C-D018859FD29C:4
2016-03-31 10:14:27.943 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening: success
ok 145 Can call startUpdateAdvertisingAndListening without error
2016-03-31 10:14:27.945 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:14:27.945 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
,2016-03-31 10:14:27.945 ThaliTest[2499:4662781] multipeer manager: stop client timer
2016-03-31 10:14:27.947 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
ok 146 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 10:14:52.240 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:14:52.241 ThaliTest[2499:46627,81] jxcore: stopListeningForAdvertisements: success
ok 147 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:14:52.242 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:14:52.242 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:14:52.242 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 10:16:15.383 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:15.384 ThaliTest[2499:4662781] server: starting 2F92EB85-432C-485C-AE1C-D018859FD29C:5
2016-03-31 10:16:15.384 ThaliTest[2499:4662781] multipeer m,anager: start client restart timer: 0x14da5540
2016-03-31 10:16:15.384 ThaliTest[2499:4662781] THEMultipeerManager initialized peer 2F92EB85-432C-485C-AE1C-D018859FD29C:5
2016-03-31 10:16:15.384 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening: success
ok 149 Can call startUpdateAdvertisingAndListening without error
2016-03-31 10:16:15.385 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:15.385 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
,2016-03-31 10:16:15.385 ThaliTest[2499:4662781] multipeer manager: stop client timer
2016-03-31 10:16:15.388 ThaliTest[2499:4662781] server: starting 2F92EB85-432C-485C-AE1C-D018859FD29C:6
2016-03-31 10:16:15.389 ThaliTest[2499:4662781] multipeer manager,: start client restart timer: 0x14da5540
2016-03-31 10:16:15.389 ThaliTest[2499:4662781] THEMultipeerManager initialized peer 2F92EB85-432C-485C-AE1C-D018859FD29C:6
2016-03-31 10:16:15.389 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 10:16:15.743 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 10:16:15.744 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
ok 151 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:16:15.744 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:16:15.744 ThaliTest[2499:4662781,] THEMultipeerManager stopping peer
2016-03-31 10:16:15.744 ThaliTest[2499:4662781] multipeer manager: stop client timer
2016-03-31 10:16:15.745 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-31 10:16:16.280 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:16.280 ThaliTest[2499:4662781] server: starting 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:16.281 ThaliTest[2499:4662781] multipeer manager: start client restart timer: 0x14da5540
2016-03-31 10:16:16.281 ThaliTest[2499:4662781] THEMultipeerManager initialized peer 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:16.283 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening: success
ok 153 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 10:16:16.284 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 10:16:16.284 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error
,2016-03-31 10:16:17.462 ThaliTest[2499:4662620] client: found new peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
ok 155 peers must be an array
ok 156 peers must not be zero-length
ok 157 peer must have peerIdentifier
ok 158 peerIdentifier must be a strin,g
ok 159 peer must have peerAvailable
ok 160 peer must have pleaseConnect
,# teardown
,2016-03-31 10:16:18.113 ThaliTest[2499:4662620] client: found new peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:7
,2016-03-31 10:16:18.283 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 10:16:18.284 ThaliTest[2499:466278,1] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:16:18.284 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:16:18.284 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:16:18.285 ThaliTest[2499:4662781] multipeer manager: stop client timer
2016-03-31 10:16:18.285 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. Can connect to a remote peer
,2016-03-31 10:16:18.711 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:18.711 ThaliTest[2499:4662781] server: starting 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:18.712 ThaliTest[2499:4662781] multipeer m,anager: start client restart timer: 0x14da5540
2016-03-31 10:16:18.712 ThaliTest[2499:4662781] THEMultipeerManager initialized peer 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:18.712 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening: success
ok 163 Can call startUpdateAdvertisingAndListening without error
2016-03-31 10:16:18.713 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 10:16:18.713 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-31 10:16:19.688 ThaliTest[2499:4662620] client: found new peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7","pleaseConnect":0}]
,2016-03-31 10:16:19.691 ThaliTest[2499:4662781] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:19.692 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:16:19.692 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:16:19.692 ThaliTest[2499:4662781] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
,2016-03-31 10:16:19.945 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:19.946 ThaliTest[2499:4662620] server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:20.764 ThaliTest[2499:4662620] client: found new peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"3F6A8788-1777-4148-9D5D-A7C8608DD,267:7","pleaseConnect":0}]
,2016-03-31 10:16:21.006 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:21.006 ThaliTest[2499:4662620] server: rejecting invitation from 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:21.269 ThaliTest[2499:4663549] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:21.269 ThaliTest[2499:4663549] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
2016-03-31 10:16:21.269 ThaliTest[2499:4663549] client session: disconnect
2016-03-31 10:16:21.269 ThaliTest[2499:4663549] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:21.269 ThaliTest[2499:4663549] client session: no connect callback (server initiated)
,2016-03-31 10:16:23.254 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:23.255 ThaliTest[2499:4662620] server: disconnecting to refresh session (3F6A8788-1777-4148-9D5D-A7C8608DD267)
2016-03-31 10:16:23.255 ThaliTest[2499:4662620] server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:24.287 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:24.287 ThaliTest[2499:4662620] server: disconnecting to refresh session (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C)
2016-03-31 10:16:24.287 ThaliTest[2499:4662620], server: rejecting invitation from 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:26.501 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:26.501 ThaliTest[2499:4662620] server: disconnecting to refresh session (3F6A8788-1777-4148-9D5D-A7C8608DD267)
2016-03-31 10:16:26.501 ThaliTest[2499:4662620] server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:27.457 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:27.457 ThaliTest[2499:4662620] server: disconnecting to refresh session (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C)
2016-03-31 10:16:27.457 ThaliTest[2499:4662620] server: rejecting invitation from 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:29.583 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:29.583 ThaliTest[2499:4662620] server: disconnecting to refresh session (3F6A8788-1777-4148-9D5D-A7C8608DD267)
2016-03-31 10:16:29.583 ThaliTest[2499:4662620] server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:29.693 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 10:16:30.615 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:30.615 ThaliTest[2499:4662620] server: disconnecting to refresh session (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C)
2016-03-31 10:16:30.615 ThaliTest[2499:4662620] server: rejecting invitation from 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:32.705 ThaliTest[2499:4662781] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:32.705 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:16:32.705 ThaliTest[2499:4662781] client session: reverseConn,ect
2016-03-31 10:16:32.705 ThaliTest[2499:4662781] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:32.713 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:32.714 ThaliTest[2499:4662620] se,rver: disconnecting to refresh session (3F6A8788-1777-4148-9D5D-A7C8608DD267)
2016-03-31 10:16:32.714 ThaliTest[2499:4662620] server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:32.779 ThaliTest[2499:4663549] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:32.779 ThaliTest[2499:4663549] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
2016-03-31 10:16:32.779 ThaliTest[2499:4663549] client session: disconnect
2016-03-31 10:16:32.779 ThaliTest[2499:4663549] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:32.779 ThaliTest[2499:4663549] client session: no connect callback (server initiated)
,2016-03-31 10:16:33.737 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:33.738 ThaliTest[2499:4662620] server: disconnecting to refresh session (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C)
2016-03-31 10:16:33.738 ThaliTest[2499:4662620], server: rejecting invitation from 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:35.815 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:35.815 ThaliTest[2499:4662620] server: disconnecting to refresh session (3F6A8788-1777-4148-9D5D-A7C8608DD267)
2016-03-31 10:16:35.815 ThaliTest[2499:4662620] server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:36.916 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:36.916 ThaliTest[2499:4662620] server: disconnecting to refresh session (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C)
2016-03-31 10:16:36.917 ThaliTest[2499:4662620], server: rejecting invitation from 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:38.713 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:16:38.724 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:7
2016-03-31 10:16:38.725 ThaliTest[2499:4662620] client: found updated peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8","pleaseConnect":0}]
,2016-03-31 10:16:38.958 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:38.958 ThaliTest[2499:4662620] server: disconnecting to refresh session (3F6A8788-1777-4148-9D5D-A7C8608DD267)
2016-03-31 10:16:38.958 ThaliTest[2499:4662620], server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:40.031 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:40.031 ThaliTest[2499:4662620] server: disconnecting to refresh session (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C)
2016-03-31 10:16:40.031 ThaliTest[2499:4662620] server: rejecting invitation from 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:42.107 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:42.107 ThaliTest[2499:4662620] server: disconnecting to refresh session (3F6A8788-1777-4148-9D5D-A7C8608DD267)
2016-03-31 10:16:42.108 ThaliTest[2499:4662620] server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:42.706 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 10:16:43.271 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:43.272 ThaliTest[2499:4662620] server: disconnecting to refresh session (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C)
2016-03-31 10:16:43.272 ThaliTest[2499:4662620], server: rejecting invitation from 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:45.251 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:45.251 ThaliTest[2499:4662620] server: disconnecting to refresh session (3F6A8788-1777-4148-9D5D-A7C8608DD267)
2016-03-31 10:16:45.251 ThaliTest[2499:4662620] server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:45.714 ThaliTest[2499:4662781] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:45.714 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:16:45.714 ThaliTest[2499:4662781] client session: reverseConn,ect
2016-03-31 10:16:45.714 ThaliTest[2499:4662781] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:16:45.838 ThaliTest[2499:4663674] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:16:45.840 ThaliTest[2499:4663674] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
2016-03-31 10:16:45.840 ThaliTest[2499:4663674] client session: disconnect
2016-03-31 10:16:45.840 ThaliTest[2499:4663674] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:16:45.840 ThaliTest[2499:4663674] client session: no connect callback (server initiated)
,2016-03-31 10:16:46.446 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:46.446 ThaliTest[2499:4662620] server: disconnecting to refresh session (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C)
2016-03-31 10:16:46.446 ThaliTest[2499:4662620] server: rejecting invitation from 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:48.461 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:48.461 ThaliTest[2499:4662620] server: disconnecting to refresh session (3F6A8788-1777-4148-9D5D-A7C8608DD267)
2016-03-31 10:16:48.461 ThaliTest[2499:4662620], server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:49.571 ThaliTest[2499:4662620] multipeer session: reset timer
2016-03-31 10:16:49.572 ThaliTest[2499:4662620] server: disconnecting to refresh session (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C)
2016-03-31 10:16:49.572 ThaliTest[2499:4662620] server: rejecting invitation from 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C due to previous generation (2F92EB85-432C-485C-AE1C-D018859FD29C:8 != 2F92EB85-432C-485C-AE1C-D018859FD29C:7)
,2016-03-31 10:16:55.715 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 10:16:58.713 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:16:58.724 ThaliTest[2499:4662620] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:16:58.724 ThaliTest[2499:4662620] client: found updated peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:16:58.725 ThaliTest[2499:4662781] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:58.725 ThaliTest[2499:4662781] client: server will connect
,2016-03-31 10:16:58.725 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:16:58.728 ThaliTest[2499:4662781] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"3F6A8788-1777-4148-9D5D-A7C8608DD267:8","pleaseConnect":0}]
,2016-03-31 10:16:59.002 ThaliTest[2499:4663674] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:16:59.003 ThaliTest[2499:4663674] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
2016-03-31 10:16:59.003 ThaliTest[2499:4663674] client session: disconnect
2016-03-31 10:16:59.003 ThaliTest[2499:4663674] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:16:59.003 ThaliTest[2499:4663674] client session: no connect callback (server initiated)
,2016-03-31 10:17:08.726 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 10:17:11.729 ThaliTest[2499:4662781] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:17:11.729 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:17:11.729 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:17:11.730 ThaliTest[2499:4662781] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:17:12.049 ThaliTest[2499:4663810] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:17:12.050 ThaliTest[2499:4663810] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
2016-03-31 10:17:12.050 ThaliTest[2499:4663810] client session: disconnect
,2016-03-31 10:17:12.051 ThaliTest[2499:4663810] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:17:12.052 ThaliTest[2499:4663810] client session: no connect callback (server initiated)
,2016-03-31 10:17:18.713 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:17:18.724 ThaliTest[2499:4662620] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:17:18.727 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:17:21.730 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 10:17:24.741 ThaliTest[2499:4662781] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:17:24.742 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:17:24.742 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:17:24.742 ThaliTest[2499:4662781] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:17:25.147 ThaliTest[2499:4663810] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:17:25.148 ThaliTest[2499:4663810] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
2016-03-31 10:17:25.148 ThaliTest[2499:4663810] client session: disconnect
2016-03-31 10:17:25.148 ThaliTest[2499:4663810] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:17:25.148 ThaliTest[2499:4663810] client session: no connect callback (server initiated)
,2016-03-31 10:17:34.743 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 10:17:37.749 ThaliTest[2499:4662781] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:17:37.749 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:17:37.749 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:17:37.749 ThaliTest[2499:4662781] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:17:37.808 ThaliTest[2499:4663868] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:17:37.808 ThaliTest[2499:4663868] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
2016-03-31 10:17:37.8,08 ThaliTest[2499:4663868] client session: disconnect
2016-03-31 10:17:37.809 ThaliTest[2499:4663868] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:17:37.809 ThaliTest[2499:4663868] client session: no connect callback (server initiated)
,2016-03-31 10:17:38.713 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:17:38.719 ThaliTest[2499:4662620] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:17:38.720 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:17:47.750 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 10:17:50.764 ThaliTest[2499:4662781] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:17:50.764 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:17:50.764 ThaliTest[2499:4662781] client session: reverseConn,ect
2016-03-31 10:17:50.765 ThaliTest[2499:4662781] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:17:51.854 ThaliTest[2499:4663902] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:17:51.855 ThaliTest[2499:4663902] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
2016-03-31 10:17:51.8,55 ThaliTest[2499:4663902] client session: disconnect
2016-03-31 10:17:51.855 ThaliTest[2499:4663902] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:17:51.855 ThaliTest[2499:4663902] client session: no connect callback (server initiated)
,2016-03-31 10:17:58.713 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:17:58.720 ThaliTest[2499:4662620] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:17:58.720 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:18:00.765 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 10:18:03.772 ThaliTest[2499:4662781] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:18:03.772 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:18:03.772 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:18:03.772 ThaliTest[2499:4662781] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:18:03.936 ThaliTest[2499:4663902] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:18:03.936 ThaliTest[2499:4663902] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
2016-03-31 10:18:03.936 ThaliTest[2499:4663902] client session: disconnect
2016-03-31 10:18:03.937 ThaliTest[2499:4663902] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:18:03.938 ThaliTest[2499:4663902] client session: no connect callback (server initiated)
,2016-03-31 10:18:13.773 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 10:18:16.781 ThaliTest[2499:4662781] jxcore: connect 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:18:16.782 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:18:16.782 ThaliTest[2499:4662781] client session: reverseConn,ect
2016-03-31 10:18:16.782 ThaliTest[2499:4662781] client session: stateChange:0->1 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
,2016-03-31 10:18:17.043 ThaliTest[2499:4663955] client session: not connected 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:18:17.044 ThaliTest[2499:4663955] client session: onLinkFailure: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C
2016-03-31 10:18:17.045 ThaliTest[2499:4663955] client session: disconnect
2016-03-31 10:18:17.045 ThaliTest[2499:4663955] client session: stateChange:1->0 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:18:17.045 ThaliTest[2499:4663955] client session: no connect callback (server initiated)
,2016-03-31 10:18:18.713 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:18:18.720 ThaliTest[2499:4662620] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:18:18.721 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:18:26.783 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
WARN testThaliMobileNative: Too many connect retries!
,not ok 165 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-31 10:18:26.911 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 10:18:26.912 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
,ok 166 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 10:18:26.913 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:18:26.913 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:18:26.913 ThaliTest[2499:4662781] multipeer manager: stop client timer
2016-03-31 10:18:26.913 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
ok 167 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. Can shift large amounts of data
,2016-03-31 10:18:31.747 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 10:18:31.748 ThaliTest[2499:4662781] server: starting 2F92EB85-432C-485C-AE1C-D018859FD29C:9
,2016-03-31 10:18:31.754 ThaliTest[2499:4662781] multipeer manager: start client restart timer: 0x14da5540
,2016-03-31 10:18:31.757 ThaliTest[2499:4662781] THEMultipeerManager initialized peer 2F92EB85-432C-485C-AE1C-D018859FD29C:9
,2016-03-31 10:18:31.758 ThaliTest[2499:4662781] jxcore: startUpdateAdvertisingAndListening: success
,ok 168 Can call startUpdateAdvertisingAndListening without error
,2016-03-31 10:18:31.759 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-31 10:18:31.760 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements: success
,ok 169 Can call startListeningForAdvertisements without error
,2016-03-31 10:18:33.707 ThaliTest[2499:4662620] client: found new peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:18:33.708 ThaliTest[2499:4662620] client: found new peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:18:33.708 ThaliTest[2499:4662781] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:18:33.709 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:18:33.709 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:18:33.709 ThaliTest[2499:4662781] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:18:35.214 ThaliTest[2499:4664044] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:18:35.215 ThaliTest[2499:4664044] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:18:35.216 ThaliTest[2499:4664044] client session: disconnect
2016-03-31 10:18:35.216 ThaliTest[2499:4664044] client session: stateChange:1->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:18:35.216 ThaliTest[2499:4664044] client session: no connect callback (server initiated)
,2016-03-31 10:18:43.710 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 10:18:46.724 ThaliTest[2499:4662781] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:18:46.724 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:18:46.724 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:18:46.724 ThaliTest[2499:4662781] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:18:46.853 ThaliTest[2499:4663955] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:18:46.853 ThaliTest[2499:4663955] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:18:46.853 ThaliTest[2499:4663955] client session: disconnect
2016-03-31 10:18:46.853 ThaliTest[2499:4663955] client session: stateChange:1->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:18:46.854 ThaliTest[2499:4663955] client session: no connect callback (server initiated)
,2016-03-31 10:18:51.758 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:18:51.769 ThaliTest[2499:4662620] client: found updated peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:18:51.773 ThaliTest[2499:4662620] client: found updated peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9
,2016-03-31 10:18:56.725 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 10:18:59.729 ThaliTest[2499:4662781] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:18:59.729 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:18:59.729 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:18:59.729 ThaliTest[2499:4662781] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:18:59.937 ThaliTest[2499:4664047] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:18:59.937 ThaliTest[2499:4664047] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:18:59.937 ThaliTest[2499:4664047] client session: disconnect
2016-03-31 10:18:59.937 ThaliTest[2499:4664047] client session: stateChange:1->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:18:59.938 ThaliTest[2499:4664047] client session: no connect callback (server initiated)
,2016-03-31 10:19:09.730 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 10:19:11.758 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:19:11.766 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:19:11.767 ThaliTest[2499:4662620] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9
,2016-03-31 10:19:12.737 ThaliTest[2499:4662781] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:19:12.737 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:19:12.737 ThaliTest[2499:4662781] client session: reverseConn,ect
2016-03-31 10:19:12.737 ThaliTest[2499:4662781] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:19:14.074 ThaliTest[2499:4664257] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:19:14.075 ThaliTest[2499:4664257] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:19:14.075 ThaliTest[2499:4664257] client session: disconnect
2016-03-31 10:19:14.075 ThaliTest[2499:4664257] client session: stateChange:1->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:19:14.075 ThaliTest[2499:4664257] client session: no connect callback (server initiated)
,2016-03-31 10:19:22.738 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 10:19:25.749 ThaliTest[2499:4662781] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:19:25.749 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:19:25.749 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:19:25.750 ThaliTest[2499:4662781] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:19:25.945 ThaliTest[2499:4664255] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:19:25.945 ThaliTest[2499:4664255] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:19:25.9,45 ThaliTest[2499:4664255] client session: disconnect
2016-03-31 10:19:25.946 ThaliTest[2499:4664255] client session: stateChange:1->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:19:25.946 ThaliTest[2499:4664255] client session: no connect callback (server initiated)
,2016-03-31 10:19:31.758 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:19:31.766 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:19:31.767 ThaliTest[2499:4662620] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9
,2016-03-31 10:19:35.750 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 10:19:38.756 ThaliTest[2499:4662781] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:19:38.757 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:19:38.757 ThaliTest[2499:4662781] client session: reverseConn,ect
2016-03-31 10:19:38.757 ThaliTest[2499:4662781] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:19:39.134 ThaliTest[2499:4664305] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:19:39.136 ThaliTest[2499:4664305] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:19:39.136 ThaliTest[2499:4664305] client session: disconnect
2016-03-31 10:19:39.136 ThaliTest[2499:4664305] client session: stateChange:1->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:19:39.136 ThaliTest[2499:4664305] client session: no connect callback (server initiated)
,2016-03-31 10:19:48.758 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 10:19:51.758 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:19:51.764 ThaliTest[2499:4662781] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:19:51.764 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:19:51.765 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:19:51.765 ThaliTest[2499:4662781] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:19:51.769 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:19:51.769 ThaliTest[2499:4662620] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9
,2016-03-31 10:19:52.013 ThaliTest[2499:4664308] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:19:52.015 ThaliTest[2499:4664308] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:19:52.015 ThaliTest[2499:4664308] client session: disconnect
2016-03-31 10:19:52.015 ThaliTest[2499:4664308] client session: stateChange:1->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:19:52.015 ThaliTest[2499:4664308] client session: no connect callback (server initiated)
,2016-03-31 10:20:01.769 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 10:20:04.781 ThaliTest[2499:4662781] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:20:04.782 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:20:04.782 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:20:04.782 ThaliTest[2499:4662781] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:20:05.017 ThaliTest[2499:4664339] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:20:05.017 ThaliTest[2499:4664339] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
,2016-03-31 10:20:05.017 ThaliTest[2499:4664339] client session: disconnect
2016-03-31 10:20:05.018 ThaliTest[2499:4664339] client session: stateChange:1->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:20:05.019 ThaliTest[2499:4664339] client session: no connect callback (server initiated)
,2016-03-31 10:20:11.758 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:20:11.767 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:20:11.767 ThaliTest[2499:4662620] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9
,2016-03-31 10:20:14.783 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 10:20:17.795 ThaliTest[2499:4662781] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:20:17.795 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:20:17.795 ThaliTest[2499:4662781] client session: reverseConnect
2016-03-31 10:20:17.795 ThaliTest[2499:4662781] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:20:18.060 ThaliTest[2499:4664308] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:20:18.060 ThaliTest[2499:4664308] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:20:18.0,60 ThaliTest[2499:4664308] client session: disconnect
2016-03-31 10:20:18.060 ThaliTest[2499:4664308] client session: stateChange:1->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:20:18.061 ThaliTest[2499:4664308] client session: no connect callback (server initiated)
,2016-03-31 10:20:27.796 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 10:20:30.809 ThaliTest[2499:4662781] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
2016-03-31 10:20:30.809 ThaliTest[2499:4662781] client: server will connect
2016-03-31 10:20:30.809 ThaliTest[2499:4662781] client session: reverseConn,ect
2016-03-31 10:20:30.809 ThaliTest[2499:4662781] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:20:31.085 ThaliTest[2499:4664413] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:20:31.085 ThaliTest[2499:4664413] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:20:31.085 ThaliTest[2499:4664413] client session: disconnect
2016-03-31 10:20:31.086 ThaliTest[2499:4664413] client session: stateChange:1->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:20:31.086 ThaliTest[2499:4664413] client session: no connect callback (server initiated)
,2016-03-31 10:20:31.758 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:20:31.767 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:20:31.767 ThaliTest[2499:4662620] client: found existing peer: 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9
,2016-03-31 10:20:40.810 ThaliTest[2499:4662620] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 170 Connect failed!
  ---
    operator: fail
,  ...
,# teardown
,2016-03-31 10:20:40.982 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 10:20:40.983 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 10:20:40.984 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:20:40.984 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:20:40.984 ThaliTest[2499:4662781] multipeer manager: stop client timer
2016-03-31 10:20:40.985 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-31 10:20:41.779 ThaliTest[2499:4662781] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:41.780 ThaliTest[2499:4662781] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:41.780 ThaliTest[2499:4662781] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 10:20:41.781 ThaliTest[2499:4662781] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 173 specific error should be returned
,# teardown
,ok 174 must be stopped
,# setup
,2016-03-31 10:20:44.728 ThaliTest[2499:4662781] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:44.728 ThaliTest[2499:4662781] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:44.728 ThaliTest[2499:4662781] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 10:20:44.730 ThaliTest[2499:4662781] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 175 specific error should be returned
,# teardown
,ok 176 must be stopped
,# setup
,2016-03-31 10:20:47.274 ThaliTest[2499:4662781] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:47.275 ThaliTest[2499:4662781] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:47.275 ThaliTest[2499:4662781] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 10:20:47.276 ThaliTest[2499:4662781] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55198
2016-03-31 10:20:47.733 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:20:47.734 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
ok 177 no errors
2016-03-31 10:20:47.734 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 10:20:47.735 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
,ok 178 still no errors
# teardown
,2016-03-31 10:20:48.059 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening
2016-03-31 10:20:48.059 ThaliTest[2499:4662781] THEMultipeerManager stopping peer
2016-03-31 10:20:48.059 ThaliTest[2499:4662781] jxcore: stopAdvertisingAndListening: success
2016-03-31 10:20:48.060 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:20:48.060 ThaliTest[2499:4662781] jxcore: stopListeningForAdvertisements: success
ok 179 must be stopped
# setup
,2016-03-31 10:20:48.816 ThaliTest[2499:4662781] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:48.816 ThaliTest[2499:4662781] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:48.816 ThaliTest[2499:4662781] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 10:20:48.817 ThaliTest[2499:4662781] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55200
,2016-03-31 10:20:49.543 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements
2016-03-31 10:20:49.544 ThaliTest[2499:4662781] multipeer manager: start client restart timer: 0x14da5540
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:20:49.544 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements: success
ok 180 no errors
,2016-03-31 10:20:49.545 ThaliTest[2499:4662781] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:20:49.546 ThaliTest[2499:46627,81] jxcore: startListeningForAdvertisements: success
ok 181 still no errors
# teardown
,2016-03-31 10:20:49.871 ThaliTest[2499:4662620] client: found new peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,2016-03-31 10:21:09.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:21:09.551 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:21:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:21:29.550 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:21:49.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:21:49.553 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:22:09.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:22:09.549 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:22:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:22:29.551 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:22:49.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:22:49.550 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:23:09.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:23:09.552 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:23:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:23:29.550 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:23:49.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:23:49.549 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:24:09.544 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:24:09.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:24:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:24:29.551 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:24:49.544 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:24:49.549 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:25:09.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:25:09.549 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:25:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:25:29.552 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:25:49.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:25:49.550 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:26:09.546 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:26:09.554 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:26:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:26:29.549 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:26:49.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:26:49.553 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:27:09.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:27:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:27:29.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:27:49.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:27:49.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:28:09.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:28:09.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:28:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:28:29.549 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:28:49.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:28:49.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:29:09.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:29:09.549 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:29:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:29:29.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:29:49.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:29:49.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:30:09.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:30:09.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:30:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:30:29.549 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:30:49.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:30:49.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:31:09.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:31:09.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:31:29.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:31:29.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:31:49.544 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:31:49.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:32:09.545 ThaliTest[2499:4662620] multipeer manager: restart client
,2016-03-31 10:32:09.548 ThaliTest[2499:4662620] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9

```
