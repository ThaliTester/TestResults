#### Test 64941069b7d3db0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64941069b7d3db0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/1525182B-BB08-4A40-9525-D0006A490722/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1525182B-BB08-4A40-9525-D0006A490722/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64941069b7d3db0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64941069b7d3db0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50257"
,(lldb)     command script import "/tmp/1525182B-BB08-4A40-9525-D0006A490722/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 15:26:07.183 ThaliTest[2678:4883014] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0178D705-5BD9-40B0-90DC-6C65F0932AAE/Library/Cookies/Cookies.binarycookies
,2016-04-01 15:26:07.440 ThaliTest[2678:4883014] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 15:26:07.441 ThaliTest[2678:4883014] Multi-tasking -> Device: YES, App: YES
,2016-04-01 15:26:07.461 ThaliTest[2678:4883014] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 15:26:08.263 ThaliTest[2678:4883014] Using UIWebView
2016-04-01 15:26:08.266 ThaliTest[2678:4883014] [CDVTimer][handleopenurl] 0.165999ms
,2016-04-01 15:26:08.270 ThaliTest[2678:4883014] [CDVTimer][intentandnavigationfilter] 3.777027ms
2016-04-01 15:26:08.270 ThaliTest[2678:4883014] [CDVTimer][gesturehandler] 0.131011ms
2016-04-01 15:26:08.270 ThaliTest[2678:4883014] [CDVTimer][TotalPluginS,tartup] 4.696965ms
,2016-04-01 15:26:11.488 ThaliTest[2678:4883014] Resetting plugins due to page load.
,2016-04-01 15:26:12.965 ThaliTest[2678:4883014] Finished load of: file:///var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/index.html
,2016-04-01 15:26:13.147 ThaliTest[2678:4883014] JXcore Cordova plugin initializing
2016-04-01 15:26:13.148 ThaliTest[2678:4883167] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 15:26:21.449 ThaliTest[2678:4883167] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 15:26:21.450 ThaliTest[2678:4883167] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 15:26:21.450 ThaliTest[2678:4,883167] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 15:26:21.451 ThaliTest[2678:4883167] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2BF1068B-A51D-4A20-AEDF-29D10B3CE1ED/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58162
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58164
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
DEBUG createNativeListener: listening 58167
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
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58171
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
,ok 9 Send/recvd #2 should be equal length
,ok 10 Send/recvd #2 should be same
,ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58176
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
,DEBUG createNativeListener: listening 58180
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
DEBUG createNativeListener: listening 58184
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 58188
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
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
DEBUG createNativeListener: listening 58192
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
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
D,EBUG createNativeListener: new mux
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
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58244
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
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
DEBUG createNativeListener: listening 58248
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
,# teardown
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
,[{"uuid":"00808060-5bbe-4b5b-bcc4-94f4c6c425a9","data":"custom data"},{"uuid":"9268d93e-6496-4daa-a1e8-946cc4e33b31","data":"custom data"},{"uuid":"2be5ebec-a935-4f30-8b82-7039b8b8a0e2","data":"custom data"},{"uuid":"bd0104a2-12f2-49a9-9a5a-2c37d046ad3e","data":"custom data"}]
ok 76 test participant has uuid
,ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83 participant data matches
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
,# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58258
2016-04-01 15:29:00.151 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:29:00.152 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-01 15:29:00.154 ThaliTest[2678:4883167] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:29:00.154 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-01 15:29:00.373 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening
2016-04-01 15:29:00.373 ThaliTest[2678:4883167] THEMultipeerManager stopping peer
2016-04-01 15:29:00.373 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening: success
2016-04-01 15:29:00.374 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:29:00.374 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58260
,2016-04-01 15:29:00.649 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements
,2016-04-01 15:29:00.651 ThaliTest[2678:4883167] multipeer manager: start client restart timer: 0x17eb1520
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 15:29:00.652 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
,2016-04-01 15:29:00.787 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 15:29:00.788 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-01 15:29:01.574 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening
2016-04-01 15:29:01.574 ThaliTest[2678:4883167] THEMultipeerManager stopping peer
2016-04-01 15:29:01.574 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening: success
2016-04-01 15:29:01.574 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements
2016-04-01 15:29:01.574 ThaliTest[2678:4883167] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:29:01.575 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58262
2016-04-01 15:29:48.554 ThaliTest[2678:4883167] jxcore: startUpdateAdvertisingAndListening
2016-04-01 15:29:48.555 ThaliTest[2678:4883167] server: starting D1,9A1B90-A6F2-46A8-9688-806FAF3329E8:1
2016-04-01 15:29:48.555 ThaliTest[2678:4883167] multipeer manager: start client restart timer: 0x17eb1520
2016-04-01 15:29:48.555 ThaliTest[2678:4883167] THEMultipeerManager initialized peer D19A1B90-A6F2-46A8-9688-806FAF3329E8:1
2016-04-01 15:29:48.555 ThaliTest[2678:4883167] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-01 15:29:48.572 ThaliTest[2678:4883167] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 15:29:48.573 ThaliTest[2678:4883167] THEMultipeerManager stopping peer
,2016-04-01 15:29:48.575 ThaliTest[2678:4883167] multipeer manager: stop client timer
,2016-04-01 15:29:48.577 ThaliTest[2678:4883167] server: starting D19A1B90-A6F2-46A8-9688-806FAF3329E8:2
,2016-04-01 15:29:48.580 ThaliTest[2678:4883167] multipeer manager: start client restart timer: 0x17eb1520
,2016-04-01 15:29:48.583 ThaliTest[2678:4883167] THEMultipeerManager initialized peer D19A1B90-A6F2-46A8-9688-806FAF3329E8:2
,2016-04-01 15:29:48.584 ThaliTest[2678:4883167] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
,# teardown
,2016-04-01 15:29:49.759 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening
2016-04-01 15:29:49.759 ThaliTest[2678:4883167] THEMultipeerManager stopping peer
2016-04-01 15:29:49.759 ThaliTest[2678:4883167] multipeer manager: stop client timer
2016-04-01 15:29:49.759 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening: success
2016-04-01 15:29:49.759 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:29:49.760 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58267
2016-04-01 15:29:50.463 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening
2016-04-01 15:29:50.463 ThaliTest[2678:4883167] THEMultipeerManager stoppi,ng peer
2016-04-01 15:29:50.463 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
,2016-04-01 15:29:50.465 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening
2016-04-01 15:29:50.467 ThaliTest[2678:4883167] THEMultipeerManager stopping peer
2016-04-01 15:29:50.467 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-01 15:29:51.766 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening
2016-04-01 15:29:51.766 ThaliTest[2678:4883167] THEMultipeerManager stopping peer
2016-04-01 15:29:51.766 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 15:29:51.766 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:29:51.767 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58269
,ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
,# teardown
,2016-04-01 15:30:22.570 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening
2016-04-01 15:30:22.571 ThaliTest[2678:4883167] THEMultipeerManager stopping peer
2016-04-01 15:30:22.571 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening: success
2016-04-01 15:30:22.571 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:30:22.572 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58271
2016-04-01 15:30:23.191 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements
2016-04-01 15:30:23.191 ThaliTest[2678:4883167] multipeer manager: start client restart timer: 0x17eb1520
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 15:30:23.192 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements: success,
,2016-04-01 15:30:23.233 ThaliTest[2678:4883167] jxcore: startUpdateAdvertisingAndListening
2016-04-01 15:30:23.233 ThaliTest[2678:4883167] server: starting D19A1B90-A6F2-46A8-9688-806FAF3329E8:3
2016-04-01 15:30:23.234 ThaliTest[2678:4883167] THEMultipee,rManager initialized peer D19A1B90-A6F2-46A8-9688-806FAF3329E8:3
2016-04-01 15:30:23.234 ThaliTest[2678:4883167] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-01 15:30:23.449 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening
2016-04-01 15:30:23.449 ThaliTest[2678:4883167] THEMultipeerManager stopping peer
2016-04-01 15:30:23.449 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 15:30:23.449 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements
2016-04-01 15:30:23.449 ThaliTest[2678:4883167] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 15:30:23.450 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 123 error should be null
ok 124 error should be null
# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
,ok 126 should not have been called more than once
,# teardown
,ok 127 error should be null
,ok 128 error should be null
,# setup
,# 32. can get the network status
,ok 129 network status should have certain non-empty properties
,# teardown
,ok 130 error should be null
ok 131 error should be null
# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
ok 133 port should match
,ok 134 host address should be null
,ok 135 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-01 15:31:10.843 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements
2016-04-01 15:31:10.843 ThaliTest[2678:4883167] multipeer manager: start client restart timer: 0x17eb1520
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 15:31:10.844 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-01 15:31:10.845 ThaliTes,t[2678:4883167] jxcore: stopListeningForAdvertisements
2016-04-01 15:31:10.845 ThaliTest[2678:4883167] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:31:10.846 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 15:31:11.865 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:31:11.866 ThaliTest[2678:48831,67] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 15:31:11.867 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening
2016-04-01 15:31:11.867 ThaliTest[2678:4883167] THEMultipeerManager stopping peer
2016-04-01 15:31:11.867 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-01 15:31:16.635 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements
2016-04-01 15:31:16.636 ThaliTest[2678:4883167] multipeer manager: start client restart timer: 0x17eb1520
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 15:31:16.637 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-01 15:31:16.637 ThaliTes,t[2678:4883167] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 15:31:16.638 ThaliTest[2678:4883167] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-01 15:31:36.637 ThaliTest[2678:4883014] multipeer manager: restart client
,2016-04-01 15:31:56.637 ThaliTest[2678:4883014] multipeer manager: restart client
,2016-04-01 15:32:08.495 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements
2016-04-01 15:32:08.495 ThaliTest[2678:4883167] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-01 15:32:08.496 ThaliTest[2678:4883167] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 15:32:08.497 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening
2016-04-01 15:32:08.497 ThaliTest[2678:4883167] THEMultipeerManager stopping peer
2016-04-01 15:32:08.498 ThaliTest[2678:4883167] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup

```
