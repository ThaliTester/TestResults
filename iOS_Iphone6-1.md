#### Test 639808773799dbd_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639808773799dbd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A0D9DFB0-77A0-4F6B-8178-932A3EF555DF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A0D9DFB0-77A0-4F6B-8178-932A3EF555DF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639808773799dbd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639808773799dbd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56022"
,(lldb)     command script import "/tmp/A0D9DFB0-77A0-4F6B-8178-932A3EF555DF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 22:48:01.254 ThaliTest[2163:3710216] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/63196634-740A-43EB-A0A4-BB62EA554FBE/Library/Cookies/Cookies.binarycookies
,2016-03-24 22:48:01.479 ThaliTest[2163:3710216] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 22:48:01.480 ThaliTest[2163:3710216] Multi-tasking -> Device: YES, App: YES
,2016-03-24 22:48:01.495 ThaliTest[2163:3710216] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 22:48:02.268 ThaliTest[2163:3710216] Using UIWebView
2016-03-24 22:48:02.270 ThaliTest[2163:3710216] [CDVTimer][handleopenurl] 0.124991ms
,2016-03-24 22:48:02.273 ThaliTest[2163:3710216] [CDVTimer][intentandnavigationfilter] 3.265023ms
2016-03-24 22:48:02.273 ThaliTest[2163:3710216] [CDVTimer][gesturehandler] 0.109017ms
2016-03-24 22:48:02.273 ThaliTest[2163:3710216] [CDVTimer][TotalPluginS,tartup] 3.969014ms
,2016-03-24 22:48:05.404 ThaliTest[2163:3710216] Resetting plugins due to page load.
,2016-03-24 22:48:06.651 ThaliTest[2163:3710216] Finished load of: file:///var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/index.html
,2016-03-24 22:48:06.821 ThaliTest[2163:3710216] JXcore Cordova plugin initializing
2016-03-24 22:48:06.823 ThaliTest[2163:3710388] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-24 22:48:13.853 ThaliTest[2163:3710388] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 22:48:13.854 ThaliTest[2163:3710388] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 22:48:13.855 ThaliTest[2163:3710388] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 22:48:13.856 ThaliTest[2163:3710388] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFD54CB0-193E-44D5-8417-8D619F9AC8E8/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52631
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52633
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52636
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
DEBUG createNativeListener: listening 52640
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
DEBUG createNativeListener: listening 52645
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
,DEBUG createNativeListener: listening 52649
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
DEBUG createNativeListener: listening 52653
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52657
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 52661
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
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeL,istener: new mux
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
,DEBUG createNativeListener: listening 52713
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
DEBUG createNativeListener: listening 52717
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
# teardown
,# setup
,# 19. mix enqueue and enqueueAtTop
,ok 65 fourth
ok 66 fourth
,ok 67 second
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
,# teardown
,# setup
,# 23. can pass data in setup
,ok 77 test participant has uuid
ok 78 participant data matches
,ok 79 test participant has uuid
,ok 80 participant data matches
,ok 81 test participant has uuid
,ok 82 participant data matches
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
# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52729
2016-03-24 22:50:52.265 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:52.266 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
ok 89 error should be null
ok 90 error should be null
2016-03-24 22:50:52.267 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:52.268 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
# teardown
,2016-03-24 22:50:52.383 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:52.384 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
2016-03-24 22:50:52.384 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:50:52.384 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:52.384 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52731
2016-03-24 22:50:52.609 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements
,2016-03-24 22:50:52.610 ThaliTest[2163:3710388] multipeer manager: start client restart timer: 0x14688250
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:50:52.611 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-24 22:50:52.616 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-24 22:50:52.617 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
# teardown
,2016-03-24 22:50:52.623 ThaliTest[2163:3710216] client: found new peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= 0
,2016-03-24 22:50:52.979 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:52.980 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
2016-03-24 22:50:52.980 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:50:52.980 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements
2016-03-24 22:50:52.980 ThaliTest[2163:3710388] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:52.981 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 99 error should be n,ull
ok 100 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52734
,2016-03-24 22:50:53.593 ThaliTest[2163:3710388] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:50:53.593 ThaliTest[2163:3710388] server: starting 05FC36F1-7B36-49B4-923C-C63498127D86:1
2016-03-24 22:50:53.594 ThaliTest[2163:3710388] multipeer manager: start client restart timer: 0x14688250
2016-03-24 22:50:53.594 ThaliTest[2163:3710388] THEMultipeerManager initialized peer 05FC36F1-7B36-49B4-923C-C63498127D86:1
2016-03-24 22:50:53.594 ThaliTest[2163:3710388] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
,ok 102 error should be null
,2016-03-24 22:50:53.606 ThaliTest[2163:3710216] client: found new peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,2016-03-24 22:50:53.610 ThaliTest[2163:3710388] jxcore: startUpdateAdvertisingAndListening
,2016-03-24 22:50:53.611 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
,2016-03-24 22:50:53.613 ThaliTest[2163:3710388] multipeer manager: stop client timer
,2016-03-24 22:50:53.616 ThaliTest[2163:3710388] server: starting 05FC36F1-7B36-49B4-923C-C63498127D86:2
,2016-03-24 22:50:53.618 ThaliTest[2163:3710388] multipeer manager: start client restart timer: 0x14688250
,2016-03-24 22:50:53.622 ThaliTest[2163:3710388] THEMultipeerManager initialized peer 05FC36F1-7B36-49B4-923C-C63498127D86:2
2016-03-24 22:50:53.623 ThaliTest[2163:3710388] jxcore: startUpdateAdvertisingAndListening: success
2016-03-24 22:50:53.624 ThaliTest[2163:3710216] client: found new peer: 58017D93-DB78-45D5-8EDE-0ADA8EDA76CC:7
,ok 103 error should be null
ok 104 error should be null
,# teardown
,2016-03-24 22:50:54.057 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:54.058 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
2016-03-24 22:50:54.058 ThaliTest[2163:3710388] multipeer manager: stop client timer
20,16-03-24 22:50:54.058 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:50:54.058 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 22:50:54.059 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 105 error should be null
,ok 106 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52739
2016-03-24 22:50:54.911 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:54.911 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
2016-03-24 22:50:54.911 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
2016-03-24 22:50:54.912 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24, 22:50:54.912 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
2016-03-24 22:50:54.912 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
# teardown
,2016-03-24 22:50:55.125 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:55.125 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
2016-03-24 22:50:55.126 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:50:55.126 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:55.126 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
ok 111 error should be null
ok 112 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52741
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
# teardown
,2016-03-24 22:50:55.959 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:55.959 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
2016-03-24 22:50:55.959 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
2016-03-24 22:50:55.959 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:50:55.960 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52743
2016-03-24 22:50:56.493 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements
2016-03-24 22:50:56.493 ThaliTest[2163:3710388] multipeer manager: start client restart timer: 0x14688250
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:50:56.494 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements: success
,2016-03-24 22:50:56.500 ThaliTest[2163:3710388] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:50:56.500 ThaliTest[2163:3710388] server: starting 05FC36F1-7B36-49B4-923C-C63498127D86:3
2016-03-24 22:50:56.500 ThaliTest[2163:3710388] THEMultipeerManager initialized peer 05FC36F1-7B36-49B4-923C-C63498127D86:3
2016-03-24 22:50:56.500 ThaliTest[2163:3710388] jxcore: startUpdateAdvertisingAndListening: success
ok 118 called only once
,ok 119 discovery state matches
,ok 120 advertising state matches
,# teardown
,2016-03-24 22:50:56.610 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24 22:50:56.610 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
,2016-03-24 22:50:56.611 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
,2016-03-24 22:50:56.612 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements
,2016-03-24 22:50:56.612 ThaliTest[2163:3710388] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 22:50:56.613 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 121 error should be null
,ok 122 error should be null
,# setup
,# 32. does not send duplicate availability changes
,ok 123 should be called once
,ok 124 should not have been called more than once
,# teardown
,ok 125 error should be null
ok 126 error should be null
# setup
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
,ok 133 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-24 22:51:32.209 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements
2016-03-24 22:51:32.209 ThaliTest[2163:3710388] multipeer manager: start client restart timer: 0x14688250
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:51:32.210 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-24 22:51:32.210 ThaliTes,t[2163:3710388] jxcore: stopListeningForAdvertisements
2016-03-24 22:51:32.210 ThaliTest[2163:3710388] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:51:32.211 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-24 22:51:32.448 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:51:32.448 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 22:51:32.449 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24 22:51:32.449 ThaliTest[2163:371038,8] THEMultipeerManager stopping peer
2016-03-24 22:51:32.449 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 22:51:32.975 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements
2016-03-24 22:51:32.975 ThaliTest[2163:3710388] multipeer manager: start client restart timer: 0x14688250
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:51:32.976 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-24 22:51:32.977 ThaliTes,t[2163:3710388] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 22:51:32.977 ThaliTest[2163:3710388] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 22:51:33.150 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements
2016-03-24 22:51:33.150 ThaliTest[2163:3710388] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 22:51:33.150 ThaliTest[2163:3710388] jxcore: stopListeningForAdvertisements: success
,ok 142 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 22:51:33.151 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24 22:51:33.151 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
2016-03-24 22:51:33.152 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 22:51:35.133 ThaliTest[2163:3710388] jxcore: startUpdateAdvertisingAndListening
2016-03-24 22:51:35.133 ThaliTest[2163:3710388] server: starting 05FC36F1-7B36-49B4-923C-C63498127D86:4
2016-03-24 22:51:35.134 ThaliTest[2163:3710388] multipeer m,anager: start client restart timer: 0x14688250
2016-03-24 22:51:35.134 ThaliTest[2163:3710388] THEMultipeerManager initialized peer 05FC36F1-7B36-49B4-923C-C63498127D86:4
2016-03-24 22:51:35.134 ThaliTest[2163:3710388] jxcore: startUpdateAdvertisingAndListening: success
ok 144 Can call startUpdateAdvertisingAndListening without error
2016-03-24 22:51:35.134 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening
2016-03-24 22:51:35.135 ThaliTest[2163:3710388] THEMultipeerManager stopping peer
,2016-03-24 22:51:35.135 ThaliTest[2163:3710388] multipeer manager: stop client timer
2016-03-24 22:51:35.139 ThaliTest[2163:3710388] jxcore: stopAdvertisingAndListening: success
ok 145 Can call stopAdvertisingAndListening without error
# teardown
,* thread #1: tid = 0x389d08, 0x338ffae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0xb)
  * frame #0: 0x338ffae6 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x24410dea MultipeerConnectivity`<redacted> + 270
    frame #2: 0x217b2c3c CFNetwork`<redacted> + 816
    frame #3: 0x217b232c CFNetwork`<redacted> + 36
    frame #4: 0x2170fdf0 CFNetwork`<redacted> + 668
    frame #5: 0x340dcbcc libsystem_dnssd.dylib`<redacted> + 128
    frame #6: 0x340db490 libsystem_dnssd.dylib`DNSServiceProcessResult + 528
    frame #7: 0x2170f798 CFNetwork`<redacted> + 20
    frame #8: 0x21e8b4f6 CoreFoundation`<redacted> + 818
    frame #9: 0x21e877c6 CoreFoundation`<redacted> + 14
    frame #10: 0x21e873b6 CoreFoundation`<redacted> + 454
    frame #11: 0x21e8571e CoreFoundation`<redacted> + 806
    frame #12: 0x21dd80d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #13: 0x21dd7ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #14: 0x2b10daf8 GraphicsServices`GSEventRunModal + 160
    frame #15: 0x260612dc UIKit`UIApplicationMain + 144
    frame #16: 0x00021572 ThaliTest`main + 50

```
