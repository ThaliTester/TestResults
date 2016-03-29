#### Test 63998117d1f6a2b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63998117d1f6a2b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/820B21FF-5F18-4057-9A83-F9926BCEE6A3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/820B21FF-5F18-4057-9A83-F9926BCEE6A3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63998117d1f6a2b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63998117d1f6a2b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56399"
,(lldb)     command script import "/tmp/820B21FF-5F18-4057-9A83-F9926BCEE6A3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-29 13:27:09.713 ThaliTest[2422:4431373] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5EE59059-9C47-4242-A92E-95BC4C44C715/Library/Cookies/Cookies.binarycookies
,2016-03-29 13:27:09.967 ThaliTest[2422:4431373] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-29 13:27:09.969 ThaliTest[2422:4431373] Multi-tasking -> Device: YES, App: YES
,2016-03-29 13:27:09.988 ThaliTest[2422:4431373] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 13:27:10.808 ThaliTest[2422:4431373] Using UIWebView
,2016-03-29 13:27:10.812 ThaliTest[2422:4431373] [CDVTimer][handleopenurl] 0.149012ms
2016-03-29 13:27:10.815 ThaliTest[2422:4431373] [CDVTimer][intentandnavigationfilter] 2.662003ms
2016-03-29 13:27:10.816 ThaliTest[2422:4431373] [CDVTimer][gesturehandler] 0.124991ms
2016-03-29 13:27:10.816 ThaliTest[2422:4431373] [CDVTimer][TotalPluginStartup] 3.544986ms
,2016-03-29 13:27:14.083 ThaliTest[2422:4431373] Resetting plugins due to page load.
,2016-03-29 13:27:15.434 ThaliTest[2422:4431373] Finished load of: file:///var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/index.html
,2016-03-29 13:27:15.621 ThaliTest[2422:4431373] JXcore Cordova plugin initializing
,2016-03-29 13:27:15.622 ThaliTest[2422:4431551] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-29 13:27:23.982 ThaliTest[2422:4431551] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-29 13:27:23.984 ThaliTest[2422:4431551] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-29 13:27:23.985 ThaliTest[2422:4431551] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 13:27:23.987 ThaliTest[2422:4431551] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CB84EDDA-DB1E-4D03-9F56-DD0FEC653DE0/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54989
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54991
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54994
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
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54998
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
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55003
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 55007
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
DEBUG createNativeListener: listening 55011
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
DEBUG createNativeListener: listening 55015
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
DEBUG createNativeListener: listening 55019
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
DEBUG createNativeListener: new incoming socket
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
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBU,G createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG ,createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
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
DEBU,G createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeL,istener: incoming socket close
DEBUG createNativeListener: incoming socket close
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
,DEBUG createNativeListener: listening 55071
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
,DEBUG createNativeListener: listening 55075
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,ok 60 secondPromise - second to run
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
,ok 68 secondPromise - in then
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
,# teardown
,ok 84 error should be null
ok 85 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 86 specific error should be returned
,# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55087
2016-03-29 13:30:07.087 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 13:30:07.087 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements: success
ok 89 error should be null
ok 90 error should be null
2016-03-29 13:30:07.089 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements
DEBUG thaliMob,ileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 13:30:07.090 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
# teardown
,2016-03-29 13:30:07.220 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening
2016-03-29 13:30:07.221 ThaliTest[2422:4431551] THEMultipeerManager stopping peer
2016-03-29 13:30:07.221 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 13:30:07.221 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 13:30:07.222 ThaliTest[2422,:4431551] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55089
,2016-03-29 13:30:07.618 ThaliTest[2422:4431551] jxcore: startListeningForAdvertisements
,2016-03-29 13:30:07.620 ThaliTest[2422:4431551] multipeer manager: start client restart timer: 0x17df77a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 13:30:07.621 ThaliTest[2422:4431551] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-29 13:30:07.660 ThaliTest[2422:4431551] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 13:30:07.661 ThaliTest[2422:4431551] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
,# teardown
,2016-03-29 13:30:07.925 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening
2016-03-29 13:30:07.925 ThaliTest[2422:4431551] THEMultipeerManager stopping peer
2016-03-29 13:30:07.925 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening: success
2016-03-29 13:30:07.925 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements
2016-03-29 13:30:07.926 ThaliTest[2422:4431551] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 13:30:07.926 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 99 error should be null
,ok 100 error should be null
,# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55091
,2016-03-29 13:30:08.513 ThaliTest[2422:4431551] jxcore: startUpdateAdvertisingAndListening
,2016-03-29 13:30:08.514 ThaliTest[2422:4431551] server: starting 74D7C97C-328D-4704-A543-6E976EFB077B:1
,2016-03-29 13:30:08.514 ThaliTest[2422:4431551] multipeer manager: start client restart timer: 0x17df77a0
2016-03-29 13:30:08.515 ThaliTest[2422:4431551] THEMultipeerManager initialized peer 74D7C97C-328D-4704-A543-6E976EFB077B:1
2016-03-29 13:30:08.515 ThaliTest[2422:4431551] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
2016-03-29 13:30:08.570 ThaliTest[2422:4431551] jxcore: startUpdateAdvertisingAndListening
2016-03-29 13:30:08.570 ThaliTest[2422:4431551] THEMultipeerManager stopping peer
2016-03-29 13:30:08.570 ThaliTest[2422:4431551] multipeer manager: stop client timer
2016-03-29 13:30:08.571 ThaliTest[2422:4431551] server: starting 74D7C97C-328D-4704-A543-6E976EFB077B:2
2016-03-29 13:30:08.571 ThaliTest[2422:4431551] multipeer manager: start client restart ,timer: 0x17df77a0
2016-03-29 13:30:08.571 ThaliTest[2422:4431551] THEMultipeerManager initialized peer 74D7C97C-328D-4704-A543-6E976EFB077B:2
2016-03-29 13:30:08.571 ThaliTest[2422:4431551] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
# teardown
,2016-03-29 13:30:09.524 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening
2016-03-29 13:30:09.524 ThaliTest[2422:4431551] THEMultipeerManager stopping peer
2016-03-29 13:30:09.524 ThaliTest[2422:4431551] multipeer manager: stop client timer
20,16-03-29 13:30:09.524 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening: success
2016-03-29 13:30:09.524 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 13:30:09.525 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 105 error should be null
ok 106 error should be null
# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55096
2016-03-29 13:30:10.517 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening
2016-03-29 13:30:10.518 ThaliTest[2422:4431551] THEMultipeerManager stopping peer
2016-03-29 13:30:10.518 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
,2016-03-29 13:30:10.519 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening
2016-03-29 13:30:10.521 ThaliTest[2422:4431551] THEMultipeerManager stopping peer
2016-03-29 13:30:10.521 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
,# teardown
,2016-03-29 13:30:10.699 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening
2016-03-29 13:30:10.699 ThaliTest[2422:4431551] THEMultipeerManager stopping peer
2016-03-29 13:30:10.700 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening: success
2016-03-29 13:30:10.700 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 13:30:10.700 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements: success
,ok 111 error should be null
ok 112 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55098
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
,# teardown
,2016-03-29 13:30:11.252 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening
2016-03-29 13:30:11.253 ThaliTest[2422:4431551] THEMultipeerManager stopping peer
2016-03-29 13:30:11.253 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 13:30:11.253 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 13:30:11.254 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55100
,2016-03-29 13:30:11.791 ThaliTest[2422:4431551] jxcore: startListeningForAdvertisements
,2016-03-29 13:30:11.792 ThaliTest[2422:4431551] multipeer manager: start client restart timer: 0x17df77a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 13:30:11.794 ThaliTest[2422:4431551] jxcore: startListeningForAdvertisements: success
,2016-03-29 13:30:11.825 ThaliTest[2422:4431551] jxcore: startUpdateAdvertisingAndListening
2016-03-29 13:30:11.825 ThaliTest[2422:4431551] server: starting 74D7C97C-328D-4704-A543-6E976EFB077B:3
2016-03-29 13:30:11.825 ThaliTest[2422:4431551] THEMultipee,rManager initialized peer 74D7C97C-328D-4704-A543-6E976EFB077B:3
2016-03-29 13:30:11.825 ThaliTest[2422:4431551] jxcore: startUpdateAdvertisingAndListening: success
,ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
,# teardown
,2016-03-29 13:30:12.027 ThaliTest[2422:4431373] client: found new peer: C0830F96-51A4-4755-940E-1508F1453FB9:2
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,2016-03-29 13:30:12.086 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening
2016-03-29 13:30:12.087 ThaliTest[2422:4431551] THEMultipeerManager stopping peer
2016-03-29 13:30:12.087 ThaliTest[2422:4431551] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 13:30:12.087 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements
2016-03-29 13:30:12.087 ThaliTest[2422:4431551] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 13:30:12.088 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements: success
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
ok 129 error should be null
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
,2016-03-29 13:30:32.549 ThaliTest[2422:4431551] jxcore: startListeningForAdvertisements
2016-03-29 13:30:32.550 ThaliTest[2422:4431551] multipeer manager: start client restart timer: 0x17df77a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 13:30:32.550 ThaliTest[2422:4431551] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-29 13:30:32.551 ThaliTes,t[2422:4431551] jxcore: stopListeningForAdvertisements
2016-03-29 13:30:32.551 ThaliTest[2422:4431551] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-29 13:30:32.552 ThaliTest[2422:4431551] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
,# teardown
,* thread #1: tid = 0x439e0d, 0x38d8bae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x1000000c)
  * frame #0: 0x38d8bae6 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x2996cdea MultipeerConnectivity`<redacted> + 270
    frame #2: 0x26d0ec3c CFNetwork`<redacted> + 816
    frame #3: 0x26d0e32c CFNetwork`<redacted> + 36
    frame #4: 0x26c6bdf0 CFNetwork`<redacted> + 668
    frame #5: 0x39568bcc libsystem_dnssd.dylib`<redacted> + 128
    frame #6: 0x39567490 libsystem_dnssd.dylib`DNSServiceProcessResult + 528
    frame #7: 0x26c6b798 CFNetwork`<redacted> + 20
    frame #8: 0x273e74f6 CoreFoundation`<redacted> + 818
    frame #9: 0x273e37c6 CoreFoundation`<redacted> + 14
    frame #10: 0x273e33b6 CoreFoundation`<redacted> + 454
    frame #11: 0x273e171e CoreFoundation`<redacted> + 806
    frame #12: 0x273340d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #13: 0x27333ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #14: 0x30669af8 GraphicsServices`GSEventRunModal + 160
    frame #15: 0x2b5bd2dc UIKit`UIApplicationMain + 144
    frame #16: 0x000b9572 ThaliTest`main + 50

```
