#### Test 640346198400100_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/AD7927B8-A248-4DBA-838C-172CFD916744/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AD7927B8-A248-4DBA-838C-172CFD916744/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55554"
,(lldb)     command script import "/tmp/AD7927B8-A248-4DBA-838C-172CFD916744/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 15:01:44.462 ThaliTest[2121:3739664] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/491C086C-0251-451F-9CE5-3594F2F71ADA/Library/Cookies/Cookies.binarycookies
,2016-03-24 15:01:44.715 ThaliTest[2121:3739664] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 15:01:44.717 ThaliTest[2121:3739664] Multi-tasking -> Device: YES, App: YES
,2016-03-24 15:01:44.732 ThaliTest[2121:3739664] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 15:01:45.542 ThaliTest[2121:3739664] Using UIWebView
,2016-03-24 15:01:45.546 ThaliTest[2121:3739664] [CDVTimer][handleopenurl] 0.154972ms
,2016-03-24 15:01:45.550 ThaliTest[2121:3739664] [CDVTimer][intentandnavigationfilter] 3.144979ms
2016-03-24 15:01:45.550 ThaliTest[2121:3739664] [CDVTimer][gesturehandler] 0.174999ms
2016-03-24 15:01:45.550 ThaliTest[2121:3739664] [CDVTimer][TotalPluginStartup] 4.177034ms
,2016-03-24 15:01:48.779 ThaliTest[2121:3739664] Resetting plugins due to page load.
,2016-03-24 15:01:50.263 ThaliTest[2121:3739664] Finished load of: file:///var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/index.html
,2016-03-24 15:01:50.449 ThaliTest[2121:3739664] JXcore Cordova plugin initializing
,2016-03-24 15:01:50.452 ThaliTest[2121:3739945] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 15:01:58.916 ThaliTest[2121:3739945] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 15:01:58.917 ThaliTest[2121:3739945] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 15:01:58.917 ThaliTest[2121:3739945] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 15:01:58.921 ThaliTest[2121:3739945] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1DF71F18-089C-4707-804F-A812D887B473/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52093
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52095
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
DEBUG createNativeListener: listening 52098
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 52102
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52107
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
DEBUG createNativeListener: listening 52111
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
DEBUG createNativeListener: listening 52115
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
DEBUG createNativeListener: listening 52119
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 52123
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
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createN,ativeListener: new incoming socket
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
,DEBUG createNativeListener: new stream: 
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
DEBUG cr,eateNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DE,BUG createNativeListener: mux close
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG cr,eateNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativ,eListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNative,Listener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52175
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 52179
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
,# 14. multiplex can send data
,ok 47 String should be length:200
,# teardown
,# setup
,# 15. enqueue and run in order
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
,ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# teardown
,# setup
,# 16. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
ok 58 thirdPromise - in resolve
ok 59 secondPromise - second to run
ok 60 secondPromise - in catch
ok 61 firstPromise - third to run
ok 62 firstPromise - in then
ok 63 testing promises
# teardown
,# setup
,# 17. mix enqueue and enqueueAtTop
,ok 64 fourth
ok 65 fourth
ok 66 second
ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
ok 70 third
ok 71 thirdPromise - in then
ok 72 testingPromises
# teardown
,# setup
,# 18. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
,# setup
,# 19. basic
,ok 74 sane
# teardown
,# setup
,# 20. another
,ok 75 sane
# teardown
,# setup
,# 21. can pass data in setup
,ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
# teardown
,# setup
,# 22. #startListeningForAdvertisements should fail if start not called
,ok 82 specific error should be returned
# teardown
,ok 83 error should be null
ok 84 error should be null
# setup
,# 23. #startUpdateAdvertisingAndListening should fail if start not called
,ok 85 specific error should be returned
# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52191
2016-03-24 15:04:19.418 ThaliTest[2121:3739945] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.421 ThaliTest[2121:3739945] jxcore: stopListeningForAdvertisements: success
ok 88 error should be null
ok 89 e,rror should be null
2016-03-24 15:04:19.422 ThaliTest[2121:3739945] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.423, ThaliTest[2121:3739945] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
# teardown
,2016-03-24 15:04:19.516 ThaliTest[2121:3739945] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:19.516 ThaliTest[2121:3739945] THEMultipeerManager stopping peer
2016-03-24 15:04:19.517 ThaliTest[2121:3739945] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:04:19.517 ThaliTest[2121:3739945] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.518 ThaliTest[2121,:3739945] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
ok 93 error should be null
# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52193
2016-03-24 15:04:19.699 ThaliTest[2121:3739945] jxcore: startListeningForAdvertisements
2016-03-24 15:04:19.699 ThaliTest[2121:3739945] multipeer manager: start client restart timer: 0x145d2260
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:04:19.700 ThaliTest[2121:3739945] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
2016-03-24 15:04:19.751 ThaliTest[2121:3739945] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:04:19.751 ThaliTest[2121:3739945] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# teardown
,2016-03-24 15:04:19.831 ThaliTest[2121:3739945] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:19.831 ThaliTest[2121:3739945] THEMultipeerManager stopping peer
2016-03-24 15:04:19.831 ThaliTest[2121:3739945] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:04:19.831 ThaliTest[2121:3739945] jxcore: stopListeningForAdvertisements
2016-03-24 15:04:19.831 ThaliTest[2121:3739945] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.832 ThaliTest[2121:3739945] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 98 error should be null
ok 99 error should be null
# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52195
2016-03-24 15:04:20.203 ThaliTest[2121:3739945] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:04:20.203 ThaliTest[2121:3739945] server: starting 8661695A-63F5-42E8-B81B-2E389A3D12D6:1
,2016-03-24 15:04:20.205 ThaliTest[2121:3739945] multipeer manager: start client restart timer: 0x145d2260
2016-03-24 15:04:20.205 ThaliTest[2121:3739945] THEMultipeerManager initialized peer 8661695A-63F5-42E8-B81B-2E389A3D12D6:1
2016-03-24 15:04:20.205 ThaliTest[2121:3739945] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
2016-03-24 15:04:20.217 ThaliTest[2121:3739945] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:04:20.218 ThaliTest[2121:3739945] THEMultipeerManager stopping peer
2016-03-24 15:04:20.218, ThaliTest[2121:3739945] multipeer manager: stop client timer
2016-03-24 15:04:20.218 ThaliTest[2121:3739945] server: starting 8661695A-63F5-42E8-B81B-2E389A3D12D6:2
,2016-03-24 15:04:20.218 ThaliTest[2121:3739945] multipeer manager: start client restart timer: 0x145d2260
2016-03-24 15:04:20.224 ThaliTest[2121:3739945] THEMultipeerManager initialized peer 8661695A-63F5-42E8-B81B-2E389A3D12D6:2
2016-03-24 15:04:20.224 ThaliTest[2121:3739945] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
# teardown
,2016-03-24 15:04:20.614 ThaliTest[2121:3739945] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:20.614 ThaliTest[2121:3739945] THEMultipeerManager stopping peer
2016-03-24 15:04:20.614 ThaliTest[2121:3739945] multipeer manager: stop client timer
20,16-03-24 15:04:20.614 ThaliTest[2121:3739945] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:04:20.615 ThaliTest[2121:3739945] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:20.615 ThaliTest[2121:3739945] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 104 error should be null
ok 105 error should be null
# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52200
,2016-03-24 15:04:26.826 ThaliTest[2121:3739945] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:26.826 ThaliTest[2121:3739945] THEMultipeerManager stopping peer
2016-03-24 15:04:26.827 ThaliTest[2121:3739945] jxcore: stopAdvertisingAndListening: success
ok 106 error should be null
,ok 107 error should be null
,2016-03-24 15:04:26.829 ThaliTest[2121:3739945] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:26.829 ThaliTest[2121:3739945] THEMultipeerManager stopping peer
2016-03-24 15:04:26.829 ThaliTest[2121:3739945] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
,ok 109 error should be null
,# teardown
,Disconnected from the test server
,Reconnected to the test server

```
