#### Test 65745020fc66909_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/65745020fc66909/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/CE4C9AA2-8083-4E0A-946E-18046D316F39/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CE4C9AA2-8083-4E0A-946E-18046D316F39/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/65745020fc66909/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/65745020fc66909/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52048"
,(lldb)     command script import "/tmp/CE4C9AA2-8083-4E0A-946E-18046D316F39/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-08 10:08:48.828 ThaliTest[3020:5848042] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4C542692-B234-4400-BA7C-FD5B1F30F9EA/Library/Cookies/Cookies.binarycookies
,2016-04-08 10:08:49.075 ThaliTest[3020:5848042] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-08 10:08:49.076 ThaliTest[3020:5848042] Multi-tasking -> Device: YES, App: YES
,2016-04-08 10:08:49.094 ThaliTest[3020:5848042] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-08 10:08:49.872 ThaliTest[3020:5848042] Using UIWebView
,2016-04-08 10:08:49.876 ThaliTest[3020:5848042] [CDVTimer][handleopenurl] 0.179052ms
,2016-04-08 10:08:49.879 ThaliTest[3020:5848042] [CDVTimer][intentandnavigationfilter] 2.799988ms
2016-04-08 10:08:49.880 ThaliTest[3020:5848042] [CDVTimer][gesturehandler] 0.124037ms
2016-04-08 10:08:49.880 ThaliTest[3020:5848042] [CDVTimer][TotalPluginStartup] 3.750026ms
,2016-04-08 10:08:52.969 ThaliTest[3020:5848042] Resetting plugins due to page load.
,2016-04-08 10:08:54.209 ThaliTest[3020:5848042] Finished load of: file:///var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/index.html
,2016-04-08 10:08:54.399 ThaliTest[3020:5848042] JXcore Cordova plugin initializing
,2016-04-08 10:08:54.401 ThaliTest[3020:5848194] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-08 10:09:02.826 ThaliTest[3020:5848194] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-08 10:09:02.826 ThaliTest[3020:5848194] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-08 10:09:02.826 ThaliTest[3020:5848194] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-08 10:09:02.830 ThaliTest[3020:5848194] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1606E7DC-A552-4EEC-8176-5F1DFC43A191/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 61043
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 61045
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
,DEBUG createNativeListener: listening 61048
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
,DEBUG createNativeListener: listening 61052
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 61057
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
,DEBUG createNativeListener: listening 61061
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 61065
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
DEBUG createNativeListener: listening 61069
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
ok 26 The mux object should be closed,
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 61073
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
D,EBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 61125
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
,DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 61129
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,ok 69 firstPromise - in catch
ok 70 third
ok 71 thirdPromise - in then
ok 72 testingPromises
# teardown
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
,[{"uuid":"954a9fdb-faef-45fa-8c4a-e2bfb48a901a","data":"custom data"},{"uuid":"310bd762-5c41-4013-ba98-1cdb5e69f42c","data":"custom data"},{"uuid":"81db905b-3019-4407-af41-b12970730dfa","data":"custom data"},{"uuid":"11a5596c-0abf-49aa-b899-484cc8fc4f8f",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83, participant data matches
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
DEBUG createNativeListener: listening 61139
2016-04-08 10:11:50.986 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 10:11:50.987 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-08 10:11:50.989 ThaliTest[3020:5848194] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 10:11:50.989 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements: succes,s
,ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-08 10:11:51.319 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening
2016-04-08 10:11:51.319 ThaliTest[3020:5848194] THEMultipeerManager stopping peer
2016-04-08 10:11:51.319 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 10:11:51.319 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 10:11:51.320 ThaliTest[3020,:5848194] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 61141
2016-04-08 10:11:54.988 ThaliTest[3020:5848194] jxcore: startListeningForAdvertisements
,2016-04-08 10:11:54.990 ThaliTest[3020:5848194] multipeer manager: start client restart timer: 0x175fae80
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 10:11:54.991 ThaliTest[3020:5848194] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-08 10:11:55.004 ThaliTest[3020:5848194] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-08 10:11:55.006 ThaliTest[3020:5848194] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-08 10:12:14.990 ThaliTest[3020:5848042] multipeer manager: restart client
,2016-04-08 10:12:34.741 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening
2016-04-08 10:12:34.741 ThaliTest[3020:5848194] THEMultipeerManager stopping peer
2016-04-08 10:12:34.742 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 10:12:34.742 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements
2016-04-08 10:12:34.742 ThaliTest[3020:5848194] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-08 10:12:34.743 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 61144
2016-04-08 10:14:03.143 ThaliTest[3020:5848194] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 10:14:03.143 ThaliTest[3020:5848194] server: starting 09D76348-A147-4FF6-84B4-6DA72A5C4602:1
2016-04-08 10:14:03.144 ThaliTest[3020:5848194] multipeer manager: start client restart timer: 0x175fae80
2016-04-08 10:14:03.144 ThaliTest[3020:58481,94] THEMultipeerManager initialized peer 09D76348-A147-4FF6-84B4-6DA72A5C4602:1
2016-04-08 10:14:03.144 ThaliTest[3020:5848194] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-08 10:14:03.162 ThaliTest[3020:5848194] jxcore: startUpdateAdvertisingAndListening
,2016-04-08 10:14:03.164 ThaliTest[3020:5848194] THEMultipeerManager stopping peer
,2016-04-08 10:14:03.168 ThaliTest[3020:5848194] multipeer manager: stop client timer
,2016-04-08 10:14:03.169 ThaliTest[3020:5848194] server: starting 09D76348-A147-4FF6-84B4-6DA72A5C4602:2
,2016-04-08 10:14:03.173 ThaliTest[3020:5848194] multipeer manager: start client restart timer: 0x175fae80
,2016-04-08 10:14:03.177 ThaliTest[3020:5848194] THEMultipeerManager initialized peer 09D76348-A147-4FF6-84B4-6DA72A5C4602:2
,2016-04-08 10:14:03.179 ThaliTest[3020:5848194] jxcore: startUpdateAdvertisingAndListening: success
,2016-04-08 10:14:03.182 ThaliTest[3020:5848042] client: found new peer: 33B8A67F-CB3A-4E1D-BE92-04CE29FBE967:2
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-08 10:14:06.001 ThaliTest[3020:5848042] client: found new peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:2
,2016-04-08 10:14:11.215 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening
2016-04-08 10:14:11.215 ThaliTest[3020:5848194] THEMultipeerManager stopping peer
2016-04-08 10:14:11.215 ThaliTest[3020:5848194] multipeer manager: stop client timer
20,16-04-08 10:14:11.216 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening: success
2016-04-08 10:14:11.216 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-08 10:14:11.217 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 61149
2016-04-08 10:14:28.307 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening
2016-04-08 10:14:28.308 ThaliTest[3020:5848194] THEMultipeerManager stoppi,ng peer
2016-04-08 10:14:28.308 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
2016-04-08 10:14:28.309 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening
2016-04-08, 10:14:28.309 ThaliTest[3020:5848194] THEMultipeerManager stopping peer
,2016-04-08 10:14:28.310 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-08 10:14:28.428 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening
2016-04-08 10:14:28.428 ThaliTest[3020:5848194] THEMultipeerManager stopping peer
2016-04-08 10:14:28.429 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 10:14:28.429 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 10:14:28.429 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 61151
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-08 10:14:28.892 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening
2016-04-08 10:14:28.892 ThaliTest[3020:5848194] THEMultipeerManager stopping peer
2016-04-08 10:14:28.892 ThaliTest[3020:5848194] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-08 10:14:28.892 ThaliTest[3020:5848194] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-08 10:14:28.893 ThaliTest[3020,:5848194] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 61153
,2016-04-08 10:14:29.079 ThaliTest[3020:5848194] jxcore: startListeningForAdvertisements
2016-04-08 10:14:29.080 ThaliTest[3020:5848194] multipeer manager: start client restart timer: 0x175fae80
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-08 10:14:29.081 ThaliTest[3020:5848194] jxcore: startListeningForAdvertisements: success
,2016-04-08 10:14:29.089 ThaliTest[3020:5848042] client: found new peer: 33B8A67F-CB3A-4E1D-BE92-04CE29FBE967:2
,2016-04-08 10:14:29.112 ThaliTest[3020:5848194] jxcore: startUpdateAdvertisingAndListening

```
