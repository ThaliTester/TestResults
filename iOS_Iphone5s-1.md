#### Test 657450204f13c43_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/D6E21770-D5A6-4354-B106-7F69486A5644/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D6E21770-D5A6-4354-B106-7F69486A5644/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/657450204f13c43/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51983"
,(lldb)     command script import "/tmp/D6E21770-D5A6-4354-B106-7F69486A5644/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-08 09:29:20.166 ThaliTest[3008:5841634] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/063CC2A5-2D15-4E29-8205-D88E11C14FC6/Library/Cookies/Cookies.binarycookies
,2016-04-08 09:29:20.410 ThaliTest[3008:5841634] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-08 09:29:20.412 ThaliTest[3008:5841634] Multi-tasking -> Device: YES, App: YES
,2016-04-08 09:29:20.430 ThaliTest[3008:5841634] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-08 09:29:21.208 ThaliTest[3008:5841634] Using UIWebView
2016-04-08 09:29:21.210 ThaliTest[3008:5841634] [CDVTimer][handleopenurl] 0.158012ms
,2016-04-08 09:29:21.215 ThaliTest[3008:5841634] [CDVTimer][intentandnavigationfilter] 4.004002ms
2016-04-08 09:29:21.215 ThaliTest[3008:5841634] [CDVTimer][gesturehandler] 0.168025ms
2016-04-08 09:29:21.215 ThaliTest[3008:5841634] [CDVTimer][TotalPluginS,tartup] 4.966974ms
,2016-04-08 09:29:24.290 ThaliTest[3008:5841634] Resetting plugins due to page load.
,2016-04-08 09:29:25.533 ThaliTest[3008:5841634] Finished load of: file:///var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/index.html
,2016-04-08 09:29:25.720 ThaliTest[3008:5841634] JXcore Cordova plugin initializing
,2016-04-08 09:29:25.721 ThaliTest[3008:5841789] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-08 09:29:34.266 ThaliTest[3008:5841789] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-08 09:29:34.267 ThaliTest[3008:5841789] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-08 09:29:34.268 ThaliTest[3008:5841789] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-08 09:29:34.270 ThaliTest[3008:5841789] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7F5F3566-4A1F-4D80-B51F-27AFC80B8296/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60837
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60839
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
DEBUG createNativeListener: listening 60842
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 60846
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 60851
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
DEBUG createNativeListener: listening 60855
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
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
,DEBUG createNativeListener: listening 60859
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
DEBUG createNativeListener: listening 60863
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
DEBUG createNativeListener: listening 60867
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
DEBUG createNativeListener: new ,mux
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
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
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
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
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
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBU,G createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
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
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
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
DEBUG createNativeListener: listening 60919
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
DEBUG createNativeListener: listening 60923
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
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
,# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
,# setup
,# 20. basic
,ok 74 sane
# teardown
,# setup
,# 21. another
,ok 75 sane
# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"6bac6588-a6e4-44a8-b2ac-e4b77439f88c","data":"custom data"},{"uuid":"281113d3-0e97-4786-a620-6936cd6b2a37","data":"custom data"},{"uuid":"981e6d0f-5d06-4f4c-bdce-22c4d8fdd816","data":"custom data"},{"uuid":"e825a612-6c5c-4d54-afc9-816449e93798","data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
,ok 83 participant data matches
ok 84 own UUID is found from the participants list
# teardown
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
DEBUG createNativeListener: listening 60933
2016-04-08 09:32:22.565 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:22.566 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-08 09:32:22.568 ThaliTest[3008:5841789] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:22.568 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-08 09:32:22.712 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:22.712 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:32:22.712 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:32:22.713 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:22.713 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60935
2016-04-08 09:32:22.890 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements
,2016-04-08 09:32:22.892 ThaliTest[3008:5841789] multipeer manager: start client restart timer: 0x17ea86e0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:32:22.893 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-08 09:32:22.932 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-08 09:32:22.933 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-08 09:32:23.192 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:23.192 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:32:23.192 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:32:23.192 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
2016-04-08 09:32:23.193 ThaliTest[3008:5841789] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:23.193 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60937
,2016-04-08 09:32:23.675 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:32:23.676 ThaliTest[3008:5841789] server: starting 5401A4DE-2020-4411-800F-72E067EDFF0D:1
,2016-04-08 09:32:23.678 ThaliTest[3008:5841789] multipeer manager: start client restart timer: 0x17ea86e0
2016-04-08 09:32:23.678 ThaliTest[3008:5841789] THEMultipeerManager initialized peer 5401A4DE-2020-4411-800F-72E067EDFF0D:1
2016-04-08 09:32:23.678 ,ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-08 09:32:23.718 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:32:23.718 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:32:23.719 ThaliTest[3008:5841789] multipeer manager: stop client ti,mer
2016-04-08 09:32:23.719 ThaliTest[3008:5841789] server: starting 5401A4DE-2020-4411-800F-72E067EDFF0D:2
2016-04-08 09:32:23.719 ThaliTest[3008:5841789] multipeer manager: start client restart timer: 0x17ea86e0
2016-04-08 09:32:23.719 ThaliTest[3008:,5841789] THEMultipeerManager initialized peer 5401A4DE-2020-4411-800F-72E067EDFF0D:2
2016-04-08 09:32:23.720 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-08 09:32:23.844 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:23.844 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:32:23.844 ThaliTest[3008:5841789] multipeer manager: stop client timer
20,16-04-08 09:32:23.844 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
2016-04-08 09:32:23.845 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
,2016-04-08 09:32:23.845 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60942
2016-04-08 09:32:28.363 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:28.363 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:32:28.364 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
ok 110 error should be null
2016-04-08 09:32:28.366 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:28.367 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:32:28.367 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-08 09:32:48.035 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:32:48.035 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:32:48.035 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:32:48.035 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:32:48.036 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60944
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-08 09:33:27.029 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:27.030 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:33:27.030 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:33:27.030 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:27.030 ThaliTest[3008,:5841789] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60946
2016-04-08 09:33:27.268 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements
2016-04-08 09:33:27.269 ThaliTest[3008:5841789] multipeer manager: sta,rt client restart timer: 0x17ea86e0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:33:27.270 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements: success
,2016-04-08 09:33:27.310 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:33:27.311 ThaliTest[3008:5841789] server: starting 5401A4DE-2020-4411-800F-72E067EDFF0D:3
2016-04-08 09:33:27.311 ThaliTest[3008:5841789] THEMultipee,rManager initialized peer 5401A4DE-2020-4411-800F-72E067EDFF0D:3
2016-04-08 09:33:27.311 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
,# teardown
,2016-04-08 09:33:27.529 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:27.529 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:33:27.529 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 09:33:27.529 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
2016-04-08 09:33:27.530 ThaliTest[3008:5841789] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:33:27.530 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 123 error should be null
,ok 124 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
,ok 126 should not have been called more than once
,# teardown
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
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
,ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-08 09:33:53.255 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements
2016-04-08 09:33:53.256 ThaliTest[3008:5841789] multipeer manager: start client restart timer: 0x17ea86e0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:33:53.259 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-08 09:33:53.260 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
2016-04-08 09:33:53.260 ThaliTest[3008:5841789] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingSt,ateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:33:53.261 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-08 09:33:58.256 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-08 09:33:58.257 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:33:58.259 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:33:58.259 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:33:58.259 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-08 09:34:13.331 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements
2016-04-08 09:34:13.332 ThaliTest[3008:5841789] multipeer manager: start client restart timer: 0x17ea86e0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:34:13.333 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
,2016-04-08 09:34:13.334 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 09:34:13.335 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-08 09:34:33.333 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:34:33.714 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
2016-04-08 09:34:33.714 ThaliTest[3008:5841789] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-08 09:34:33.715 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:34:33.716 ThaliTest[3008:5841,789] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:33.716 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:34:33.716 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-08 09:34:52.682 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:52.682 ThaliTest[3008:58417,89] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-08 09:34:52.683 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:52.684 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-08 09:34:52.751 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:52.752 ThaliTest[3008:58417,89] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:34:52.752 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:52.752 ThaliTest[3008:58417,89] THEMultipeerManager stopping peer
2016-04-08 09:34:52.753 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-08 09:34:53.009 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:34:53.009 ThaliTest[3008:5841789] server: starting 5401A4DE-2020-4411-800F-72E067EDFF0D:4
2016-04-08 09:34:53.009 ThaliTest[3008:5841789] multipeer m,anager: start client restart timer: 0x17ea86e0
2016-04-08 09:34:53.009 ThaliTest[3008:5841789] THEMultipeerManager initialized peer 5401A4DE-2020-4411-800F-72E067EDFF0D:4
2016-04-08 09:34:53.009 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:34:53.010 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:53.010 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
,2016-04-08 09:34:53.010 ThaliTest[3008:5841789] multipeer manager: stop client timer
2016-04-08 09:34:53.015 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-08 09:34:53.094 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:34:53.095 ThaliTest[3008:58417,89] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:34:53.095 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:53.095 ThaliTest[3008:58417,89] THEMultipeerManager stopping peer
2016-04-08 09:34:53.095 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-08 09:34:53.424 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:34:53.424 ThaliTest[3008:5841789] server: starting 5401A4DE-2020-4411-800F-72E067EDFF0D:5
2016-04-08 09:34:53.424 ThaliTest[3008:5841789] multipeer m,anager: start client restart timer: 0x17ea86e0
2016-04-08 09:34:53.425 ThaliTest[3008:5841789] THEMultipeerManager initialized peer 5401A4DE-2020-4411-800F-72E067EDFF0D:5
2016-04-08 09:34:53.425 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:34:53.425 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:34:53.426 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
,2016-04-08 09:34:53.426 ThaliTest[3008:5841789] multipeer manager: stop client timer
2016-04-08 09:34:53.430 ThaliTest[3008:5841789] server: starting 5401A4DE-2020-4411-800F-72E067EDFF0D:6
2016-04-08 09:34:53.430 ThaliTest[3008:5841789] multipeer manager,: start client restart timer: 0x17ea86e0
2016-04-08 09:34:53.430 ThaliTest[3008:5841789] THEMultipeerManager initialized peer 5401A4DE-2020-4411-800F-72E067EDFF0D:6
2016-04-08 09:34:53.431 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-08 09:34:53.498 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-08 09:34:53.499 ThaliTest[3008:584178,9] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:34:53.499 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:53.500 ThaliTest[3008:584178,9] THEMultipeerManager stopping peer
2016-04-08 09:34:53.500 ThaliTest[3008:5841789] multipeer manager: stop client timer
2016-04-08 09:34:53.500 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-08 09:34:55.537 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:55.537 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:34:55.537 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-08 09:34:55.538 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:34:55.538 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:34:55.538 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-08 09:35:00.417 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:35:00.418 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:35:00.419 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:35:00.419 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:35:00.419 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-08 09:35:16.654 ThaliTest[3008:5841789] jxcore: connect foo
2016-04-08 09:35:16.655 ThaliTest[3008:5841789] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvert,isements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-08 09:35:16.739 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 09:35:16.740 ThaliTest[3008:58417,89] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:35:16.740 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:35:16.740 ThaliTest[3008:58417,89] THEMultipeerManager stopping peer
2016-04-08 09:35:16.740 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-08 09:35:16.909 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:35:16.909 ThaliTest[3008:5841789] server: starting 5401A4DE-2020-4411-800F-72E067EDFF0D:7
2016-04-08 09:35:16.910 ThaliTest[3008:5841789] multipeer m,anager: start client restart timer: 0x17ea86e0
2016-04-08 09:35:16.910 ThaliTest[3008:5841789] THEMultipeerManager initialized peer 5401A4DE-2020-4411-800F-72E067EDFF0D:7
2016-04-08 09:35:16.910 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-08 09:35:16.911 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-08 09:35:16.912 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-08 09:35:18.627 ThaliTest[3008:5841634] client: found new peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:7
2016-04-08 09:35:18.627 ThaliTest[3008:5841634] client: found new peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:7
,ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-08 09:35:20.037 ThaliTest[3008:5841634] client: found new peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,2016-04-08 09:35:21.740 ThaliTest[3008:5841634] client: lost peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227
2016-04-08 09:35:21.740 ThaliTest[3008:5841634] client session: onPeerLost: B29A2A64-B1EF-4545-BC19-F0DD94E05227
,2016-04-08 09:35:21.776 ThaliTest[3008:5841634] client: lost peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:35:21.776 ThaliTest[3008:5841634] client session: onPeerLost: C76D48A2-6720-4997-B51C-ADA808AA0AC0
,2016-04-08 09:35:24.452 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-08 09:35:24.453 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-08 09:35:24.454 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening
2016-04-08 09:35:24.454 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:35:24.455 ThaliTest[3008:5841789] multipeer manager: stop client timer
2016-04-08 09:35:24.455 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-08 09:35:41.515 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:35:41.515 ThaliTest[3008:5841789] server: starting 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:35:41.515 ThaliTest[3008:5841789] multipeer m,anager: start client restart timer: 0x17ea86e0
2016-04-08 09:35:41.516 ThaliTest[3008:5841789] THEMultipeerManager initialized peer 5401A4DE-2020-4411-800F-72E067EDFF0D:8
2016-04-08 09:35:41.516 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-08 09:35:41.517 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-08 09:35:41.519 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements: success
,ok 176 Can call startListeningForAdvertisements without error
,2016-04-08 09:35:41.525 ThaliTest[3008:5841634] client: found new peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7","pleaseConnect":0}]
,2016-04-08 09:35:41.530 ThaliTest[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,2016-04-08 09:35:41.531 ThaliTest[3008:5841789] client: server will connect
,2016-04-08 09:35:41.532 ThaliTest[3008:5841789] client session: reverseConnect
,2016-04-08 09:35:41.532 ThaliTest[3008:5841789] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
,2016-04-08 09:35:43.562 ThaliTest[3008:5841634] client: found new peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C76D48A2-6720-4997-B51C-ADA808AA0AC0:8","pleaseConnect":0}]
,2016-04-08 09:35:43.777 ThaliTest[3008:5841634] client: found new peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B29A2A64-B1EF-4545-BC19-F0DD94E05227:8","pleaseConnect":0}]
,2016-04-08 09:35:43.831 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:35:43.831 ThaliTest[3008:5841634] server session: connect
2016-04-08 09:35:43.831 ThaliTest[3008:5841634] server session: stateChange:0->1 9D491E36-B0DA-4A12-9CC,8-423B0B7AB3BC:8
2016-04-08 09:35:43.835 ThaliTest[3008:5841634] server: accepting invitation 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:35:43.844 ThaliTest[3008:5842620] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-,04-08 09:35:43.844 ThaliTest[3008:5842620] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:35:43.844 ThaliTest[3008:5842620] client session: disconnect
2016-04-08 09:35:43.847 ThaliTest[3008:5842620] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:7
2016-04-08 09:35:43.848 ThaliTest[3008:5842620] client session: no connect callback (server initiated)
,2016-04-08 09:35:46.406 ThaliTest[3008:5842646] server session: p2p link connected
,2016-04-08 09:35:46.439 ThaliTest[3008:5841634] server relay: connected (to port: 60954)
2016-04-08 09:35:46.440 ThaliTest[3008:5841634] server session: stateChange:1->2 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:35:46.440 ThaliTest[3008:584163,4] jxcore: connect: success
INFO testThaliMobileNative: 
ok 177 Must have listeningPort
ok 178 listeningPort must be a number
ok 179 Connection must have clientPort
ok 180 clientPort must be a number
ok 181 Connection must have serverPort
ok 182 ser,verPort must be a number
ok 183 reverse connection must have clientPort != 0
ok 184 reverse connection must have serverPort != 0
,# teardown
,2016-04-08 09:35:49.131 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:35:49.131 ThaliTest[3008:5841634] server session: connect
2016-04-08 09:35:49.131 ThaliTest[3008:5841634] server session: stateChange:0->1 C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:35:49.136 ThaliTest[3008:5841634] server: accepting invitation C76D48A2-6720-4997-B51C-ADA808AA0AC0
,2016-04-08 09:35:52.181 ThaliTest[3008:5842634] server session: p2p link connected
,2016-04-08 09:35:52.225 ThaliTest[3008:5841634] server relay: connected (to port: 60954)
,2016-04-08 09:35:52.225 ThaliTest[3008:5841634] server session: stateChange:1->2 C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
,2016-04-08 09:36:01.517 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:36:01.533 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:01.533 ThaliTest[3008:5841634] client: found updated peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:01.534 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8","pleaseConnect":0}]
,2016-04-08 09:36:14.049 ThaliTest[3008:5842634] server session: not connected C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
,2016-04-08 09:36:14.512 ThaliTest[3008:5841634] server relay: socket disconnected
2016-04-08 09:36:14.513 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements
2016-04-08 09:36:14.513 ThaliTest[3008:5841634] server relay: 0x19f577b0 disconnected, with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"disc,overyActive":false}
2016-04-08 09:36:14.514 ThaliTest[3008:5841789] jxcore: stopListeningForAdvertisements: success
ok 185 Should be able to call stopListeningForAdvertisements in teardown
2016-04-08 09:36:14.514 ThaliTest[3008:5841789] jxcore: stopAdve,rtisingAndListening
2016-04-08 09:36:14.514 ThaliTest[3008:5841789] THEMultipeerManager stopping peer
2016-04-08 09:36:14.515 ThaliTest[3008:5841789] server session: disconnect
2016-04-08 09:36:14.515 ThaliTest[3008:5841634] server relay: socket discon,nected
2016-04-08 09:36:14.515 ThaliTest[3008:5841789] server session: stateChange:2->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:14.518 ThaliTest[3008:5841634] server relay: 0x19e5a590 disconnected with error Error Domain=GCDAsyncSocketErr,orDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-04-08 09:36:14.525 ThaliTest[3008:5841789] server session: disconnect
2016-04-08 09:36:14.525 ThaliTest[3008:5841789] server session: stateChange:2->0 C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
,2016-04-08 09:36:14.531 ThaliTest[3008:5841789] multipeer manager: stop client timer
2016-04-08 09:36:14.537 ThaliTest[3008:5841789] jxcore: stopAdvertisingAndListening: success
ok 186 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-08 09:36:17.473 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening
2016-04-08 09:36:17.473 ThaliTest[3008:5841789] server: starting 5401A4DE-2020-4411-800F-72E067EDFF0D:9
2016-04-08 09:36:17.473 ThaliTest[3008:5841789] multipeer m,anager: start client restart timer: 0x17ea86e0
2016-04-08 09:36:17.473 ThaliTest[3008:5841789] THEMultipeerManager initialized peer 5401A4DE-2020-4411-800F-72E067EDFF0D:9
,2016-04-08 09:36:17.477 ThaliTest[3008:5841789] jxcore: startUpdateAdvertisingAndListening: success
ok 187 Can call startUpdateAdvertisingAndListening without error
2016-04-08 09:36:17.478 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-08 09:36:17.478 ThaliTest[3008:5841789] jxcore: startListeningForAdvertisements: success
ok 188 Can call startListeningForAdvertisements without error
,2016-04-08 09:36:18.519 ThaliTest[3008:5841634] client: found new peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:18.520 ThaliTest[3008:5841634] client: found new peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
2016-04-08 09:36:18.520 ThaliTes,t[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:18.521 ThaliTest[3008:5841789] client: server will connect
2016-04-08 09:36:18.521 ThaliTest[3008:5841789] client session: reverseConnect
2016-04-08 09:36:18.521 Tha,liTest[3008:5841789] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:36:18.708 ThaliTest[3008:5841634] client: lost peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0
2016-04-08 09:36:18.709 ThaliTest[3008:5841634] client session: onPeerLost: C76D48A2-6720-4997-B51C-ADA808AA0AC0
,2016-04-08 09:36:19.760 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:8
,2016-04-08 09:36:19.763 ThaliTest[3008:5841634] client: found new peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:8
,2016-04-08 09:36:19.775 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:36:19.775 ThaliTest[3008:5841634] server: rejecting invitation from C76D48A2-6720-4997-B51C-ADA808AA0AC0 due to previous generation (5401A4DE-2020-4411-800F-72E06,7EDFF0D:9 != 5401A4DE-2020-4411-800F-72E067EDFF0D:8)
,2016-04-08 09:36:20.140 ThaliTest[3008:5842758] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:20.140 ThaliTest[3008:5842758] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:36:20.140 ThaliTest[3008:5842758] client session: disconnect
2016-04-08 09:36:20.140 ThaliTest[3008:5842758] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:36:20.143 ThaliTest[3008:5842758] client session: no connect callback (server initiated)
,2016-04-08 09:36:23.080 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:36:23.080 ThaliTest[3008:5841634] server: disconnecting to refresh session (C76D48A2-6720-4997-B51C-ADA808AA0AC0)
2016-04-08 09:36:23.080 ThaliTest[3008:5841634], server: rejecting invitation from C76D48A2-6720-4997-B51C-ADA808AA0AC0 due to previous generation (5401A4DE-2020-4411-800F-72E067EDFF0D:9 != 5401A4DE-2020-4411-800F-72E067EDFF0D:8)
,2016-04-08 09:36:27.151 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:36:27.151 ThaliTest[3008:5841634] server: disconnecting to refresh session (C76D48A2-6720-4997-B51C-ADA808AA0AC0)
2016-04-08 09:36:27.151 ThaliTest[3008:5841634], server: rejecting invitation from C76D48A2-6720-4997-B51C-ADA808AA0AC0 due to previous generation (5401A4DE-2020-4411-800F-72E067EDFF0D:9 != 5401A4DE-2020-4411-800F-72E067EDFF0D:8)
,2016-04-08 09:36:28.522 ThaliTest[3008:5841634] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-08 09:36:30.329 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:36:30.329 ThaliTest[3008:5841634] server: disconnecting to refresh session (C76D48A2-6720-4997-B51C-ADA808AA0AC0)
2016-04-08 09:36:30.329 ThaliTest[3008:5841634], server: rejecting invitation from C76D48A2-6720-4997-B51C-ADA808AA0AC0 due to previous generation (5401A4DE-2020-4411-800F-72E067EDFF0D:9 != 5401A4DE-2020-4411-800F-72E067EDFF0D:8)
,2016-04-08 09:36:31.531 ThaliTest[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:31.532 ThaliTest[3008:5841789] client: server will connect
2016-04-08 09:36:31.532 ThaliTest[3008:5841789] client session: reverseConn,ect
2016-04-08 09:36:31.532 ThaliTest[3008:5841789] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
,2016-04-08 09:36:33.442 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:36:33.442 ThaliTest[3008:5841634] server: disconnecting to refresh session (C76D48A2-6720-4997-B51C-ADA808AA0AC0)
2016-04-08 09:36:33.443 ThaliTest[3008:5841634] server: rejecting invitation from C76D48A2-6720-4997-B51C-ADA808AA0AC0 due to previous generation (5401A4DE-2020-4411-800F-72E067EDFF0D:9 != 5401A4DE-2020-4411-800F-72E067EDFF0D:8)
,2016-04-08 09:36:33.519 ThaliTest[3008:5842755] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:33.520 ThaliTest[3008:5842755] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:36:33.5,20 ThaliTest[3008:5842755] client session: disconnect
2016-04-08 09:36:33.520 ThaliTest[3008:5842755] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:33.520 ThaliTest[3008:5842755] client session: no connect callback (server initiated)
,2016-04-08 09:36:36.636 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:36:36.637 ThaliTest[3008:5841634] server: disconnecting to refresh session (C76D48A2-6720-4997-B51C-ADA808AA0AC0)
2016-04-08 09:36:36.637 ThaliTest[3008:5841634] server: rejecting invitation from C76D48A2-6720-4997-B51C-ADA808AA0AC0 due to previous generation (5401A4DE-2020-4411-800F-72E067EDFF0D:9 != 5401A4DE-2020-4411-800F-72E067EDFF0D:8)
,2016-04-08 09:36:37.474 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:36:37.488 ThaliTest[3008:5841634] client: found updated peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:37.489 ThaliTest[3008:5841634] client: found updated peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:36:37.489 ThaliTest[3008:5841634] client: found updated peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:36:39.790 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:36:39.790 ThaliTest[3008:5841634] server: disconnecting to refresh session (C76D48A2-6720-4997-B51C-ADA808AA0AC0)
2016-04-08 09:36:39.790 ThaliTest[3008:5841634] server: rejecting invitation from C76D48A2-6720-4997-B51C-ADA808AA0AC0 due to previous generation (5401A4DE-2020-4411-800F-72E067EDFF0D:9 != 5401A4DE-2020-4411-800F-72E067EDFF0D:8)
,2016-04-08 09:36:41.533 ThaliTest[3008:5841634] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-08 09:36:42.876 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:36:42.876 ThaliTest[3008:5841634] server: disconnecting to refresh session (C76D48A2-6720-4997-B51C-ADA808AA0AC0)
2016-04-08 09:36:42.876 ThaliTest[3008:5841634] server: rejecting invitation from C76D48A2-6720-4997-B51C-ADA808AA0AC0 due to previous generation (5401A4DE-2020-4411-800F-72E067EDFF0D:9 != 5401A4DE-2020-4411-800F-72E067EDFF0D:8)
,2016-04-08 09:36:44.537 ThaliTest[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:44.537 ThaliTest[3008:5841789] client: server will connect
2016-04-08 09:36:44.537 ThaliTest[3008:5841789] client session: reverseConn,ect
,2016-04-08 09:36:44.537 ThaliTest[3008:5841789] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:36:46.065 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:36:46.066 ThaliTest[3008:5841634] server: disconnecting to refresh session (C76D48A2-6720-4997-B51C-ADA808AA0AC0)
2016-04-08 09:36:46.066 ThaliTest[3008:5841634] server: rejecting invitation from C76D48A2-6720-4997-B51C-ADA808AA0AC0 due to previous generation (5401A4DE-2020-4411-800F-72E067EDFF0D:9 != 5401A4DE-2020-4411-800F-72E067EDFF0D:8)
,2016-04-08 09:36:46.098 ThaliTest[3008:5842760] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:36:46.098 ThaliTest[3008:5842760] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:36:46.099 ThaliTest[3008:5842760] client session: disconnect
2016-04-08 09:36:46.099 ThaliTest[3008:5842760] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:36:46.100 ThaliTest[3008:5842760] client session: no connect callback (server initiated)
,2016-04-08 09:36:49.180 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:36:49.180 ThaliTest[3008:5841634] server: disconnecting to refresh session (C76D48A2-6720-4997-B51C-ADA808AA0AC0)
2016-04-08 09:36:49.180 ThaliTest[3008:5841634] server: rejecting invitation from C76D48A2-6720-4997-B51C-ADA808AA0AC0 due to previous generation (5401A4DE-2020-4411-800F-72E067EDFF0D:9 != 5401A4DE-2020-4411-800F-72E067EDFF0D:8)
,2016-04-08 09:36:54.538 ThaliTest[3008:5841634] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-08 09:36:57.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:36:57.489 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:36:57.490 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:36:57.490 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:36:57.546 ThaliTest[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:36:57.547 ThaliTest[3008:5841789] client: server will connect
2016-04-08 09:36:57.547 ThaliTest[3008:5841789] client session: reverseConn,ect
2016-04-08 09:36:57.547 ThaliTest[3008:5841789] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:00.843 ThaliTest[3008:5842861] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:37:00.843 ThaliTest[3008:5842861] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:37:00.843 ThaliTest[3008:5842861] client session: disconnect
2016-04-08 09:37:00.844 ThaliTest[3008:5842861] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:37:00.844 ThaliTest[3008:5842861] client session: no connect callback (server initiated)
,2016-04-08 09:37:07.548 ThaliTest[3008:5841634] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-08 09:37:10.560 ThaliTest[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:10.560 ThaliTest[3008:5841789] client: server will connect
2016-04-08 09:37:10.560 ThaliTest[3008:5841789] client session: reverseConnect
2016-04-08 09:37:10.560 ThaliTest[3008:5841789] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:12.412 ThaliTest[3008:5842760] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:37:12.413 ThaliTest[3008:5842760] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:37:12.4,14 ThaliTest[3008:5842760] client session: disconnect
2016-04-08 09:37:12.414 ThaliTest[3008:5842760] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:37:12.414 ThaliTest[3008:5842760] client session: no connect callb,ack (server initiated)
,2016-04-08 09:37:17.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:37:17.490 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:17.490 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:37:17.49,0 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:20.561 ThaliTest[3008:5841634] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-08 09:37:23.564 ThaliTest[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:23.564 ThaliTest[3008:5841789] client: server will connect
2016-04-08 09:37:23.565 ThaliTest[3008:5841789] client session: reverseConnect
2016-04-08 09:37:23.565 ThaliTest[3008:5841789] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:25.787 ThaliTest[3008:5842940] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:37:25.787 ThaliTest[3008:5842940] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:37:25.7,87 ThaliTest[3008:5842940] client session: disconnect
2016-04-08 09:37:25.787 ThaliTest[3008:5842940] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:37:25.787 ThaliTest[3008:5842940] client session: no connect callback (server initiated)
,2016-04-08 09:37:33.566 ThaliTest[3008:5841634] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-08 09:37:36.567 ThaliTest[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:36.567 ThaliTest[3008:5841789] client: server will connect
2016-04-08 09:37:36.567 ThaliTest[3008:5841789] client session: reverseConnect
2016-04-08 09:37:36.567 ThaliTest[3008:5841789] client session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:37.474 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:37:37.497 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:37.497 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:37:37.497 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:37:46.568 ThaliTest[3008:5841634] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-08 09:37:49.571 ThaliTest[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:49.572 ThaliTest[3008:5841789] client: already connect(ing/ed) to 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:49.572 Thali,Test[3008:5841789] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-08 09:37:52.582 ThaliTest[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:52.582 ThaliTest[3008:5841789] client: already connect(ing/ed) to 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:52.582 ThaliTest[3008:5841789] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-08 09:37:55.589 ThaliTest[3008:5841789] jxcore: connect 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:55.589 ThaliTest[3008:5841789] client: already connect(ing/ed) to 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:8
2016-04-08 09:37:55.589 ThaliTest[3008:5841789] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,2016-04-08 09:37:57.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:37:57.491 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:37:57.491 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:37:57.492 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:38:09.539 ThaliTest[3008:5843018] client session: not connected 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:09.539 ThaliTest[3008:5843018] client session: onLinkFailure: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
2016-04-08 09:38:09.5,39 ThaliTest[3008:5843018] client session: disconnect
2016-04-08 09:38:09.540 ThaliTest[3008:5843018] client session: stateChange:1->0 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:09.540 ThaliTest[3008:5843018] client session: no connect callb,ack (server initiated)
,2016-04-08 09:38:17.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:38:17.492 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:17.492 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:38:17.492 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:38:37.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:38:37.490 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:37.490 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:38:37.490 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:38:57.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:38:57.490 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:38:57.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:38:57.491 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:39:17.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:39:17.489 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:39:17.491 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:39:17.491 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:39:37.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:39:37.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:39:37.491 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:39:37.491 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:39:53.859 ThaliTest[3008:5841634] multipeer session: reset timer
2016-04-08 09:39:53.859 ThaliTest[3008:5841634] server session: connect
2016-04-08 09:39:53.859 ThaliTest[3008:5841634] server session: stateChange:0->1 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:39:53.864 ThaliTest[3008:5841634] server: accepting invitation 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC
,2016-04-08 09:39:55.409 ThaliTest[3008:5843372] server session: p2p link connected
,2016-04-08 09:39:55.805 ThaliTest[3008:5841634] server relay: connected (to port: 60962)
,2016-04-08 09:39:55.806 ThaliTest[3008:5841634] server session: stateChange:1->2 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:39:57.474 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:39:57.490 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:39:57.490 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:39:57.490 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:40:17.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:40:17.490 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:40:17.490 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:40:17.490 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:40:37.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:40:37.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:40:37.492 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:40:37.492 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:40:57.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:40:57.490 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:40:57.490 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:40:57.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:41:17.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:41:17.490 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:41:17.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:41:17.492 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:41:37.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:41:37.490 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:41:37.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:41:37.49,1 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:41:57.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:41:57.491 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:41:57.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:41:57.495 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:42:17.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:42:17.491 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:42:17.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:42:17.491 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:42:37.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:42:37.497 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:42:37.500 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:42:37.500 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:42:57.474 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:42:57.490 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:42:57.491 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:42:57.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:43:17.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:43:17.496 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:43:17.496 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:43:17.49,6 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:43:37.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:43:37.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:43:37.492 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:43:37.49,2 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:43:57.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:43:57.492 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:43:57.492 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:43:57.493 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:44:17.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:44:17.490 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:44:17.491 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:44:17.491 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:44:37.475 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:44:37.491 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:44:37.491 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:44:37.492 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:44:57.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:44:57.471 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:44:57.471 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:44:57.47,2 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:45:17.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:45:17.473 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:45:17.473 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:45:17.473 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:45:37.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:45:37.472 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:45:37.472 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:45:37.476 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:45:57.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:45:57.479 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:45:57.479 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:45:57.480 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:46:17.455 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:46:17.471 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:46:17.471 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:46:17.475 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:46:37.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:46:57.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:46:57.473 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:46:57.473 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:46:57.47,4 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:47:17.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:47:17.472 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:47:17.473 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:47:17.47,3 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:47:37.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:47:37.472 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:47:37.473 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:47:37.47,3 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:47:57.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:47:57.472 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:47:57.472 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:47:57.47,2 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:48:17.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:48:17.480 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:48:17.480 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:48:17.481 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:48:37.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:48:37.479 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:48:37.479 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:48:37.48,0 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:48:57.455 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:48:57.473 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:48:57.473 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:48:57.474 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:49:17.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:49:17.474 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:49:17.475 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:49:17.476 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:49:37.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:49:37.471 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:49:37.472 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:49:37.472 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
,2016-04-08 09:49:57.455 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:49:57.472 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:49:57.472 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:49:57.472 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:50:17.455 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:50:17.474 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:50:17.474 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:50:17.475 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:50:37.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:50:37.474 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:50:37.474 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:50:37.474 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
,2016-04-08 09:50:57.456 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:50:57.472 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:50:57.473 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9
2016-04-08 09:50:57.473 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
,2016-04-08 09:51:17.455 ThaliTest[3008:5841634] multipeer manager: restart client
,2016-04-08 09:51:17.472 ThaliTest[3008:5841634] client: found existing peer: 9D491E36-B0DA-4A12-9CC8-423B0B7AB3BC:9
2016-04-08 09:51:17.472 ThaliTest[3008:5841634] client: found existing peer: B29A2A64-B1EF-4545-BC19-F0DD94E05227:9
2016-04-08 09:51:17.472 ThaliTest[3008:5841634] client: found existing peer: C76D48A2-6720-4997-B51C-ADA808AA0AC0:9

```
