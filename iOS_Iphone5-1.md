#### Test 648099366fd8e87_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/648099366fd8e87/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/DC5019B7-764C-4920-8D7D-706FEC336D60/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/DC5019B7-764C-4920-8D7D-706FEC336D60/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/648099366fd8e87/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/648099366fd8e87/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50188"
,(lldb)     command script import "/tmp/DC5019B7-764C-4920-8D7D-706FEC336D60/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 10:25:54.347 ThaliTest[2003:5073366] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9D874B8E-726D-41E8-B255-F71EE1C47B1B/Library/Cookies/Cookies.binarycookies
2016-04-01 10:25:54.441 ThaliTest[2003:5073366] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 10:25:54.442 ThaliTest[2003:5073366] Multi-tasking -> Device: YES, App: YES
,2016-04-01 10:25:54.460 ThaliTest[2003:5073366] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 10:25:55.657 ThaliTest[2003:5073366] Using UIWebView
2016-04-01 10:25:55.661 ThaliTest[2003:5073366] [CDVTimer][handleopenurl] 0.270963ms
,2016-04-01 10:25:55.667 ThaliTest[2003:5073366] [CDVTimer][intentandnavigationfilter] 5.497992ms
2016-04-01 10:25:55.667 ThaliTest[2003:5073366] [CDVTimer][gesturehandler] 0.216007ms
2016-04-01 10:25:55.668 ThaliTest[2003:5073366] [CDVTimer][TotalPluginStartup] 6.797969ms
,2016-04-01 10:26:00.986 ThaliTest[2003:5073366] Resetting plugins due to page load.
,2016-04-01 10:26:02.919 ThaliTest[2003:5073366] Finished load of: file:///var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/index.html
,2016-04-01 10:26:03.115 ThaliTest[2003:5073366] JXcore Cordova plugin initializing
,2016-04-01 10:26:03.117 ThaliTest[2003:5073530] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 10:26:17.286 ThaliTest[2003:5073530] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 10:26:17.287 ThaliTest[2003:5073530] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 10:26:17.287 ThaliTest[2003:5,073530] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 10:26:17.291 ThaliTest[2003:5073530] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B1181ED2-A574-476A-9B5F-92EA25FECC42/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57193
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57195
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
DEBUG createNativeListener: listening 57198
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 57202
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57207
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57211
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
DEBUG createNativeListener: listening 57215
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
,DEBUG createNativeListener: listening 57219
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
DEBUG createNativeListener: listening 57223
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
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
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 57275
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
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57279
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
,ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
,ok 55 thirdPromise result
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
# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
# teardown
,# setup
,# 20. basic
,ok 74 sane
,# teardown
,# setup
,# 21. another
,ok 75 sane
# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"ccbe122f-8216-4649-a64f-eb913b58c9dd","data":"custom data"},{"uuid":"a43a42fb-60cd-429b-9482-f47c6b29e394","data":"custom data"},{"uuid":"674acf2f-26d0-4b75-8664-1b61e32c9c92","data":"custom data"},{"uuid":"4f3079db-5318-489d-b5a2-5da219f54744",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
,ok 83 participant data matches
,ok 84 own UUID is found from the participants list
,# teardown
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
DEBUG createNativeListener: listening 57289
,2016-04-01 10:29:11.341 ThaliTest[2003:5073530] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 10:29:11.342 ThaliTest[2003:5073530] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
,2016-04-01 10:29:11.345 ThaliTest[2003:5073530] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 10:29:11.346 ThaliTest[2003:5073530] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
,# teardown
,2016-04-01 10:29:11.482 ThaliTest[2003:5073530] jxcore: stopAdvertisingAndListening
2016-04-01 10:29:11.482 ThaliTest[2003:5073530] THEMultipeerManager stopping peer
2016-04-01 10:29:11.482 ThaliTest[2003:5073530] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 10:29:11.483 ThaliTest[2003:5073530] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 10:29:11.483 ThaliTest[2003:5073530] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57291
2016-04-01 10:29:11.868 ThaliTest[2003:5073530] jxcore: startListeningForAdvertisements
,2016-04-01 10:29:11.870 ThaliTest[2003:5073530] multipeer manager: start client restart timer: 0x14df81c0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 10:29:11.872 Th,aliTest[2003:5073530] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-01 10:29:11.889 ThaliTest[2003:5073530] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 10:29:11.893 ThaliTest[2003:5073530] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
,# teardown
,2016-04-01 10:29:12.365 ThaliTest[2003:5073530] jxcore: stopAdvertisingAndListening
2016-04-01 10:29:12.365 ThaliTest[2003:5073530] THEMultipeerManager stopping peer
2016-04-01 10:29:12.365 ThaliTest[2003:5073530] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 10:29:12.365 ThaliTest[2003:5073530] jxcore: stopListeningForAdvertisements
2016-04-01 10:29:12.366 ThaliTest[2003:5073530] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 10:29:12.367 ThaliTest[2003:5073530] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57293
,2016-04-01 10:29:26.247 ThaliTest[2003:5073530] jxcore: startUpdateAdvertisingAndListening
2016-04-01 10:29:26.247 ThaliTest[2003:5073530] server: starting 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:1
2016-04-01 10:29:26.248 ThaliTest[2003:5073530] multipeer m,anager: start client restart timer: 0x14df81c0
2016-04-01 10:29:26.248 ThaliTest[2003:5073530] THEMultipeerManager initialized peer 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:1
2016-04-01 10:29:26.248 ThaliTest[2003:5073530] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-01 10:29:26.262 ThaliTest[2003:5073530] jxcore: startUpdateAdvertisingAndListening
2016-04-01 10:29:26.262 ThaliTest[2003:5073530] THEMultipeerManager stopping peer
2016-04-01 10:29:26.262, ThaliTest[2003:5073530] multipeer manager: stop client timer
2016-04-01 10:29:26.262 ThaliTest[2003:5073530] server: starting 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
2016-04-01 10:29:26.263 ThaliTest[2003:5073530] multipeer manager: start client restart ,timer: 0x14df81c0
2016-04-01 10:29:26.263 ThaliTest[2003:5073530] THEMultipeerManager initialized peer 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
2016-04-01 10:29:26.263 ThaliTest[2003:5073530] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
# teardown
,2016-04-01 10:29:27.873 ThaliTest[2003:5073366] client: found new peer: 8094618C-E7CE-4DA5-8DA1-5309D649EE33:2
,2016-04-01 10:29:30.410 ThaliTest[2003:5073366] client: found new peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:29:46.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:29:46.290 ThaliTest[2003:5073366] client: found existing peer: 8094618C-E7CE-4DA5-8DA1-5309D649EE33:2
2016-04-01 10:29:46.294 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:29:54.799 ThaliTest[2003:5073366] client: lost peer: 8094618C-E7CE-4DA5-8DA1-5309D649EE33
2016-04-01 10:29:54.800 ThaliTest[2003:5073366] client session: onPeerLost: 8094618C-E7CE-4DA5-8DA1-5309D649EE33
,2016-04-01 10:30:06.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:30:06.285 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:30:26.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:30:26.282 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:30:46.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:30:46.286 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:30:47.073 ThaliTest[2003:5073366] client: lost peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F
2016-04-01 10:30:47.073 ThaliTest[2003:5073366] client session: onPeerLost: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F
,2016-04-01 10:30:47.409 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:30:54.624 ThaliTest[2003:5073366] client: lost peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F
2016-04-01 10:30:54.625 ThaliTest[2003:5073366] client session: onPeerLost: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F
,2016-04-01 10:31:06.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:31:06.297 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:31:26.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:31:26.284 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:31:46.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:31:46.280 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:31:59.802 ThaliTest[2003:5073366] client: lost peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F
2016-04-01 10:31:59.802 ThaliTest[2003:5073366] client session: onPeerLost: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F
,2016-04-01 10:32:06.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:32:06.480 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:32:26.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:32:26.282 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:32:46.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:32:46.283 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:33:06.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:33:26.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:33:26.275 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:33:46.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:33:46.275 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:34:06.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:34:06.274 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:34:26.264 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:34:26.274 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:34:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:34:46.211 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:35:06.199 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:35:06.208 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:35:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:35:26.209 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:35:46.199 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:35:46.707 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:36:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:36:06.210 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:36:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:36:26.215 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:36:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:36:46.209 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:37:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:37:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:37:26.215 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:37:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:37:46.212 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:37:54.689 ThaliTest[2003:5073366] client: lost peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F
2016-04-01 10:37:54.690 ThaliTest[2003:5073366] client session: onPeerLost: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F
,2016-04-01 10:38:01.227 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:38:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:38:06.208 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:38:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:38:26.209 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:38:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:38:46.209 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:39:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:39:06.208 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:39:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:39:26.225 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:39:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:39:46.220 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:40:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:40:06.208 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:40:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:40:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:40:46.210 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:41:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:41:06.217 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:41:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:41:26.211 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:41:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:41:46.209 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:42:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:42:06.208 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:42:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:42:26.210 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:42:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:42:46.210 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:43:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:43:06.211 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:43:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:43:26.210 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:43:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:43:46.208 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:44:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:44:06.210 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:44:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:44:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:44:46.209 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:45:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:45:06.210 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:45:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:45:26.215 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:45:46.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:45:46.211 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:46:06.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:46:06.209 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:46:26.200 ThaliTest[2003:5073366] multipeer manager: restart client
,2016-04-01 10:46:26.211 ThaliTest[2003:5073366] client: found existing peer: AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
,2016-04-01 10:46:27.642 ThaliTest[2003:5073530] Error!: read ETIMEDOUT
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$k","_lineNumber":"519,","_columnNumber":"13","_msg":"    at $k@net.js:519:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
,[ { _fileName: 'net.js',
    _functionName: '$c',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '    at $c@net.js:837:7' },
  { _fileName: 'net.js',
    _functionName: '$k',
    _lineNumber: '519',
    _columnNumber: '13',
    _msg: ' ,   at $k@net.js:519:13' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '' },
  toString: [Function] ]
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
Error: read ETIMEDOUT (net.js 837:7)


```
