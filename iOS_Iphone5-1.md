#### Test 657450204f13c43_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/5F5B0167-8AB4-4D0F-9392-292B1A69B750/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/5F5B0167-8AB4-4D0F-9392-292B1A69B750/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51979"
,(lldb)     command script import "/tmp/5F5B0167-8AB4-4D0F-9392-292B1A69B750/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-08 09:28:51.255 ThaliTest[2252:6125068] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DC4B2DCD-02CD-4837-AB0D-D5A4B7CC6444/Library/Cookies/Cookies.binarycookies
,2016-04-08 09:28:51.352 ThaliTest[2252:6125068] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-08 09:28:51.354 ThaliTest[2252:6125068] Multi-tasking -> Device: YES, App: YES
,2016-04-08 09:28:51.377 ThaliTest[2252:6125068] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-08 09:28:52.511 ThaliTest[2252:6125068] Using UIWebView
2016-04-08 09:28:52.515 ThaliTest[2252:6125068] [CDVTimer][handleopenurl] 0.289977ms
2016-04-08 09:28:52.520 ThaliTest[2252:6125068] [CDVTimer][intentandnavigationfilter] 4.399955ms
2016-04,-08 09:28:52.520 ThaliTest[2252:6125068] [CDVTimer][gesturehandler] 0.213027ms
2016-04-08 09:28:52.520 ThaliTest[2252:6125068] [CDVTimer][TotalPluginStartup] 5.728006ms
,2016-04-08 09:28:57.184 ThaliTest[2252:6125068] Resetting plugins due to page load.
,2016-04-08 09:28:59.491 ThaliTest[2252:6125068] Finished load of: file:///var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/index.html
,2016-04-08 09:28:59.685 ThaliTest[2252:6125068] JXcore Cordova plugin initializing
,2016-04-08 09:28:59.691 ThaliTest[2252:6125206] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-08 09:29:13.852 ThaliTest[2252:6125206] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-08 09:29:13.854 ThaliTest[2252:6125206] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-08 09:29:13.854 ThaliTest[2252:6125206] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {,"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-08 09:29:13.857 ThaliTest[2252:6125206] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-,BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EBF6D57E-1459-4627-BC29-9552F6C82D3C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59272
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59274
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59277
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 59281
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59286
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59290
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
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
DEBUG createNativeListener: listening 59294
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 59298
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
DEBUG createNativeListener: listening 59302
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
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 59354
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
,DEBUG createNativeListener: stream close:
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
,DEBUG createNativeListener: listening 59358
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
ok 42 incomi,ng has been removed
ok 43 The mux object should be closed
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
# teardown
,# setup
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
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
,# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"6bac6588-a6e4-44a8-b2ac-e4b77439f88c","data":"custom data"},{"uuid":"281113d3-0e97-4786-a620-6936cd6b2a37","data":"custom data"},{"uuid":"981e6d0f-5d06-4f4c-bdce-22c4d8fdd816","data":"custom data"},{"uuid":"e825a612-6c5c-4d54-afc9-816449e93798",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
,ok 83 participant data matches
ok 84 own UUID is found from the participants list
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
,DEBUG createNativeListener: listening 59368
,2016-04-08 09:32:22.649 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:32:22.651 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-08 09:32:22.655 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:32:22.657 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-08 09:32:22.766 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:22.766 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
2016-04-08 09:32:22.766 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:32:22.767 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:22.768 ThaliTest[2252,:6125206] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59370
2016-04-08 09:32:22.934 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements
,2016-04-08 09:32:22.936 ThaliTest[2252:6125206] multipeer manager: start client restart timer: 0x155ceec0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:32:22.938 Th,aliTest[2252:6125206] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-08 09:32:22.950 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-04-08 09:32:22.951 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-08 09:32:23.242 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:23.242 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
2016-04-08 09:32:23.242 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:32:23.243 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
2016-04-08 09:32:23.243 ThaliTest[2252:6125206] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:23.244 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59372
,2016-04-08 09:32:23.736 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:32:23.736 ThaliTest[2252:6125206] server: starting 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:1
2016-04-08 09:32:23.737 ThaliTest[2252:6125206] multipeer m,anager: start client restart timer: 0x155ceec0
2016-04-08 09:32:23.737 ThaliTest[2252:6125206] THEMultipeerManager initialized peer 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:1
2016-04-08 09:32:23.737 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-08 09:32:23.755 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:32:23.756 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
,2016-04-08 09:32:23.758 ThaliTest[2252:6125206] multipeer manager: stop client timer
,2016-04-08 09:32:23.761 ThaliTest[2252:6125206] server: starting 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:2
,2016-04-08 09:32:23.764 ThaliTest[2252:6125206] multipeer manager: start client restart timer: 0x155ceec0
,2016-04-08 09:32:23.771 ThaliTest[2252:6125206] THEMultipeerManager initialized peer 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:2
,2016-04-08 09:32:23.772 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-08 09:32:23.899 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:23.900 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
2016-04-08 09:32:23.900 ThaliTest[2252:6125206] multipeer manager: stop client timer
20,16-04-08 09:32:23.900 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
2016-04-08 09:32:23.900 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:23.901 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59377
,2016-04-08 09:32:46.637 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:46.638 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
2016-04-08 09:32:46.638 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-08 09:32:46.643 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
,2016-04-08 09:32:46.644 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
,2016-04-08 09:32:46.644 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-08 09:33:12.047 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:12.048 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
2016-04-08 09:33:12.048 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:33:12.048 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:12.050 ThaliTest[2252,:6125206] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59379
,ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-08 09:33:27.081 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:27.081 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
2016-04-08 09:33:27.082 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:33:27.082 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:27.083 ThaliTest[2252,:6125206] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59381
2016-04-08 09:33:27.329 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements
2016-04-08 09:33:27.329 ThaliTest[2252:6125206] multipeer manager: start client restart timer: 0x155ceec0
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:33:27.330 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements: success
,2016-04-08 09:33:27.347 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 09:33:27.348 ThaliTest[2252:6125206] server: starting 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:3
,2016-04-08 09:33:27.350 ThaliTest[2252:6125206] THEMultipeerManager initialized peer 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:3
,2016-04-08 09:33:27.353 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-08 09:33:27.592 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:27.593 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
2016-04-08 09:33:27.593 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:33:27.593 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
2016-04-08 09:33:27.593 ThaliTest[2252:6125206] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:27.594 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).
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
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-08 09:33:53.285 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements
2016-04-08 09:33:53.285 ThaliTest[2252:6125206] multipeer manager: start client restart timer: 0x155ceec0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:33:53.286 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-08 09:33:53.287 ThaliTes,t[2252:6125206] jxcore: stopListeningForAdvertisements
2016-04-08 09:33:53.288 ThaliTest[2252:6125206] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-04-08 09:33:53.289 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-08 09:33:53.585 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:53.586 ThaliTest[2252:61252,06] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:33:53.587 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:53.588 ThaliTest[2252:61252,06] THEMultipeerManager stopping peer
2016-04-08 09:33:53.588 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-08 09:34:15.485 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements
2016-04-08 09:34:15.485 ThaliTest[2252:6125206] multipeer manager: start client restart timer: 0x155ceec0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:34:15.486 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-08 09:34:15.487 ThaliTes,t[2252:6125206] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:34:15.488 ThaliTest[2252:6125206] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-08 09:34:35.423 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:34:51.036 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
2016-04-08 09:34:51.036 ThaliTest[2252:6125206] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-08 09:34:51.037 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:34:51.038 ThaliTest[2252:6125,206] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:51.038 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
2016-04-08 09:34:51.038 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-08 09:34:52.492 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:52.493 ThaliTest[2252:61252,06] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-08 09:34:52.494 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:52.495 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-08 09:34:52.826 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:52.827 ThaliTest[2252:61252,06] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:34:52.828 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:52.828 ThaliTest[2252:61252,06] THEMultipeerManager stopping peer
2016-04-08 09:34:52.829 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-08 09:34:52.976 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:34:52.977 ThaliTest[2252:6125206] server: starting 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:4
2016-04-08 09:34:52.977 ThaliTest[2252:6125206] multipeer m,anager: start client restart timer: 0x155ceec0
2016-04-08 09:34:52.977 ThaliTest[2252:6125206] THEMultipeerManager initialized peer 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:4
2016-04-08 09:34:52.977 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:34:52.979 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:52.979 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
,2016-04-08 09:34:52.979 ThaliTest[2252:6125206] multipeer manager: stop client timer
2016-04-08 09:34:52.983 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-08 09:34:53.078 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:53.079 ThaliTest[2252:61252,06] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:34:53.080 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:53.080 ThaliTest[2252:61252,06] THEMultipeerManager stopping peer
2016-04-08 09:34:53.080 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-08 09:34:53.411 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:34:53.412 ThaliTest[2252:6125206] server: starting 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:5
2016-04-08 09:34:53.412 ThaliTest[2252:6125206] multipeer m,anager: start client restart timer: 0x155ceec0
2016-04-08 09:34:53.412 ThaliTest[2252:6125206] THEMultipeerManager initialized peer 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:5
2016-04-08 09:34:53.412 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:34:53.414 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:34:53.414 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
,2016-04-08 09:34:53.414 ThaliTest[2252:6125206] multipeer manager: stop client timer
2016-04-08 09:34:53.421 ThaliTest[2252:6125206] server: starting 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:6
2016-04-08 09:34:53.422 ThaliTest[2252:6125206] multipeer manager,: start client restart timer: 0x155ceec0
2016-04-08 09:34:53.422 ThaliTest[2252:6125206] THEMultipeerManager initialized peer 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:6
2016-04-08 09:34:53.422 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-04-08 09:34:53.497 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-08 09:34:53.498 ThaliTest[2252:612520,6] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:34:53.499 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:53.500 ThaliTest[2252:612520,6] THEMultipeerManager stopping peer
2016-04-08 09:34:53.500 ThaliTest[2252:6125206] multipeer manager: stop client timer
2016-04-08 09:34:53.500 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-08 09:34:57.500 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:57.500 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
2016-04-08 09:34:57.500 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:34:57.501 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:57.501 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
2016-04-08 09:34,:57.502 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-08 09:35:12.063 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:35:12.064 ThaliTest[2252:61252,06] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:35:12.065 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:35:12.065 ThaliTest[2252:61252,06] THEMultipeerManager stopping peer
2016-04-08 09:35:12.065 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-08 09:35:16.648 ThaliTest[2252:6125206] jxcore: connect foo
2016-04-08 09:35:16.648 ThaliTest[2252:6125206] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvert,isements is not active'
    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-08 09:35:16.725 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:35:16.726 ThaliTest[2252:61252,06] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:35:16.727 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:35:16.727 ThaliTest[2252:61252,06] THEMultipeerManager stopping peer
