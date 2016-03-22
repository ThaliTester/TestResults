#### Test 636801181df08af_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D8D54787-B3B9-404D-B9A9-61ECA3C10C4B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D8D54787-B3B9-404D-B9A9-61ECA3C10C4B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54588"
,(lldb)     command script import "/tmp/D8D54787-B3B9-404D-B9A9-61ECA3C10C4B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-22 09:05:18.542 ThaliTest[1946:3314815] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/41317D9D-7AB6-407A-907A-24F1EE2A1A43/Library/Cookies/Cookies.binarycookies
,2016-03-22 09:05:18.926 ThaliTest[1946:3314815] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-22 09:05:18.928 ThaliTest[1946:3314815] Multi-tasking -> Device: YES, App: YES
,2016-03-22 09:05:18.956 ThaliTest[1946:3314815] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-22 09:05:20.850 ThaliTest[1946:3314815] Using UIWebView
,2016-03-22 09:05:20.857 ThaliTest[1946:3314815] [CDVTimer][handleopenurl] 0.415981ms
,2016-03-22 09:05:20.865 ThaliTest[1946:3314815] [CDVTimer][intentandnavigationfilter] 7.344007ms
2016-03-22 09:05:20.866 ThaliTest[1946:3314815] [CDVTimer][gesturehandler] 0.374019ms
2016-03-22 09:05:20.867 ThaliTest[1946:3314815] [CDVTimer][TotalPluginS,tartup] 9.935975ms
,2016-03-22 09:05:28.225 ThaliTest[1946:3314815] Resetting plugins due to page load.
,2016-03-22 09:05:31.382 ThaliTest[1946:3314815] Finished load of: file:///var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/index.html
,2016-03-22 09:05:31.626 ThaliTest[1946:3314815] JXcore Cordova plugin initializing
2016-03-22 09:05:31.627 ThaliTest[1946:3315013] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-22 09:05:38.914 ThaliTest[1946:3315013] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 09:05:38.915 ThaliTest[1946:3315013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 09:05:38.916 ThaliTest[1946:3315013] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:05:38.918 ThaliTest[1946:3315013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/08318311-FD0F-417F-B93E-12FF628E3967/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-22 09:05:44.800 ThaliTest[1946:3314815] THREAD WARNING: ['JXcore'] took '5566.964355' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50029
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50031
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# setup
,# 3. emits routerPortConnectionFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50034
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
,ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# setup
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# 4. native server connections all up
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50038
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
,ok 9 Send/recvd #2 should be equal length
,ok 10 Send/recvd #2 should be same
,ok 11 Should be exactly 2 client sockets
,# setup
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50044
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# setup
,DEBUG createNativeListener: mux close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50048
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
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50052
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# setup
,DEBUG createNativeListener: mux close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50056
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
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50060
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
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50112
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
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50116
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
,# setup
,# 12. closeAll can close even when connections open
,# teardown
,ok 45 not possible to connect to the server anymore
,# setup
,# 13. closeAll with promise
,# teardown
,ok 46 not possible to connect to the server anymore
,# setup
,# 14. multiplex can send data
,# teardown
,ok 47 String should be length:200
,# setup
,# 15. enqueue and run in order
,# teardown
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
,ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# setup
,# 16. enqueueAtTop and run backwards
,# teardown
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# setup
,# 17. mix enqueue and enqueueAtTop
,# teardown
,ok 64 fourth
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# setup
,# 18. queues handled independently
,# teardown
,ok 73 all short operations completed before the long resolves
,# setup
,# 19. basic
,# teardown
,ok 74 sane
,# setup
,# 20. another
,# teardown
,ok 75 sane
,# setup
,# 21. can pass data in setup
,# teardown
,ok 76 test participant has uuid
,ok 77 participant data matches
,ok 78 test participant has uuid
,ok 79 participant data matches
,# setup
,# 22. #startListeningForAdvertisements should fail if start not called
,# teardown
,ok 80 specific error should be returned
,# setup
,ok 81 error should be null
,ok 82 error should be null
,# 23. #startUpdateAdvertisingAndListening should fail if start not called
,# teardown
,ok 83 specific error should be returned
,# setup
,ok 84 error should be null
,ok 85 error should be null
,# 24. should be able to call #stopListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50128
,2016-03-22 09:07:40.812 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:40.815 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,2016-03-22 09:07:40.821 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:40.823 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,# setup
,2016-03-22 09:07:41.003 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:41.004 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:41.004 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
,2016-03-22 09:07:41.006 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:41.008 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# 25. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50130
,2016-03-22 09:07:41.343 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
,2016-03-22 09:07:41.347 ThaliTest[1946:3315013] multipeer manager: start client restart timer: 0x17594bf0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:07:41.350 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,2016-03-22 09:07:41.367 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:07:41.370 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,# setup
,2016-03-22 09:07:41.789 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:41.789 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:41.790 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 09:07:41.791 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,2016-03-22 09:07:41.791 ThaliTest[1946:3315013] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 09:07:41.797 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 96 error should be null
,ok 97 error should be null
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50132
,2016-03-22 09:07:42.371 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:42.372 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:1
2016-03-22 09:07:42.373 ThaliTest[1946:3315013] multipeer m,anager: start client restart timer: 0x17594bf0
2016-03-22 09:07:42.374 ThaliTest[1946:3315013] THEMultipeerManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:1
2016-03-22 09:07:42.374 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening: success
,ok 98 error should be null
ok 99 error should be null
,2016-03-22 09:07:42.391 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:42.393 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:42.394 ThaliTest[1946:3315013] multipeer manager: stop client timer
2016-03-22 09:07:42.394 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:2
,2016-03-22 09:07:42.395 ThaliTest[1946:3315013] multipeer manager: start client restart timer: 0x17594bf0
,2016-03-22 09:07:42.396 ThaliTest[1946:3315013] THEMultipeerManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:2
,2016-03-22 09:07:42.397 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,# setup
,2016-03-22 09:07:42.883 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:42.883 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:42.883 ThaliTest[1946:3315013] multipeer manager: stop client timer
2016-03-22 09:07:42.884 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
,2016-03-22 09:07:42.886 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:42.890 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 102 error should be null
,ok 103 error should be null
,# 27. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50137
,2016-03-22 09:07:43.643 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:43.643 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:43.643 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: suc,cess
,ok 104 error should be null
,ok 105 error should be null
,2016-03-22 09:07:43.650 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:43.651 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:43.651 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
ok 106 error should be null
,ok 107 error should be null
,# setup
,2016-03-22 09:07:43.818 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:43.818 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:43.818 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
2016-03-22 09:07:43.819 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:43.822 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 108 error should be null
,ok 109 error should be null
,# 28. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50139
,ok 110 first call should succeed
,ok 111 first call should succeed
,ok 112 specific error should be returned
,# setup
,2016-03-22 09:07:44.385 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:44.386 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:44.386 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
2016-03-22 09:07:44.387 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:44.390 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50141
,2016-03-22 09:07:44.815 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
2016-03-22 09:07:44.816 ThaliTest[1946:3315013] multipeer manager: start client restart timer: 0x17594bf0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 09:07:44.820 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
,2016-03-22 09:07:44.833 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:44.834 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:3
2016-03-22 09:07:44.834 ThaliTest[1946:3315013] THEMultipee,rManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:3
2016-03-22 09:07:44.835 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening: success
,ok 115 called only once
,ok 116 discovery state matches
,ok 117 advertising state matches
,# setup
,2016-03-22 09:07:45.476 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:45.477 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:45.477 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
2016-03-22 09:07:45.478 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,2016-03-22 09:07:45.478 ThaliTest[1946:3315013] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 09:07:45.485 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 118 error should be null
,ok 119 error should be null
,# 30. does not send duplicate availability changes
,# teardown
,ok 120 should be called once
,ok 121 should not have been called more than once
,# setup
,ok 122 error should be null
,ok 123 error should be null
,# 31. can get the network status
,# teardown
,ok 124 network status should have certain non-empty properties
,# setup
,ok 125 error should be null
,ok 126 error should be null
,# 32. wifi peer is marked unavailable if announcements stop
,# teardown
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 127 host address should match
,ok 128 port should match
,ok 129 host address should be null
,ok 130 port should should be null
,# setup
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 131 error should be null
,ok 132 error should be null
,# 33. Can call start/stopListeningForAdvertisements
,# teardown
,2016-03-22 09:07:51.368 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
2016-03-22 09:07:51.369 ThaliTest[1946:3315013] multipeer manager: start client restart timer: 0x17594bf0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 09:07:51.371 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
ok 133 Can call startListeningForAdvertisements without error
,2016-03-22 09:07:51.374 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
2016-03-22 09:07:51.375 ThaliTest[1946:3315013] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-22 09:07:51.378 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
ok 134 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-22 09:07:51.623 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:51.625 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:07:51.628 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:51.629 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:51.629 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-22 09:07:51.858 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
2016-03-22 09:07:51.859 ThaliTest[1946:3315013] multipeer manager: start client restart timer: 0x17594bf0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 09:07:51.863 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
,2016-03-22 09:07:51.866 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 09:07:51.870 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-22 09:07:52.385 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
2016-03-22 09:07:52.386 ThaliTest[1946:3315013] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:52.388 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
2016-03-22 09:07:52.392 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:52.392 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:0,7:52.393 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
,ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-22 09:07:52.822 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:52.823 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:4
2016-03-22 09:07:52.824 ThaliTest[1946:3315013] multipeer m,anager: start client restart timer: 0x17594bf0
2016-03-22 09:07:52.824 ThaliTest[1946:3315013] THEMultipeerManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:4
2016-03-22 09:07:52.824 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 09:07:52.827 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
,2016-03-22 09:07:52.828 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:52.829 ThaliTest[1946:3315013] multipeer manager: stop client timer
2016-03-22 09:07:52.829 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: su,ccess
ok 142 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-22 09:07:53.192 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:53.194 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:07:53.197 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:53.197 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:53.198 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: suc,cess
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-22 09:07:53.378 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:53.378 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:5
2016-03-22 09:07:53.379 ThaliTest[1946:3315013] multipeer m,anager: start client restart timer: 0x17594bf0
2016-03-22 09:07:53.380 ThaliTest[1946:3315013] THEMultipeerManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:5
2016-03-22 09:07:53.380 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 09:07:53.383 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:53.384 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:53.384 ThaliTest[1946:3315013] multipeer manager: stop client timer
2016-03-22 09:07:53.385 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:07:53.385 ThaliTest[1946:3315013] multipeer manager: start client restart timer: 0x17594bf0
2016-03-22 09:07:53.386 ThaliTest[1946:,3315013] THEMultipeerManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:07:53.386 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening: success
ok 146 Can call startUpdateAdvertisingAndListening twice without error
# setup
,2016-03-22 09:07:54.465 ThaliTest[1946:3314815] client: found new peer: E9CB2080-C667-4537-8057-9C336E6593A8:6
,2016-03-22 09:07:54.794 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 09:07:54.796 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 147 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:07:54.799 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:54.800 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:07:54.800 ThaliTest[1946:3315013] multipeer manager: stop client timer
2016-03-22 09:07:54.801 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
,# 37. peerAvailabilityChange is called
,# teardown
,2016-03-22 09:07:55.359 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:55.359 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:7
2016-03-22 09:07:55.360 ThaliTest[1946:3315013] multipeer manager: start client restart timer: 0x17594bf0
,2016-03-22 09:07:55.360 ThaliTest[1946:3315013] THEMultipeerManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:7
,2016-03-22 09:07:55.363 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening: success
,ok 149 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-22 09:07:55.367 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-22 09:07:55.377 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
,ok 150 Can call startListeningForAdvertisements without error
,2016-03-22 09:07:56.083 ThaliTest[1946:3314815] client: found new peer: E9CB2080-C667-4537-8057-9C336E6593A8:6
,ok 151 peers must be an array
,ok 152 peers must not be zero-length
ok 153 peer must have peerIdentifier
ok 154 peerIdentifier must be a string
,ok 155 peer must have peerAvailable
,ok 156 peer must have pleaseConnect
,# setup
,2016-03-22 09:07:56.382 ThaliTest[1946:3314815] client: found existing peer: E9CB2080-C667-4537-8057-9C336E6593A8:6
,2016-03-22 09:07:56.388 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-22 09:07:56.390 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
ok 157 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:07:56.392 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
,2016-03-22 09:07:56.392 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
,2016-03-22 09:07:56.394 ThaliTest[1946:3315013] multipeer manager: stop client timer
2016-03-22 09:07:56.394 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
ok 158 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can connect to a remote peer
,# teardown
,2016-03-22 09:07:56.928 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:56.929 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:07:56.930 ThaliTest[1946:3315013] multipeer m,anager: start client restart timer: 0x17594bf0
2016-03-22 09:07:56.931 ThaliTest[1946:3315013] THEMultipeerManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:07:56.931 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 159 Can call startUpdateAdvertisingAndListening without error
2016-03-22 09:07:56.933 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-22 09:07:56.935 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
,ok 160 Can call startListeningForAdvertisements without error
,2016-03-22 09:07:57.600 ThaliTest[1946:3314815] client: found new peer: E9CB2080-C667-4537-8057-9C336E6593A8:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E9CB2080-C667-4537-8057-9C336E6593A8:7","pleaseConnect":0}]
2016-03-22 09:07:57.605 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8,057-9C336E6593A8:7
2016-03-22 09:07:57.605 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:07:57.606 ThaliTest[1946:3315013] client session: reverseConnect
2016-03-22 09:07:57.606 ThaliTest[1946:3315013] client session: stateChange:0->,1 E9CB2080-C667-4537-8057-9C336E6593A8:7
,2016-03-22 09:07:59.279 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:07:59.280 ThaliTest[1946:3314815] server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6)
,2016-03-22 09:07:59.614 ThaliTest[1946:3315333] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:7
,2016-03-22 09:07:59.615 ThaliTest[1946:3315333] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
2016-03-22 09:07:59.616 ThaliTest[1946:3315333] client session: disconnect
2016-03-22 09:07:59.616 ThaliTest[1946:3315333] client session:, stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:07:59.617 ThaliTest[1946:3315333] client session: no connect callback (server initiated)
,2016-03-22 09:08:02.436 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:08:02.436 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:08:02.437 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6)
,2016-03-22 09:08:05.641 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:08:05.641 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:08:05.641 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6)
,2016-03-22 09:08:07.606 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-22 09:08:08.859 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:08:08.860 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:08:08.860 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6)
,2016-03-22 09:08:10.615 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:10.616 ThaliTest[1946:3315013] client: server will connect
,2016-03-22 09:08:10.616 ThaliTest[1946:3315013] client session: reverseConnect
,2016-03-22 09:08:10.617 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:7
,2016-03-22 09:08:11.891 ThaliTest[1946:3315333] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:11.891 ThaliTest[1946:3315333] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
2016-03-22 09:08:11.8,91 ThaliTest[1946:3315333] client session: disconnect
,2016-03-22 09:08:11.892 ThaliTest[1946:3315333] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:11.895 ThaliTest[1946:3315333] client session: no connect callback (server initiated)
,2016-03-22 09:08:11.984 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:08:11.985 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:08:11.985 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6)
,2016-03-22 09:08:15.492 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:08:15.493 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:08:15.493 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6)
,2016-03-22 09:08:16.932 ThaliTest[1946:3314815] multipeer manager: restart client
,2016-03-22 09:08:16.950 ThaliTest[1946:3314815] client: found updated peer: E9CB2080-C667-4537-8057-9C336E6593A8:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E9CB2080-C667-4537-8057-9C336E6593A8:8","pleaseConnect":0}]
,2016-03-22 09:08:18.644 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:08:18.644 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:08:18.645 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6)
,2016-03-22 09:08:20.618 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-22 09:08:21.786 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:08:21.786 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:08:21.787 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6)
,2016-03-22 09:08:23.626 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:23.627 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:08:23.627 ThaliTest[1946:3315013] client session: reverseConn,ect
2016-03-22 09:08:23.628 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:8
,2016-03-22 09:08:24.929 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:08:24.930 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:08:24.930 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6)
,2016-03-22 09:08:24.978 ThaliTest[1946:3315303] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:08:24.979 ThaliTest[1946:3315303] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
2016-03-22 09:08:24.9,79 ThaliTest[1946:3315303] client session: disconnect
2016-03-22 09:08:24.979 ThaliTest[1946:3315303] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:8
,2016-03-22 09:08:24.982 ThaliTest[1946:3315303] client session: no connect callback (server initiated)
,2016-03-22 09:08:28.245 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:08:28.245 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:08:28.246 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6)
,2016-03-22 09:08:33.628 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-22 09:08:36.639 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:36.640 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:08:36.640 ThaliTest[1946:3315013] client session: reverseConnect
2016-03-22 09:08:36.640 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:8
,2016-03-22 09:08:36.932 ThaliTest[1946:3314815] multipeer manager: restart client
,2016-03-22 09:08:36.953 ThaliTest[1946:3314815] client: found existing peer: E9CB2080-C667-4537-8057-9C336E6593A8:8
,2016-03-22 09:08:46.641 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-22 09:08:49.653 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:49.653 ThaliTest[1946:3315013] client: already connect(ing/ed) to E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:49.654 Thali,Test[1946:3315013] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-22 09:08:52.665 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:52.666 ThaliTest[1946:3315013] client: already connect(ing/ed) to E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:52.666 Thali,Test[1946:3315013] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-22 09:08:55.674 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:55.674 ThaliTest[1946:3315013] client: already connect(ing/ed) to E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:55.675 Thali,Test[1946:3315013] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-22 09:08:56.932 ThaliTest[1946:3314815] multipeer manager: restart client
,2016-03-22 09:08:56.949 ThaliTest[1946:3314815] client: found existing peer: E9CB2080-C667-4537-8057-9C336E6593A8:8
,2016-03-22 09:08:58.694 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:58.695 ThaliTest[1946:3315013] client: already connect(ing/ed) to E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:08:58.696 Thali,Test[1946:3315013] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-22 09:09:01.709 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:09:01.710 ThaliTest[1946:3315013] client: already connect(ing/ed) to E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:09:01.710 ThaliTest[1946:3315013] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-22 09:09:04.728 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:09:04.728 ThaliTest[1946:3315013] client: already connect(ing/ed) to E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:09:04.729 Thali,Test[1946:3315013] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 161 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-22 09:09:04.837 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 09:09:04.839 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
ok 162 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:09:04.842 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:09:04.843 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:09:04.843 ThaliTest[1946:3315013] client session: disconnect
2016-03-22 09:09:04.843 ThaliTest[1946:3315013] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:09:04.844 ThaliTest[1946:3315013] multipeer manager: stop client timer
2016-03-22 09:09:04.844 ThaliTest[1946:3315013] jxcore: stopA,dvertisingAndListening: success
ok 163 Should be able to call stopAdvertisingAndListening in teardown
,# 39. Can shift large amounts of data
,# teardown
,2016-03-22 09:09:05.811 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:09:05.811 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
2016-03-22 09:09:05.812 ThaliTest[1946:3315013] multipeer m,anager: start client restart timer: 0x17594bf0
2016-03-22 09:09:05.813 ThaliTest[1946:3315013] THEMultipeerManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
2016-03-22 09:09:05.813 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening: success
,ok 164 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 09:09:05.816 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-22 09:09:05.817 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
ok 165 Can call startListeningForAdvertisements without error
,2016-03-22 09:09:06.800 ThaliTest[1946:3314815] client: found new peer: E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:09:06.802 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:09:06.803 ThaliTest[1946:3315013] client: server will connect
,2016-03-22 09:09:06.804 ThaliTest[1946:3315013] client session: reverseConnect
2016-03-22 09:09:06.804 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:8
,2016-03-22 09:09:07.893 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:09:07.894 ThaliTest[1946:3314815] server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8)
,2016-03-22 09:09:08.480 ThaliTest[1946:3315526] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:09:08.481 ThaliTest[1946:3315526] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
2016-03-22 09:09:08.4,81 ThaliTest[1946:3315526] client session: disconnect
2016-03-22 09:09:08.482 ThaliTest[1946:3315526] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:09:08.482 ThaliTest[1946:3315526] client session: no connect callb,ack (server initiated)
,2016-03-22 09:09:11.646 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:09:11.647 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:09:11.647 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8)
,2016-03-22 09:09:14.759 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:09:14.760 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:09:14.760 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8)
,2016-03-22 09:09:16.804 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-22 09:09:17.983 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:09:17.983 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:09:17.984 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8)
,2016-03-22 09:09:19.814 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:09:19.814 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:09:19.815 ThaliTest[1946:3315013] client session: reverseConnect
2016-03-22 09:09:19.815 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:8
,2016-03-22 09:09:20.141 ThaliTest[1946:3315546] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:09:20.142 ThaliTest[1946:3315546] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
2016-03-22 09:09:20.1,43 ThaliTest[1946:3315546] client session: disconnect
2016-03-22 09:09:20.143 ThaliTest[1946:3315546] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:8
,2016-03-22 09:09:20.145 ThaliTest[1946:3315546] client session: no connect callback (server initiated)
,2016-03-22 09:09:21.252 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:09:21.252 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:09:21.253 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8)
,2016-03-22 09:09:24.714 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:09:24.714 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:09:24.715 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8)
,2016-03-22 09:09:25.814 ThaliTest[1946:3314815] multipeer manager: restart client
,2016-03-22 09:09:25.832 ThaliTest[1946:3314815] client: found updated peer: E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:09:28.394 ThaliTest[1946:3314815] multipeer session: reset timer
,2016-03-22 09:09:28.395 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
,2016-03-22 09:09:28.396 ThaliTest[1946:3314815] server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8)
,2016-03-22 09:09:29.816 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-22 09:09:31.595 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:09:31.595 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:09:31.595 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8)
,2016-03-22 09:09:32.821 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:09:32.821 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:09:32.822 ThaliTest[1946:3315013] client session: reverseConnect
2016-03-22 09:09:32.822 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:09:32.986 ThaliTest[1946:3315564] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:09:32.986 ThaliTest[1946:3315564] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
,2016-03-22 09:09:32.987 ThaliTest[1946:3315564] client session: disconnect
,2016-03-22 09:09:32.988 ThaliTest[1946:3315564] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:09:32.989 ThaliTest[1946:3315564] client session: no connect callback (server initiated)
,2016-03-22 09:09:34.712 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:09:34.713 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:09:34.713 ThaliTest[1946:3314815] server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8)
,2016-03-22 09:09:37.886 ThaliTest[1946:3314815] multipeer session: reset timer
2016-03-22 09:09:37.887 ThaliTest[1946:3314815] server: disconnecting to refresh session (E9CB2080-C667-4537-8057-9C336E6593A8)
2016-03-22 09:09:37.887 ThaliTest[1946:3314815], server: rejecting invitation from E9CB2080-C667-4537-8057-9C336E6593A8 due to previous generation (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9 != 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8)
,2016-03-22 09:09:42.823 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-22 09:09:45.814 ThaliTest[1946:3314815] multipeer manager: restart client
,2016-03-22 09:09:45.831 ThaliTest[1946:3314815] client: found existing peer: E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:09:45.834 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:09:45.835 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:09:45.836 ThaliTest[1946:3315013] client session: reverseConn,ect
2016-03-22 09:09:45.836 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:09:46.287 ThaliTest[1946:3315625] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:09:46.287 ThaliTest[1946:3315625] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
,2016-03-22 09:09:46.288 ThaliTest[1946:3315625] client session: disconnect
2016-03-22 09:09:46.289 ThaliTest[1946:3315625] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:09:46.290 ThaliTest[1946:3315625] client sess,ion: no connect callback (server initiated)
,2016-03-22 09:09:55.837 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-22 09:09:58.847 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:09:58.848 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:09:58.849 ThaliTest[1946:3315013] client session: reverseConnect
2016-03-22 09:09:58.849 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:09:59.604 ThaliTest[1946:3315665] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:09:59.606 ThaliTest[1946:3315665] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
,2016-03-22 09:09:59.606 ThaliTest[1946:3315665] client session: disconnect
,2016-03-22 09:09:59.607 ThaliTest[1946:3315665] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:09:59.609 ThaliTest[1946:3315665] client session: no connect callback (server initiated)
,2016-03-22 09:10:05.814 ThaliTest[1946:3314815] multipeer manager: restart client
,2016-03-22 09:10:08.850 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-22 09:10:08.860 ThaliTest[1946:3314815] client: found existing peer: E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:10:11.860 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:10:11.860 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:10:11.861 ThaliTest[1946:3315013] client session: reverseConnect
2016-03-22 09:10:11.861 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:10:13.824 ThaliTest[1946:3315705] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:10:13.824 ThaliTest[1946:3315705] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
2016-03-22 09:10:13.8,24 ThaliTest[1946:3315705] client session: disconnect
2016-03-22 09:10:13.826 ThaliTest[1946:3315705] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:10:13.826 ThaliTest[1946:3315705] client session: no connect callb,ack (server initiated)
,2016-03-22 09:10:21.862 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-22 09:10:24.875 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:10:24.876 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:10:24.876 ThaliTest[1946:3315013] client session: reverseConn,ect
2016-03-22 09:10:24.877 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:10:25.324 ThaliTest[1946:3315705] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:10:25.325 ThaliTest[1946:3315705] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
2016-03-22 09:10:25.3,25 ThaliTest[1946:3315705] client session: disconnect
2016-03-22 09:10:25.326 ThaliTest[1946:3315705] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:10:25.330 ThaliTest[1946:3315705] client session: no connect callback (server initiated)
,2016-03-22 09:10:25.814 ThaliTest[1946:3314815] multipeer manager: restart client
,2016-03-22 09:10:25.832 ThaliTest[1946:3314815] client: found existing peer: E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:10:34.878 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-22 09:10:37.883 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:10:37.884 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:10:37.884 ThaliTest[1946:3315013] client session: reverseConn,ect
2016-03-22 09:10:37.885 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:10:38.204 ThaliTest[1946:3315705] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:10:38.206 ThaliTest[1946:3315705] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
2016-03-22 09:10:38.2,06 ThaliTest[1946:3315705] client session: disconnect
2016-03-22 09:10:38.206 ThaliTest[1946:3315705] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:10:38.207 ThaliTest[1946:3315705] client session: no connect callb,ack (server initiated)
,2016-03-22 09:10:45.814 ThaliTest[1946:3314815] multipeer manager: restart client
,2016-03-22 09:10:45.833 ThaliTest[1946:3314815] client: found existing peer: E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:10:47.886 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-22 09:10:50.901 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:10:50.901 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:10:50.902 ThaliTest[1946:3315013] client session: reverseConnect
2016-03-22 09:10:50.902 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:10:52.674 ThaliTest[1946:3315705] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:10:52.674 ThaliTest[1946:3315705] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
2016-03-22 09:10:52.675 ThaliTest[1946:3315705] client session: disconnect
2016-03-22 09:10:52.675 ThaliTest[1946:3315705] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:10:52.676 ThaliTest[1946:3315705] client session: no connect callb,ack (server initiated)
,2016-03-22 09:11:00.903 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-22 09:11:03.910 ThaliTest[1946:3315013] jxcore: connect E9CB2080-C667-4537-8057-9C336E6593A8:8
2016-03-22 09:11:03.911 ThaliTest[1946:3315013] client: server will connect
2016-03-22 09:11:03.911 ThaliTest[1946:3315013] client session: reverseConn,ect
2016-03-22 09:11:03.911 ThaliTest[1946:3315013] client session: stateChange:0->1 E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:11:04.448 ThaliTest[1946:3315783] client session: not connected E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:11:04.448 ThaliTest[1946:3315783] client session: onLinkFailure: E9CB2080-C667-4537-8057-9C336E6593A8
2016-03-22 09:11:04.4,49 ThaliTest[1946:3315783] client session: disconnect
2016-03-22 09:11:04.449 ThaliTest[1946:3315783] client session: stateChange:1->0 E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:11:04.452 ThaliTest[1946:3315783] client session: no connect callback (server initiated)
,2016-03-22 09:11:05.814 ThaliTest[1946:3314815] multipeer manager: restart client
,2016-03-22 09:11:05.831 ThaliTest[1946:3314815] client: found existing peer: E9CB2080-C667-4537-8057-9C336E6593A8:9
,2016-03-22 09:11:13.913 ThaliTest[1946:3314815] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 166 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-22 09:11:13.973 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 09:11:13.975 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 167 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:11:13.978 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:11:13.978 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:11:13.979 ThaliTest[1946:3315013] multipeer manager: stop client timer
20,16-03-22 09:11:13.979 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
ok 168 Should be able to call stopAdvertisingAndListening in teardown
,# 40. #startListeningForAdvertisements should fail if start not called
,2016-03-22 09:11:14.120 ThaliTest[1946:3315013] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 09:11:14.122 ThaliTest[1946:3315013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 09:11:14.124 ThaliTest[1946:3315013] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:14.128 ThaliTest[1946:3315013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 169 specific error should be returned
,# setup
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-22 09:11:14.687 ThaliTest[1946:3315013] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:14.688 ThaliTest[1946:3315013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:14.688 ThaliTest[1946:3,315013] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:14.692 ThaliTest[1946:3315013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 170 specific error should be returned
,# setup
,# 42. should be able to call #stopListeningForAdvertisements many times
,2016-03-22 09:11:15.468 ThaliTest[1946:3315013] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:15.469 ThaliTest[1946:3315013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:15.470 ThaliTest[1946:3,315013] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:15.473 ThaliTest[1946:3315013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50184
,2016-03-22 09:11:15.582 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:11:15.584 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 171 no errors
,2016-03-22 09:11:15.587 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:11:15.589 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,ok 172 still no errors
,# setup
,2016-03-22 09:11:15.742 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:11:15.742 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:11:15.743 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 09:11:15.743 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 09:11:15.745 ThaliTest[1946,:3315013] jxcore: stopListeningForAdvertisements: success
,# 43. should be able to call #startListeningForAdvertisements many times
,2016-03-22 09:11:16.047 ThaliTest[1946:3315013] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:16.048 ThaliTest[1946:3315013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:16.049 ThaliTest[1946:3,315013] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:16.052 ThaliTest[1946:3315013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50186
,2016-03-22 09:11:16.204 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
2016-03-22 09:11:16.204 ThaliTest[1946:3315013] multipeer manager: start client restart timer: 0x17594bf0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:11:16.207 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
ok 173 no errors
,2016-03-22 09:11:16.211 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 09:11:16.213 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success
ok 174 still no errors
,# setup
,2016-03-22 09:11:16.503 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:11:16.503 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:11:16.504 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 09:11:16.504 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
2016-03-22 09:11:16.505 ThaliTest[1946:3315013] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 09:11:16.509 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,# 44. should be able to call #startUpdateAdvertisingAndListening many times
,2016-03-22 09:11:16.651 ThaliTest[1946:3315013] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:16.652 ThaliTest[1946:3315013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:16.652 ThaliTest[1946:3,315013] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:16.656 ThaliTest[1946:3315013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50188
,2016-03-22 09:11:16.779 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:11:16.780 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:10
2016-03-22 09:11:16.780 ThaliTest[1946:3315013] multipeer ,manager: start client restart timer: 0x17594bf0
2016-03-22 09:11:16.781 ThaliTest[1946:3315013] THEMultipeerManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:10
2016-03-22 09:11:16.782 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 175 no errors
,2016-03-22 09:11:16.785 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:11:16.786 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:11:16.786 ThaliTest[1946:3315013] multipeer manager: stop client ti,mer
2016-03-22 09:11:16.787 ThaliTest[1946:3315013] server: starting 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:11
2016-03-22 09:11:16.788 ThaliTest[1946:3315013] multipeer manager: start client restart timer: 0x17594bf0
2016-03-22 09:11:16.788 ThaliTest[1946,:3315013] THEMultipeerManager initialized peer 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:11
2016-03-22 09:11:16.790 ThaliTest[1946:3315013] jxcore: startUpdateAdvertisingAndListening: success
ok 176 still no errors
# setup
,2016-03-22 09:11:17.089 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:11:17.090 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:11:17.090 ThaliTest[1946:3315013] multipeer manager: stop client timer
20,16-03-22 09:11:17.090 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
2016-03-22 09:11:17.091 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 09:11:17.095 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,# 45. should be able to call #stopAdvertisingAndListening many times
,2016-03-22 09:11:17.252 ThaliTest[1946:3315013] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:17.253 ThaliTest[1946:3315013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:17.254 ThaliTest[1946:3,315013] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:17.257 ThaliTest[1946:3315013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50192
,2016-03-22 09:11:17.570 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
,2016-03-22 09:11:17.571 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
,2016-03-22 09:11:17.573 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
,ok 177 no errors
,2016-03-22 09:11:17.577 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
,2016-03-22 09:11:17.578 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
,2016-03-22 09:11:17.579 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: success
,ok 178 still no errors
,# setup
,2016-03-22 09:11:18.157 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening
2016-03-22 09:11:18.158 ThaliTest[1946:3315013] THEMultipeerManager stopping peer
2016-03-22 09:11:18.158 ThaliTest[1946:3315013] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 09:11:18.159 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:11:18.160 ThaliTest[1946:3315013] jxcore: stopListeningForAdvertisements: success
,# 46. can get the network status before starting
,2016-03-22 09:11:18.313 ThaliTest[1946:3315013] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:18.314 ThaliTest[1946:3315013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:18.314 ThaliTest[1946:3315013] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:18.318 ThaliTest[1946:3315013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 179 network status should have certain non-empty properties
,# setup
,# 47. error returned with bad router
,2016-03-22 09:11:19.129 ThaliTest[1946:3315013] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:19.130 ThaliTest[1946:3315013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:19.131 ThaliTest[1946:3,315013] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:19.133 ThaliTest[1946:3315013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 180 specific error expected
,# setup
,# 48. all services are stopped when we call stop
,2016-03-22 09:11:23.602 ThaliTest[1946:3315013] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 09:11:23.604 ThaliTest[1946:3315013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 09:11:23.606 ThaliTest[1946:3315013] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:23.610 ThaliTest[1946:3315013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50194
,2016-03-22 09:11:23.858 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements
,2016-03-22 09:11:23.860 ThaliTest[1946:3315013] multipeer manager: start client restart timer: 0x17594bf0
,2016-03-22 09:11:23.870 ThaliTest[1946:3314815] client: found new peer: E9CB2080-C667-4537-8057-9C336E6593A8:9
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 09:11:23.8,72 ThaliTest[1946:3315013] jxcore: startListeningForAdvertisements: success

```
