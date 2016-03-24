#### Test 639107046ed3de5_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D2E37B34-D4F5-4BC8-8B87-73CBDC430C0C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D2E37B34-D4F5-4BC8-8B87-73CBDC430C0C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55674"
,(lldb)     command script import "/tmp/D2E37B34-D4F5-4BC8-8B87-73CBDC430C0C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-24 16:43:23.703 ThaliTest[2105:3661425] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E71BED6C-ED8F-40C1-84BB-E30DCA6D5CA0/Library/Cookies/Cookies.binarycookies
,2016-03-24 16:43:23.935 ThaliTest[2105:3661425] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 16:43:23.936 ThaliTest[2105:3661425] Multi-tasking -> Device: YES, App: YES
,2016-03-24 16:43:23.952 ThaliTest[2105:3661425] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 16:43:24.734 ThaliTest[2105:3661425] Using UIWebView
2016-03-24 16:43:24.736 ThaliTest[2105:3661425] [CDVTimer][handleopenurl] 0.120997ms
,2016-03-24 16:43:24.739 ThaliTest[2105:3661425] [CDVTimer][intentandnavigationfilter] 3.183007ms
2016-03-24 16:43:24.739 ThaliTest[2105:3661425] [CDVTimer][gesturehandler] 0.117004ms
2016-03-24 16:43:24.739 ThaliTest[2105:3661425] [CDVTimer][TotalPluginS,tartup] 3.894031ms
,2016-03-24 16:43:27.856 ThaliTest[2105:3661425] Resetting plugins due to page load.
,2016-03-24 16:43:29.234 ThaliTest[2105:3661425] Finished load of: file:///var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/index.html
,2016-03-24 16:43:29.387 ThaliTest[2105:3661425] JXcore Cordova plugin initializing
2016-03-24 16:43:29.389 ThaliTest[2105:3661584] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 16:43:36.307 ThaliTest[2105:3661584] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 16:43:36.308 ThaliTest[2105:3661584] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:43:36.309 ThaliTest[2105:3661584] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 16:43:36.310 ThaliTest[2105:3661584] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49080AC5-7940-4C6C-B938-D2FC840CE1C2/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-24 16:43:41.885 ThaliTest[2105:3661425] THREAD WARNING: ['JXcore'] took '5271.331787' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51641
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51643
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
,DEBUG createNativeListener: listening 51646
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
,DEBUG createNativeListener: listening 51650
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
,# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51655
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
DEBUG createNativeListener: listening 51659
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
DEBUG createNativeListener: listening 51663
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
DEBUG createNativeListener: listening 51667
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
,DEBUG createNativeListener: listening 51671
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
DEBUG createNativeListener: new ,outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG ,createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DEBUG ,createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
,ok 30 incoming has been removed
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51723
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
,ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51727
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
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
,# 14. multiplex can send data
,ok 47 String should be length:200
,# teardown
,# setup
,# 15. enqueue and run in order
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue
# teardown
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
ok 69 firstPromise - in catch
,ok 70 third
ok 71 thirdPromise - in then
ok 72 testingPromises
# teardown
,# setup
,# 18. queues handled independently
,ok 73 all short operations completed before the long resolves
# teardown
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
DEBUG createNativeListener: listening 51739
2016-03-24 16:45:54.156 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:54.157 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
ok 88 error should be null
ok 89 error should be null
2016-03-24 16:45:54.158 ThaliTest[2105:3661584] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:54.159 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
# teardown
,2016-03-24 16:45:54.280 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:54.280 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:45:54.280 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:45:54.280 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:54.281 ThaliTest[2105,:3661584] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 51741
2016-03-24 16:45:54.625 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
,2016-03-24 16:45:54.626 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:45:54.627 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
2016-03-24 16:45:54.632 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-24 16:45:54.632 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# teardown
,2016-03-24 16:45:55.478 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:55.478 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:45:55.478 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:45:55.479 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
2016-03-24 16:45:55.479 ThaliTest[2105:3661584] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:55.479 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 98 error should be null
ok 99 error should be null
# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51743
,2016-03-24 16:45:58.543 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:45:58.543 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:1
2016-03-24 16:45:58.543 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
2016-03-24 16:45:58.543 ThaliTest[2105:3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:1
2016-03-24 16:45:58.544 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
,2016-03-24 16:45:58.551 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:45:58.551 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:45:58.551 ThaliTest[2105:3661584] multipeer manager: stop client timer
2016-03-24 16:45:58.551 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:2
2016-03-24 16:45:58.551 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
2016-03-24 16:45:58.552 ThaliTest[2105:,3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:2
2016-03-24 16:45:58.552 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
,# teardown
,2016-03-24 16:45:58.896 ThaliTest[2105:3661425] client: found new peer: 5F451984-F7B7-4F39-B182-72023C9FD000:2
,2016-03-24 16:45:59.071 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
,2016-03-24 16:45:59.072 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
,2016-03-24 16:45:59.073 ThaliTest[2105:3661584] multipeer manager: stop client timer
,2016-03-24 16:45:59.077 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
,2016-03-24 16:45:59.077 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 16:45:59.079 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51748
,2016-03-24 16:45:59.784 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:59.785 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:45:59.785 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
ok 106 error should be null
ok 107 error should be null
,2016-03-24 16:45:59.786 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:59.787 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:45:59.787 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: suc,cess
ok 108 error should be null
ok 109 error should be null
,# teardown
,2016-03-24 16:46:00.821 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:00.821 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:46:00.821 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:46:00.821 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:00.822 ThaliTest[2105,:3661584] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51750
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-24 16:46:01.771 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
,2016-03-24 16:46:01.772 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:46:01.772 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
,2016-03-24 16:46:01.772 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 16:46:01.773 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51752
,2016-03-24 16:46:02.243 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
2016-03-24 16:46:02.243 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 16:46:02.245 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
,2016-03-24 16:46:02.258 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:46:02.259 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:3
2016-03-24 16:46:02.259 ThaliTest[2105:3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:3
2016-03-24 16:46:02.259 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
ok 118 discovery state matches
ok 119 advertising state matches
,# teardown
,2016-03-24 16:46:03.221 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:03.222 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:46:03.222 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:46:03.222 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
2016-03-24 16:46:03.222 ThaliTest[2105:3661584] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:03.223 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 120 error should be null
ok 121 error should be null
,# setup
,# 30. does not send duplicate availability changes
,ok 122 should be called once
ok 123 should not have been called more than once
# teardown
,ok 124 error should be null
,ok 125 error should be null
# setup
,# 31. can get the network status
,ok 126 network status should have certain non-empty properties
# teardown
,ok 127 error should be null
ok 128 error should be null
# setup
,# 32. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 129 host address should match
ok 130 port should match
,ok 131 host address should be null
,ok 132 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 133 error should be null
,ok 134 error should be null
# setup
,# 33. Can call start/stopListeningForAdvertisements
,2016-03-24 16:46:33.361 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
2016-03-24 16:46:33.361 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:33.362 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
ok 135 Can call startListeningForAdvertisements without error
2016-03-24 16:46:33.362 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
2016-03-24 16:46:33.362 ThaliTest[2105:3661584] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:33.363 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
ok 136 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-24 16:46:33.607 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:33.607 ThaliTest[2105:36615,84] jxcore: stopListeningForAdvertisements: success
ok 137 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:46:33.608 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:33.608 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:46:33.608 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 16:46:34.131 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
2016-03-24 16:46:34.131 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:34.132 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-24 16:46:34.132 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:34.133 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 16:46:34.292 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
2016-03-24 16:46:34.292 ThaliTest[2105:3661584] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-24 16:46:34.293 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:46:34.293 ThaliTest[2105:36615,84] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:34.293 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:46:34.293 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 16:46:38.901 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:46:38.901 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:4
2016-03-24 16:46:38.901 ThaliTest[2105:3661584] multipeer m,anager: start client restart timer: 0x17d4dee0
2016-03-24 16:46:38.901 ThaliTest[2105:3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:4
2016-03-24 16:46:38.902 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-24 16:46:38.902 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:38.902 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
,2016-03-24 16:46:38.902 ThaliTest[2105:3661584] multipeer manager: stop client timer
2016-03-24 16:46:38.906 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-24 16:47:28.501 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:47:28.502 ThaliTest[2105:36615,84] jxcore: stopListeningForAdvertisements: success
ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:47:28.502 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:47:28.502 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:47:28.502 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-24 16:48:21.086 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:21.086 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:5
2016-03-24 16:48:21.086 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
2016-03-24 16:48:21.086 ThaliTest[2105:3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:5
2016-03-24 16:48:21.086 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-24 16:48:21.087 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:21.088 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
,2016-03-24 16:48:21.088 ThaliTest[2105:3661584] multipeer manager: stop client timer
2016-03-24 16:48:21.091 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:6
2016-03-24 16:48:21.091 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
2016-03-24 16:48:21.091 ThaliTest[2105:3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:6
2016-03-24 16:48:21.091 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 148 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-24 16:48:21.336 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:48:21.336 ThaliTest[2105:366158,4] jxcore: stopListeningForAdvertisements: success
ok 149 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:48:21.337 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:48:21.337 ThaliTest[2105:3661584,] THEMultipeerManager stopping peer
2016-03-24 16:48:21.337 ThaliTest[2105:3661584] multipeer manager: stop client timer
2016-03-24 16:48:21.337 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. peerAvailabilityChange is called
,2016-03-24 16:48:21.567 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:21.568 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:48:21.568 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
2016-03-24 16:48:21.568 ThaliTest[2105:3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
2016-03-24 16:48:21.568 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-24 16:48:21.569 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-24 16:48:21.569 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
ok 152 Can call startListeningForAdvertisements without error
,2016-03-24 16:48:23.814 ThaliTest[2105:3661425] client: found new peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:23.814 ThaliTest[2105:3661425] client: found new peer: 5F451984-F7B7-4F39-B182-72023C9FD000:7
ok 153 peers must be an array
o,k 154 peers must not be zero-length
ok 155 peer must have peerIdentifier
ok 156 peerIdentifier must be a string
ok 157 peer must have peerAvailable
ok 158 peer must have pleaseConnect
,# teardown
,2016-03-24 16:48:39.089 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:48:39.089 ThaliTest[2105:366158,4] jxcore: stopListeningForAdvertisements: success
ok 159 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:48:39.090 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:48:39.090 ThaliTest[2105:3661584,] THEMultipeerManager stopping peer
2016-03-24 16:48:39.090 ThaliTest[2105:3661584] multipeer manager: stop client timer
2016-03-24 16:48:39.090 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Can connect to a remote peer
,2016-03-24 16:48:39.298 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:39.298 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:48:39.298 ThaliTest[2105:3661584] multipeer m,anager: start client restart timer: 0x17d4dee0
2016-03-24 16:48:39.298 ThaliTest[2105:3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:48:39.298 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening: success
ok 161 Can call startUpdateAdvertisingAndListening without error
2016-03-24 16:48:39.299 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-24 16:48:39.300 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-24 16:48:40.209 ThaliTest[2105:3661425] client: found new peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:40.209 ThaliTest[2105:3661425] client: found new peer: 5F451984-F7B7-4F39-B182-72023C9FD000:7
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AE71735-F944-4906-BE1F-E88A7F36E6EE:7","pleaseConnect":0}]
2016-03-24 16:48:40.210 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:40.210 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:48:40.210 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5F451984-F7B7-4F39-B182-72023C9FD000:7","pleaseConnect":0}]
,2016-03-24 16:48:41.651 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:48:41.651 ThaliTest[2105:3661425] server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7)
,2016-03-24 16:48:41.734 ThaliTest[2105:3663189] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:41.735 ThaliTest[2105:3663189] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:41.7,35 ThaliTest[2105:3663189] client session: disconnect
2016-03-24 16:48:41.735 ThaliTest[2105:3663189] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:41.735 ThaliTest[2105:3663189] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:41.735 ThaliTest[2105:3663189] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-24 16:48:44.739 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:44.739 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:48:44.739 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,2016-03-24 16:48:45.072 ThaliTest[2105:3663190] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:45.072 ThaliTest[2105:3663190] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:45.0,72 ThaliTest[2105:3663190] client session: disconnect
2016-03-24 16:48:45.072 ThaliTest[2105:3663190] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:45.072 ThaliTest[2105:3663190] client session: fireConnectCallb,ack: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:45.072 ThaliTest[2105:3663190] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-24 16:48:48.083 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:48.084 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:48:48.084 ThaliTest[2105:3661584] client session: stateChange:0->,1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,2016-03-24 16:48:48.792 ThaliTest[2105:3663232] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:48.793 ThaliTest[2105:3663232] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:48.793 ThaliTest[2105:3663232] client session: disconnect
2016-03-24 16:48:48.793 ThaliTest[2105:3663232] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:48.794 ThaliTest[2105:3663232] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:48.794 ThaliTest[2105:3663232] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-24 16:48:51.806 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:51.807 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:48:51.807 ThaliTest[2105:3661584] client session: stateChange:0->,1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,2016-03-24 16:48:52.905 ThaliTest[2105:3663189] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:52.905 ThaliTest[2105:3663189] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:52.9,05 ThaliTest[2105:3663189] client session: disconnect
2016-03-24 16:48:52.905 ThaliTest[2105:3663189] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:52.905 ThaliTest[2105:3663189] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:52.905 ThaliTest[2105:3663189] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 6
,2016-03-24 16:48:53.632 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:48:53.632 ThaliTest[2105:3661425] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:48:53.632 ThaliTest[2105:3661425], server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7)
,2016-03-24 16:48:55.913 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:55.913 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:48:55.914 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,2016-03-24 16:48:59.299 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:48:59.308 ThaliTest[2105:3661425] client: found updated peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:48:59.309 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5F451984-F7B7-4F39-B182-72023C9FD000:8","pleaseConnect":0}]
,2016-03-24 16:49:06.761 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:49:06.761 ThaliTest[2105:3661425] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:49:06.761 ThaliTest[2105:3661425], server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7)
,2016-03-24 16:49:19.299 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:49:19.313 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:49:19.313 ThaliTest[2105:3661425] client: found updated peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AE71735-F944-4906-BE1F-E88A7F36E6EE:8","pleaseConnect":0}]
,2016-03-24 16:49:28.899 ThaliTest[2105:3663232] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:49:28.899 ThaliTest[2105:3663232] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:49:28.8,99 ThaliTest[2105:3663232] client session: disconnect
2016-03-24 16:49:28.899 ThaliTest[2105:3663232] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:28.901 ThaliTest[2105:3663232] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:49:28.901 ThaliTest[2105:3663232] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-24 16:49:31.903 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:49:31.903 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:49:31.903 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:39.299 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:49:39.313 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:49:39.313 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:59.299 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:49:59.310 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:49:59.310 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
,2016-03-24 16:50:04.909 ThaliTest[2105:3663382] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:50:04.909 ThaliTest[2105:3663382] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:50:04.909 ThaliTest[2105:3663382] client session: disconnect
2016-03-24 16:50:04.909 ThaliTest[2105:3663382] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:50:04.911 ThaliTest[2105:3663382] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:50:04.911 ThaliTest[2105:3663382] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-24 16:50:07.917 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:50:07.917 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:50:07.917 ThaliTest[2105:3661584] client session: stateChange:0->,1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:50:19.299 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:50:19.310 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:50:19.311 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:50:39.299 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:50:39.311 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:50:39.312 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
,2016-03-24 16:50:40.899 ThaliTest[2105:3663440] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:50:40.899 ThaliTest[2105:3663440] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:50:40.899 ThaliTest[2105:3663440] client session: disconnect
2016-03-24 16:50:40.899 ThaliTest[2105:3663440] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:50:40.901 ThaliTest[2105:3663440] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:50:40.901 ThaliTest[2105:3663440] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-24 16:50:43.914 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:50:43.914 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:50:43.915 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:50:59.299 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:50:59.311 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:50:59.315 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
,2016-03-24 16:51:16.899 ThaliTest[2105:3663585] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:51:16.899 ThaliTest[2105:3663585] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:51:16.8,99 ThaliTest[2105:3663585] client session: disconnect
2016-03-24 16:51:16.899 ThaliTest[2105:3663585] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:51:16.901 ThaliTest[2105:3663585] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:51:16.901 ThaliTest[2105:3663585] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-24 16:51:19.299 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:51:19.310 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:51:19.312 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
,2016-03-24 16:51:19.913 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:51:19.913 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:51:19.913 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:51:39.300 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:51:39.308 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:51:39.308 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
,2016-03-24 16:51:52.919 ThaliTest[2105:3663714] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:51:52.919 ThaliTest[2105:3663714] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:51:52.919 ThaliTest[2105:3663714] client session: disconnect
2016-03-24 16:51:52.919 ThaliTest[2105:3663714] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:51:52.921 ThaliTest[2105:3663714] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:51:52.921 ThaliTest[2105:3663714] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-24 16:51:55.923 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:51:55.923 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:51:55.924 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:51:59.299 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:51:59.308 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:51:59.309 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
,2016-03-24 16:52:19.299 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:52:19.307 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:19.307 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
,2016-03-24 16:52:28.919 ThaliTest[2105:3663816] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:28.919 ThaliTest[2105:3663816] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:28.9,19 ThaliTest[2105:3663816] client session: disconnect
2016-03-24 16:52:28.919 ThaliTest[2105:3663816] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:28.921 ThaliTest[2105:3663816] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:28.921 ThaliTest[2105:3663816] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
not ok 163 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-03-24 16:52:29.025 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:52:29.026 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
ok 164 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:52:29.027 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:52:29.027 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:52:29.027 ThaliTest[2105:3661584] multipeer manager: stop client timer
2016-03-24 16:52:29.027 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
ok 165 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 39. Can shift large amounts of data
,2016-03-24 16:52:30.267 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:52:30.267 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:52:30.268 ThaliTest[2105:3661584] multipeer m,anager: start client restart timer: 0x17d4dee0
2016-03-24 16:52:30.268 ThaliTest[2105:3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:52:30.268 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening: success
ok 166 Can call startUpdateAdvertisingAndListening without error
,2016-03-24 16:52:30.269 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-24 16:52:30.271 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
ok 167 Can call startListeningForAdvertisements without error
,2016-03-24 16:52:30.531 ThaliTest[2105:3661425] client: found new peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:30.532 ThaliTest[2105:3661425] client: found new peer: 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:52:30.532 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:30.533 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:52:30.533 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F,36E6EE:8
,2016-03-24 16:52:31.673 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:52:31.673 ThaliTest[2105:3661425] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8)
,2016-03-24 16:52:32.088 ThaliTest[2105:3663887] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:32.088 ThaliTest[2105:3663887] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
,2016-03-24 16:52:32.088 ThaliTest[2105:3663887] client session: disconnect
2016-03-24 16:52:32.088 ThaliTest[2105:3663887] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:32.089 ThaliTest[2105:3663887] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:32.089 ThaliTest[2105:3663887] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-24 16:52:35.101 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:35.102 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:52:35.102 ThaliTest[2105:3661584] client session: stateChange:0->,1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:35.889 ThaliTest[2105:3663816] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:35.889 ThaliTest[2105:3663816] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:35.8,89 ThaliTest[2105:3663816] client session: disconnect
2016-03-24 16:52:35.889 ThaliTest[2105:3663816] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:35.890 ThaliTest[2105:3663816] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:35.891 ThaliTest[2105:3663816] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-24 16:52:38.904 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:38.904 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:52:38.904 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:39.026 ThaliTest[2105:3663867] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:39.027 ThaliTest[2105:3663867] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:39.027 ThaliTest[2105:3663867] client session: disconnect
2016-03-24 16:52:39.027 ThaliTest[2105:3663867] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:39.027 ThaliTest[2105:3663867] client session: fireConnectCallb,ack: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:39.027 ThaliTest[2105:3663867] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-24 16:52:42.031 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:42.032 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:52:42.032 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:42.172 ThaliTest[2105:3663870] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:42.172 ThaliTest[2105:3663870] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:42.174 ThaliTest[2105:3663870] client session: disconnect
2016-03-24 16:52:42.174 ThaliTest[2105:3663870] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:42.174 ThaliTest[2105:3663870] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:42.174 ThaliTest[2105:3663870] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-24 16:52:44.790 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:52:44.791 ThaliTest[2105:3661425] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:52:44.791 ThaliTest[2105:3661425], server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8)
,2016-03-24 16:52:45.178 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:45.178 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:52:45.178 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:45.274 ThaliTest[2105:3663887] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:45.275 ThaliTest[2105:3663887] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
,2016-03-24 16:52:45.275 ThaliTest[2105:3663887] client session: disconnect
2016-03-24 16:52:45.276 ThaliTest[2105:3663887] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:45.276 ThaliTest[2105:3663887] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:45.276 ThaliTest[2105:3663887] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-24 16:52:48.283 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:48.283 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:52:48.284 ThaliTest[2105:3661584] client session: stateChange:0->,1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:48.465 ThaliTest[2105:3663908] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:48.465 ThaliTest[2105:3663908] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:48.465 ThaliTest[2105:3663908] client session: disconnect
,2016-03-24 16:52:48.466 ThaliTest[2105:3663908] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:48.467 ThaliTest[2105:3663908] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:48.467 ThaliTest[2105:3663908] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-24 16:52:50.269 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:52:50.277 ThaliTest[2105:3661425] client: found updated peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:52:50.278 ThaliTest[2105:3661425] client: found updated peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:52:51.475 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:51.476 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:52:51.476 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
,2016-03-24 16:52:51.610 ThaliTest[2105:3663908] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:52:51.610 ThaliTest[2105:3663908] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:51.6,11 ThaliTest[2105:3663908] client session: disconnect
2016-03-24 16:52:51.611 ThaliTest[2105:3663908] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:52:51.611 ThaliTest[2105:3663908] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:51.611 ThaliTest[2105:3663908] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-24 16:52:54.621 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:54.622 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:52:54.622 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
,2016-03-24 16:52:54.748 ThaliTest[2105:3663887] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:52:54.748 ThaliTest[2105:3663887] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:54.7,49 ThaliTest[2105:3663887] client session: disconnect
2016-03-24 16:52:54.749 ThaliTest[2105:3663887] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:52:54.749 ThaliTest[2105:3663887] client session: fireConnectCallb,ack: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:54.749 ThaliTest[2105:3663887] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-24 16:52:57.759 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:57.759 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:52:57.759 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
,2016-03-24 16:52:57.900 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:52:57.900 ThaliTest[2105:3661425] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:52:57.900 ThaliTest[2105:3661425] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8)
,2016-03-24 16:52:57.909 ThaliTest[2105:3663908] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:52:57.909 ThaliTest[2105:3663908] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:57.9,09 ThaliTest[2105:3663908] client session: disconnect
2016-03-24 16:52:57.909 ThaliTest[2105:3663908] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:52:57.910 ThaliTest[2105:3663908] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:52:57.910 ThaliTest[2105:3663908] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-24 16:53:00.913 ThaliTest[2105:3661584] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:53:00.913 ThaliTest[2105:3661584] client session: connect
2016-03-24 16:53:00.913 ThaliTest[2105:3661584] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
,2016-03-24 16:53:01.050 ThaliTest[2105:3663984] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
,2016-03-24 16:53:01.051 ThaliTest[2105:3663984] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:53:01.051 ThaliTest[2105:3663984] client session: disconnect
2016-03-24 16:53:01.051 ThaliTest[2105:3663984] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:53:01.052 ThaliTest[2105:3663984] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:53:01.052 ThaliTest[2105:3663984] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 168 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-24 16:53:10.269 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:53:10.278 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:53:10.278 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:53:11.130 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:53:11.130 ThaliTest[2105:3661425] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:53:11.130 ThaliTest[2105:3661425] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8)
,2016-03-24 16:53:23.639 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:53:23.640 ThaliTest[2105:3661425] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:53:23.640 ThaliTest[2105:3661425] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8)
,2016-03-24 16:53:30.269 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:53:30.277 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:53:30.277 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:53:36.687 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:53:36.688 ThaliTest[2105:3661425] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:53:36.688 ThaliTest[2105:3661425], server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8)
,2016-03-24 16:53:49.857 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:53:49.857 ThaliTest[2105:3661425] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:53:49.857 ThaliTest[2105:3661425], server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8)
,2016-03-24 16:53:50.269 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:53:50.277 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:53:50.277 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
,2016-03-24 16:54:03.350 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:54:03.350 ThaliTest[2105:3661425] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:54:03.350 ThaliTest[2105:3661425] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8)
,2016-03-24 16:54:10.269 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:54:10.278 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
2016-03-24 16:54:10.278 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:54:15.997 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:54:15.997 ThaliTest[2105:3661425] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:54:15.997 ThaliTest[2105:3661425] server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8)
,2016-03-24 16:54:28.783 ThaliTest[2105:3661425] multipeer session: reset timer
2016-03-24 16:54:28.784 ThaliTest[2105:3661425] server: disconnecting to refresh session (5F451984-F7B7-4F39-B182-72023C9FD000)
2016-03-24 16:54:28.784 ThaliTest[2105:3661425], server: rejecting invitation from 5F451984-F7B7-4F39-B182-72023C9FD000 due to previous generation (B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9 != B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8)
,2016-03-24 16:54:30.269 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:54:30.277 ThaliTest[2105:3661425] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
,2016-03-24 16:54:30.279 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:54:39.603 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:54:39.604 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
,ok 169 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 16:54:39.605 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
,2016-03-24 16:54:39.605 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
,2016-03-24 16:54:39.606 ThaliTest[2105:3661584] multipeer manager: stop client timer
2016-03-24 16:54:39.606 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
ok 170 Should be able to call stopAdvertisingAndListening in teardown
# setup
,2016-03-24 16:54:39.782 ThaliTest[2105:3661584] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:39.782 ThaliTest[2105:3661584] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:39.782 ThaliTest[2105:3661584] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:54:39.784 ThaliTest[2105:3661584] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 40. #startListeningForAdvertisements should fail if start not called
,ok 171 specific error should be returned
,# teardown
,# setup
,2016-03-24 16:54:41.057 ThaliTest[2105:3661584] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:41.057 ThaliTest[2105:3661584] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:41.058 ThaliTest[2105:3661584] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:54:41.059 ThaliTest[2105:3661584] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-24 16:54:41.818 ThaliTest[2105:3661584] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:41.819 ThaliTest[2105:3661584] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:41.819 ThaliTest[2105:3661584] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:54:41.820 ThaliTest[2105:3661584] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51796
,2016-03-24 16:54:43.050 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 16:54:43.051 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
ok 173 no errors
,2016-03-24 16:54:43.052 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 16:54:43.052 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
,ok 174 still no errors
,# teardown
,2016-03-24 16:54:43.626 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:54:43.626 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:54:43.626 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:54:43.626 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:54:43.627 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-24 16:54:46.231 ThaliTest[2105:3661584] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:46.231 ThaliTest[2105:3661584] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:46.231 ThaliTest[2105:3661584] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:54:46.233 ThaliTest[2105:3661584] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51798
,2016-03-24 16:54:46.551 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
2016-03-24 16:54:46.551 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:54:46.551 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
ok 175 no errors
,2016-03-24 16:54:46.552 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:54:46.553 ThaliTest[2105:3661584] jxcore: startListeningForAdvertisements: success
ok 176 still no errors
# teardown
,2016-03-24 16:54:47.136 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening
2016-03-24 16:54:47.136 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:54:47.136 ThaliTest[2105:3661584] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:54:47.136 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements
2016-03-24 16:54:47.137 ThaliTest[2105:3661584] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 16:54:47.137 ThaliTest[2105:3661584] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-24 16:54:47.600 ThaliTest[2105:3661584] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:47.601 ThaliTest[2105:3661584] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:47.601 ThaliTest[2105:3,661584] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:54:47.602 ThaliTest[2105:3661584] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51800
,2016-03-24 16:54:49.447 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:54:49.447 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:10
2016-03-24 16:54:49.448 ThaliTest[2105:3661584] multipeer ,manager: start client restart timer: 0x17d4dee0
2016-03-24 16:54:49.448 ThaliTest[2105:3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:10
2016-03-24 16:54:49.448 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 177 no errors
2016-03-24 16:54:49.449 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:54:49.449 ThaliTest[2105:3661584] THEMultipeerManager stopping peer
2016-03-24 16:54:49.449 ThaliTest[2105:3661584] multipeer manager: stop client timer
2016-03-24 16:54:49.449 ThaliTest[2105:3661584] server: starting B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 16:54:49.449 ThaliTest[2105:3661584] multipeer manager: start client restart timer: 0x17d4dee0
,2016-03-24 16:54:49.450 ThaliTest[2105:3661584] THEMultipeerManager initialized peer B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 16:54:49.450 ThaliTest[2105:3661584] jxcore: startUpdateAdvertisingAndListening: success
ok 178 still no errors
,# teardown
,2016-03-24 16:54:51.572 ThaliTest[2105:3661425] client: found new peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:54:52.569 ThaliTest[2105:3661425] client: found new peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:11
,2016-03-24 16:54:59.219 ThaliTest[2105:3661425] client: lost peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:54:59.219 ThaliTest[2105:3661425] client session: onPeerLost: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
,2016-03-24 16:55:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:55:09.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:55:29.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:55:29.465 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:9
,2016-03-24 16:55:49.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:55:49.467 ThaliTest[2105:3661425] client: found updated peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:56:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:56:09.459 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:56:29.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:56:29.459 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:56:49.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:56:49.498 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:57:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:57:09.462 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:57:29.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:57:29.456 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:57:49.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:57:49.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:58:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:58:09.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:58:29.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:58:29.458 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:58:49.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:58:49.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:59:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:59:09.458 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:59:29.450 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:59:29.456 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 16:59:49.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 16:59:49.458 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:00:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:00:09.458 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:00:29.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:00:29.458 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:00:49.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:00:49.458 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:01:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:01:09.456 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:01:29.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:01:29.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:01:49.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:01:49.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:02:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:02:09.456 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:02:29.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:02:29.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:02:49.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:02:49.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:03:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:03:09.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:03:29.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:03:29.456 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:03:49.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:03:50.011 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:04:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:04:29.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:04:29.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:04:49.450 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:04:49.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11
,2016-03-24 17:05:09.451 ThaliTest[2105:3661425] multipeer manager: restart client
,2016-03-24 17:05:09.457 ThaliTest[2105:3661425] client: found existing peer: 5F451984-F7B7-4F39-B182-72023C9FD000:11

```
