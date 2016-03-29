#### Test 639808779d5bfaa_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639808779d5bfaa/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/771CF0F8-ED22-48D4-974D-9600DCC40BA6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/771CF0F8-ED22-48D4-974D-9600DCC40BA6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639808779d5bfaa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639808779d5bfaa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56334"
,(lldb)     command script import "/tmp/771CF0F8-ED22-48D4-974D-9600DCC40BA6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-29 11:04:46.243 ThaliTest[2411:4416573] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/55B5550D-3807-44EA-BCBB-5B09FDE7F8D4/Library/Cookies/Cookies.binarycookies
,2016-03-29 11:04:46.499 ThaliTest[2411:4416573] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-29 11:04:46.500 ThaliTest[2411:4416573] Multi-tasking -> Device: YES, App: YES
,2016-03-29 11:04:46.519 ThaliTest[2411:4416573] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 11:04:47.346 ThaliTest[2411:4416573] Using UIWebView
,2016-03-29 11:04:47.349 ThaliTest[2411:4416573] [CDVTimer][handleopenurl] 0.302970ms
,2016-03-29 11:04:47.352 ThaliTest[2411:4416573] [CDVTimer][intentandnavigationfilter] 2.932012ms
2016-03-29 11:04:47.353 ThaliTest[2411:4416573] [CDVTimer][gesturehandler] 0.145972ms
2016-03-29 11:04:47.353 ThaliTest[2411:4416573] [CDVTimer][TotalPluginStartup] 4.082024ms
,2016-03-29 11:04:50.593 ThaliTest[2411:4416573] Resetting plugins due to page load.
,2016-03-29 11:04:51.939 ThaliTest[2411:4416573] Finished load of: file:///var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/index.html
,2016-03-29 11:04:52.127 ThaliTest[2411:4416573] JXcore Cordova plugin initializing
,2016-03-29 11:04:52.129 ThaliTest[2411:4416739] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-29 11:05:00.538 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:05:00.539 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:05:00.539 ThaliTest[2411:4416739] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:05:00.541 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2FD7D8F9-FA2B-4F63-A744-BE451FA0740E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54753
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54755
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54758
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
DEBUG createNativeListener: listening 54762
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
DEBUG createNativeListener: listening 54767
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
DEBUG createNativeListener: listening 54771
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
DEBUG createNativeListener: listening 54775
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 54779
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
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
DEBUG createNativeListener: listening 54783
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
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
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54835
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
,ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54839
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
DEBUG createNativeListener: listening 54851
2016-03-29 11:07:29.416 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:29.417 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
ok 89 error should be null
ok 90 error should be null
2016-03-29 11:07:29.419 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:29.419 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
# teardown
,2016-03-29 11:07:29.646 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:07:29.647 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:07:29.647 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:07:29.647 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:29.648 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54853
2016-03-29 11:07:29.919 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
,2016-03-29 11:07:29.922 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:07:29.923 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-29 11:07:30.058 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-29 11:07:30.059 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
# teardown
,2016-03-29 11:07:30.801 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:07:30.802 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:07:30.802 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:07:30.802 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
2016-03-29 11:07:30.802 ThaliTest[2411:4416739] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:30.803 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 99 error should be null
ok 100 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54855
,2016-03-29 11:07:34.554 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:07:34.555 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:1
2016-03-29 11:07:34.555 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
2016-03-29 11:07:34.555 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:1
2016-03-29 11:07:34.555 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
2016-03-29 11:07:34.567 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:07:34.567 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:07:34.568 ThaliTest[2411:4416739] multipeer manager: stop client timer
2016-03-29 11:07:34.568 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
2016-03-29 11:07:34.568 ThaliTest[2411:4416739] multipeer manager: start client restart ,timer: 0x15dc2780
2016-03-29 11:07:34.568 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
2016-03-29 11:07:34.569 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-29 11:07:34.584 ThaliTest[2411:4416573] client: found new peer: F067257C-7084-41CC-A4B5-8A232A1C6437:2
,ok 103 error should be null
ok 104 error should be null
# teardown
,2016-03-29 11:07:39.775 ThaliTest[2411:4416573] client: found new peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
,2016-03-29 11:07:54.569 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:07:54.582 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
,2016-03-29 11:08:14.570 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:08:14.582 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
,2016-03-29 11:08:34.570 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:08:34.584 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
,2016-03-29 11:08:38.651 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:38.652 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:08:38.652 ThaliTest[2411:4416739] multipeer manager: stop client timer
20,16-03-29 11:08:38.652 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:08:38.652 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:08:38.657 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 105 error should be null
,ok 106 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54861
,2016-03-29 11:08:46.295 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.295 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:08:46.295 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
,ok 108 error should be null
,2016-03-29 11:08:46.298 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.298 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:08:46.298 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: suc,cess
ok 109 error should be null
ok 110 error should be null
,# teardown
,2016-03-29 11:08:46.564 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.565 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:08:46.565 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:08:46.565 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:08:46.566 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,ok 111 error should be null
,ok 112 error should be null
,# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54863
,ok 113 first call should succeed
ok 114 first call should succeed
,ok 115 specific error should be returned
,# teardown
,2016-03-29 11:08:46.974 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.974 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:08:46.974 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:08:46.975 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:08:46.975 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,ok 116 error should be null
,ok 117 error should be null
,# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54865
,2016-03-29 11:08:47.211 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
,2016-03-29 11:08:47.212 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-29 11:08:47.213 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
,2016-03-29 11:08:47.245 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:08:47.245 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:3
2016-03-29 11:08:47.246 ThaliTest[2411:4416739] THEMultipee,rManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:3
2016-03-29 11:08:47.246 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening: success
,ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
,# teardown
,2016-03-29 11:08:47.369 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:47.370 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:08:47.370 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:08:47.370 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
2016-03-29 11:08:47.370 ThaliTest[2411:4416739] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 11:08:47.371 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 121 error should be null
ok 122 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 123 should be called once
ok 124 should not have been called more than once
,# teardown
,ok 125 error should be null
ok 126 error should be null
# setup
,# 33. can get the network status
,ok 127 network status should have certain non-empty properties
# teardown
,ok 128 error should be null
,ok 129 error should be null
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
,2016-03-29 11:09:40.361 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
2016-03-29 11:09:40.361 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:09:40.362 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-29 11:09:40.363 ThaliTes,t[2411:4416739] jxcore: stopListeningForAdvertisements
2016-03-29 11:09:40.363 ThaliTest[2411:4416739] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-29 11:09:40.363 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 11:09:40.467 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:09:40.467 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:09:40.468 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:09:40.468 ThaliTest[2411:441673,9] THEMultipeerManager stopping peer
2016-03-29 11:09:40.468 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-29 11:10:01.424 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
2016-03-29 11:10:01.425 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:10:01.426 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
,2016-03-29 11:10:01.427 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:10:01.428 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-29 11:10:05.414 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
2016-03-29 11:10:05.414 ThaliTest[2411:4416739] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-29 11:10:05.415 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:10:05.416 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:05.416 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:10:05.416 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-29 11:10:26.802 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:26.803 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:4
2016-03-29 11:10:26.803 ThaliTest[2411:4416739] multipeer m,anager: start client restart timer: 0x15dc2780
2016-03-29 11:10:26.803 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:4
2016-03-29 11:10:26.803 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening: success
ok 144 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:10:26.804 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
,2016-03-29 11:10:26.805 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
,2016-03-29 11:10:26.805 ThaliTest[2411:4416739] multipeer manager: stop client timer
2016-03-29 11:10:26.806 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 145 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-29 11:10:41.943 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:10:41.944 ThaliTest[2411:44167,39] jxcore: stopListeningForAdvertisements: success
ok 146 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:10:41.945 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:41.945 ThaliTest[2411:441673,9] THEMultipeerManager stopping peer
2016-03-29 11:10:41.945 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 147 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-29 11:10:55.242 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:55.243 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:5
2016-03-29 11:10:55.243 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
2016-03-29 11:10:55.243 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:5
2016-03-29 11:10:55.243 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 148 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:10:55.244 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:55.244 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
,2016-03-29 11:10:55.244 ThaliTest[2411:4416739] multipeer manager: stop client timer
2016-03-29 11:10:55.249 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:6
2016-03-29 11:10:55.250 ThaliTest[2411:4416739] multipeer manager,: start client restart timer: 0x15dc2780
2016-03-29 11:10:55.250 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:6
2016-03-29 11:10:55.250 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening: success
ok 149 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-29 11:10:55.505 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 11:10:55.506 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
ok 150 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:10:55.507 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:55.507 ThaliTest[2411:4416739,] THEMultipeerManager stopping peer
2016-03-29 11:10:55.507 ThaliTest[2411:4416739] multipeer manager: stop client timer
2016-03-29 11:10:55.507 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 151 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-29 11:10:56.039 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:56.039 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:10:56.039 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
2016-03-29 11:10:56.039 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:10:56.040 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 152 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-29 11:10:56.041 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"disc,overyActive":true}
2016-03-29 11:10:56.042 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
ok 153 Can call startListeningForAdvertisements without error
,2016-03-29 11:10:56.835 ThaliTest[2411:4416573] client: found new peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
ok 154 peers must be an array
ok 155 peers must not be zero-length
ok 156 peer must have peerIdentifier
ok 157 peerIdentifier must be a strin,g
ok 158 peer must have peerAvailable
ok 159 peer must have pleaseConnect
,# teardown
,2016-03-29 11:10:56.977 ThaliTest[2411:4416573] client: found new peer: F067257C-7084-41CC-A4B5-8A232A1C6437:7
,2016-03-29 11:10:58.781 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-29 11:10:58.782 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-29 11:10:58.783 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:58.784 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:10:58.784 ThaliTest[2411:4416739] multipeer manager: stop client timer
2016-03-29 11:10:58.784 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. Can connect to a remote peer
,2016-03-29 11:11:33.222 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:11:33.222 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8
2016-03-29 11:11:33.223 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
2016-03-29 11:11:33.223 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8
2016-03-29 11:11:33.223 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 162 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:11:33.224 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-29 11:11:33.224 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
ok 163 Can call startListeningForAdvertisements without error
,2016-03-29 11:11:34.648 ThaliTest[2411:4416573] client: found new peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:11:34.648 ThaliTest[2411:4416573] client: found new peer: F067257C-7084-41CC-A4B5-8A232A1C6437:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"CF5927A1-42FA-4DDF-8112-8BFA72204E68:2","pleaseConnect":0}]
2016-03-29 11:11:34.650 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 1,1:11:34.650 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:11:34.650 ThaliTest[2411:4416739] client session: reverseConnect
2016-03-29 11:11:34.650 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F067257C-7084-41CC-A4B5-8A232A1C6437:7","pleaseConnect":0}]
,2016-03-29 11:11:35.573 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:7
,2016-03-29 11:11:36.395 ThaliTest[2411:4417709] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:11:36.396 ThaliTest[2411:4417709] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:11:36.3,96 ThaliTest[2411:4417709] client session: disconnect
2016-03-29 11:11:36.396 ThaliTest[2411:4417709] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:11:36.396 ThaliTest[2411:4417709] client session: no connect callback (server initiated)
,2016-03-29 11:11:37.107 ThaliTest[2411:4416573] multipeer session: reset timer
2016-03-29 11:11:37.107 ThaliTest[2411:4416573] server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (AAA6A3C2-4C66-4755-8AC6-E775E,23EAFBB:8 != AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7)
,2016-03-29 11:11:40.592 ThaliTest[2411:4416573] multipeer session: reset timer
2016-03-29 11:11:40.593 ThaliTest[2411:4416573] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:11:40.593 ThaliTest[2411:4416573], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8 != AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7)
,2016-03-29 11:11:44.652 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 11:11:44.992 ThaliTest[2411:4416573] multipeer session: reset timer
2016-03-29 11:11:44.992 ThaliTest[2411:4416573] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:11:44.992 ThaliTest[2411:4416573] server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8 != AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7)
,2016-03-29 11:11:47.659 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:11:47.659 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:11:47.659 ThaliTest[2411:4416739] client session: reverseConnect
2016-03-29 11:11:47.659 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
,2016-03-29 11:11:48.054 ThaliTest[2411:4417665] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:11:48.057 ThaliTest[2411:4417665] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:11:48.0,57 ThaliTest[2411:4417665] client session: disconnect
2016-03-29 11:11:48.057 ThaliTest[2411:4417665] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:11:48.057 ThaliTest[2411:4417665] client session: no connect callback (server initiated)
,2016-03-29 11:11:48.867 ThaliTest[2411:4416573] multipeer session: reset timer
2016-03-29 11:11:48.867 ThaliTest[2411:4416573] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:11:48.867 ThaliTest[2411:4416573], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8 != AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7)
,2016-03-29 11:11:52.392 ThaliTest[2411:4416573] multipeer session: reset timer
2016-03-29 11:11:52.392 ThaliTest[2411:4416573] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:11:52.392 ThaliTest[2411:4416573], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8 != AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7)
,2016-03-29 11:11:53.224 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:11:53.236 ThaliTest[2411:4416573] client: found updated peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:11:53.237 ThaliTest[2411:4416573] client: found updated peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"CF5927A1-42FA-4DDF-8112-8BFA72204E68:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier,":"F067257C-7084-41CC-A4B5-8A232A1C6437:8","pleaseConnect":0}]
,2016-03-29 11:11:55.908 ThaliTest[2411:4416573] multipeer session: reset timer
2016-03-29 11:11:55.908 ThaliTest[2411:4416573] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:11:55.908 ThaliTest[2411:4416573], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8 != AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7)
,2016-03-29 11:11:57.660 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 11:11:59.490 ThaliTest[2411:4416573] multipeer session: reset timer
2016-03-29 11:11:59.490 ThaliTest[2411:4416573] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:11:59.490 ThaliTest[2411:4416573] server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8 != AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7)
,2016-03-29 11:12:00.664 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:12:00.664 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:12:00.664 ThaliTest[2411:4416739] client session: reverseConn,ect
2016-03-29 11:12:00.664 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:12:01.021 ThaliTest[2411:4417709] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:01.022 ThaliTest[2411:4417709] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:12:01.022 ThaliTest[2411:4417709] client session: disconnect
2016-03-29 11:12:01.022 ThaliTest[2411:4417709] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:01.023 ThaliTest[2411:4417709] client session: no connect callback (server initiated)
,2016-03-29 11:12:03.132 ThaliTest[2411:4416573] multipeer session: reset timer
2016-03-29 11:12:03.132 ThaliTest[2411:4416573] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:12:03.132 ThaliTest[2411:4416573], server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8 != AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7)
,2016-03-29 11:12:06.796 ThaliTest[2411:4416573] multipeer session: reset timer
2016-03-29 11:12:06.796 ThaliTest[2411:4416573] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:12:06.796 ThaliTest[2411:4416573] server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8 != AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7)
,2016-03-29 11:12:10.123 ThaliTest[2411:4416573] multipeer session: reset timer
2016-03-29 11:12:10.123 ThaliTest[2411:4416573] server: disconnecting to refresh session (F067257C-7084-41CC-A4B5-8A232A1C6437)
2016-03-29 11:12:10.124 ThaliTest[2411:4416573] server: rejecting invitation from F067257C-7084-41CC-A4B5-8A232A1C6437 due to previous generation (AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:8 != AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7)
,2016-03-29 11:12:10.665 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 11:12:13.223 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:12:13.236 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:13.237 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:12:13.669 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:12:13.669 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:12:13.669 ThaliTest[2411:4416739] client session: reverseConnect
2016-03-29 11:12:13.670 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:12:13.800 ThaliTest[2411:4417709] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:13.800 ThaliTest[2411:4417709] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:12:13.8,00 ThaliTest[2411:4417709] client session: disconnect
2016-03-29 11:12:13.800 ThaliTest[2411:4417709] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:12:13.802 ThaliTest[2411:4417709] client session: no connect callback (server initiated)
,2016-03-29 11:12:23.670 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 11:12:26.681 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:12:26.682 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:12:26.682 ThaliTest[2411:4416739] client session: reverseConnect
2016-03-29 11:12:26.682 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:12:26.900 ThaliTest[2411:4417710] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:26.900 ThaliTest[2411:4417710] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:12:26.9,00 ThaliTest[2411:4417710] client session: disconnect
2016-03-29 11:12:26.901 ThaliTest[2411:4417710] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:26.901 ThaliTest[2411:4417710] client session: no connect callback (server initiated)
,2016-03-29 11:12:33.224 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:12:33.237 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:33.237 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:12:36.683 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 11:12:39.686 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:12:39.686 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:12:39.686 ThaliTest[2411:4416739] client session: reverseConnect
2016-03-29 11:12:39.686 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:12:40.014 ThaliTest[2411:4417969] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:40.015 ThaliTest[2411:4417969] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:12:40.015 ThaliTest[2411:4417969] client session: disconnect
2016-03-29 11:12:40.016 ThaliTest[2411:4417969] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:40.016 ThaliTest[2411:4417969] client session: no connect callb,ack (server initiated)
,2016-03-29 11:12:49.687 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 11:12:52.699 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:12:52.699 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:12:52.699 ThaliTest[2411:4416739] client session: reverseConnect
2016-03-29 11:12:52.699 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:12:53.059 ThaliTest[2411:4417973] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:53.060 ThaliTest[2411:4417973] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:12:53.0,60 ThaliTest[2411:4417973] client session: disconnect
2016-03-29 11:12:53.060 ThaliTest[2411:4417973] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:53.060 ThaliTest[2411:4417973] client session: no connect callback (server initiated)
,2016-03-29 11:12:53.223 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:12:53.237 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:12:53.238 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:13:02.700 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 11:13:05.712 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:13:05.713 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:13:05.713 ThaliTest[2411:4416739] client session: reverseConn,ect
2016-03-29 11:13:05.713 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:06.161 ThaliTest[2411:4417973] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:06.161 ThaliTest[2411:4417973] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:06.1,61 ThaliTest[2411:4417973] client session: disconnect
2016-03-29 11:13:06.161 ThaliTest[2411:4417973] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:06.162 ThaliTest[2411:4417973] client session: no connect callback (server initiated)
,2016-03-29 11:13:13.224 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:13:13.236 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:13.237 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:13:15.714 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 2
,2016-03-29 11:13:18.716 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:13:18.717 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:13:18.717 ThaliTest[2411:4416739] client session: reverseConnect
2016-03-29 11:13:18.717 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:18.898 ThaliTest[2411:4417973] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:18.899 ThaliTest[2411:4417973] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:18.899 ThaliTest[2411:4417973] client session: disconnect
2016-03-29 11:13:18.900 ThaliTest[2411:4417973] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:18.900 ThaliTest[2411:4417973] client session: no connect callback (server initiated)
,2016-03-29 11:13:28.718 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 11:13:31.723 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
2016-03-29 11:13:31.723 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:13:31.723 ThaliTest[2411:4416739] client session: reverseConnect
2016-03-29 11:13:31.724 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:32.432 ThaliTest[2411:4417999] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:32.433 ThaliTest[2411:4417999] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:32.433 ThaliTest[2411:4417999] client session: disconnect
,2016-03-29 11:13:32.433 ThaliTest[2411:4417999] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:32.435 ThaliTest[2411:4417999] client session: no connect callback (server initiated)
,2016-03-29 11:13:33.224 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:13:33.240 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:33.245 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:13:41.725 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
WARN testThaliMobileNative: Too many connect retries!
not ok 164 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-03-29 11:13:42.058 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 11:13:42.059 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,ok 165 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-29 11:13:42.060 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:13:42.061 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:13:42.061 ThaliTest[2411:4416739] multipeer manager: stop client timer
2016-03-29 11:13:42.061 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 166 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. Can shift large amounts of data
,2016-03-29 11:13:43.072 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
,2016-03-29 11:13:43.072 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
2016-03-29 11:13:43.073 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
,2016-03-29 11:13:43.073 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:13:43.073 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening: success
,ok 167 Can call startUpdateAdvertisingAndListening without error
,2016-03-29 11:13:43.075 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 11:13:43.076 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
ok 168 Can call startListeningForAdvertisements without error
,2016-03-29 11:13:43.871 ThaliTest[2411:4416573] client: found new peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:43.873 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:43.873 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:13:43.873 ThaliTest[2411:4416739] client session: reverseConnect
2016-03-29 11:13:43.873 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:4,3.875 ThaliTest[2411:4416573] client: found new peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:13:45.929 ThaliTest[2411:4417999] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:45.930 ThaliTest[2411:4417999] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:45.9,30 ThaliTest[2411:4417999] client session: disconnect
2016-03-29 11:13:45.930 ThaliTest[2411:4417999] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:45.931 ThaliTest[2411:4417999] client session: no connect callback (server initiated)
,2016-03-29 11:13:53.880 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 11:13:56.891 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:56.892 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:13:56.892 ThaliTest[2411:4416739] client session: reverseConnect
2016-03-29 11:13:56.892 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:56.994 ThaliTest[2411:4417973] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:56.996 ThaliTest[2411:4417973] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:56.996 ThaliTest[2411:4417973] client session: disconnect
2016-03-29 11:13:56.996 ThaliTest[2411:4417973] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:56.996 ThaliTest[2411:4417973] client session: no connect callback (server initiated)
,2016-03-29 11:14:03.074 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:14:03.087 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:14:03.087 ThaliTest[2411:4416573] client: found updated peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:06.893 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 11:14:09.901 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:09.902 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:14:09.902 ThaliTest[2411:4416739] client session: reverseConn,ect
2016-03-29 11:14:09.902 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:10.228 ThaliTest[2411:4418183] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:10.228 ThaliTest[2411:4418183] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:10.2,28 ThaliTest[2411:4418183] client session: disconnect
2016-03-29 11:14:10.228 ThaliTest[2411:4418183] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:10.230 ThaliTest[2411:4418183] client session: no connect callback (server initiated)
,2016-03-29 11:14:19.903 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 11:14:22.916 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:22.917 ThaliTest[2411:4416739] client: server will connect
2016-03-29 11:14:22.917 ThaliTest[2411:4416739] client session: reverseConn,ect
2016-03-29 11:14:22.917 ThaliTest[2411:4416739] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:23.074 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:14:23.091 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:14:23.091 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:32.918 ThaliTest[2411:4416573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 11:14:35.928 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:35.928 ThaliTest[2411:4416739] client: already connect(ing/ed) to CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:35.928 Thali,Test[2411:4416739] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 11:14:38.931 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:38.932 ThaliTest[2411:4416739] client: already connect(ing/ed) to CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:38.932 Thali,Test[2411:4416739] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 11:14:41.941 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:41.941 ThaliTest[2411:4416739] client: already connect(ing/ed) to CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:41.941 ThaliTest[2411:4416739] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 11:14:43.074 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:14:43.086 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:43.086 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:14:44.945 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:44.945 ThaliTest[2411:4416739] client: already connect(ing/ed) to CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:44.946 Thali,Test[2411:4416739] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 11:14:47.955 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:47.956 ThaliTest[2411:4416739] client: already connect(ing/ed) to CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:47.956 ThaliTest[2411:4416739] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 11:14:50.960 ThaliTest[2411:4416739] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:50.960 ThaliTest[2411:4416739] client: already connect(ing/ed) to CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:50.960 Thali,Test[2411:4416739] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 169 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-29 11:14:55.886 ThaliTest[2411:4417973] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:55.886 ThaliTest[2411:4417973] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:55.887 ThaliTest[2411:4417973] client session: disconnect
2016-03-29 11:14:55.887 ThaliTest[2411:4417973] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:55.887 ThaliTest[2411:4417973] client session: no connect callback (server initiated)
,2016-03-29 11:15:03.074 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:15:03.090 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:15:03.091 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:15:23.074 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:15:23.768 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:15:23.769 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:8
,2016-03-29 11:15:23.802 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 11:15:23.803 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,ok 170 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-29 11:15:23.804 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:23.804 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:15:23.804 ThaliTest[2411:4416739] multipeer manager: stop client timer
2016-03-29 11:15:23.805 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 171 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-29 11:15:23.978 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:23.979 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:23.979 ThaliTest[2411:4416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:23.981 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-29 11:15:24.423 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:24.424 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:24.424 ThaliTest[2411:4,416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:24.426 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 173 specific error should be returned
,# teardown
,# setup
,2016-03-29 11:15:25.476 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:25.476 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:25.477 ThaliTest[2411:4,416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:25.478 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54899
,2016-03-29 11:15:25.899 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:15:25.899 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,ok 174 no errors
,2016-03-29 11:15:25.901 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:15:25.902 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,ok 175 still no errors
,# teardown
,2016-03-29 11:15:26.103 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:26.104 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:15:26.104 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:15:26.104 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:15:26.105 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:15:26.264 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:26.264 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:26.264 ThaliTest[2411:4416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:26.266 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54901
,2016-03-29 11:15:26.501 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
2016-03-29 11:15:26.501 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:15:26.502 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
ok 176 no errors
,2016-03-29 11:15:26.503 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:15:26.507 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
ok 177 still no errors
,# teardown
,2016-03-29 11:15:26.747 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:26.747 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:15:26.747 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:15:26.747 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
2016-03-29 11:15:26.747 ThaliTest[2411:4416739] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:15:26.748 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:15:26.909 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-29 11:15:26.910 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-29 11:15:26.910 ThaliTest[2411:4416739] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:26.912 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54903
,2016-03-29 11:15:27.113 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:15:27.113 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:10
2016-03-29 11:15:27.114 ThaliTest[2411:4416739] multipeer ,manager: start client restart timer: 0x15dc2780
2016-03-29 11:15:27.114 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:10
2016-03-29 11:15:27.114 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 178 no errors
2016-03-29 11:15:27.115 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:15:27.115 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:15:27.115 ThaliTest[2411:4416,739] multipeer manager: stop client timer
2016-03-29 11:15:27.115 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:11
,2016-03-29 11:15:27.116 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
,2016-03-29 11:15:27.122 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:11
2016-03-29 11:15:27.128 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening: success
,ok 179 still no errors
,# teardown
,2016-03-29 11:15:27.234 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
,2016-03-29 11:15:27.235 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
,2016-03-29 11:15:27.236 ThaliTest[2411:4416739] multipeer manager: stop client timer
,2016-03-29 11:15:27.238 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
,2016-03-29 11:15:27.239 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:15:27.241 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:15:27.391 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-29 11:15:27.392 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-29 11:15:27.393 ThaliTest[2411:4416739] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:27.394 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54907
,2016-03-29 11:15:28.041 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:28.041 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:15:28.041 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 180 no errors
,2016-03-29 11:15:28.042 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:28.042 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:15:28.042 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
ok 181 still no errors
,# teardown
,2016-03-29 11:15:28.363 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:28.363 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:15:28.363 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:15:28.364 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:15:28.364 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:15:35.488 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:35.489 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:35.489 ThaliTest[2411:4,416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:35.490 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 48. can get the network status before starting
,ok 182 network status should have certain non-empty properties
,# teardown
,# setup
,2016-03-29 11:16:14.909 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:14.909 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:14.909 ThaliTest[2411:4,416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:16:14.911 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 49. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 183 specific error expected
,# teardown
,# setup
,2016-03-29 11:16:15.781 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:15.781 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:15.781 ThaliTest[2411:4416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:16:15.782 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 50. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54909
,2016-03-29 11:16:16.489 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
2016-03-29 11:16:16.489 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-29 11:16:16.490 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
,2016-03-29 11:16:16.492 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
,2016-03-29 11:16:16.494 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:12
2016-03-29 11:16:16.496 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:12
2016-03-29 11:16:16.496 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 184 connection to servers manager should succeed after starting
,ok 185 connection to router server should succeed after starting
,2016-03-29 11:16:16.535 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:16:16.536 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:16:16.536 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:16:16.536 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
2016-03-29 11:16:16.537 ThaliTest[2411:4416739] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:16:16.538 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 186 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 187 connection to servers manager should fail after stopping
,ok 188 connection to router server should fail after stopping
,# teardown
,# setup
,2016-03-29 11:16:19.777 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:19.777 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:19.777 ThaliTest[2411:4416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:16:19.779 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure terminateConnection is properly hooked up
,ok 189 called with right arguments
,# teardown
,# setup
,2016-03-29 11:17:00.268 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:00.269 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:00.269 ThaliTest[2411:4,416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:17:00.271 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. make sure terminateListener is properly hooked up
,ok 190 called with right arguments
,# teardown
,# setup
,2016-03-29 11:17:01.043 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:01.044 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:01.044 ThaliTest[2411:4416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:17:01.045 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 53. make sure we actually call kill connections properly
,2016-03-29 11:17:01.293 ThaliTest[2411:4416739] jxcore: killConnections
2016-03-29 11:17:01.293 ThaliTest[2411:4416739] jxcore: killConnections: badParam
,not ok 191 should not fail on iOS
  ---
,    operator: fail
  ...
,# teardown
,# setup
,2016-03-29 11:17:02.089 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:02.089 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:02.090 ThaliTest[2411:4,416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:17:02.091 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54916
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":54915,"error":{}}
,2016-03-29 11:17:05.293 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:17:05.294 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:17:05.294 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
,2016-03-29 11:17:05.295 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:17:05.296 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,ok 192 failure reason is as expected
,ok 193 error description is as expected
,ok 194 must be stopped
,# teardown
,# setup
,2016-03-29 11:17:05.578 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:05.579 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:05.579 ThaliTest[2411:4,416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:17:05.580 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 55. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54918
,ok 195 peerIdentifier matches
ok 196 error description matches
,# teardown
,2016-03-29 11:17:14.399 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:17:14.399 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:17:14.399 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:17:14.399 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:17:14.400 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:17:14.578 ThaliTest[2411:4416739] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:14.579 ThaliTest[2411:4416739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:14.579 ThaliTest[2411:4,416739] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:17:14.580 ThaliTest[2411:4416739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 56. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54920
,2016-03-29 11:17:14.839 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements
2016-03-29 11:17:14.839 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
ok 197 discoveryActive matches
,ok 198 advertisingActive matches
2016-03-29 11:17:14.841 ThaliTest[2411:4416739] jxcore: startListeningForAdvertisements: success
2016-03-29 11:17:14.842 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening
2016-03-29 11:17:14.842 ThaliTest[2411:4416739] THEMultipeerManager stopping peer
2016-03-29 11:17:14.844 ThaliTest[2411:4416739] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:17:14.846 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements
2016-03-29 11:17:14.846 ThaliT,est[2411:4416739] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,ok 199 discoveryActive matches
ok 200 advertisingActive matches
2016-03-29 11:17:14.848 ThaliTest[2411:4416739] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54922
,2016-03-29 11:17:14.857 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:17:14.857 ThaliTest[2411:4416739] server: starting AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:17:14.858 ThaliTest[2411:4416739] multipeer manager: start client restart timer: 0x15dc2780
2016-03-29 11:17:14.858 ThaliTest[2411:4416739] THEMultipeerManager initialized peer AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:17:14.858 ThaliTest[2411:4416739] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-29 11:17:16.877 ThaliTest[2411:4416573] client: found new peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:17:17.027 ThaliTest[2411:4416573] client: found new peer: F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:17:34.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:17:34.871 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:17:34.871 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:17:54.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:17:59.633 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:17:59.636 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:18:14.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:18:14.871 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:18:14.874 ThaliTest[2411:4416573] client: found updated peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:18:34.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:18:34.871 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:18:34.871 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:18:54.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:18:54.870 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:18:54.871 ThaliTest[2411:4416573] client: found updated peer: F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:19:14.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:19:14.872 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:19:14.872 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:19:34.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:19:34.871 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:19:34.875 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:9
,2016-03-29 11:19:54.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:19:54.871 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:19:54.872 ThaliTest[2411:4416573] client: found updated peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:20:14.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:20:14.870 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:20:14.871 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:20:34.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:20:54.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:20:54.867 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:20:54.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:21:14.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:21:14.868 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:21:14.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:21:34.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:21:34.867 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:21:34.868 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:21:54.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:21:54.868 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:21:54.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:22:14.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:22:14.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:22:14.868 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:22:34.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:22:34.868 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:22:34.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:22:54.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:22:54.869 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:22:54.870 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:23:14.858 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:23:14.867 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:23:14.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:23:34.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:23:34.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:23:34.868 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:23:54.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:23:54.867 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:23:54.869 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:24:14.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:24:14.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:24:14.868 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:24:34.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:24:34.867 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:24:34.869 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:24:54.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:24:54.867 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:24:54.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:25:14.858 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:25:14.867 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:25:14.867 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:25:34.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:25:34.867 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:25:34.869 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:25:54.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:25:54.868 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:25:54.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:26:14.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:26:14.867 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:26:14.867 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13
,2016-03-29 11:26:34.859 ThaliTest[2411:4416573] multipeer manager: restart client
,2016-03-29 11:26:34.868 ThaliTest[2411:4416573] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:26:34.868 ThaliTest[2411:4416573] client: found existing peer: F067257C-7084-41CC-A4B5-8A232A1C6437:13

```
