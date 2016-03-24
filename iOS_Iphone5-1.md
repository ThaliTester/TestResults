#### Test 64065450860dd96_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/96C12878-A4A3-42F8-8D90-6A881FA6E581/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/96C12878-A4A3-42F8-8D90-6A881FA6E581/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55807"
,(lldb)     command script import "/tmp/96C12878-A4A3-42F8-8D90-6A881FA6E581/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 18:23:19.205 ThaliTest[1648:3928670] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/00AC0E92-1EDA-4D25-A874-0C9FC9089447/Library/Cookies/Cookies.binarycookies
,2016-03-24 18:23:19.303 ThaliTest[1648:3928670] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 18:23:19.305 ThaliTest[1648:3928670] Multi-tasking -> Device: YES, App: YES
,2016-03-24 18:23:19.323 ThaliTest[1648:3928670] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 18:23:20.483 ThaliTest[1648:3928670] Using UIWebView
2016-03-24 18:23:20.487 ThaliTest[1648:3928670] [CDVTimer][handleopenurl] 0.232995ms
,2016-03-24 18:23:20.493 ThaliTest[1648:3928670] [CDVTimer][intentandnavigationfilter] 5.454004ms
2016-03-24 18:23:20.493 ThaliTest[1648:3928670] [CDVTimer][gesturehandler] 0.213981ms
2016-03-24 18:23:20.493 ThaliTest[1648:3928670] [CDVTimer][TotalPluginStartup] 6.723046ms
,2016-03-24 18:23:25.449 ThaliTest[1648:3928670] Resetting plugins due to page load.
,2016-03-24 18:23:27.824 ThaliTest[1648:3928670] Finished load of: file:///var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/index.html
,2016-03-24 18:23:28.018 ThaliTest[1648:3928670] JXcore Cordova plugin initializing
2016-03-24 18:23:28.020 ThaliTest[1648:3928826] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 18:23:42.097 ThaliTest[1648:3928826] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 18:23:42.098 ThaliTest[1648:3928826] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 18:23:42.099 ThaliTest[1648:3,928826] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 18:23:42.101 ThaliTest[1648:3928826] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CAB40E9B-D585-4451-9D41-13E89CFCB2B5/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52857
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52859
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
,DEBUG createNativeListener: listening 52862
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 52866
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
DEBUG createNativeListener: listening 52871
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
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52875
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
,DEBUG createNativeListener: listening 52879
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
DEBUG createNativeListener: listening 52883
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
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
DEBUG createNativeListener: listening 52887
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: mux close
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
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
,ok 29 native server should be closed
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
DEBUG createNativeListener: listening 52939
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 52943
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue
,# teardown
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
# teardown
,# setup
,# 18. queues handled independently
,ok 73 all short operations completed before the long resolves
# teardown
,# setup
,# 19. basic
,ok 74 sane
,# teardown
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
,# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52956
,2016-03-24 18:26:30.712 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 18:26:30.714 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements: success
ok 88 error should be null
ok 89 error should be null
2016-03-24 18:26:30.717 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:30.718 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
# teardown
,2016-03-24 18:26:30.858 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:30.859 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
2016-03-24 18:26:30.859 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 18:26:30.859 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:30.861 ThaliTest[1648,:3928826] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52958
,2016-03-24 18:26:31.246 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements
,2016-03-24 18:26:31.248 ThaliTest[1648:3928826] multipeer manager: start client restart timer: 0x1659b600
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:31.250 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
2016-03-24 18:26:31.264 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:31.265 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# teardown
,2016-03-24 18:26:31.579 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:31.579 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
2016-03-24 18:26:31.579 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 18:26:31.580 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:31.580 ThaliTest[1648:3928826] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:31.581 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52960
,2016-03-24 18:26:32.203 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening
,2016-03-24 18:26:32.204 ThaliTest[1648:3928826] server: starting 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:1
,2016-03-24 18:26:32.205 ThaliTest[1648:3928826] multipeer manager: start client restart timer: 0x1659b600
,2016-03-24 18:26:32.210 ThaliTest[1648:3928826] THEMultipeerManager initialized peer 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:1
,2016-03-24 18:26:32.213 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-24 18:26:32.271 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening
,2016-03-24 18:26:32.272 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
,2016-03-24 18:26:32.273 ThaliTest[1648:3928826] multipeer manager: stop client timer
,2016-03-24 18:26:32.277 ThaliTest[1648:3928826] server: starting 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:2
,2016-03-24 18:26:32.278 ThaliTest[1648:3928826] multipeer manager: start client restart timer: 0x1659b600
,2016-03-24 18:26:32.285 ThaliTest[1648:3928826] THEMultipeerManager initialized peer 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:2
,2016-03-24 18:26:32.286 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
,# teardown
,2016-03-24 18:26:32.624 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:32.624 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
2016-03-24 18:26:32.624 ThaliTest[1648:3928826] multipeer manager: stop client timer
20,16-03-24 18:26:32.625 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:32.625 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:32.626 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
ok 105 error should be null
# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52965
,2016-03-24 18:26:33.228 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:33.228 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
2016-03-24 18:26:33.228 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: suc,cess
ok 106 error should be null
ok 107 error should be null
2016-03-24 18:26:33.231 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:33.231 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
2016-03-24 18:26:33.231 ,ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
ok 109 error should be null
# teardown
,2016-03-24 18:26:33.592 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:33.592 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
2016-03-24 18:26:33.592 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 18:26:33.593 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:33.594 ThaliTest[1648,:3928826] jxcore: stopListeningForAdvertisements: success
ok 110 error should be null
ok 111 error should be null
# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52967
,ok 112 first call should succeed
ok 113 first call should succeed
ok 114 specific error should be returned
# teardown
,2016-03-24 18:26:34.224 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:34.224 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
2016-03-24 18:26:34.225 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:34.225 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:34.226 ThaliTest[1648,:3928826] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52969
2016-03-24 18:26:35.075 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements
2016-03-24 18:26:35.075 ThaliTest[1648:3928826] multipeer manager: start client restart timer: 0x1659b600
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:35.076 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements: success
,2016-03-24 18:26:35.089 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:26:35.089 ThaliTest[1648:3928826] server: starting 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:3
2016-03-24 18:26:35.089 ThaliTest[1648:3928826] THEMultipee,rManager initialized peer 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:3
2016-03-24 18:26:35.090 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
ok 118 discovery state matches
ok 119 advertising state matches
# teardown
,2016-03-24 18:26:35.268 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:35.268 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
2016-03-24 18:26:35.268 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 18:26:35.269 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:35.269 ThaliTest[1648:3928826] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:35.270 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements: success
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
ok 128 error should be null
# setup
,# 32. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 129 host address should match
ok 130 port should match
,ok 131 host address should be null
ok 132 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 133 error should be null
ok 134 error should be null
# setup
,# 33. Can call start/stopListeningForAdvertisements
,2016-03-24 18:26:57.336 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements
,2016-03-24 18:26:57.338 ThaliTest[1648:3928826] multipeer manager: start client restart timer: 0x1659b600
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:57.339 Th,aliTest[1648:3928826] jxcore: startListeningForAdvertisements: success
ok 135 Can call startListeningForAdvertisements without error
2016-03-24 18:26:57.340 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:57.340 ThaliTest,[1648:3928826] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:57.341 ThaliTest[1648:3928826] jxcore: stopListeningForAdverti,sements: success
ok 136 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-24 18:26:57.439 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:57.440 ThaliTest[1648:39288,26] jxcore: stopListeningForAdvertisements: success
ok 137 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:26:57.441 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:57.441 ThaliTest[1648:392882,6] THEMultipeerManager stopping peer
2016-03-24 18:26:57.441 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 18:26:58.118 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements
2016-03-24 18:26:58.118 ThaliTest[1648:3928826] multipeer manager: start client restart timer: 0x1659b600
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:58.122 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAd,vertisements without error
2016-03-24 18:26:58.124 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26,:58.125 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 18:26:58.208 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:58.208 ThaliTest[1648:3928826] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-24 18:26:58.209 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:26:58.210 ThaliTest[1648:39288,26] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:58.210 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
2016-03-24 18:26:58.210 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 18:26:59.259 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:26:59.260 ThaliTest[1648:3928826] server: starting 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:4
2016-03-24 18:26:59.260 ThaliTest[1648:3928826] multipeer m,anager: start client restart timer: 0x1659b600
2016-03-24 18:26:59.260 ThaliTest[1648:3928826] THEMultipeerManager initialized peer 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:4
2016-03-24 18:26:59.260 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:26:59.262 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:59.262 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
,2016-03-24 18:26:59.262 ThaliTest[1648:3928826] multipeer manager: stop client timer
2016-03-24 18:26:59.268 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-24 18:27:00.211 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:27:00.212 ThaliTest[1648:39288,26] jxcore: stopListeningForAdvertisements: success
ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:27:00.214 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:27:00.214 ThaliTest[1648:392882,6] THEMultipeerManager stopping peer
2016-03-24 18:27:00.214 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-24 18:27:00.793 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:00.794 ThaliTest[1648:3928826] server: starting 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:5
2016-03-24 18:27:00.794 ThaliTest[1648:3928826] multipeer m,anager: start client restart timer: 0x1659b600
2016-03-24 18:27:00.795 ThaliTest[1648:3928826] THEMultipeerManager initialized peer 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:5
2016-03-24 18:27:00.795 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:27:00.796 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:00.796 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
,2016-03-24 18:27:00.796 ThaliTest[1648:3928826] multipeer manager: stop client timer
2016-03-24 18:27:00.803 ThaliTest[1648:3928826] server: starting 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:6
2016-03-24 18:27:00.803 ThaliTest[1648:3928826] multipeer manager,: start client restart timer: 0x1659b600
2016-03-24 18:27:00.804 ThaliTest[1648:3928826] THEMultipeerManager initialized peer 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:6
2016-03-24 18:27:00.804 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-24 18:27:01.196 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 18:27:01.198 ThaliTest[1648:392882,6] jxcore: stopListeningForAdvertisements: success
ok 149 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:27:01.199 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:27:01.199 ThaliTest[1648:3928826,] THEMultipeerManager stopping peer
2016-03-24 18:27:01.199 ThaliTest[1648:3928826] multipeer manager: stop client timer
2016-03-24 18:27:01.200 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. peerAvailabilityChange is called
,2016-03-24 18:27:01.426 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:01.426 ThaliTest[1648:3928826] server: starting 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:27:01.427 ThaliTest[1648:3928826] multipeer m,anager: start client restart timer: 0x1659b600
2016-03-24 18:27:01.427 ThaliTest[1648:3928826] THEMultipeerManager initialized peer 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
2016-03-24 18:27:01.427 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-24 18:27:01.428 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-24 18:27:01.430 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements: success
ok 152 Can call startListeningForAdvertisements without error
,2016-03-24 18:27:02.625 ThaliTest[1648:3928670] client: found new peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:7
ok 153 peers must be an array
ok 154 peers must not be zero-length
ok 155 peer must have peerIdentifier
ok 156 peerIdentifier must be a strin,g
ok 157 peer must have peerAvailable
ok 158 peer must have pleaseConnect
,2016-03-24 18:27:02.635 ThaliTest[1648:3928670] client: found new peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:7
# teardown
,2016-03-24 18:27:05.998 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 18:27:05.999 ThaliTest[1648:392882,6] jxcore: stopListeningForAdvertisements: success
ok 159 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:27:05.999 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:27:06.000 ThaliTest[1648:3928826,] THEMultipeerManager stopping peer
2016-03-24 18:27:06.000 ThaliTest[1648:3928826] multipeer manager: stop client timer
2016-03-24 18:27:06.000 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Can connect to a remote peer
,2016-03-24 18:27:41.361 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:41.362 ThaliTest[1648:3928826] server: starting 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
2016-03-24 18:27:41.362 ThaliTest[1648:3928826] multipeer m,anager: start client restart timer: 0x1659b600
2016-03-24 18:27:41.362 ThaliTest[1648:3928826] THEMultipeerManager initialized peer 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
2016-03-24 18:27:41.362 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 161 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:27:41.364 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-24 18:27:41.365 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-24 18:27:43.406 ThaliTest[1648:3928670] client: found new peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"14C3A3B7-F65B-4CDF-8939-7B9ED734B,46B:8","pleaseConnect":0}]
2016-03-24 18:27:43.408 ThaliTest[1648:3928826] jxcore: connect 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
2016-03-24 18:27:43.408 ThaliTest[1648:3928826] client session: connect
2016-03-24 18:27:43.408 ThaliTest[1648:3928826] cli,ent session: stateChange:0->1 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
2016-03-24 18:27:43.412 ThaliTest[1648:3928670] client: found new peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [,{"peerAvailable":1,"peerIdentifier":"1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8","pleaseConnect":0}]
,2016-03-24 18:27:43.538 ThaliTest[1648:3928670] multipeer session: reset timer
,2016-03-24 18:27:43.540 ThaliTest[1648:3928670] server: rejecting invitation for lexical ordering 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8","pleaseConnect":1}]
,2016-03-24 18:27:46.864 ThaliTest[1648:3929366] client session: p2p link connected
,2016-03-24 18:27:46.873 ThaliTest[1648:3929366] client session: stateChange:1->2 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
2016-03-24 18:27:46.873 ThaliTest[1648:3929366] client session: fireConnectCallback: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
2016-03-24 1,8:27:46.873 ThaliTest[1648:3929366] jxcore: connect: success
INFO testThaliMobileNative: 
ok 163 Must have listeningPort
,ok 164 listeningPort must be a number
,ok 165 Connection must have clientPort
,ok 166 clientPort must be a number
,ok 167 Connection must have serverPort
,ok 168 serverPort must be a number
,ok 169 forward connection must have clientPort == 0
,ok 170 forward connection must have serverPort == 0
,# teardown
,2016-03-24 18:27:50.276 ThaliTest[1648:3929344] client session: not connected 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
2016-03-24 18:27:50.276 ThaliTest[1648:3929344] client session: onLinkFailure: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
2016-03-24 18:27:50.276 ThaliTest[1648:3929344] client session: disconnect
2016-03-24 18:27:50.277 ThaliTest[1648:3929344] client session: stateChange:2->0 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
,2016-03-24 18:27:50.561 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 18:27:50.562 ThaliTest[1648:3928826] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 18:27:50.563 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening
2016-03-24 18:27:50.563 ThaliTest[1648:3928826] THEMultipeerManager stopping peer
,2016-03-24 18:27:50.564 ThaliTest[1648:3928826] multipeer manager: stop client timer
,2016-03-24 18:27:50.564 ThaliTest[1648:3928826] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can shift large amounts of data
,2016-03-24 18:27:51.244 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:51.244 ThaliTest[1648:3928826] server: starting 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:27:51.244 ThaliTest[1648:3928826] multipeer m,anager: start client restart timer: 0x1659b600
2016-03-24 18:27:51.245 ThaliTest[1648:3928826] THEMultipeerManager initialized peer 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:27:51.245 ThaliTest[1648:3928826] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:27:51.247 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-24 18:27:51.248 ThaliTest[1648:3928826] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-24 18:27:53.454 ThaliTest[1648:3928670] client: found new peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
2016-03-24 18:27:53.454 ThaliTest[1648:3928670] client: found new peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8
2016-03-24 18:27:53.455 ThaliTes,t[1648:3928826] jxcore: connect 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
2016-03-24 18:27:53.455 ThaliTest[1648:3928826] client session: connect
2016-03-24 18:27:53.456 ThaliTest[1648:3928826] client session: stateChange:0->1 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,2016-03-24 18:27:53.552 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:27:53.553 ThaliTest[1648:3928670] server: rejecting invitation from 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8,E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8)
,2016-03-24 18:27:56.112 ThaliTest[1648:3929366] client session: p2p link connected
,2016-03-24 18:27:56.116 ThaliTest[1648:3929366] client session: stateChange:1->2 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
2016-03-24 18:27:56.116 ThaliTest[1648:3929366] client session: fireConnectCallback: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
,2016-03-24 18:27:56.116 ThaliTest[1648:3929366] jxcore: connect: success
,INFO testThaliMobileNative: 
,INFO testThaliMobileNative: Forward connection
,2016-03-24 18:27:56.121 ThaliTest[1648:3928670] client: relay established
2016-03-24 18:27:56.121 ThaliTest[1648:3928670] client: new accepted socket: 0x1ae20410
,INFO testThaliMobileNative: forwardSend
,INFO testThaliMobileNative: forwardData
ok 175 received should match sent forward
# teardown
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
2016-03-24 18:27:56.824 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:27:56.825 ThaliTest[1648:3928670] server: rejecting invitation from 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7)
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-24 18:28:05.084 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:28:05.085 ThaliTest[1648:3928670] server: disconnecting to refresh session (1CD2D13E-74CD-4DBE-AC77-A03D24A564FA)
2016-03-24 18:28:05.085 ThaliTest[1648:3928670], server: rejecting invitation from 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7)
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-24 18:28:11.246 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:28:11.265 ThaliTest[1648:3928670] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-24 18:28:17.988 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:28:17.988 ThaliTest[1648:3928670] server: disconnecting to refresh session (1CD2D13E-74CD-4DBE-AC77-A03D24A564FA)
2016-03-24 18:28:17.989 ThaliTest[1648:3928670] server: rejecting invitation from 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7)
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-24 18:28:30.965 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:28:30.965 ThaliTest[1648:3928670] server: disconnecting to refresh session (1CD2D13E-74CD-4DBE-AC77-A03D24A564FA)
2016-03-24 18:28:30.965 ThaliTest[1648:3928670], server: rejecting invitation from 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7)
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-24 18:28:31.246 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:28:31.262 ThaliTest[1648:3928670] client: found updated peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
INFO testThaliMobileNative: forwardData
,2016-03-24 18:28:31.272 ThaliTest[1648:3928670] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-24 18:28:43.905 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:28:43.905 ThaliTest[1648:3928670] server: disconnecting to refresh session (1CD2D13E-74CD-4DBE-AC77-A03D24A564FA)
2016-03-24 18:28:43.906 ThaliTest[1648:3928670], server: rejecting invitation from 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7)
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-24 18:28:51.246 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:28:51.268 ThaliTest[1648:3928670] client: found existing peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
2016-03-24 18:28:51.269 ThaliTest[1648:3928670] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-24 18:28:53.639 ThaliTest[1648:3928670] client: lost peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
2016-03-24 18:28:53.639 ThaliTest[1648:3928670] client session: onPeerLost: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
2016-03-24 18:28:53.639 ThaliTest[164,8:3928670] client session: onLinkFailure: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
INFO testThaliMobileNative: forwardData
2016-03-24 18:28:53.639 ThaliTest[1648:3928670] client session: disconnect
2016-03-24 18:28:53.641 ThaliTest[1648:3928670] client sess,ion: stateChange:2->0 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,2016-03-24 18:28:54.347 ThaliTest[1648:3928670] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,2016-03-24 18:28:57.037 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:28:57.037 ThaliTest[1648:3928670] server: disconnecting to refresh session (1CD2D13E-74CD-4DBE-AC77-A03D24A564FA)
2016-03-24 18:28:57.037 ThaliTest[1648:3928670], server: rejecting invitation from 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7)
,2016-03-24 18:29:10.146 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:29:10.146 ThaliTest[1648:3928670] server: disconnecting to refresh session (1CD2D13E-74CD-4DBE-AC77-A03D24A564FA)
2016-03-24 18:29:10.147 ThaliTest[1648:3928670], server: rejecting invitation from 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7)
,2016-03-24 18:29:11.246 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:29:11.272 ThaliTest[1648:3928670] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
2016-03-24 18:29:11.273 ThaliTest[1648:3928670] client: found existing peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
,Disconnected from the test server
,2016-03-24 18:29:23.638 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:29:23.638 ThaliTest[1648:3928670] server: disconnecting to refresh session (1CD2D13E-74CD-4DBE-AC77-A03D24A564FA)
2016-03-24 18:29:23.638 ThaliTest[1648:3928670], server: rejecting invitation from 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7)
,2016-03-24 18:29:31.246 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:29:31.269 ThaliTest[1648:3928670] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
2016-03-24 18:29:31.270 ThaliTest[1648:3928670] client: found existing peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
,2016-03-24 18:29:34.002 ThaliTest[1648:3928670] client: lost peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
2016-03-24 18:29:34.002 ThaliTest[1648:3928670] client session: onPeerLost: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
,2016-03-24 18:29:35.735 ThaliTest[1648:3928670] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,2016-03-24 18:29:36.224 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:29:36.225 ThaliTest[1648:3928670] server: disconnecting to refresh session (1CD2D13E-74CD-4DBE-AC77-A03D24A564FA)
2016-03-24 18:29:36.225 ThaliTest[1648:3928670], server: rejecting invitation from 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7)
,Reconnected to the test server
,2016-03-24 18:29:49.392 ThaliTest[1648:3928670] multipeer session: reset timer
2016-03-24 18:29:49.392 ThaliTest[1648:3928670] server: disconnecting to refresh session (1CD2D13E-74CD-4DBE-AC77-A03D24A564FA)
2016-03-24 18:29:49.392 ThaliTest[1648:3928670], server: rejecting invitation from 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA due to previous generation (97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9 != 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7)
,2016-03-24 18:29:51.246 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:29:51.267 ThaliTest[1648:3928670] client: found existing peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
2016-03-24 18:29:51.268 ThaliTest[1648:3928670] client: found existing peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
,2016-03-24 18:30:02.386 ThaliTest[1648:3928670] client: lost peer: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
2016-03-24 18:30:02.387 ThaliTest[1648:3928670] client session: onPeerLost: 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B
,2016-03-24 18:30:11.246 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:30:31.246 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:30:51.246 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:31:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:31:31.158 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:31:51.158 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:32:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:32:31.158 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:32:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:33:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:33:31.158 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:33:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:34:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:34:31.158 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:34:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:35:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:35:31.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:35:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:36:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:36:31.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:36:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:37:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:37:31.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:37:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:38:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,Disconnected from the test server
,2016-03-24 18:38:31.159 ThaliTest[1648:3928670] multipeer manager: restart client
,Reconnected to the test server
,2016-03-24 18:38:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:39:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:39:31.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:39:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:40:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:40:31.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:40:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:41:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:41:31.158 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:41:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:42:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:42:31.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:42:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:43:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:43:31.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:43:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:44:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:44:31.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:44:51.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:45:11.159 ThaliTest[1648:3928670] multipeer manager: restart client
,2016-03-24 18:45:31.159 ThaliTest[1648:3928670] multipeer manager: restart client

```
