#### Test 639107040172e2e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639107040172e2e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F50A287F-F92B-44CF-AA41-62E3C1371872/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F50A287F-F92B-44CF-AA41-62E3C1371872/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639107040172e2e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639107040172e2e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55964"
,(lldb)     command script import "/tmp/F50A287F-F92B-44CF-AA41-62E3C1371872/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 22:19:05.745 ThaliTest[2154:3705432] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1B02CE00-7CDB-4E3D-A069-4B577EC431F7/Library/Cookies/Cookies.binarycookies
,2016-03-24 22:19:05.973 ThaliTest[2154:3705432] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 22:19:05.974 ThaliTest[2154:3705432] Multi-tasking -> Device: YES, App: YES
,2016-03-24 22:19:05.988 ThaliTest[2154:3705432] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 22:19:06.765 ThaliTest[2154:3705432] Using UIWebView
2016-03-24 22:19:06.767 ThaliTest[2154:3705432] [CDVTimer][handleopenurl] 0.110030ms
2016-03-24 22:19:06.769 ThaliTest[2154:3705432] [CDVTimer][intentandnavigationfilter] 2.141953ms
2016-03-24 22:19:06.769 ThaliTest[2154:3705432] [CDVTimer][gesturehandler] 0.091970ms
2016-03-24 22:19:06.769 ThaliTest[2154:3705432] [CDVTimer][TotalPluginStartup] 2.770960ms
,2016-03-24 22:19:09.893 ThaliTest[2154:3705432] Resetting plugins due to page load.
,2016-03-24 22:19:11.289 ThaliTest[2154:3705432] Finished load of: file:///var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/index.html
,2016-03-24 22:19:11.448 ThaliTest[2154:3705432] JXcore Cordova plugin initializing
2016-03-24 22:19:11.449 ThaliTest[2154:3705595] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 22:19:18.341 ThaliTest[2154:3705595] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 22:19:18.341 ThaliTest[2154:3705595] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 22:19:18.341 ThaliTest[2154:3705595] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 22:19:18.343 ThaliTest[2154:3705595] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/065ACDCF-178F-49D6-A4E3-3F8221F0652B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52441
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52443
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52446
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 52450
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
,# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52455
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
DEBUG createNativeListener: listening 52459
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52463
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
DEBUG createNativeListener: listening 52467
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52471
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
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creati,ng incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNati,veListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNat,iveListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new outgoing socket
DEBUG cr,eateNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG cr,eateNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG crea,teNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG cr,eateNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG crea,teNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
D,EBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52523
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 52527
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,ok 53 secondPromise result
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
,ok 66 fourth
,ok 67 second
,ok 68 secondPromise - in then
,ok 69 first
,ok 70 firstPromise - in catch
,ok 71 third
,ok 72 thirdPromise - in then
,ok 73 testingPromises
,# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
# teardown
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
,# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 83 specific error should be returned
# teardown
,ok 84 error should be null
ok 85 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 86 specific error should be returned
,# teardown
,ok 87 error should be null
,ok 88 error should be null
,# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52539
,2016-03-24 22:22:08.775 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 22:22:08.776 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements: success
,ok 89 error should be null
,ok 90 error should be null
,2016-03-24 22:22:08.778 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 22:22:08.779 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,# teardown
,2016-03-24 22:22:08.905 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:22:08.905 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:22:08.905 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 22:22:08.906 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 22:22:08.906 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52541
2016-03-24 22:22:09.137 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements
,2016-03-24 22:22:09.139 ThaliTest[2154:3705595] multipeer manager: start client restart timer: 0x15dd8390
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:22:09.139 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-24 22:22:09.144 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:22:09.145 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
# teardown
,2016-03-24 22:22:09.491 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:22:09.491 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:22:09.491 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:22:09.491 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
2016-03-24 22:22:09.492 ThaliTest[2154:3705595] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 22:22:09.492 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 99 error should be null
ok 100 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52543
,2016-03-24 22:22:10.002 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:22:10.002 ThaliTest[2154:3705595] server: starting 27FBAC05-2FDA-4176-9320-3D1E49CE6608:1
2016-03-24 22:22:10.002 ThaliTest[2154:3705595] multipeer m,anager: start client restart timer: 0x15dd8390
2016-03-24 22:22:10.002 ThaliTest[2154:3705595] THEMultipeerManager initialized peer 27FBAC05-2FDA-4176-9320-3D1E49CE6608:1
2016-03-24 22:22:10.003 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
,ok 102 error should be null
,2016-03-24 22:22:10.010 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:22:10.010 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:22:10.010 ThaliTest[2154:3705595] multipeer manager: stop client timer
2016-03-24 22:22:10.010 ThaliTest[2154:3705595] server: starting 27FBAC05-2FDA-4176-9320-3D1E49CE6608:2
2016-03-24 22:22:10.010 ThaliTest[2154:3705595] multipeer manager: start client restart timer: 0x15dd8390
2016-03-24 22:22:10.010 ThaliTest[2154:,3705595] THEMultipeerManager initialized peer 27FBAC05-2FDA-4176-9320-3D1E49CE6608:2
2016-03-24 22:22:10.011 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,# teardown
,2016-03-24 22:22:11.608 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:22:11.609 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:22:11.609 ThaliTest[2154:3705595] multipeer manager: stop client timer
20,16-03-24 22:22:11.609 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:22:11.609 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:22:11.609 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 105 error should be null
ok 106 error should be null
# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52548
2016-03-24 22:22:31.535 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:22:31.535 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:22:31.535 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
,2016-03-24 22:22:31.537 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:22:31.538 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:22:31.538 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
# teardown
,2016-03-24 22:22:31.637 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:22:31.637 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:22:31.637 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:22:31.638 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:22:31.638 ThaliTest[2154,:3705595] jxcore: stopListeningForAdvertisements: success
,ok 111 error should be null
ok 112 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52550
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
,# teardown
,2016-03-24 22:22:35.185 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:22:35.185 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:22:35.185 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 22:22:35.186 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:22:35.186 ThaliTest[2154,:3705595] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52552
2016-03-24 22:22:37.952 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements
2016-03-24 22:22:37.953 ThaliTest[2154:3705595] multipeer manager: start client restart timer: 0x15dd8390
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:22:37.953 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements: success
,2016-03-24 22:22:37.960 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:22:37.960 ThaliTest[2154:3705595] server: starting 27FBAC05-2FDA-4176-9320-3D1E49CE6608:3
2016-03-24 22:22:37.961 ThaliTest[2154:3705595] THEMultipee,rManager initialized peer 27FBAC05-2FDA-4176-9320-3D1E49CE6608:3
2016-03-24 22:22:37.961 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening: success
ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
# teardown
,2016-03-24 22:22:38.147 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:22:38.148 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:22:38.148 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 22:22:38.148 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
2016-03-24 22:22:38.148 ThaliTest[2154:3705595] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 22:22:38.149 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 121 error should be null
ok 122 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 123 should be called once
ok 124 should not have been called more than once
# teardown
,ok 125 error should be null
ok 126 error should be null
# setup
,# 33. can get the network status
,ok 127 network status should have certain non-empty properties
# teardown
,ok 128 error should be null
ok 129 error should be null
,# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 130 host address should match
,ok 131 port should match
,ok 132 host address should be null
ok 133 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-24 22:23:51.948 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements
2016-03-24 22:23:51.948 ThaliTest[2154:3705595] multipeer manager: start client restart timer: 0x15dd8390
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:23:51.949 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-24 22:23:51.950 ThaliTes,t[2154:3705595] jxcore: stopListeningForAdvertisements
2016-03-24 22:23:51.950 ThaliTest[2154:3705595] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-24 22:23:51.950 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-24 22:23:52.190 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:23:52.191 ThaliTest[2154:37055,95] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 22:23:52.191 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:23:52.191 ThaliTest[2154:370559,5] THEMultipeerManager stopping peer
2016-03-24 22:23:52.192 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 22:23:52.850 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements
2016-03-24 22:23:52.850 ThaliTest[2154:3705595] multipeer manager: start client restart timer: 0x15dd8390
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:23:52.850 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-24 22:23:52.851 ThaliTes,t[2154:3705595] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:23:52.852 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 22:23:55.210 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
2016-03-24 22:23:55.211 ThaliTest[2154:3705595] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 22:23:55.211 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 22:23:55.212 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2,016-03-24 22:23:55.212 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:23:55.212 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 22:24:46.982 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:24:46.982 ThaliTest[2154:3705595] server: starting 27FBAC05-2FDA-4176-9320-3D1E49CE6608:4
2016-03-24 22:24:46.983 ThaliTest[2154:3705595] multipeer manager: start client restart timer: 0x15dd8390
2016-03-24 22:24:46.983 ThaliTest[2154:3705595] THEMultipeerManager initialized peer 27FBAC05-2FDA-4176-9320-3D1E49CE6608:4
,2016-03-24 22:24:46.986 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening: success
ok 144 Can call startUpdateAdvertisingAndListening without error
2016-03-24 22:24:46.986 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:24:46.987 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:24:46.987 ThaliTest[2154:3705595] multipeer manager: stop client timer
2016-03-24 22:24:46.987 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: succes,s
ok 145 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-24 22:24:47.225 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:24:47.225 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements: success
ok 146 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 22:24:47.226 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:24:47.226 ThaliTest[2154:370559,5] THEMultipeerManager stopping peer
2016-03-24 22:24:47.226 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: success
ok 147 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-24 22:24:47.767 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:24:47.768 ThaliTest[2154:3705595] server: starting 27FBAC05-2FDA-4176-9320-3D1E49CE6608:5
2016-03-24 22:24:47.768 ThaliTest[2154:3705595] multipeer manager: start client restart timer: 0x15dd8390
2016-03-24 22:24:47.768 ThaliTest[2154:3705595] THEMultipeerManager initialized peer 27FBAC05-2FDA-4176-9320-3D1E49CE6608:5
,2016-03-24 22:24:47.771 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening without error
2016-03-24 22:24:47.772 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListenin,g
2016-03-24 22:24:47.772 ThaliTest[2154:3705595] THEMultipeerManager stopping peer
2016-03-24 22:24:47.772 ThaliTest[2154:3705595] multipeer manager: stop client timer
2016-03-24 22:24:47.772 ThaliTest[2154:3705595] server: starting 27FBAC05-2FDA-4176-9320-3D1E49CE6608:6
2016-03-24 22:24:47.772 ThaliTest[2154:3705595] multipeer manager: start client restart timer: 0x15dd8390
2016-03-24 22:24:47.772 ThaliTest[2154:3705595] THEMultipeerManager initialized peer 27FBAC05-2FDA-4176-9320-3D1E49CE6608:6
,2016-03-24 22:24:47.772 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening: success
ok 149 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-24 22:24:47.897 ThaliTest[2154:3705595] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 22:24:47.898 ThaliTest[2154:370559,5] jxcore: stopListeningForAdvertisements: success
ok 150 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 22:24:47.898 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening
2016-03-24 22:24:47.898 ThaliTest[2154:3705595,] THEMultipeerManager stopping peer
2016-03-24 22:24:47.898 ThaliTest[2154:3705595] multipeer manager: stop client timer
2016-03-24 22:24:47.899 ThaliTest[2154:3705595] jxcore: stopAdvertisingAndListening: success
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. peerAvailabilityChange is called
,2016-03-24 22:25:05.295 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:25:05.295 ThaliTest[2154:3705595] server: starting 27FBAC05-2FDA-4176-9320-3D1E49CE6608:7
2016-03-24 22:25:05.295 ThaliTest[2154:3705595] multipeer m,anager: start client restart timer: 0x15dd8390
2016-03-24 22:25:05.296 ThaliTest[2154:3705595] THEMultipeerManager initialized peer 27FBAC05-2FDA-4176-9320-3D1E49CE6608:7
2016-03-24 22:25:05.296 ThaliTest[2154:3705595] jxcore: startUpdateAdvertisingAndListening: success
ok 152 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-24 22:25:05.296 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-24 22:25:05.297 ThaliTest[2154:3705595] jxcore: startListeningForAdvertisements: success
ok 153 Can call startListeningForAdvertisements without error
,2016-03-24 22:25:07.267 ThaliTest[2154:3705432] client: found new peer: 004CEAE4-FCC2-4544-89D9-F3CBE7F3259F:7
ok 154 peers must be an array
ok 155 peers must not be zero-length
ok 156 peer must have peerIdentifier
ok 157 peerIdentifier must be a string
ok 158 peer must have peerAvailable
ok 159 peer must have pleaseConnect
,# teardown
,2016-03-24 22:25:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:25:25.304 ThaliTest[2154:3705432] client: found existing peer: 004CEAE4-FCC2-4544-89D9-F3CBE7F3259F:7
,2016-03-24 22:25:26.900 ThaliTest[2154:3705432] client: found new peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:25:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:25:45.309 ThaliTest[2154:3705432] client: found existing peer: 004CEAE4-FCC2-4544-89D9-F3CBE7F3259F:7
2016-03-24 22:25:45.309 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:26:04.517 ThaliTest[2154:3705432] client: lost peer: 004CEAE4-FCC2-4544-89D9-F3CBE7F3259F
2016-03-24 22:26:04.517 ThaliTest[2154:3705432] client session: onPeerLost: 004CEAE4-FCC2-4544-89D9-F3CBE7F3259F
,2016-03-24 22:26:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:26:05.306 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:26:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:26:25.310 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,Disconnected from the test server
,2016-03-24 22:26:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:26:45.306 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:27:05.296 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:27:05.305 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:27:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:27:25.306 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:27:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:27:45.305 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:28:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:28:05.306 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,Reconnected to the test server
,2016-03-24 22:28:25.296 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:28:25.305 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:28:34.574 ThaliTest[2154:3705432] client: lost peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC
2016-03-24 22:28:34.574 ThaliTest[2154:3705432] client session: onPeerLost: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC
,2016-03-24 22:28:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:28:45.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:29:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:29:05.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:29:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:29:25.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:29:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:29:45.306 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:30:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:30:05.305 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:30:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:30:25.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:30:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:30:45.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:31:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:31:05.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:31:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:31:25.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:31:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:31:45.305 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:32:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:32:05.303 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:32:25.296 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:32:25.302 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:32:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:32:45.302 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:33:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:33:05.305 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:33:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:33:25.305 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:33:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:33:45.305 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:34:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:34:05.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:34:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:34:25.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:34:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:34:45.307 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:35:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:35:05.303 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:35:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:35:25.305 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:35:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:35:45.303 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:36:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:36:05.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:36:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:36:25.303 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:36:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:36:45.302 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:37:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:37:05.310 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:37:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:37:25.302 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:37:45.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:37:45.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:38:05.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:38:05.304 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:38:25.297 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:38:25.305 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:38:45.182 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:38:45.189 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:39:05.181 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:39:05.197 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:39:25.182 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:39:25.190 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:39:45.182 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:39:45.190 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:40:05.182 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:40:05.189 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:40:25.182 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:40:25.190 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:40:45.182 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:40:45.190 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:41:05.182 ThaliTest[2154:3705432] multipeer manager: restart client
,2016-03-24 22:41:05.190 ThaliTest[2154:3705432] client: found existing peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7

```