2016-04-08 09:35:16.727 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-08 09:35:16.898 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:35:16.899 ThaliTest[2252:6125206] server: starting 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:16.900 ThaliTest[2252:6125206] multipeer m,anager: start client restart timer: 0x155ceec0
2016-04-08 09:35:16.900 ThaliTest[2252:6125206] THEMultipeerManager initialized peer 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:16.900 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-08 09:35:16.901 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-08 09:35:16.902 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-08 09:35:17.940 ThaliTest[2252:6125068] client: found new peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a strin,g
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-08 09:35:18.167 ThaliTest[2252:6125068] client: found new peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:7
,2016-04-08 09:35:18.571 ThaliTest[2252:6125068] client: found new peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:7
,2016-04-08 09:35:21.794 ThaliTest[2252:6125068] client: lost peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:35:21.794 ThaliTest[2252:6125068] client session: onPeerLost: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:35:21.794 ThaliTest[225,2:6125068] client: lost peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227
2016-04-08 09:35:21.794 ThaliTest[2252:6125068] client session: onPeerLost: B29A2A64-B1EF-4545-BC19-F0DD94E05227
,2016-04-08 09:35:25.916 ThaliTest[2252:6125068] client: lost peer: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:35:25.916 ThaliTest[2252:6125068] client session: onPeerLost: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:35:32.692 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-08 09:35:32.694 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:35:32.695 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
,2016-04-08 09:35:32.696 ThaliTest[2252:6125206] THEMultipeerManager stopping peer
,2016-04-08 09:35:32.696 ThaliTest[2252:6125206] multipeer manager: stop client timer
2016-04-08 09:35:32.697 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-08 09:35:41.499 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:35:41.499 ThaliTest[2252:6125206] server: starting 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:35:41.500 ThaliTest[2252:6125206] multipeer m,anager: start client restart timer: 0x155ceec0
2016-04-08 09:35:41.500 ThaliTest[2252:6125206] THEMultipeerManager initialized peer 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:35:41.500 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:35:41.501 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-08 09:35:41.502 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-08 09:35:43.608 ThaliTest[2252:6125068] client: found new peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5401A4DE-2020-4411-800F-72E067EDF,F0D:8","pleaseConnect":0}]
2016-04-08 09:35:43.611 ThaliTest[2252:6125068] client: found new peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:8
2016-04-08 09:35:43.611 ThaliTest[2252:6125068] client: found new peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
,2016-04-08 09:35:43.612 ThaliTest[2252:6125206] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:35:43.617 ThaliTest[2252:6125206] client session: connect
2016-04-08 09:35:43.617 ThaliTest[2252:6125206] client session: stateChange:0->,1 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B29A2A64-B1EF-4545-BC19-F0DD94E05227:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvai,lable":1,"peerIdentifier":"C76D48A2-6720-4997-B51C-ADA808AA0AC0:8","pleaseConnect":0}]
,2016-04-08 09:35:43.824 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:35:43.824 ThaliTest[2252:6125068] server: rejecting invitation from 5401A4DE-2020-4411-800F-72E067EDFF0D due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0,B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:35:45.064 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:35:45.066 ThaliTest[2252:6125068] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:35:46.405 ThaliTest[2252:6126340] client session: p2p link connected
,2016-04-08 09:35:46.420 ThaliTest[2252:6126332] client session: stateChange:1->2 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:35:46.420 ThaliTest[2252:6126332] client session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 0,9:35:46.420 ThaliTest[2252:6126332] jxcore: connect: success
INFO testThaliMobileNative: 
ok 177 Must have listeningPort
ok 178 listeningPort must be a number
ok 179 Connection must have clientPort
ok 180 clientPort must be a number
ok 181 Connection, must have serverPort
ok 182 serverPort must be a number
ok 183 forward connection must have clientPort == 0
ok 184 forward connection must have serverPort == 0
,# teardown
,2016-04-08 09:35:48.356 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:35:48.358 ThaliTest[2252:6125068] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:35:48.358 ThaliTest[2252:6125068], server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:35:51.551 ThaliTest[2252:6125068] multipeer session: reset timer
,2016-04-08 09:35:51.551 ThaliTest[2252:6125068] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:35:51.551 ThaliTest[2252:6125068] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to p,revious generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:35:54.695 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:35:54.695 ThaliTest[2252:6125068] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:35:54.695 ThaliTest[2252:6125068], server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:35:57.853 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:35:57.853 ThaliTest[2252:6125068] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:35:57.854 ThaliTest[2252:6125068], server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:36:00.997 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:36:00.997 ThaliTest[2252:6125068] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:36:00.997 ThaliTest[2252:6125068], server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:36:01.501 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:36:01.522 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:8
,2016-04-08 09:36:01.536 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:01.538 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:04.097 ThaliTest[2252:6125068] multipeer session: reset timer
,2016-04-08 09:36:04.098 ThaliTest[2252:6125068] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
,2016-04-08 09:36:04.098 ThaliTest[2252:6125068] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:36:07.276 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:36:07.277 ThaliTest[2252:6125068] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:36:07.277 ThaliTest[2252:6125068], server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:36:10.369 ThaliTest[2252:6125068] multipeer session: reset timer
,2016-04-08 09:36:10.369 ThaliTest[2252:6125068] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:36:10.369 ThaliTest[2252:6125068] server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to p,revious generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:36:13.570 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:36:13.571 ThaliTest[2252:6125068] server: disconnecting to refresh session (B29A2A64-B1EF-4545-BC19-F0DD94E05227)
2016-04-08 09:36:13.571 ThaliTest[2252:6125068], server: rejecting invitation from B29A2A64-B1EF-4545-BC19-F0DD94E05227 due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7)
,2016-04-08 09:36:14.538 ThaliTest[2252:6126332] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:14.538 ThaliTest[2252:6126332] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:36:14.542 ThaliTest[2252:6126332] client session: disconnect
,2016-04-08 09:36:14.542 ThaliTest[2252:6126332] client session: stateChange:2->0 5401A4DE-2020-4411-800F-72E067EDFF0D:8
,2016-04-08 09:36:15.019 ThaliTest[2252:6125206] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-08 09:36:15.020 ThaliTest[2252:612520,6] jxcore: stopListeningForAdvertisements: success
ok 185 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:36:15.021 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening
2016-04-08 09:36:15.021 ThaliTest[2252:612520,6] THEMultipeerManager stopping peer
2016-04-08 09:36:15.022 ThaliTest[2252:6125206] multipeer manager: stop client timer
2016-04-08 09:36:15.022 ThaliTest[2252:6125206] jxcore: stopAdvertisingAndListening: success
ok 186 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-08 09:36:17.488 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:36:17.488 ThaliTest[2252:6125206] server: starting 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:36:17.489 ThaliTest[2252:6125206] multipeer m,anager: start client restart timer: 0x155ceec0
2016-04-08 09:36:17.489 ThaliTest[2252:6125206] THEMultipeerManager initialized peer 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:36:17.489 ThaliTest[2252:6125206] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 187 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:36:17.491 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-08 09:36:17.491 ThaliTest[2252:6125206] jxcore: startListeningForAdvertisements: success
ok 188 Can call startListeningForAdvertisements without error
,2016-04-08 09:36:19.745 ThaliTest[2252:6125068] client: found new peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:19.747 ThaliTest[2252:6125206] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:19.747 ThaliTest[2252:6,125206] client: server will connect
2016-04-08 09:36:19.747 ThaliTest[2252:6125206] client session: reverseConnect
2016-04-08 09:36:19.747 ThaliTest[2252:6125206] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:1,9.750 ThaliTest[2252:6125068] client: found new peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:36:19.756 ThaliTest[2252:6125068] client: found new peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:8
,2016-04-08 09:36:19.915 ThaliTest[2252:6126260] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:19.916 ThaliTest[2252:6126260] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:36:19.9,16 ThaliTest[2252:6126260] client session: disconnect
2016-04-08 09:36:19.917 ThaliTest[2252:6126260] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:19.917 ThaliTest[2252:6126260] client session: no connect callb,ack (server initiated)
,2016-04-08 09:36:20.123 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:36:20.124 ThaliTest[2252:6125068] server: rejecting invitation from 5401A4DE-2020-4411-800F-72E067EDFF0D due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8)
,2016-04-08 09:36:29.747 ThaliTest[2252:6125068] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-08 09:36:32.758 ThaliTest[2252:6125206] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:32.758 ThaliTest[2252:6125206] client: server will connect
2016-04-08 09:36:32.758 ThaliTest[2252:6125206] client session: reverseConn,ect
2016-04-08 09:36:32.758 ThaliTest[2252:6125206] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:36:33.099 ThaliTest[2252:6126435] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:33.099 ThaliTest[2252:6126435] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:36:33.1,00 ThaliTest[2252:6126435] client session: disconnect
2016-04-08 09:36:33.100 ThaliTest[2252:6126435] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:33.101 ThaliTest[2252:6126435] client session: no connect callback (server initiated)
,2016-04-08 09:36:33.503 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:36:33.503 ThaliTest[2252:6125068] server: disconnecting to refresh session (5401A4DE-2020-4411-800F-72E067EDFF0D)
2016-04-08 09:36:33.504 ThaliTest[2252:6125068], server: rejecting invitation from 5401A4DE-2020-4411-800F-72E067EDFF0D due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8)
,2016-04-08 09:36:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:36:37.512 ThaliTest[2252:6125068] client: found updated peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:36:37.513 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:37.513 ThaliTest[2252:6125068] client: found updated peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:36:42.759 ThaliTest[2252:6125068] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-08 09:36:45.771 ThaliTest[2252:6125206] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:45.772 ThaliTest[2252:6125206] client: server will connect
2016-04-08 09:36:45.772 ThaliTest[2252:6125206] client session: reverseConn,ect
2016-04-08 09:36:45.772 ThaliTest[2252:6125206] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:36:46.079 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:36:46.083 ThaliTest[2252:6125068] server: disconnecting to refresh session (5401A4DE-2020-4411-800F-72E067EDFF0D)
2016-04-08 09:36:46.083 ThaliTest[2252:6125068], server: rejecting invitation from 5401A4DE-2020-4411-800F-72E067EDFF0D due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8)
,2016-04-08 09:36:46.158 ThaliTest[2252:6126432] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:46.159 ThaliTest[2252:6126432] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:36:46.1,60 ThaliTest[2252:6126432] client session: disconnect
2016-04-08 09:36:46.160 ThaliTest[2252:6126432] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:46.161 ThaliTest[2252:6126432] client session: no connect callb,ack (server initiated)
,2016-04-08 09:36:51.099 ThaliTest[2252:6125068] client: lost peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227
2016-04-08 09:36:51.099 ThaliTest[2252:6125068] client session: onPeerLost: B29A2A64-B1EF-4545-BC19-F0DD94E05227
,2016-04-08 09:36:53.784 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:36:55.773 ThaliTest[2252:6125068] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-08 09:36:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:36:57.521 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:57.521 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:57.52,4 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:36:58.780 ThaliTest[2252:6125206] jxcore: connect C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:58.781 ThaliTest[2252:6125206] client: server will connect
2016-04-08 09:36:58.781 ThaliTest[2252:6125206] client session: reverseConn,ect
2016-04-08 09:36:58.781 ThaliTest[2252:6125206] client session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:36:59.696 ThaliTest[2252:6126560] client session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:59.696 ThaliTest[2252:6126560] client session: onLinkFailure: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:36:59.6,96 ThaliTest[2252:6126560] client session: disconnect
2016-04-08 09:36:59.696 ThaliTest[2252:6126560] client session: stateChange:1->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:59.697 ThaliTest[2252:6126560] client session: no connect callb,ack (server initiated)
,2016-04-08 09:37:00.293 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:37:00.293 ThaliTest[2252:6125068] server session: connect
2016-04-08 09:37:00.294 ThaliTest[2252:6125068] server session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:00.302 ThaliTest[2252:6125068] server: accepting invitation C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:37:00.320 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:37:00.321 ThaliTest[2252:6125068] server: disconnecting to refresh session (5401A4DE-2020-4411-800F-72E067EDFF0D)
2016-04-08 09:37:00.321 ThaliTest[2252:6125068] server: rejecting invitation from 5401A4DE-2020-4411-800F-72E067EDFF0D due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8)
,2016-04-08 09:37:03.481 ThaliTest[2252:6126558] server session: p2p link connected
,2016-04-08 09:37:03.512 ThaliTest[2252:6125068] server relay: connected (to port: 59393)
,2016-04-08 09:37:03.513 ThaliTest[2252:6125068] server session: stateChange:1->2 C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:03.513 ThaliTest[2252:6125068] jxcore: connect: success
,2016-04-08 09:37:12.381 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:37:12.382 ThaliTest[2252:6125068] server: disconnecting to refresh session (5401A4DE-2020-4411-800F-72E067EDFF0D)
2016-04-08 09:37:12.382 ThaliTest[2252:6125068], server: rejecting invitation from 5401A4DE-2020-4411-800F-72E067EDFF0D due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8)
,2016-04-08 09:37:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:37:17.515 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:17.518 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:37:17.51,8 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:37:25.772 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:37:25.772 ThaliTest[2252:6125068] server: disconnecting to refresh session (5401A4DE-2020-4411-800F-72E067EDFF0D)
2016-04-08 09:37:25.773 ThaliTest[2252:6125068], server: rejecting invitation from 5401A4DE-2020-4411-800F-72E067EDFF0D due to previous generation (9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9 != 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8)
,2016-04-08 09:37:33.724 ThaliTest[2252:6125068] client: lost peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227
2016-04-08 09:37:33.725 ThaliTest[2252:6125068] client session: onPeerLost: B29A2A64-B1EF-4545-BC19-F0DD94E05227
,2016-04-08 09:37:35.492 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:35.493 ThaliTest[2252:6125206] jxcore: connect B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:35.493 ThaliTest[2,252:6125206] client: server will connect
2016-04-08 09:37:35.494 ThaliTest[2252:6125206] client session: reverseConnect
2016-04-08 09:37:35.494 ThaliTest[2252:6125206] client session: stateChange:0->1 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:37:35.931 ThaliTest[2252:6126646] client session: not connected B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:35.931 ThaliTest[2252:6126646] client session: onLinkFailure: B29A2A64-B1EF-4545-BC19-F0DD94E05227
2016-04-08 09:37:35.9,31 ThaliTest[2252:6126646] client session: disconnect
2016-04-08 09:37:35.932 ThaliTest[2252:6126646] client session: stateChange:1->0 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:35.933 ThaliTest[2252:6126646] client session: no connect callb,ack (server initiated)
,2016-04-08 09:37:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:37:37.518 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:37.518 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:37:37.531 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:37:45.495 ThaliTest[2252:6125068] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-08 09:37:48.501 ThaliTest[2252:6125206] jxcore: connect B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:48.501 ThaliTest[2252:6125206] client: server will connect
2016-04-08 09:37:48.502 ThaliTest[2252:6125206] client session: reverseConnect
2016-04-08 09:37:48.502 ThaliTest[2252:6125206] client session: stateChange:0->1 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:37:49.000 ThaliTest[2252:6126646] client session: not connected B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:37:49.001 ThaliTest[2252:6126646] client session: onLinkFailure: B29A2A64-B1EF-4545-BC19-F0DD94E05227
2016-04-08 09:37:49.001 ThaliTest[2252:6126646] client session: disconnect
2016-04-08 09:37:49.002 ThaliTest[2252:6126646] client session:, stateChange:1->0 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:49.002 ThaliTest[2252:6126646] client session: no connect callback (server initiated)
,2016-04-08 09:37:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:37:57.510 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:57.512 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:37:57.515 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:37:58.503 ThaliTest[2252:6125068] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-08 09:38:01.504 ThaliTest[2252:6125206] jxcore: connect B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:01.505 ThaliTest[2252:6125206] client: server will connect
2016-04-08 09:38:01.505 ThaliTest[2252:6125206] client session: reverseConn,ect
2016-04-08 09:38:01.505 ThaliTest[2252:6125206] client session: stateChange:0->1 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:38:01.773 ThaliTest[2252:6126732] client session: not connected B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:01.773 ThaliTest[2252:6126732] client session: onLinkFailure: B29A2A64-B1EF-4545-BC19-F0DD94E05227
2016-04-08 09:38:01.7,73 ThaliTest[2252:6126732] client session: disconnect
2016-04-08 09:38:01.774 ThaliTest[2252:6126732] client session: stateChange:1->0 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:01.774 ThaliTest[2252:6126732] client session: no connect callb,ack (server initiated)
,2016-04-08 09:38:11.506 ThaliTest[2252:6125068] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-08 09:38:14.516 ThaliTest[2252:6125206] jxcore: connect B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:14.517 ThaliTest[2252:6125206] client: server will connect
2016-04-08 09:38:14.517 ThaliTest[2252:6125206] client session: reverseConn,ect
2016-04-08 09:38:14.517 ThaliTest[2252:6125206] client session: stateChange:0->1 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:38:14.844 ThaliTest[2252:6126733] client session: not connected B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:14.844 ThaliTest[2252:6126733] client session: onLinkFailure: B29A2A64-B1EF-4545-BC19-F0DD94E05227
2016-04-08 09:38:14.8,44 ThaliTest[2252:6126733] client session: disconnect
2016-04-08 09:38:14.846 ThaliTest[2252:6126733] client session: stateChange:1->0 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:14.846 ThaliTest[2252:6126733] client session: no connect callb,ack (server initiated)
,2016-04-08 09:38:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:38:17.513 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:38:17.517 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:38:17.518 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:38:24.518 ThaliTest[2252:6125068] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-08 09:38:27.530 ThaliTest[2252:6125206] jxcore: connect B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:27.531 ThaliTest[2252:6125206] client: server will connect
2016-04-08 09:38:27.531 ThaliTest[2252:6125206] client session: reverseConn,ect
2016-04-08 09:38:27.531 ThaliTest[2252:6125206] client session: stateChange:0->1 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:38:27.766 ThaliTest[2252:6126809] client session: not connected B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:27.767 ThaliTest[2252:6126809] client session: onLinkFailure: B29A2A64-B1EF-4545-BC19-F0DD94E05227
2016-04-08 09:38:27.7,67 ThaliTest[2252:6126809] client session: disconnect
2016-04-08 09:38:27.768 ThaliTest[2252:6126809] client session: stateChange:1->0 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:27.768 ThaliTest[2252:6126809] client session: no connect callback (server initiated)
,2016-04-08 09:38:27.836 ThaliTest[2252:6125068] multipeer session: reset timer
2016-04-08 09:38:27.837 ThaliTest[2252:6125068] server session: connect
2016-04-08 09:38:27.837 ThaliTest[2252:6125068] server session: stateChange:0->1 B29A2A64-B1EF-4545-BC1,9-F0DD94E05227:9
2016-04-08 09:38:27.844 ThaliTest[2252:6125068] server: accepting invitation B29A2A64-B1EF-4545-BC19-F0DD94E05227
,2016-04-08 09:38:30.646 ThaliTest[2252:6126809] server session: p2p link connected
,2016-04-08 09:38:31.832 ThaliTest[2252:6125068] server relay: connected (to port: 59393)
2016-04-08 09:38:31.833 ThaliTest[2252:6125068] server session: stateChange:1->2 B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:31.833 ThaliTest[2252:6125068] jxcore: connect: success
,2016-04-08 09:38:35.888 ThaliTest[2252:6125068] client: lost peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227
,2016-04-08 09:38:35.889 ThaliTest[2252:6125068] client session: onPeerLost: B29A2A64-B1EF-4545-BC19-F0DD94E05227
,2016-04-08 09:38:37.489 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:38:37.512 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:37.513 ThaliTest[2252:6125206] jxcore: connect B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:37.513 ThaliTest[2,252:6125206] client: server already connected
2016-04-08 09:38:37.513 ThaliTest[2252:6125206] jxcore: connect: success
,2016-04-08 09:38:37.524 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:38:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:38:57.524 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:38:57.525 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:38:57.526 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:39:02.804 ThaliTest[2252:6125068] client: lost peer: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:39:02.804 ThaliTest[2252:6125068] client session: onPeerLost: 5401A4DE-2020-4411-800F-72E067EDFF0D
,2016-04-08 09:39:17.461 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:17.463 ThaliTest[2252:6125206] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:17.463 ThaliTest[2,252:6125206] client session: connect
2016-04-08 09:39:17.463 ThaliTest[2252:6125206] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:39:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:39:17.531 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:39:17.532 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:39:17.53,3 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:39:24.318 ThaliTest[2252:6125068] client: lost peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227
,2016-04-08 09:39:24.320 ThaliTest[2252:6125068] client session: onPeerLost: B29A2A64-B1EF-4545-BC19-F0DD94E05227
,2016-04-08 09:39:27.313 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:39:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:39:37.521 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:37.521 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:39:37.52,3 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:39:50.452 ThaliTest[2252:6127030] client session: not connected 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:50.452 ThaliTest[2252:6127030] client session: onLinkFailure: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:39:50.4,52 ThaliTest[2252:6127030] client session: disconnect
2016-04-08 09:39:50.453 ThaliTest[2252:6127030] client session: stateChange:1->0 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:50.453 ThaliTest[2252:6127030] client session: fireConnectCallb,ack: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:39:50.453 ThaliTest[2252:6127030] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 9
,2016-04-08 09:39:53.456 ThaliTest[2252:6125206] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:53.457 ThaliTest[2252:6125206] client session: connect
2016-04-08 09:39:53.457 ThaliTest[2252:6125206] client session: stateChange:0->1 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:39:55.551 ThaliTest[2252:6127134] client session: p2p link connected
2016-04-08 09:39:55.554 ThaliTest[2252:6127134] client session: stateChange:1->2 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:55.554 ThaliTest[2252:6127134] cli,ent session: fireConnectCallback: 5401A4DE-2020-4411-800F-72E067EDFF0D
2016-04-08 09:39:55.554 ThaliTest[2252:6127134] jxcore: connect: success
,2016-04-08 09:39:55.568 ThaliTest[2252:6125206] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:55.569 ThaliTest[2252:6125206] client: already connect(ing/ed) to 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:55.569 Thali,Test[2252:6125068] client: relay established
2016-04-08 09:39:55.569 ThaliTest[2252:6125206] jxcore: connect: fail: Already connect(ing/ed)
2016-04-08 09:39:55.569 ThaliTest[2252:6125068] client: new accepted socket: 0x1b88dad0
ok 189 Expected error
ok, 190 Null connection as expected
2016-04-08 09:39:55.571 ThaliTest[2252:6125206] jxcore: connect 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:39:55.571 ThaliTest[2252:6125206] client: already connect(ing/ed) to 5401A4DE-2020-4411-800F-72E067EDFF0,D:9
2016-04-08 09:39:55.571 ThaliTest[2252:6125206] jxcore: connect: fail: Already connect(ing/ed)
ok 191 Expected error
ok 192 Null connection as expected
,# teardown
,2016-04-08 09:39:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:39:57.508 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:39:57.520 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:39:57.521 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:40:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:40:17.514 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:40:17.529 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:40:17.532 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:40:17.633 ThaliTest[2252:6125068] client: lost peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:40:17.635 ThaliTest[2252:6125068] client session: onPeerLost: C76D48A2-6720-4997-B51C-ADA808AA0AC0
,2016-04-08 09:40:22.971 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:40:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:40:37.515 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:40:37.530 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:40:37.531 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:40:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:41:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:41:17.512 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:41:17.512 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:41:17.51,2 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:41:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:41:37.510 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:41:37.511 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:41:37.51,1 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:41:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:41:57.509 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:41:57.510 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:41:57.51,0 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:42:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:42:17.506 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:42:17.506 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:42:17.50,9 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:42:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:42:37.508 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:42:37.510 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:42:37.511 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:42:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:42:57.508 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:42:57.509 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:42:57.509 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:43:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:43:17.511 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:43:17.512 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:43:17.512 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:43:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:43:37.513 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:43:37.513 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:43:37.51,4 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:43:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:43:57.509 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:43:57.509 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:43:57.510 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:44:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:44:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:44:37.509 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:44:37.509 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:44:37.51,2 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:44:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:44:57.514 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:44:57.514 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:44:57.51,4 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:45:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:45:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:45:37.509 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:45:37.510 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:45:37.51,1 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:45:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:45:57.512 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:45:57.512 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:45:57.51,2 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:46:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:46:17.511 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:46:17.511 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:46:17.51,1 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:46:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:46:37.512 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:46:37.512 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:46:37.51,2 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:46:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:46:57.517 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:46:57.517 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:46:57.51,7 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:47:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:47:17.509 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:47:17.509 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:47:17.509 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:47:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:47:37.510 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:47:37.511 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:47:37.512 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:47:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:47:57.510 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:47:57.513 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:47:57.51,3 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:48:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:48:17.513 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:48:17.513 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:48:17.51,4 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:48:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:48:37.515 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:48:37.515 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:48:37.51,5 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:48:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:48:57.506 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:48:57.507 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:48:57.50,7 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:49:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:49:17.510 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:49:17.511 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:49:17.517 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:49:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:49:37.510 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:49:37.513 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:49:37.513 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:49:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:49:57.512 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:49:57.512 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:49:57.51,3 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:50:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:50:17.510 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:50:17.512 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:50:17.51,2 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:50:37.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:50:37.513 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:50:37.516 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:50:37.51,6 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:50:57.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:50:57.511 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:50:57.513 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:50:57.51,8 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:51:17.490 ThaliTest[2252:6125068] multipeer manager: restart client
,2016-04-08 09:51:17.510 ThaliTest[2252:6125068] client: found existing peer: 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:51:17.510 ThaliTest[2252:6125068] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:51:17.51,1 ThaliTest[2252:6125068] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9

```
