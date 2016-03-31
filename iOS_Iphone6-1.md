#### Test 645312549bcf247_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9956E57E-1CBC-4D02-9E12-E46A78F7D77D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9956E57E-1CBC-4D02-9E12-E46A78F7D77D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49487"
,(lldb)     command script import "/tmp/9956E57E-1CBC-4D02-9E12-E46A78F7D77D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 01:47:35.500 ThaliTest[2468:4609882] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FD917659-C608-4BE4-BADD-50FDD691F644/Library/Cookies/Cookies.binarycookies
,2016-03-31 01:47:35.732 ThaliTest[2468:4609882] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 01:47:35.733 ThaliTest[2468:4609882] Multi-tasking -> Device: YES, App: YES
,2016-03-31 01:47:35.748 ThaliTest[2468:4609882] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 01:47:36.526 ThaliTest[2468:4609882] Using UIWebView
2016-03-31 01:47:36.528 ThaliTest[2468:4609882] [CDVTimer][handleopenurl] 0.104964ms
,2016-03-31 01:47:36.531 ThaliTest[2468:4609882] [CDVTimer][intentandnavigationfilter] 3.223956ms
2016-03-31 01:47:36.532 ThaliTest[2468:4609882] [CDVTimer][gesturehandler] 0.119984ms
2016-03-31 01:47:36.532 ThaliTest[2468:4609882] [CDVTimer][TotalPluginStartup] 3.915012ms
,2016-03-31 01:47:39.675 ThaliTest[2468:4609882] Resetting plugins due to page load.
,2016-03-31 01:47:41.075 ThaliTest[2468:4609882] Finished load of: file:///var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/index.html
,2016-03-31 01:47:41.231 ThaliTest[2468:4609882] JXcore Cordova plugin initializing
2016-03-31 01:47:41.231 ThaliTest[2468:4610061] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 01:47:48.241 ThaliTest[2468:4610061] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 01:47:48.242 ThaliTest[2468:4610061] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 01:47:48.242 ThaliTest[2468:4,610061] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 01:47:48.243 ThaliTest[2468:4610061] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5CFCF56E-3F25-4493-ABA7-D303AD3D353C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54739
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54741
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
DEBUG createNativeListener: listening 54744
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
DEBUG createNativeListener: listening 54748
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 54753
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
DEBUG createNativeListener: listening 54757
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
DEBUG createNativeListener: listening 54761
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
DEBUG createNativeListener: listening 54765
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
DEBUG createNativeListener: listening 54769
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
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
,DEBUG createNativeListener: new stream: 
,eateNativeListener: new stream: 
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
DEBUG cr,DEBUG createNativeListener: new outgoing socket
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
DEBUG cr,eateNativeListener: new stream: 
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: mux close
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
ok 28 ,native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
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
DEBUG createNativeListener: listening 54821
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 54825
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
,# 16. enqueue and run in order
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
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# teardown
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
# teardown
,# setup
,# 22. can pass data in setup
,ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 own UUID is found from the participants list
# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 83 specific error should be returned
# teardown
,ok 84 error should be null
ok 85 error should be null
# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 86 specific error should be returned
# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54835
2016-03-31 01:50:22.211 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.212 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
ok 89 error should be null
ok 90 error should be null
2016-03-31 01:50:22.213 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.214 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: succes,s
ok 91 error should be null
ok 92 error should be null
# teardown
,2016-03-31 01:50:22.403 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:22.403 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:50:22.403 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 01:50:22.404 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.404 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54837
2016-03-31 01:50:22.720 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements
,2016-03-31 01:50:22.722 ThaliTest[2468:4610061] multipeer manager: start client restart timer: 0x176a9360
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:22.722 Th,aliTest[2468:4610061] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-31 01:50:22.727 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:22.728 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
# teardown
,2016-03-31 01:50:22.969 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:22.970 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:50:22.970 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
2016-03-31 01:50:22.970 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:22.970 ThaliTest[2468:4610061] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.971 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 99 error should be null
ok 100 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54839
,2016-03-31 01:50:23.656 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:50:23.656 ThaliTest[2468:4610061] server: starting 9BF3B351-B42F-4B62-994E-93C3F024E3C4:1
2016-03-31 01:50:23.656 ThaliTest[2468:4610061] multipeer m,anager: start client restart timer: 0x176a9360
2016-03-31 01:50:23.657 ThaliTest[2468:4610061] THEMultipeerManager initialized peer 9BF3B351-B42F-4B62-994E-93C3F024E3C4:1
2016-03-31 01:50:23.657 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening: success
ok 101 error should be null
ok 102 error should be null
2016-03-31 01:50:23.662 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:50:23.663 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-,03-31 01:50:23.663 ThaliTest[2468:4610061] multipeer manager: stop client timer
2016-03-31 01:50:23.663 ThaliTest[2468:4610061] server: starting 9BF3B351-B42F-4B62-994E-93C3F024E3C4:2
2016-03-31 01:50:23.663 ThaliTest[2468:4610061] multipeer manager: sta,rt client restart timer: 0x176a9360
2016-03-31 01:50:23.667 ThaliTest[2468:4610061] THEMultipeerManager initialized peer 9BF3B351-B42F-4B62-994E-93C3F024E3C4:2
2016-03-31 01:50:23.667 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
# teardown
,2016-03-31 01:50:24.646 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:24.646 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:50:24.647 ThaliTest[2468:4610061] multipeer manager: stop client timer
2016-03-31 01:50:24.647 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
2016-03-31 01:50:24.647 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:24.647 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 105 error should be null
ok 106 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54844
2016-03-31 01:50:25.259 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:25.259 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:50:25.259 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
2016-03-31 01:50:25.260 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:25.260 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:50:25.260 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
# teardown
,2016-03-31 01:50:25.698 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:25.699 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:50:25.699 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 01:50:25.699 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:25.699 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
ok 111 error should be null
ok 112 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54846
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
# teardown
,2016-03-31 01:50:27.357 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:27.357 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:50:27.357 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 01:50:27.357 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:27.358 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
,ok 116 error should be null
ok 117 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54848
2016-03-31 01:50:27.807 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements
2016-03-31 01:50:27.807 ThaliTest[2468:4610061] multipeer manager: sta,rt client restart timer: 0x176a9360
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:27.808 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements: success
,2016-03-31 01:50:27.815 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 01:50:27.816 ThaliTest[2468:4610061] server: starting 9BF3B351-B42F-4B62-994E-93C3F024E3C4:3
,2016-03-31 01:50:27.816 ThaliTest[2468:4610061] THEMultipeerManager initialized peer 9BF3B351-B42F-4B62-994E-93C3F024E3C4:3
,2016-03-31 01:50:27.817 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening: success
,ok 118 called only once
,ok 119 discovery state matches
,ok 120 advertising state matches
,# teardown
,2016-03-31 01:50:27.916 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:27.917 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
,2016-03-31 01:50:27.917 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
,2016-03-31 01:50:27.918 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
,2016-03-31 01:50:27.919 ThaliTest[2468:4610061] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:27.921 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 121 error should be null
ok 122 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 123 should be called once
,ok 124 should not have been called more than once
,# teardown
,ok 125 error should be null
ok 126 error should be null
# setup
,# 32. can get the network status
,ok 127 network status should have certain non-empty properties
# teardown
,ok 128 error should be null
ok 129 error should be null
# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 130 host address should match
ok 131 port should match
,ok 132 host address should be null
,ok 133 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-03-31 01:50:57.526 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements
2016-03-31 01:50:57.526 ThaliTest[2468:4610061] multipeer manager: start client restart timer: 0x176a9360
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:57.527 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-31 01:50:57.527 ThaliTes,t[2468:4610061] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:57.528 ThaliTest[2468:4610061] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:57.528 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 01:50:57.762 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:57.763 ThaliTest[2468:46100,61] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:50:57.764 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:57.764 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:50:57.764 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 01:50:58.285 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements
2016-03-31 01:50:58.286 ThaliTest[2468:4610061] multipeer manager: start client restart timer: 0x176a9360
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:58.288 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-31 01:50:58.288 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:58.289 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-31 01:50:58.440 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:58.440 ThaliTest[2468:4610061] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-31 01:50:58.441 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:50:58.441 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:58.441 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:50:58.441 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-03-31 01:51:15.023 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:15.024 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
ok 144 Can call stopListeningForAdvertisements without error
2016-03-31 01:51:15.025 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:15.025 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
ok 145 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 01:51:18.653 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:18.653 ThaliTest[2468:46100,61] jxcore: stopListeningForAdvertisements: success
ok 146 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:18.654 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:18.654 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:51:18.654 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 147 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 01:51:18.858 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:18.859 ThaliTest[2468:4610061] server: starting 9BF3B351-B42F-4B62-994E-93C3F024E3C4:4
2016-03-31 01:51:18.859 ThaliTest[2468:4610061] multipeer manager: start client restart timer: 0x176a9360
2016-03-31 01:51:18.859 ThaliTest[2468:4610061] THEMultipeerManager initialized peer 9BF3B351-B42F-4B62-994E-93C3F024E3C4:4
2016-03-31 01:51:18.859 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:18.861 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:18.861 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
,2016-03-31 01:51:18.861 ThaliTest[2468:4610061] multipeer manager: stop client timer
2016-03-31 01:51:18.863 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 149 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 01:51:19.103 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:19.104 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
ok 150 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:19.104 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:19.104 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:51:19.105 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 151 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 01:51:19.624 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:19.625 ThaliTest[2468:4610061] server: starting 9BF3B351-B42F-4B62-994E-93C3F024E3C4:5
2016-03-31 01:51:19.625 ThaliTest[2468:4610061] multipeer manager: start client restart timer: 0x176a9360
2016-03-31 01:51:19.625 ThaliTest[2468:4610061] THEMultipeerManager initialized peer 9BF3B351-B42F-4B62-994E-93C3F024E3C4:5
2016-03-31 01:51:19.625 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 152 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:19.626 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:19.626 ThaliTest[2468:4610061] THEMultipeerManager stopping pee,r
,2016-03-31 01:51:19.626 ThaliTest[2468:4610061] multipeer manager: stop client timer
2016-03-31 01:51:19.628 ThaliTest[2468:4610061] server: starting 9BF3B351-B42F-4B62-994E-93C3F024E3C4:6
2016-03-31 01:51:19.629 ThaliTest[2468:4610061] multipeer manager: start client restart timer: 0x176a9360
2016-03-31 01:51:19.629 ThaliTest[2468:4610061] THEMultipeerManager initialized peer 9BF3B351-B42F-4B62-994E-93C3F024E3C4:6
2016-03-31 01:51:19.629 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening: success
ok 153 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 01:51:19.743 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 01:51:19.744 ThaliTest[2468:461006,1] jxcore: stopListeningForAdvertisements: success
ok 154 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:19.744 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:19.744 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:51:19.745 ThaliTest[2468:4610061] multipeer manager: stop client timer
2016-03-31 01:51:19.745 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 155 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-03-31 01:51:20.821 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:20.821 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:51:20.821 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: suc,cess
ok 156 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:20.822 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:20.822 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:51:20.822 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 157 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 01:51:38.326 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:38.327 ThaliTest[2468:46100,61] jxcore: stopListeningForAdvertisements: success
ok 158 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:38.327 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:38.327 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:51:38.327 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-03-31 01:51:38.639 ThaliTest[2468:4610061] jxcore: connect foo
2016-03-31 01:51:38.639 ThaliTest[2468:4610061] jxcore: connect: fail: Start browsing first
not ok 160 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-03-31 01:51:38.740 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:38.740 ThaliTest[2468:46100,61] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:38.741 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:38.741 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:51:38.741 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-03-31 01:51:39.016 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:39.016 ThaliTest[2468:4610061] server: starting 9BF3B351-B42F-4B62-994E-93C3F024E3C4:7
2016-03-31 01:51:39.017 ThaliTest[2468:4610061] multipeer m,anager: start client restart timer: 0x176a9360
2016-03-31 01:51:39.017 ThaliTest[2468:4610061] THEMultipeerManager initialized peer 9BF3B351-B42F-4B62-994E-93C3F024E3C4:7
2016-03-31 01:51:39.017 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening: success
ok 163 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 01:51:39.017 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-31 01:51:39.018 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-31 01:51:40.057 ThaliTest[2468:4609882] client: found new peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
ok 165 peers must be an array
ok 166 peers must not be zero-length
ok 167 peer must have peerIdentifier
ok 168 peerIdentifier must be a string
ok 169 peer must have peerAvailable
ok 170 peer must have pleaseConnect
,# teardown
,2016-03-31 01:51:42.212 ThaliTest[2468:4609882] client: found new peer: 42E93D78-2507-4BE0-9192-FC412A882204:7
,2016-03-31 01:51:43.509 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 01:51:43.510 ThaliTest[2468:461006,1] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:43.510 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:43.510 ThaliTest[2468:461006,1] THEMultipeerManager stopping peer
2016-03-31 01:51:43.510 ThaliTest[2468:4610061] multipeer manager: stop client timer
2016-03-31 01:51:43.510 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-03-31 01:51:44.023 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:44.023 ThaliTest[2468:4610061] server: starting 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:51:44.024 ThaliTest[2468:4610061] multipeer m,anager: start client restart timer: 0x176a9360
2016-03-31 01:51:44.024 ThaliTest[2468:4610061] THEMultipeerManager initialized peer 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:51:44.024 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:44.025 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 01:51:44.025 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-31 01:51:44.917 ThaliTest[2468:4609882] client: found new peer: 42E93D78-2507-4BE0-9192-FC412A882204:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"42E93D78-2507-4BE0-9192-FC412A882204:7","pleaseConnect":0}]
2016-03-31 01:51:44.919 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:44.919 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:51:44.919 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:7
,2016-03-31 01:51:46.197 ThaliTest[2468:4609882] client: found new peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7","pleaseConnect":0}]
,2016-03-31 01:51:46.299 ThaliTest[2468:4610631] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:46.299 ThaliTest[2468:4610631] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:51:46.299 ThaliTest[2468:4610631] client session: disconnect
2016-03-31 01:51:46.300 ThaliTest[2468:4610631] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:46.300 ThaliTest[2468:4610631] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:51:46.300 ThaliTest[2468:4610631] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 01:51:49.305 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:49.305 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:51:49.305 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:7
,2016-03-31 01:51:49.749 ThaliTest[2468:4610631] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:49.750 ThaliTest[2468:4610631] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:51:49.7,50 ThaliTest[2468:4610631] client session: disconnect
2016-03-31 01:51:49.750 ThaliTest[2468:4610631] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:49.750 ThaliTest[2468:4610631] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:51:49.750 ThaliTest[2468:4610631] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 01:51:52.754 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:52.754 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:51:52.754 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:7
,2016-03-31 01:51:53.176 ThaliTest[2468:4610630] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:53.177 ThaliTest[2468:4610630] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:51:53.1,77 ThaliTest[2468:4610630] client session: disconnect
2016-03-31 01:51:53.177 ThaliTest[2468:4610630] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:53.177 ThaliTest[2468:4610630] client session: fireConnectCallb,ack: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:51:53.177 ThaliTest[2468:4610630] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 01:51:56.190 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:56.190 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:51:56.190 ThaliTest[2468:4610061] client session: stateChange:0->,1 42E93D78-2507-4BE0-9192-FC412A882204:7
,2016-03-31 01:51:56.891 ThaliTest[2468:4610630] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:56.891 ThaliTest[2468:4610630] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:51:56.891 ThaliTest[2468:4610630] client session: disconnect
2016-03-31 01:51:56.891 ThaliTest[2468:4610630] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:56.892 ThaliTest[2468:4610630] client session: fireConnectCallb,ack: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:51:56.892 ThaliTest[2468:4610630] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 01:51:59.897 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:59.898 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:51:59.898 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:7
,2016-03-31 01:52:00.039 ThaliTest[2468:4610631] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:00.039 ThaliTest[2468:4610631] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
,2016-03-31 01:52:00.039 ThaliTest[2468:4610631] client session: disconnect
,2016-03-31 01:52:00.039 ThaliTest[2468:4610631] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:00.040 ThaliTest[2468:4610631] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 0,1:52:00.041 ThaliTest[2468:4610631] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 01:52:03.044 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:03.044 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:52:03.044 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:7
,2016-03-31 01:52:03.151 ThaliTest[2468:4610630] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:03.152 ThaliTest[2468:4610630] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:03.153 ThaliTest[2468:4610630] client session: disconnect
2016-03-31 01:52:03.153 ThaliTest[2468:4610630] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:03.153 ThaliTest[2468:4610630] client session: fireConnectCallb,ack: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:03.153 ThaliTest[2468:4610630] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 01:52:04.024 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:52:04.035 ThaliTest[2468:4609882] client: found updated peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"42E93D78-2507-4BE0-9192-FC412A882204:8","pleaseConnect":0}]
,2016-03-31 01:52:04.120 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8","pleaseConnect":0}]
,2016-03-31 01:52:06.164 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:06.165 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:52:06.165 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:06.293 ThaliTest[2468:4610630] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:06.293 ThaliTest[2468:4610630] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:06.293 ThaliTest[2468:4610630] client session: disconnect
2016-03-31 01:52:06.293 ThaliTest[2468:4610630] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:06.295 ThaliTest[2468:4610630] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:06.295 ThaliTest[2468:4610630] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 01:52:09.298 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:09.299 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:52:09.299 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:09.477 ThaliTest[2468:4610632] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:09.478 ThaliTest[2468:4610632] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:09.478 ThaliTest[2468:4610632] client session: disconnect
,2016-03-31 01:52:09.478 ThaliTest[2468:4610632] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:09.479 ThaliTest[2468:4610632] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:09.479 ThaliTest[2468:4610632] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 01:52:12.483 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:12.483 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:52:12.484 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:12.618 ThaliTest[2468:4610630] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:12.619 ThaliTest[2468:4610630] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:12.6,19 ThaliTest[2468:4610630] client session: disconnect
2016-03-31 01:52:12.619 ThaliTest[2468:4610630] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:12.619 ThaliTest[2468:4610630] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:12.619 ThaliTest[2468:4610630] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 01:52:15.625 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:15.625 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:52:15.625 ThaliTest[2468:4610061] client session: stateChange:0->,1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:15.767 ThaliTest[2468:4610632] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:15.767 ThaliTest[2468:4610632] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:15.768 ThaliTest[2468:4610632] client session: disconnect
2016-03-31 01:52:15.768 ThaliTest[2468:4610632] client session:, stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:15.768 ThaliTest[2468:4610632] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:15.768 ThaliTest[2468:4610632] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 175 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-31 01:52:24.024 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:52:24.036 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:24.039 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:52:44.024 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:52:44.036 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:52:44.037 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:52.156 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 01:52:52.158 ThaliTest[2468:4610061] jxcore: stopListeningForAdvertisements: success
ok 176 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-31 01:52:52.158 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening
2016-03-31 01:52:52.158 ThaliTest[2468:4610061] THEMultipeerManager stopping peer
2016-03-31 01:52:52.159 ThaliTest[2468:4610061] multipeer manager: stop client timer
20,16-03-31 01:52:52.159 ThaliTest[2468:4610061] jxcore: stopAdvertisingAndListening: success
ok 177 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-03-31 01:52:54.690 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:52:54.690 ThaliTest[2468:4610061] server: starting 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:52:54.690 ThaliTest[2468:4610061] multipeer manager: start client restart timer: 0x176a9360
2016-03-31 01:52:54.690 ThaliTest[2468:4610061] THEMultipeerManager initialized peer 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:52:54.691 ThaliTest[2468:4610061] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 178 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:52:54.691 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 01:52:54.692 ThaliTest[2468:4610061] jxcore: startListeningForAdvertisements: success
ok 179 Can call startListeningForAdvertisements without error
,2016-03-31 01:52:55.176 ThaliTest[2468:4609882] client: found new peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:55.177 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:55.177 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:52:55.178 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:55.562 ThaliTest[2468:4609882] client: found new peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:52:55.876 ThaliTest[2468:4609882] multipeer session: reset timer
2016-03-31 01:52:55.876 ThaliTest[2468:4609882] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (9BF3B351-B42F-4B62-994E-93C3F024E3C4:9 != 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8)
,2016-03-31 01:52:56.843 ThaliTest[2468:4610859] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:56.843 ThaliTest[2468:4610859] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:56.843 ThaliTest[2468:4610859] client session: disconnect
2016-03-31 01:52:56.843 ThaliTest[2468:4610859] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:56.844 ThaliTest[2468:4610859] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:56.844 ThaliTest[2468:4610859] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 01:52:59.856 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:59.856 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:52:59.856 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:00.274 ThaliTest[2468:4610859] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:00.274 ThaliTest[2468:4610859] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:00.274 ThaliTest[2468:4610859] client session: disconnect
2016-03-31 01:53:00.275 ThaliTest[2468:4610859] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:00.276 ThaliTest[2468:4610859] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:00.276 ThaliTest[2468:4610859] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 01:53:03.277 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:03.277 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:53:03.277 ThaliTest[2468:4610061] client session: stateChange:0->,1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:03.585 ThaliTest[2468:4610859] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:03.585 ThaliTest[2468:4610859] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:03.585 ThaliTest[2468:4610859] client session: disconnect
2016-03-31 01:53:03.585 ThaliTest[2468:4610859] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:03.585 ThaliTest[2468:4610859] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:03.585 ThaliTest[2468:4610859] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 01:53:06.592 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:06.592 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:53:06.592 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:07.205 ThaliTest[2468:4610872] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:07.205 ThaliTest[2468:4610872] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:07.2,05 ThaliTest[2468:4610872] client session: disconnect
2016-03-31 01:53:07.205 ThaliTest[2468:4610872] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:07.205 ThaliTest[2468:4610872] client session: fireConnectCallb,ack: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:07.205 ThaliTest[2468:4610872] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 01:53:08.636 ThaliTest[2468:4609882] multipeer session: reset timer
2016-03-31 01:53:08.636 ThaliTest[2468:4609882] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:53:08.636 ThaliTest[2468:4609882], server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (9BF3B351-B42F-4B62-994E-93C3F024E3C4:9 != 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8)
,2016-03-31 01:53:10.208 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:10.208 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:53:10.208 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:11.902 ThaliTest[2468:4610873] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:11.903 ThaliTest[2468:4610873] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:11.9,04 ThaliTest[2468:4610873] client session: disconnect
2016-03-31 01:53:11.904 ThaliTest[2468:4610873] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:11.904 ThaliTest[2468:4610873] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:11.904 ThaliTest[2468:4610873] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 01:53:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:53:14.699 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:14.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:53:14.915 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:14.915 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:53:14.915 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:16.810 ThaliTest[2468:4610632] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:16.810 ThaliTest[2468:4610632] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:16.8,10 ThaliTest[2468:4610632] client session: disconnect
2016-03-31 01:53:16.810 ThaliTest[2468:4610632] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:16.812 ThaliTest[2468:4610632] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:16.812 ThaliTest[2468:4610632] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 01:53:19.824 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:19.825 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:53:19.825 ThaliTest[2468:4610061] client session: stateChange:0->,1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:20.244 ThaliTest[2468:4610873] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:20.245 ThaliTest[2468:4610873] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:20.2,45 ThaliTest[2468:4610873] client session: disconnect
2016-03-31 01:53:20.245 ThaliTest[2468:4610873] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:20.246 ThaliTest[2468:4610873] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:20.246 ThaliTest[2468:4610873] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 01:53:21.771 ThaliTest[2468:4609882] multipeer session: reset timer
2016-03-31 01:53:21.771 ThaliTest[2468:4609882] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:53:21.771 ThaliTest[2468:4609882] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (9BF3B351-B42F-4B62-994E-93C3F024E3C4:9 != 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8)
,2016-03-31 01:53:23.257 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:23.257 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:53:23.257 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:24.776 ThaliTest[2468:4610873] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:24.778 ThaliTest[2468:4610873] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:24.778 ThaliTest[2468:4610873] client session: disconnect
2016-03-31 01:53:24.778 ThaliTest[2468:4610873] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:24.779 ThaliTest[2468:4610873] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:24.779 ThaliTest[2468:4610873] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 01:53:27.787 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:27.787 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:53:27.787 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:28.107 ThaliTest[2468:4610632] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:28.108 ThaliTest[2468:4610632] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
,2016-03-31 01:53:28.108 ThaliTest[2468:4610632] client session: disconnect
,2016-03-31 01:53:28.108 ThaliTest[2468:4610632] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:28.108 ThaliTest[2468:4610632] client session: fireConnectCallback: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:28.109 ThaliTest[2468:4610632] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 01:53:31.115 ThaliTest[2468:4610061] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:31.116 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:53:31.116 ThaliTest[2468:4610061] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:32.715 ThaliTest[2468:4610873] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:32.716 ThaliTest[2468:4610873] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:32.7,16 ThaliTest[2468:4610873] client session: disconnect
2016-03-31 01:53:32.716 ThaliTest[2468:4610873] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:32.716 ThaliTest[2468:4610873] client session: fireConnectCallb,ack: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:32.716 ThaliTest[2468:4610873] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,2016-03-31 01:53:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:53:34.701 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:34.701 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:53:35.488 ThaliTest[2468:4609882] multipeer session: reset timer
2016-03-31 01:53:35.488 ThaliTest[2468:4609882] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:53:35.488 ThaliTest[2468:4609882] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (9BF3B351-B42F-4B62-994E-93C3F024E3C4:9 != 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8)
,2016-03-31 01:53:54.691 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:53:54.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:54.701 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:53:54.701 ThaliTest[2468:4610061] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:53:54.702 ThaliTest[2468:4610061] client session: connect
2016-03-31 01:53:54.702 ThaliTest[2468:4610061] client session: stateChange:0->1 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:53:57.317 ThaliTest[2468:4610859] client session: p2p link connected
,2016-03-31 01:53:57.320 ThaliTest[2468:4611076] client session: stateChange:1->2 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:53:57.320 ThaliTest[2468:4611076] client session: fireConnectCallback: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41
2016-03-31 01:53:57.320 ThaliTest[2468:4611076] jxcore: connect: success
,2016-03-31 01:53:57.333 ThaliTest[2468:4610061] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:53:57.333 ThaliTest[2468:4609882] client: relay established
2016-03-31 01:53:57.333 ThaliTest[2468:4609882] client: new accepted socket: 0x18ee4210
2016-03-31 01:53:57.333 ThaliTest[2468:4610061] client: already connect(ing/ed) to 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:53:57.333 ThaliTest[2468:4610061] jxcore: connect: fail: Already connect(ing/ed)
ok 180 Expected error
ok 181 Null connection as expected
2016-03-31 01:53:57.334 ThaliTest[2468:4610061] jxcore: connect 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:53:57.335 ThaliTest[2468:4610061] client: already connect(ing/ed) to 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:53:57.335 ThaliTest[2468:4610061] jxcore: connect: fail: Already connect(ing/ed)
,ok 182 Expected error
ok 183 Null connection as expected
,# teardown
,2016-03-31 01:54:14.691 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:54:14.758 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:54:14.760 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:54:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:54:34.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:54:34.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:54:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:54:54.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:54:54.702 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:55:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:55:14.702 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:55:14.702 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:55:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:55:34.703 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:55:34.703 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:55:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:55:54.703 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:55:54.703 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:56:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:56:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:56:34.701 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:56:34.701 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:56:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:56:54.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:56:54.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:57:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:57:14.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:57:14.701 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:57:34.691 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:57:34.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:57:34.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:57:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:57:54.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:57:54.701 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:58:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:58:14.701 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:58:14.701 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:58:34.691 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:58:34.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:58:34.701 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:58:54.691 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:58:54.700 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 01:58:54.701 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:59:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:59:14.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:59:14.700 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:59:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:59:34.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:59:34.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 01:59:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 01:59:54.701 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:59:54.701 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:00:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:00:14.699 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:00:14.700 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:00:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:00:34.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:00:34.701 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:00:54.691 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:00:54.699 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:00:54.701 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:01:14.691 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:01:14.699 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 02:01:14.699 ThaliTest[2468:4609882] client: found updated peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:01:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:01:34.701 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 02:01:34.701 ThaliTest[2468:4609882] client: found updated peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:01:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:01:54.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:01:54.701 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:02:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:02:14.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:02:14.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:02:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:02:34.701 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:02:34.701 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:02:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:02:54.701 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 02:02:54.702 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:03:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:03:14.702 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:03:14.702 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:03:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:03:34.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:03:34.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:03:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:03:54.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:03:54.700 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:04:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:04:14.700 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 02:04:14.701 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:04:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:04:34.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:04:34.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:04:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:04:54.704 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 02:04:54.704 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:05:14.691 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:05:14.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:05:14.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:05:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:05:34.702 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:05:34.702 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:05:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:05:54.701 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:05:54.701 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:06:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:06:14.703 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:06:14.703 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:06:34.691 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:06:34.703 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:06:34.703 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:06:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:06:54.701 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:06:54.702 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:07:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:07:14.699 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:07:14.700 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:07:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:07:34.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:07:34.700 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:07:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:07:54.700 ThaliTest[2468:4609882] client: found updated peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:07:54.701 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:08:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:08:14.700 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 02:08:14.701 ThaliTest[2468:4609882] client: found updated peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:08:34.691 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:08:34.699 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:08:34.699 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:08:54.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:08:54.700 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 02:08:54.702 ThaliTest[2468:4609882] client: found existing peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
,2016-03-31 02:09:14.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:09:14.702 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 02:09:14.702 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
,2016-03-31 02:09:34.692 ThaliTest[2468:4609882] multipeer manager: restart client
,2016-03-31 02:09:34.702 ThaliTest[2468:4609882] client: found updated peer: 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 02:09:34.702 ThaliTest[2468:4609882] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8

```
