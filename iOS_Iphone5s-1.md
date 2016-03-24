#### Test 639107046ed3de5_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/30662A69-67CB-4480-95FE-43D67E124DF6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/30662A69-67CB-4480-95FE-43D67E124DF6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55676"
,(lldb)     command script import "/tmp/30662A69-67CB-4480-95FE-43D67E124DF6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 16:43:25.922 ThaliTest[2145:3752542] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/247356F0-6C83-49A1-8BEA-B9A007BE9B1E/Library/Cookies/Cookies.binarycookies
,2016-03-24 16:43:26.179 ThaliTest[2145:3752542] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 16:43:26.180 ThaliTest[2145:3752542] Multi-tasking -> Device: YES, App: YES
,2016-03-24 16:43:26.199 ThaliTest[2145:3752542] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 16:43:27.010 ThaliTest[2145:3752542] Using UIWebView
,2016-03-24 16:43:27.014 ThaliTest[2145:3752542] [CDVTimer][handleopenurl] 0.174999ms
2016-03-24 16:43:27.017 ThaliTest[2145:3752542] [CDVTimer][intentandnavigationfilter] 2.613008ms
2016-03-24 16:43:27.018 ThaliTest[2145:3752542] [CDVTimer][gesturehandle,r] 0.119030ms
2016-03-24 16:43:27.018 ThaliTest[2145:3752542] [CDVTimer][TotalPluginStartup] 3.507972ms
,2016-03-24 16:43:30.245 ThaliTest[2145:3752542] Resetting plugins due to page load.
,2016-03-24 16:43:31.760 ThaliTest[2145:3752542] Finished load of: file:///var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/index.html
,2016-03-24 16:43:31.949 ThaliTest[2145:3752542] JXcore Cordova plugin initializing
2016-03-24 16:43:31.950 ThaliTest[2145:3752700] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 16:43:40.269 ThaliTest[2145:3752700] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 16:43:40.270 ThaliTest[2145:3752700] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-24 16:43:40.271 ThaliTest[2145:3752700] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:43:40.274 ThaliTest[2145:3752700] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1D82BEB-2BFE-41CB-ABF8-FC9C9A21BEC1/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52438
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52440
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
DEBUG createNativeListener: listening 52443
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
DEBUG createNativeListener: listening 52447
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: listening 52452
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52456
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
DEBUG createNativeListener: listening 52460
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
DEBUG createNativeListener: listening 52464
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
DEBUG createNativeListener: listening 52468
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incomi,ng socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incomin,g socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52520
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 52524
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
,ok 41 server should be open
,ok 42 incoming has been removed
,ok 43 The mux object should be closed
,ok 44 The mux stream should be closed
,# teardown
,# setup
,# 12. closeAll can close even when connections open
,ok 45 not possible to connect to the server anymore
,# teardown
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
ok 49 firstPromise result
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
,ok 63 testing promises
# teardown
,# setup
,# 17. mix enqueue and enqueueAtTop
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
,# teardown
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
DEBUG createNativeListener: listening 52536
2016-03-24 16:45:54.330 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:54.333 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
ok 88 error should be null
ok 89 error should be null
,2016-03-24 16:45:54.335 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:54.336 ThaliTest[2145:37527,00] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
# teardown
,2016-03-24 16:45:54.429 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:54.429 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:45:54.429 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:45:54.430 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:54.430 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52538
2016-03-24 16:45:54.799 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
2016-03-24 16:45:54.800 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:45:54.801 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
2016-03-24 16:45:54.846 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:45:54.847 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# teardown
,2016-03-24 16:45:55.637 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:55.637 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:45:55.637 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:45:55.637 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
2016-03-24 16:45:55.637 ThaliTest[2145:3752700] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:55.638 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52540
2016-03-24 16:45:57.589 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:45:57.590 ThaliTest[2145:3752700] server: starting 5F,451984-F7B7-4F39-B182-72023C9FD000:1
,2016-03-24 16:45:57.591 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
2016-03-24 16:45:57.591 ThaliTest[2145:3752700] THEMultipeerManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:1
2016-03-24 16:45:57.591 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
2016-03-24 16:45:57.627 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:45:57.627 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:45:57.627, ThaliTest[2145:3752700] multipeer manager: stop client timer
2016-03-24 16:45:57.628 ThaliTest[2145:3752700] server: starting 5F451984-F7B7-4F39-B182-72023C9FD000:2
2016-03-24 16:45:57.628 ThaliTest[2145:3752700] multipeer manager: start client restart ,timer: 0x14ec0520
2016-03-24 16:45:57.628 ThaliTest[2145:3752700] THEMultipeerManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:2
2016-03-24 16:45:57.629 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
# teardown
,2016-03-24 16:45:59.225 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:59.225 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:45:59.225 ThaliTest[2145:3752700] multipeer manager: stop client timer
20,16-03-24 16:45:59.225 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:45:59.226 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:45:59.226 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 104 error should be null
ok 105 error should be null
# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52545
2016-03-24 16:45:59.937 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:59.937 ThaliTest[2145:3752700] THEMultipeerManager stoppi,ng peer
2016-03-24 16:45:59.937 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
ok 106 error should be null
ok 107 error should be null
2016-03-24 16:45:59.939 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:45:59.939 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:45:59.939 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
,ok 108 error should be null
ok 109 error should be null
# teardown
,2016-03-24 16:46:00.311 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:00.311 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:46:00.311 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:46:00.311 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:00.312 ThaliTest[2145,:3752700] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
ok 111 error should be null
# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52547
ok 112 first call should succeed
ok 113 first call should succeed
ok 114 specific error should be returned
# teardown
,2016-03-24 16:46:01.916 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:01.917 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:46:01.917 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:46:01.917 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:01.918 ThaliTest[2145,:3752700] jxcore: stopListeningForAdvertisements: success
ok 115 error should be null
ok 116 error should be null
# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52549
2016-03-24 16:46:03.052 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
2016-03-24 16:46:03.052 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:03.053 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements: success,
,2016-03-24 16:46:03.064 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:46:03.064 ThaliTest[2145:3752700] server: starting 5F451984-F7B7-4F39-B182-72023C9FD000:3
2016-03-24 16:46:03.064 ThaliTest[2145:3752700] THEMultipee,rManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:3
2016-03-24 16:46:03.065 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening: success
ok 117 called only once
ok 118 discovery state matches
ok 119 advertising state matches
,# teardown
,2016-03-24 16:46:03.245 ThaliTest[2145:3752542] client: found new peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:3
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,2016-03-24 16:46:03.374 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:03.375 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:46:03.375 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:46:03.375 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
2016-03-24 16:46:03.375 ThaliTest[2145:3752700] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:03.376 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 120 error should be null
ok 121 error should be null
# setup
,# 30. does not send duplicate availability changes
,ok 122 should be called once
ok 123 should not have been called more than once
# teardown
,ok 124 error should be null
ok 125 error should be null
# setup
,# 31. can get the network status
,ok 126 network status should have certain non-empty properties
# teardown
,ok 127 error should be null
,ok 128 error should be null
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
ok 134 error should be null
# setup
,# 33. Can call start/stopListeningForAdvertisements
,2016-03-24 16:46:33.473 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
2016-03-24 16:46:33.474 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:33.475 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements: success
ok 135 Can call startListeningForAdvertisements without error
2016-03-24 16:46:33.475 ThaliTes,t[2145:3752700] jxcore: stopListeningForAdvertisements
2016-03-24 16:46:33.476 ThaliTest[2145:3752700] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:33.476 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-24 16:46:33.737 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:33.738 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 16:46:33.739 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:33.739 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:46:33.739 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 16:46:34.256 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
2016-03-24 16:46:34.257 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:34.258 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-24 16:46:34.258 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:46:34.259 ThaliTest[2145:3752700] jxcore: startListeningForAdv,ertisements: success
ok 140 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 16:46:34.436 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
2016-03-24 16:46:34.436 ThaliTest[2145:3752700] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:46:34.437 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:46:34.438 ThaliTest[2145:37527,00] jxcore: stopAdvertisingAndListening
2016-03-24 16:46:34.438 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:46:34.438 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 16:47:28.308 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:47:28.308 ThaliTest[2145:3752700] server: starting 5F451984-F7B7-4F39-B182-72023C9FD000:4
2016-03-24 16:47:28.309 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
2016-03-24 16:47:28.309 ThaliTest[2145:3752700] THEMultipeerManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:4
2016-03-24 16:47:28.309 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-24 16:47:28.310 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:47:28.310 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:47:28.310 ThaliTest[2145:3752700] multipeer manager: stop client timer
2016-03-24 16:47:28.311 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-24 16:47:29.391 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:47:29.391 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:47:29.392 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:47:29.392 ThaliTest[2145:375270,0] THEMultipeerManager stopping peer
2016-03-24 16:47:29.392 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-24 16:48:21.163 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:21.164 ThaliTest[2145:3752700] server: starting 5F451984-F7B7-4F39-B182-72023C9FD000:5
2016-03-24 16:48:21.164 ThaliTest[2145:3752700] multipeer m,anager: start client restart timer: 0x14ec0520
2016-03-24 16:48:21.164 ThaliTest[2145:3752700] THEMultipeerManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:5
2016-03-24 16:48:21.165 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-24 16:48:21.166 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:21.166 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:48:21.166 ThaliTest[2145:3752700] multipeer manager: stop client timer
2016-03-24 16:48:21.166 ThaliTest[2145:3752700] server: starting 5F451984-F7B7-4F39-B182-72023C9FD000:6
,2016-03-24 16:48:21.167 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
,2016-03-24 16:48:21.167 ThaliTest[2145:3752700] THEMultipeerManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:6
2016-03-24 16:48:21.168 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-24 16:48:21.321 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:48:21.322 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
ok 149 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 16:48:21.322 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:48:21.322 ThaliTest[2145:3752700,] THEMultipeerManager stopping peer
2016-03-24 16:48:21.322 ThaliTest[2145:3752700] multipeer manager: stop client timer
2016-03-24 16:48:21.323 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 37. peerAvailabilityChange is called
,2016-03-24 16:48:21.944 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:21.944 ThaliTest[2145:3752700] server: starting 5F451984-F7B7-4F39-B182-72023C9FD000:7
2016-03-24 16:48:21.944 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
2016-03-24 16:48:21.944 ThaliTest[2145:3752700] THEMultipeerManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:7
2016-03-24 16:48:21.944 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-24 16:48:21.945 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-24 16:48:21.946 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements: success
ok 152 Can call startListeningForAdvertisements without error
,2016-03-24 16:48:23.347 ThaliTest[2145:3752542] client: found new peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
ok 153 peers must be an array
ok 154 peers must not be zero-length
ok 155 peer must have peerIdentifier
ok 156 peerIdentifier must be a string
ok 157 peer must have peerAvailable
ok 158 peer must have pleaseConnect
,# teardown
,2016-03-24 16:48:24.464 ThaliTest[2145:3752542] client: found new peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
,2016-03-24 16:48:38.718 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:48:38.719 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
,ok 159 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 16:48:38.720 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:48:38.721 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:48:38.721 ThaliTest[2145:3752700] multipeer manager: stop client timer
2016-03-24 16:48:38.721 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Can connect to a remote peer
,2016-03-24 16:48:39.454 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:48:39.454 ThaliTest[2145:3752700] server: starting 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:48:39.454 ThaliTest[2145:3752700] multipeer m,anager: start client restart timer: 0x14ec0520
2016-03-24 16:48:39.455 ThaliTest[2145:3752700] THEMultipeerManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:8
2016-03-24 16:48:39.455 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening: success
ok 161 Can call startUpdateAdvertisingAndListening without error
2016-03-24 16:48:39.456 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-24 16:48:39.457 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-24 16:48:40.075 ThaliTest[2145:3752542] client: found new peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:40.076 ThaliTest[2145:3752542] client: found new peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AE71735-F944-4906-BE1F-E88A7F36E6EE:7","pleaseConnect":0}]
2016-03-24 16:48:40.077 ThaliTest[2145:3752700] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:40.078 ThaliTest[2145:3752700] client session: connect
2016-03-24 16:48:40.078 ThaliTest[2145:3752700] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B8F5135C-E580-4A9F-90CD-0EB35830FF0E:7","pleaseConnect":0}]
,2016-03-24 16:48:41.856 ThaliTest[2145:3754225] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:41.857 ThaliTest[2145:3754225] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:41.8,57 ThaliTest[2145:3754225] client session: disconnect
2016-03-24 16:48:41.857 ThaliTest[2145:3754225] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:41.857 ThaliTest[2145:3754225] client session: fireConnectCallb,ack: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:41.857 ThaliTest[2145:3754225] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-24 16:48:44.871 ThaliTest[2145:3752700] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:44.872 ThaliTest[2145:3752700] client session: connect
2016-03-24 16:48:44.872 ThaliTest[2145:3752700] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,2016-03-24 16:48:44.940 ThaliTest[2145:3754226] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:44.942 ThaliTest[2145:3754226] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:44.942 ThaliTest[2145:3754226] client session: disconnect
2016-03-24 16:48:44.942 ThaliTest[2145:3754226] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:44.943 ThaliTest[2145:3754226] client session: fireConnectCallb,ack: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:44.943 ThaliTest[2145:3754226] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-24 16:48:47.953 ThaliTest[2145:3752700] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:47.954 ThaliTest[2145:3752700] client session: connect
2016-03-24 16:48:47.954 ThaliTest[2145:3752700] client session: stateChange:0->,1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,2016-03-24 16:48:48.084 ThaliTest[2145:3754227] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:48.085 ThaliTest[2145:3754227] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:48.085 ThaliTest[2145:3754227] client session: disconnect
2016-03-24 16:48:48.086 ThaliTest[2145:3754227] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:48.086 ThaliTest[2145:3754227] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:48.086 ThaliTest[2145:3754227] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-24 16:48:51.101 ThaliTest[2145:3752700] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:51.101 ThaliTest[2145:3752700] client session: connect
2016-03-24 16:48:51.102 ThaliTest[2145:3752700] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,2016-03-24 16:48:51.245 ThaliTest[2145:3754227] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:51.246 ThaliTest[2145:3754227] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:51.2,46 ThaliTest[2145:3754227] client session: disconnect
2016-03-24 16:48:51.246 ThaliTest[2145:3754227] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:51.247 ThaliTest[2145:3754227] client session: fireConnectCallb,ack: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:51.247 ThaliTest[2145:3754227] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-24 16:48:54.261 ThaliTest[2145:3752700] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:54.262 ThaliTest[2145:3752700] client session: connect
2016-03-24 16:48:54.262 ThaliTest[2145:3752700] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,2016-03-24 16:48:54.337 ThaliTest[2145:3754227] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:54.337 ThaliTest[2145:3754227] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:54.338 ThaliTest[2145:3754227] client session: disconnect
2016-03-24 16:48:54.338 ThaliTest[2145:3754227] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:54.338 ThaliTest[2145:3754227] client session: fireConnectCallb,ack: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:54.338 ThaliTest[2145:3754227] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-24 16:48:57.350 ThaliTest[2145:3752700] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:57.350 ThaliTest[2145:3752700] client session: connect
2016-03-24 16:48:57.350 ThaliTest[2145:3752700] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,2016-03-24 16:48:57.522 ThaliTest[2145:3754227] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:48:57.522 ThaliTest[2145:3754227] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:57.522 ThaliTest[2145:3754227] client session: disconnect
2016-03-24 16:48:57.523 ThaliTest[2145:3754227] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
,2016-03-24 16:48:57.524 ThaliTest[2145:3754227] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:48:57.524 ThaliTest[2145:3754227] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-24 16:48:59.456 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:48:59.467 ThaliTest[2145:3752542] client: found updated peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:48:59.468 ThaliTest[2145:3752542] client: found updated peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AE71735-F944-4906-BE1F-E88A7F36E6EE:8","pleaseConnect":0}]
,2016-03-24 16:49:00.526 ThaliTest[2145:3752700] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:49:00.526 ThaliTest[2145:3752700] client session: connect
2016-03-24 16:49:00.527 ThaliTest[2145:3752700] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:00.656 ThaliTest[2145:3754226] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:00.658 ThaliTest[2145:3754226] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:49:00.658 ThaliTest[2145:3754226] client session: disconnect
2016-03-24 16:49:00.658 ThaliTest[2145:3754226] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:49:00.658 ThaliTest[2145:3754226] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:49:00.658 ThaliTest[2145:3754226] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-24 16:49:03.661 ThaliTest[2145:3752700] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:49:03.661 ThaliTest[2145:3752700] client session: connect
2016-03-24 16:49:03.662 ThaliTest[2145:3752700] client session: stateChange:0->,1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:03.804 ThaliTest[2145:3754254] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:49:03.805 ThaliTest[2145:3754254] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:49:03.805 ThaliTest[2145:3754254] client session: disconnect
2016-03-24 16:49:03.805 ThaliTest[2145:3754254] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:49:03.806 ThaliTest[2145:3754254] client session: fireConnectCallb,ack: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:49:03.806 ThaliTest[2145:3754254] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-24 16:49:06.809 ThaliTest[2145:3752700] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:49:06.809 ThaliTest[2145:3752700] client session: connect
2016-03-24 16:49:06.809 ThaliTest[2145:3752700] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:06.948 ThaliTest[2145:3754254] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:49:06.948 ThaliTest[2145:3754254] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:49:06.949 ThaliTest[2145:3754254] client session: disconnect
2016-03-24 16:49:06.949 ThaliTest[2145:3754254] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:06.950 ThaliTest[2145:3754254] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:49:06.951 ThaliTest[2145:3754254] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-24 16:49:09.954 ThaliTest[2145:3752700] jxcore: connect 5AE71735-F944-4906-BE1F-E88A7F36E6EE:7
2016-03-24 16:49:09.954 ThaliTest[2145:3752700] client session: connect
2016-03-24 16:49:09.954 ThaliTest[2145:3752700] client session: stateChange:0->1 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:10.040 ThaliTest[2145:3754340] client session: not connected 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:49:10.040 ThaliTest[2145:3754340] client session: onLinkFailure: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:49:10.040 ThaliTest[2145:3754340] client session: disconnect
2016-03-24 16:49:10.040 ThaliTest[2145:3754340] client session: stateChange:1->0 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:10.041 ThaliTest[2145:3754340] client session: fireConnectCallback: 5AE71735-F944-4906-BE1F-E88A7F36E6EE
2016-03-24 16:49:10.042 ThaliTest[2145:3754340] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 163 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-24 16:49:19.455 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:49:19.468 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:49:19.468 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:39.456 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:49:39.468 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:49:39.473 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:49:59.456 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:49:59.468 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:49:59.469 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:50:19.456 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:50:19.472 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:50:19.473 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:50:39.455 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:50:39.467 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:50:39.468 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:50:59.456 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:50:59.468 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:50:59.468 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:51:19.456 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:51:19.467 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:51:19.468 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:51:39.456 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:51:39.472 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:51:39.473 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:51:59.456 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:51:59.469 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:51:59.470 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:19.456 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:52:19.472 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:52:19.473 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:52:29.353 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:52:29.354 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
,ok 164 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 16:52:29.356 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:52:29.356 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:52:29.356 ThaliTest[2145:3752700] multipeer manager: stop client timer
2016-03-24 16:52:29.356 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
ok 165 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can shift large amounts of data
,2016-03-24 16:52:31.657 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:52:31.657 ThaliTest[2145:3752700] server: starting 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:52:31.658 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
2016-03-24 16:52:31.658 ThaliTest[2145:3752700] THEMultipeerManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:9
2016-03-24 16:52:31.658 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening: success
ok 166 Can call startUpdateAdvertisingAndListening without error
2016-03-24 16:52:31.659 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-24 16:52:31.660 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements: success
ok 167 Can call startListeningForAdvertisements without error
,2016-03-24 16:52:31.672 ThaliTest[2145:3752542] client: found new peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:52:31.673 ThaliTest[2145:3752542] client: found new peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:31.674 ThaliTest[2145:3752700] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:52:31.674 ThaliTest[2145:3752700] client: server will connect
2016-03-24 16:52:31.675 ThaliTest[2145:3752700] client session: reverseConnect
2016-03-24 16:52:31.675 ThaliTest[2145:3752700] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:52:31.828 ThaliTest[2145:3754854] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:52:31.828 ThaliTest[2145:3754854] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:52:31.8,28 ThaliTest[2145:3754854] client session: disconnect
2016-03-24 16:52:31.829 ThaliTest[2145:3754854] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:52:31.831 ThaliTest[2145:3754854] client session: no connect callback (server initiated)
,2016-03-24 16:52:32.816 ThaliTest[2145:3752542] multipeer session: reset timer
2016-03-24 16:52:32.817 ThaliTest[2145:3752542] server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (5F451984-F7B7-4F39-B182-72023C9FD000:9 != 5F451984-F7B7-4F39-B182-72023C9FD000:8)
,2016-03-24 16:52:41.676 ThaliTest[2145:3752542] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-24 16:52:43.922 ThaliTest[2145:3752542] multipeer session: reset timer
2016-03-24 16:52:43.922 ThaliTest[2145:3752542] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:52:43.922 ThaliTest[2145:3752542], server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (5F451984-F7B7-4F39-B182-72023C9FD000:9 != 5F451984-F7B7-4F39-B182-72023C9FD000:8)
,2016-03-24 16:52:44.683 ThaliTest[2145:3752700] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:52:44.683 ThaliTest[2145:3752700] client: server will connect
2016-03-24 16:52:44.683 ThaliTest[2145:3752700] client session: reverseConnect
2016-03-24 16:52:44.684 ThaliTest[2145:3752700] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
,2016-03-24 16:52:44.943 ThaliTest[2145:3754855] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:52:44.943 ThaliTest[2145:3754855] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:52:44.9,43 ThaliTest[2145:3754855] client session: disconnect
2016-03-24 16:52:44.943 ThaliTest[2145:3754855] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:52:44.944 ThaliTest[2145:3754855] client session: no connect callback (server initiated)
,2016-03-24 16:52:51.659 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:52:51.670 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:52:51.670 ThaliTest[2145:3752542] client: found updated peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:52:54.684 ThaliTest[2145:3752542] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-24 16:52:57.064 ThaliTest[2145:3752542] multipeer session: reset timer
2016-03-24 16:52:57.064 ThaliTest[2145:3752542] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:52:57.065 ThaliTest[2145:3752542] server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (5F451984-F7B7-4F39-B182-72023C9FD000:9 != 5F451984-F7B7-4F39-B182-72023C9FD000:8)
,2016-03-24 16:52:57.696 ThaliTest[2145:3752700] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:52:57.696 ThaliTest[2145:3752700] client: server will connect
2016-03-24 16:52:57.697 ThaliTest[2145:3752700] client session: reverseConnect
2016-03-24 16:52:57.697 ThaliTest[2145:3752700] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:52:58.054 ThaliTest[2145:3754948] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:52:58.054 ThaliTest[2145:3754948] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:52:58.0,54 ThaliTest[2145:3754948] client session: disconnect
,2016-03-24 16:52:58.054 ThaliTest[2145:3754948] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:52:58.055 ThaliTest[2145:3754948] client session: no connect callback (server initiated)
,2016-03-24 16:53:07.698 ThaliTest[2145:3752542] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-24 16:53:10.226 ThaliTest[2145:3752542] multipeer session: reset timer
2016-03-24 16:53:10.226 ThaliTest[2145:3752542] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:53:10.227 ThaliTest[2145:3752542] server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (5F451984-F7B7-4F39-B182-72023C9FD000:9 != 5F451984-F7B7-4F39-B182-72023C9FD000:8)
,2016-03-24 16:53:10.704 ThaliTest[2145:3752700] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:53:10.704 ThaliTest[2145:3752700] client: server will connect
2016-03-24 16:53:10.704 ThaliTest[2145:3752700] client session: reverseConnect
2016-03-24 16:53:10.704 ThaliTest[2145:3752700] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:53:11.284 ThaliTest[2145:3754949] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:53:11.285 ThaliTest[2145:3754949] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:53:11.2,85 ThaliTest[2145:3754949] client session: disconnect
2016-03-24 16:53:11.285 ThaliTest[2145:3754949] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:53:11.286 ThaliTest[2145:3754949] client session: no connect callback (server initiated)
,2016-03-24 16:53:11.659 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:53:11.671 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:53:11.672 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:53:20.705 ThaliTest[2145:3752542] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-24 16:53:23.376 ThaliTest[2145:3752542] multipeer session: reset timer
2016-03-24 16:53:23.376 ThaliTest[2145:3752542] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:53:23.376 ThaliTest[2145:3752542], server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (5F451984-F7B7-4F39-B182-72023C9FD000:9 != 5F451984-F7B7-4F39-B182-72023C9FD000:8)
,2016-03-24 16:53:23.713 ThaliTest[2145:3752700] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:53:23.714 ThaliTest[2145:3752700] client: server will connect
2016-03-24 16:53:23.714 ThaliTest[2145:3752700] client session: reverseConnect
2016-03-24 16:53:23.714 ThaliTest[2145:3752700] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:53:23.793 ThaliTest[2145:3754949] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:53:23.793 ThaliTest[2145:3754949] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:53:23.793 ThaliTest[2145:3754949] client session: disconnect
2016-03-24 16:53:23.793 ThaliTest[2145:3754949] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:53:23.795 ThaliTest[2145:3754949] client session: no connect callback (server initiated)
,2016-03-24 16:53:31.659 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:53:31.670 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:53:31.671 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:53:33.715 ThaliTest[2145:3752542] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-24 16:53:36.436 ThaliTest[2145:3752542] multipeer session: reset timer
2016-03-24 16:53:36.436 ThaliTest[2145:3752542] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:53:36.437 ThaliTest[2145:3752542] server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (5F451984-F7B7-4F39-B182-72023C9FD000:9 != 5F451984-F7B7-4F39-B182-72023C9FD000:8)
,2016-03-24 16:53:36.721 ThaliTest[2145:3752700] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:53:36.722 ThaliTest[2145:3752700] client: server will connect
2016-03-24 16:53:36.722 ThaliTest[2145:3752700] client session: reverseConnect
2016-03-24 16:53:36.722 ThaliTest[2145:3752700] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:53:36.841 ThaliTest[2145:3755073] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:53:36.842 ThaliTest[2145:3755073] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:53:36.8,42 ThaliTest[2145:3755073] client session: disconnect
2016-03-24 16:53:36.842 ThaliTest[2145:3755073] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:53:36.843 ThaliTest[2145:3755073] client session: no connect callback (server initiated)
,2016-03-24 16:53:46.723 ThaliTest[2145:3752542] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-24 16:53:48.963 ThaliTest[2145:3752542] multipeer session: reset timer
2016-03-24 16:53:48.963 ThaliTest[2145:3752542] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:53:48.964 ThaliTest[2145:3752542] server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (5F451984-F7B7-4F39-B182-72023C9FD000:9 != 5F451984-F7B7-4F39-B182-72023C9FD000:8)
,2016-03-24 16:53:49.726 ThaliTest[2145:3752700] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:53:49.727 ThaliTest[2145:3752700] client: server will connect
2016-03-24 16:53:49.727 ThaliTest[2145:3752700] client session: reverseConnect
2016-03-24 16:53:49.727 ThaliTest[2145:3752700] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:53:50.011 ThaliTest[2145:3754949] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:53:50.012 ThaliTest[2145:3754949] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:53:50.012 ThaliTest[2145:3754949] client session: disconnect
2016-03-24 16:53:50.012 ThaliTest[2145:3754949] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:53:50.013 ThaliTest[2145:3754949] client session: no connect callback (server initiated)
,2016-03-24 16:53:51.659 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:53:51.671 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:53:51.672 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:53:59.728 ThaliTest[2145:3752542] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-24 16:54:02.132 ThaliTest[2145:3752542] multipeer session: reset timer
2016-03-24 16:54:02.132 ThaliTest[2145:3752542] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:54:02.133 ThaliTest[2145:3752542] server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (5F451984-F7B7-4F39-B182-72023C9FD000:9 != 5F451984-F7B7-4F39-B182-72023C9FD000:8)
,2016-03-24 16:54:02.739 ThaliTest[2145:3752700] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:54:02.739 ThaliTest[2145:3752700] client: server will connect
2016-03-24 16:54:02.739 ThaliTest[2145:3752700] client session: reverseConnect
2016-03-24 16:54:02.739 ThaliTest[2145:3752700] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:54:03.502 ThaliTest[2145:3755073] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:54:03.503 ThaliTest[2145:3755073] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:54:03.5,03 ThaliTest[2145:3755073] client session: disconnect
2016-03-24 16:54:03.503 ThaliTest[2145:3755073] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:54:03.503 ThaliTest[2145:3755073] client session: no connect callback (server initiated)
,2016-03-24 16:54:11.659 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:54:11.671 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:54:11.671 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:54:12.740 ThaliTest[2145:3752542] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-24 16:54:15.173 ThaliTest[2145:3752542] multipeer session: reset timer
2016-03-24 16:54:15.173 ThaliTest[2145:3752542] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:54:15.173 ThaliTest[2145:3752542] server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (5F451984-F7B7-4F39-B182-72023C9FD000:9 != 5F451984-F7B7-4F39-B182-72023C9FD000:8)
,2016-03-24 16:54:15.753 ThaliTest[2145:3752700] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:54:15.754 ThaliTest[2145:3752700] client: server will connect
2016-03-24 16:54:15.754 ThaliTest[2145:3752700] client session: reverseConn,ect
2016-03-24 16:54:15.754 ThaliTest[2145:3752700] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:54:16.149 ThaliTest[2145:3755073] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:54:16.151 ThaliTest[2145:3755073] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:54:16.1,51 ThaliTest[2145:3755073] client session: disconnect
2016-03-24 16:54:16.151 ThaliTest[2145:3755073] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:54:16.151 ThaliTest[2145:3755073] client session: no connect callback (server initiated)
,2016-03-24 16:54:25.755 ThaliTest[2145:3752542] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-24 16:54:28.759 ThaliTest[2145:3752700] jxcore: connect B8F5135C-E580-4A9F-90CD-0EB35830FF0E:8
2016-03-24 16:54:28.759 ThaliTest[2145:3752700] client: server will connect
2016-03-24 16:54:28.760 ThaliTest[2145:3752700] client session: reverseConnect
2016-03-24 16:54:28.760 ThaliTest[2145:3752700] client session: stateChange:0->1 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:54:28.790 ThaliTest[2145:3752542] multipeer session: reset timer
2016-03-24 16:54:28.790 ThaliTest[2145:3752542] server: disconnecting to refresh session (5AE71735-F944-4906-BE1F-E88A7F36E6EE)
2016-03-24 16:54:28.790 ThaliTest[2145:3752542], server: rejecting invitation from 5AE71735-F944-4906-BE1F-E88A7F36E6EE due to previous generation (5F451984-F7B7-4F39-B182-72023C9FD000:9 != 5F451984-F7B7-4F39-B182-72023C9FD000:8)
,2016-03-24 16:54:28.952 ThaliTest[2145:3755187] client session: not connected B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
,2016-03-24 16:54:28.952 ThaliTest[2145:3755187] client session: onLinkFailure: B8F5135C-E580-4A9F-90CD-0EB35830FF0E
2016-03-24 16:54:28.954 ThaliTest[2145:3755187] client session: disconnect
2016-03-24 16:54:28.954 ThaliTest[2145:3755187] client session: stateChange:1->0 B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:54:28.954 ThaliTest[2145:3755187] client session: no connect callback (server initiated)
,2016-03-24 16:54:31.659 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:54:31.670 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:54:31.671 ThaliTest[2145:3752542] client: found updated peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:9
,2016-03-24 16:54:38.761 ThaliTest[2145:3752542] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 168 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-24 16:54:39.348 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 16:54:39.349 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
,ok 169 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 16:54:39.350 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:54:39.351 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:54:39.351 ThaliTest[2145:3752700] multipeer manager: stop client timer
2016-03-24 16:54:39.351 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-24 16:54:40.074 ThaliTest[2145:3752700] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:40.075 ThaliTest[2145:3752700] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:40.075 ThaliTest[2145:3752700] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 16:54:40.076 ThaliTest[2145:3752700] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 40. #startListeningForAdvertisements should fail if start not called
,ok 171 specific error should be returned
,# teardown
,# setup
,2016-03-24 16:54:41.213 ThaliTest[2145:3752700] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:41.214 ThaliTest[2145:3752700] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:41.214 ThaliTest[2145:3,752700] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:54:41.215 ThaliTest[2145:3752700] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-24 16:54:42.795 ThaliTest[2145:3752700] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:42.796 ThaliTest[2145:3752700] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:42.796 ThaliTest[2145:3752700] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:54:42.797 ThaliTest[2145:3752700] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52588
,2016-03-24 16:54:43.198 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 16:54:43.199 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
,ok 173 no errors
,2016-03-24 16:54:43.201 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 16:54:43.201 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
,ok 174 still no errors
,# teardown
,2016-03-24 16:54:45.859 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:54:45.859 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:54:45.860 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: success
2016-03-24 16:54:45.860 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 16:54:45.861 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-24 16:54:46.378 ThaliTest[2145:3752700] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:46.379 ThaliTest[2145:3752700] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:46.379 ThaliTest[2145:3752700] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:54:46.380 ThaliTest[2145:3752700] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52590
,2016-03-24 16:54:46.815 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
2016-03-24 16:54:46.815 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:54:46.816 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements: success
ok 175 no errors
,2016-03-24 16:54:46.817 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 16:54:46.818 ThaliTest[2145:3752700] jxcore: startListeningForAdvertisements: success
,ok 176 still no errors
,# teardown
,2016-03-24 16:54:47.338 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening
2016-03-24 16:54:47.338 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:54:47.339 ThaliTest[2145:3752700] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 16:54:47.339 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements
2016-03-24 16:54:47.339 ThaliTest[2145:3752700] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 16:54:47.340 ThaliTest[2145:3752700] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-24 16:54:48.958 ThaliTest[2145:3752700] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 16:54:48.959 ThaliTest[2145:3752700] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:54:48.959 ThaliTest[2145:3752700] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:54:48.960 ThaliTest[2145:3752700] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52592
,2016-03-24 16:54:49.909 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:54:49.909 ThaliTest[2145:3752700] server: starting 5F451984-F7B7-4F39-B182-72023C9FD000:10
2016-03-24 16:54:49.909 ThaliTest[2145:3752700] multipeer ,manager: start client restart timer: 0x14ec0520
2016-03-24 16:54:49.910 ThaliTest[2145:3752700] THEMultipeerManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:10
2016-03-24 16:54:49.910 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening: success
ok 177 no errors
2016-03-24 16:54:49.911 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening
2016-03-24 16:54:49.911 ThaliTest[2145:3752700] THEMultipeerManager stopping peer
2016-03-24 16:54:49.911 ThaliTest[2145:3752,700] multipeer manager: stop client timer
2016-03-24 16:54:49.911 ThaliTest[2145:3752700] server: starting 5F451984-F7B7-4F39-B182-72023C9FD000:11
2016-03-24 16:54:49.911 ThaliTest[2145:3752700] multipeer manager: start client restart timer: 0x14ec0520
,2016-03-24 16:54:49.912 ThaliTest[2145:3752700] THEMultipeerManager initialized peer 5F451984-F7B7-4F39-B182-72023C9FD000:11
2016-03-24 16:54:49.913 ThaliTest[2145:3752700] jxcore: startUpdateAdvertisingAndListening: success
ok 178 still no errors
# teardown
,2016-03-24 16:54:49.930 ThaliTest[2145:3752542] client: found new peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:9
2016-03-24 16:54:49.930 ThaliTest[2145:3752542] client: found new peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:55:09.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:55:09.923 ThaliTest[2145:3752542] client: found updated peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 16:55:09.925 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:55:29.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:55:29.936 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 16:55:29.936 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:55:49.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:55:49.923 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:55:49.924 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 16:56:09.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:56:09.923 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 16:56:09.924 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:56:29.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:56:29.929 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:56:29.929 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 16:56:49.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:56:49.925 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 16:56:49.926 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:57:09.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:57:09.922 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 16:57:09.922 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:57:29.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:57:29.923 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 16:57:29.924 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:57:49.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:57:49.922 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 16:57:49.922 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:58:09.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:58:09.925 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 16:58:09.925 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:58:29.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:58:29.924 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:58:29.925 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 16:58:49.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:58:49.924 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 16:58:49.924 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 16:59:09.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:59:09.932 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 16:59:09.935 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:59:29.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:59:29.924 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 16:59:29.925 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 16:59:49.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 16:59:49.929 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 16:59:49.931 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:00:09.912 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:00:09.929 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 17:00:09.930 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:00:29.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:00:29.928 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 17:00:29.928 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 17:00:49.912 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:00:49.933 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 17:00:49.936 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:01:09.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:01:09.925 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 17:01:09.928 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:01:29.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:01:29.925 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 17:01:29.926 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 17:01:49.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:01:49.922 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 17:01:49.922 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:02:09.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:02:09.924 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 17:02:09.925 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:02:29.912 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:02:29.936 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 17:02:29.937 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:02:49.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:02:49.924 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 17:02:49.924 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 17:03:09.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:03:09.924 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 17:03:09.925 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:03:29.912 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:03:29.923 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 17:03:29.924 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:03:49.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:03:49.925 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 17:03:49.925 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:04:09.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:04:09.924 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
2016-03-24 17:04:09.924 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 17:04:29.913 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:04:29.924 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 17:04:29.926 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:04:49.912 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:04:49.924 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
2016-03-24 17:04:49.924 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8
,2016-03-24 17:05:09.912 ThaliTest[2145:3752542] multipeer manager: restart client
,2016-03-24 17:05:09.931 ThaliTest[2145:3752542] client: found existing peer: B8F5135C-E580-4A9F-90CD-0EB35830FF0E:11
,2016-03-24 17:05:09.933 ThaliTest[2145:3752542] client: found existing peer: 5AE71735-F944-4906-BE1F-E88A7F36E6EE:8

```
