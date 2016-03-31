#### Test 645312549bcf247_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/3C6E3C52-A118-4808-ACB3-88F8810CB3EF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3C6E3C52-A118-4808-ACB3-88F8810CB3EF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/645312549bcf247/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49489"
,(lldb)     command script import "/tmp/3C6E3C52-A118-4808-ACB3-88F8810CB3EF/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 01:47:36.778 ThaliTest[2531:4648767] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/86B98C83-3AEC-47AA-AEA4-44C10B692117/Library/Cookies/Cookies.binarycookies
,2016-03-31 01:47:37.024 ThaliTest[2531:4648767] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 01:47:37.025 ThaliTest[2531:4648767] Multi-tasking -> Device: YES, App: YES
,2016-03-31 01:47:37.043 ThaliTest[2531:4648767] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 01:47:37.853 ThaliTest[2531:4648767] Using UIWebView
2016-03-31 01:47:37.856 ThaliTest[2531:4648767] [CDVTimer][handleopenurl] 0.138998ms
,2016-03-31 01:47:37.859 ThaliTest[2531:4648767] [CDVTimer][intentandnavigationfilter] 2.762020ms
2016-03-31 01:47:37.859 ThaliTest[2531:4648767] [CDVTimer][gesturehandler] 0.144005ms
2016-03-31 01:47:37.859 ThaliTest[2531:4648767] [CDVTimer][TotalPluginStartup] 3.656030ms
,2016-03-31 01:47:41.062 ThaliTest[2531:4648767] Resetting plugins due to page load.
,2016-03-31 01:47:42.364 ThaliTest[2531:4648767] Finished load of: file:///var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/index.html
,2016-03-31 01:47:42.549 ThaliTest[2531:4648767] JXcore Cordova plugin initializing
,2016-03-31 01:47:42.550 ThaliTest[2531:4648937] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 01:47:50.832 ThaliTest[2531:4648937] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-31 01:47:50.833 ThaliTest[2531:4648937] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-31 01:47:50.834 ThaliTest[2531:4648937] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 01:47:50.837 ThaliTest[2531:4648937] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0EC5A17F-EC93-4416-B69D-3B49E5276B26/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-31 01:47:57.576 ThaliTest[2531:4648767] THREAD WARNING: ['JXcore'] took '6378.930908' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56202
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56204
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
DEBUG createNativeListener: listening 56207
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
DEBUG createNativeListener: listening 56211
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 56216
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
DEBUG createNativeListener: listening 56220
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
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
DEBUG createNativeListener: listening 56224
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 56228
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
,DEBUG createNativeListener: listening 56232
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56284
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
,ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56288
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
# teardown
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
,ok 65 fourth
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
,# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56298
2016-03-31 01:50:22.073 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.074 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
,ok 89 error should be null
ok 90 error should be null
2016-03-31 01:50:22.076 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.077 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
# teardown
,2016-03-31 01:50:22.252 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:22.252 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:50:22.253 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 01:50:22.253 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 01:50:22.254 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56300
,2016-03-31 01:50:22.587 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements
,2016-03-31 01:50:22.589 ThaliTest[2531:4648937] multipeer manager: start client restart timer: 0x17ed3390
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:22.590 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,2016-03-31 01:50:22.640 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 01:50:22.641 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,# teardown
,2016-03-31 01:50:22.756 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:22.757 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
,2016-03-31 01:50:22.757 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
2016-03-31 01:50:22.757 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:22.757 ThaliTest[2531:4648937] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:22.758 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 99 error should be null
ok 100 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56302
,2016-03-31 01:50:23.530 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:50:23.531 ThaliTest[2531:4648937] server: starting 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:1
2016-03-31 01:50:23.531 ThaliTest[2531:4648937] multipeer m,anager: start client restart timer: 0x17ed3390
2016-03-31 01:50:23.531 ThaliTest[2531:4648937] THEMultipeerManager initialized peer 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:1
2016-03-31 01:50:23.531 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
2016-03-31 01:50:23.543 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:50:23.543 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:50:23.543 ThaliTest[2531:4648937] multipeer manager: stop client timer
2016-03-31 01:50:23.543 ThaliTest[2531:4648937] server: starting 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:2
,2016-03-31 01:50:23.544 ThaliTest[2531:4648937] multipeer manager: start client restart timer: 0x17ed3390
2016-03-31 01:50:23.549 ThaliTest[2531:4648937] THEMultipeerManager initialized peer 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:2
2016-03-31 01:50:23.550 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
# teardown
,2016-03-31 01:50:24.492 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:24.492 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:50:24.492 ThaliTest[2531:4648937] multipeer manager: stop client timer
2016-03-31 01:50:24.492 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
2016-03-31 01:50:24.493 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 01:50:24.494 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 105 error should be null
,ok 106 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56307
,2016-03-31 01:50:25.121 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:25.122 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:50:25.122 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
,2016-03-31 01:50:25.124 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:25.124 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:50:25.124 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
,# teardown
,2016-03-31 01:50:25.557 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:25.557 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:50:25.557 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
2016-03-31 01:50:25.557 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:25.558 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
,ok 111 error should be null
,ok 112 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56309
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
,# teardown
,2016-03-31 01:50:27.180 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:27.180 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:50:27.180 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 01:50:27.181 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:27.181 ThaliTest[2531,:4648937] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56311
2016-03-31 01:50:27.649 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements
2016-03-31 01:50:27.649 ThaliTest[2531:4648937] multipeer manager: start client restart timer: 0x17ed3390
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 01:50:27.652 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements: success
,2016-03-31 01:50:27.683 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:50:27.683 ThaliTest[2531:4648937] server: starting 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:3
2016-03-31 01:50:27.683 ThaliTest[2531:4648937] THEMultipee,rManager initialized peer 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:3
2016-03-31 01:50:27.683 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening: success
ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
,# teardown
,2016-03-31 01:50:27.767 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:27.767 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:50:27.768 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
2016-03-31 01:50:27.768 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:27.768 ThaliTest[2531:4648937] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:27.769 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 121 error should be null
ok 122 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 123 should be called once
ok 124 should not have been called more than once
# teardown
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
ok 133 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-03-31 01:50:57.374 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements
2016-03-31 01:50:57.375 ThaliTest[2531:4648937] multipeer manager: start client restart timer: 0x17ed3390
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:57.375 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
,2016-03-31 01:50:57.377 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:57.378 ThaliTest[2531:4648937] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:57.379 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-31 01:50:57.625 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:57.625 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
,ok 138 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-31 01:50:57.627 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:57.627 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:50:57.627 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 01:50:58.149 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements
2016-03-31 01:50:58.149 ThaliTest[2531:4648937] multipeer manager: start client restart timer: 0x17ed3390
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:58.150 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-31 01:50:58.151 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 01:50:58.152 ThaliTest[2531:4648937] jxcore: startListeningForAdv,ertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-31 01:50:58.291 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
2016-03-31 01:50:58.292 ThaliTest[2531:4648937] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:50:58.292 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:50:58.293 ThaliTest[2531:4648,937] jxcore: stopAdvertisingAndListening
2016-03-31 01:50:58.293 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:50:58.293 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-03-31 01:51:15.071 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 01:51:15.072 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
,ok 144 Can call stopListeningForAdvertisements without error
,2016-03-31 01:51:15.074 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 01:51:15.075 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
,ok 145 Can call stopListeningForAdvertisements without error
,# teardown
,37] THEMultipeerManager stopping peer
2016-03-31 01:51:18.400 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 147 Should be able to call stopAdvertisingAndListening in teardown
# setup
2016-03-31 01:51:18.399 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:18.400 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
ok 146 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:18.400 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:18.400 ThaliTest[2531:46489,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 01:51:18.714 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:18.715 ThaliTest[2531:4648937] server: starting 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:4
2016-03-31 01:51:18.715 ThaliTest[2531:4648937] multipeer manager: start client restart timer: 0x17ed3390
2016-03-31 01:51:18.715 ThaliTest[2531:4648937] THEMultipeerManager initialized peer 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:4
2016-03-31 01:51:18.715 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 148 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:18.716 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:18.716 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
,2016-03-31 01:51:18.716 ThaliTest[2531:4648937] multipeer manager: stop client timer
2016-03-31 01:51:18.720 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 149 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 01:51:18.846 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:18.847 ThaliTest[2531:46489,37] jxcore: stopListeningForAdvertisements: success
ok 150 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:18.848 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:18.848 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:51:18.848 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 151 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 01:51:19.495 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:19.495 ThaliTest[2531:4648937] server: starting 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:5
2016-03-31 01:51:19.496 ThaliTest[2531:4648937] multipeer manager: start client restart timer: 0x17ed3390
2016-03-31 01:51:19.496 ThaliTest[2531:4648937] THEMultipeerManager initialized peer 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:5
2016-03-31 01:51:19.496 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening: success
ok 152 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:19.497 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:19.497 ThaliTest[2531:4648937] THEMultipeerManager stopping pee,r
,2016-03-31 01:51:19.497 ThaliTest[2531:4648937] multipeer manager: stop client timer
2016-03-31 01:51:19.502 ThaliTest[2531:4648937] server: starting 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:6
2016-03-31 01:51:19.502 ThaliTest[2531:4648937] multipeer manager: start client restart timer: 0x17ed3390
2016-03-31 01:51:19.502 ThaliTest[2531:4648937] THEMultipeerManager initialized peer 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:6
2016-03-31 01:51:19.502 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening: success
ok 153 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 01:51:19.629 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 01:51:19.630 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
ok 154 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:19.630 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:19.631 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:51:19.631 ThaliTest[2531:4648937] multipeer manager: stop client timer
2016-03-31 01:51:19.631 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 155 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-03-31 01:51:20.623 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:20.623 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:51:20.623 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 156 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:20.624 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:20.624 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:51:20.624 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 157 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 01:51:29.367 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:29.368 ThaliTest[2531:46489,37] jxcore: stopListeningForAdvertisements: success
ok 158 Should be able to call stopListeningForAdvertisements in teardown
2016-03-31 01:51:29.369 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:29.369 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:51:29.369 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-03-31 01:51:38.491 ThaliTest[2531:4648937] jxcore: connect foo
2016-03-31 01:51:38.492 ThaliTest[2531:4648937] jxcore: connect: fail: Start browsing first
,not ok 160 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-03-31 01:51:38.586 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 01:51:38.587 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-31 01:51:38.588 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:38.588 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:51:38.588 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-03-31 01:51:38.866 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:38.866 ThaliTest[2531:4648937] server: starting 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:38.866 ThaliTest[2531:4648937] multipeer m,anager: start client restart timer: 0x17ed3390
2016-03-31 01:51:38.867 ThaliTest[2531:4648937] THEMultipeerManager initialized peer 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7
2016-03-31 01:51:38.867 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening: success
ok 163 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 01:51:38.868 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 01:51:38.868 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-31 01:51:39.956 ThaliTest[2531:4648767] client: found new peer: 42E93D78-2507-4BE0-9192-FC412A882204:7
ok 165 peers must be an array
ok 166 peers must not be zero-length
ok 167 peer must have peerIdentifier
ok 168 peerIdentifier must be a strin,g
ok 169 peer must have peerAvailable
ok 170 peer must have pleaseConnect
,# teardown
,2016-03-31 01:51:39.977 ThaliTest[2531:4648767] client: found new peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:7
,2016-03-31 01:51:43.366 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 01:51:43.367 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-31 01:51:43.369 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:51:43.369 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
2016-03-31 01:51:43.369 ThaliTest[2531:4648937] multipeer manager: stop client timer
2016-03-31 01:51:43.369 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-03-31 01:51:43.835 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:51:43.836 ThaliTest[2531:4648937] server: starting 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:51:43.836 ThaliTest[2531:4648937] multipeer m,anager: start client restart timer: 0x17ed3390
2016-03-31 01:51:43.836 ThaliTest[2531:4648937] THEMultipeerManager initialized peer 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8
2016-03-31 01:51:43.836 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:51:43.837 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-31 01:51:43.839 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-31 01:51:44.764 ThaliTest[2531:4648767] client: found new peer: 42E93D78-2507-4BE0-9192-FC412A882204:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"42E93D78-2507-4BE0-9192-FC412A882204:7","pleaseConnect":0}]
,2016-03-31 01:51:44.766 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:44.766 ThaliTest[2531:4648937] client: server will connect
2016-03-31 01:51:44.767 ThaliTest[2531:4648937] client session: reverseConn,ect
2016-03-31 01:51:44.767 ThaliTest[2531:4648937] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:7
,2016-03-31 01:51:45.227 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:51:45.227 ThaliTest[2531:4648767] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8 != 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7)
,2016-03-31 01:51:46.124 ThaliTest[2531:4648767] client: found new peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9BF3B351-B42F-4B62-994E-93C3F024E3C4:7","pleaseConnect":0}]
,2016-03-31 01:51:46.190 ThaliTest[2531:4649397] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:46.190 ThaliTest[2531:4649397] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:51:46.190 ThaliTest[2531:4649397] client session: disconnect
2016-03-31 01:51:46.190 ThaliTest[2531:4649397] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:7
,2016-03-31 01:51:46.191 ThaliTest[2531:4649397] client session: no connect callback (server initiated)
,2016-03-31 01:51:48.364 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:51:48.364 ThaliTest[2531:4648767] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:51:48.365 ThaliTest[2531:4648767] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8 != 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7)
,2016-03-31 01:51:51.515 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:51:51.515 ThaliTest[2531:4648767] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:51:51.515 ThaliTest[2531:4648767] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8 != 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7)
,2016-03-31 01:51:54.704 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:51:54.705 ThaliTest[2531:4648767] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:51:54.705 ThaliTest[2531:4648767] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8 != 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7)
,2016-03-31 01:51:54.767 ThaliTest[2531:4648767] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 01:51:57.773 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:57.773 ThaliTest[2531:4648937] client: server will connect
2016-03-31 01:51:57.773 ThaliTest[2531:4648937] client session: reverseConnect
2016-03-31 01:51:57.774 ThaliTest[2531:4648937] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:7
,2016-03-31 01:51:57.803 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:51:57.804 ThaliTest[2531:4648767] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:51:57.805 ThaliTest[2531:4648767] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8 != 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7)
,2016-03-31 01:51:57.859 ThaliTest[2531:4649397] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:57.859 ThaliTest[2531:4649397] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:51:57.859 ThaliTest[2531:4649397] client session: disconnect
2016-03-31 01:51:57.860 ThaliTest[2531:4649397] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:51:57.860 ThaliTest[2531:4649397] client session: no connect callb,ack (server initiated)
,2016-03-31 01:52:01.405 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:52:01.405 ThaliTest[2531:4648767] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:52:01.405 ThaliTest[2531:4648767] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8 != 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7)
,2016-03-31 01:52:03.836 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:52:03.852 ThaliTest[2531:4648767] client: found updated peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:03.853 ThaliTest[2531:4648767] client: found updated peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"42E93D78-2507-4BE0-9192-FC412A882204:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9BF3B351-B42F-4B62-994E-93C3F024E3C4:8","pleaseConnect":0}]
,2016-03-31 01:52:04.566 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:52:04.566 ThaliTest[2531:4648767] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:52:04.566 ThaliTest[2531:4648767], server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8 != 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7)
,2016-03-31 01:52:07.749 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:52:07.749 ThaliTest[2531:4648767] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:52:07.749 ThaliTest[2531:4648767] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8 != 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7)
,2016-03-31 01:52:07.774 ThaliTest[2531:4648767] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 01:52:10.784 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:10.784 ThaliTest[2531:4648937] client: server will connect
2016-03-31 01:52:10.785 ThaliTest[2531:4648937] client session: reverseConnect
2016-03-31 01:52:10.785 ThaliTest[2531:4648937] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:10.903 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:52:10.903 ThaliTest[2531:4648767] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:52:10.903 ThaliTest[2531:4648767] server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8 != 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7)
,2016-03-31 01:52:10.956 ThaliTest[2531:4649501] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:10.957 ThaliTest[2531:4649501] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:10.957 ThaliTest[2531:4649501] client session: disconnect
2016-03-31 01:52:10.957 ThaliTest[2531:4649501] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:10.958 ThaliTest[2531:4649501] client session: no connect callback (server initiated)
,2016-03-31 01:52:14.168 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:52:14.168 ThaliTest[2531:4648767] server: disconnecting to refresh session (42E93D78-2507-4BE0-9192-FC412A882204)
2016-03-31 01:52:14.168 ThaliTest[2531:4648767], server: rejecting invitation from 42E93D78-2507-4BE0-9192-FC412A882204 due to previous generation (25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:8 != 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:7)
,2016-03-31 01:52:20.785 ThaliTest[2531:4648767] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 01:52:23.795 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:23.795 ThaliTest[2531:4648937] client: server will connect
2016-03-31 01:52:23.795 ThaliTest[2531:4648937] client session: reverseConnect
2016-03-31 01:52:23.795 ThaliTest[2531:4648937] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:23.837 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:52:23.853 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:23.853 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
,2016-03-31 01:52:33.795 ThaliTest[2531:4648767] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 01:52:36.804 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:36.804 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:36.805 ThaliTest[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 01:52:39.814 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:39.815 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:39.815 ThaliTest[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 01:52:42.824 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:42.825 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:42.825 Thali,Test[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 01:52:43.837 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:52:43.853 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:52:43.853 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:45.839 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:45.840 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:45.840 Thali,Test[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 01:52:48.850 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:48.851 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:48.851 ThaliTest[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 01:52:51.859 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:51.860 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:7
2016-03-31 01:52:51.860 ThaliTest[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 175 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-31 01:52:51.961 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 01:52:51.962 ThaliTest[2531:4648937] jxcore: stopListeningForAdvertisements: success
,ok 176 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-31 01:52:51.964 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening
2016-03-31 01:52:51.964 ThaliTest[2531:4648937] THEMultipeerManager stopping peer
,2016-03-31 01:52:51.964 ThaliTest[2531:4648937] client session: disconnect
2016-03-31 01:52:51.965 ThaliTest[2531:4648937] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:51.967 ThaliTest[2531:4648937] multipeer manager: stop client timer
2016-03-31 01:52:51.969 ThaliTest[2531:4648937] jxcore: stopAdvertisingAndListening: success
ok 177 Should be able to call stopAdvertisingAndListening in teardown
# set,up
,# 43. Get error when trying to double connect to a peer
,2016-03-31 01:52:54.627 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndListening
2016-03-31 01:52:54.627 ThaliTest[2531:4648937] server: starting 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:52:54.627 ThaliTest[2531:4648937] multipeer m,anager: start client restart timer: 0x17ed3390
2016-03-31 01:52:54.627 ThaliTest[2531:4648937] THEMultipeerManager initialized peer 25ECEE51-730A-4F4F-BA49-ACDAF32AFB41:9
2016-03-31 01:52:54.628 ThaliTest[2531:4648937] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 178 Can call startUpdateAdvertisingAndListening without error
2016-03-31 01:52:54.630 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 01:52:54.630 ThaliTest[2531:4648937] jxcore: startListeningForAdvertisements: success
ok 179 Can call startListeningForAdvertisements without error
,2016-03-31 01:52:55.185 ThaliTest[2531:4648767] client: found new peer: 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:55.185 ThaliTest[2531:4648767] client: found new peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:52:55.187 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:52:55.187 ThaliTest[2531:4648937] client: server will connect
,2016-03-31 01:52:55.187 ThaliTest[2531:4648937] client session: reverseConnect
2016-03-31 01:52:55.191 ThaliTest[2531:4648937] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:56.703 ThaliTest[2531:4649706] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:56.705 ThaliTest[2531:4649706] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:52:56.705 ThaliTest[2531:4649706] client session: disconnect
2016-03-31 01:52:56.705 ThaliTest[2531:4649706] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:52:56.706 ThaliTest[2531:4649706] client session: no connect callback (server initiated)
,2016-03-31 01:53:05.188 ThaliTest[2531:4648767] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 01:53:08.202 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:08.202 ThaliTest[2531:4648937] client: server will connect
2016-03-31 01:53:08.202 ThaliTest[2531:4648937] client session: reverseConn,ect
2016-03-31 01:53:08.203 ThaliTest[2531:4648937] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:08.629 ThaliTest[2531:4649704] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:08.630 ThaliTest[2531:4649704] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:08.630 ThaliTest[2531:4649704] client session: disconnect
2016-03-31 01:53:08.630 ThaliTest[2531:4649704] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:8
,2016-03-31 01:53:08.631 ThaliTest[2531:4649704] client session: no connect callback (server initiated)
,2016-03-31 01:53:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:53:14.641 ThaliTest[2531:4648767] client: found updated peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:53:14.641 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
,2016-03-31 01:53:18.203 ThaliTest[2531:4648767] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 01:53:21.210 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:21.210 ThaliTest[2531:4648937] client: server will connect
2016-03-31 01:53:21.210 ThaliTest[2531:4648937] client session: reverseConnect
2016-03-31 01:53:21.210 ThaliTest[2531:4648937] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:53:21.733 ThaliTest[2531:4649777] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:53:21.733 ThaliTest[2531:4649777] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:53:21.7,34 ThaliTest[2531:4649777] client session: disconnect
2016-03-31 01:53:21.735 ThaliTest[2531:4649777] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:53:21.735 ThaliTest[2531:4649777] client session: no connect callback (server initiated)
,2016-03-31 01:53:31.211 ThaliTest[2531:4648767] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 01:53:34.222 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:34.222 ThaliTest[2531:4648937] client: server will connect
2016-03-31 01:53:34.222 ThaliTest[2531:4648937] client session: reverseConn,ect
2016-03-31 01:53:34.223 ThaliTest[2531:4648937] client session: stateChange:0->1 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:53:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:53:34.648 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
2016-03-31 01:53:34.649 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:53:44.223 ThaliTest[2531:4648767] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 01:53:47.231 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:47.231 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:47.232 Thali,Test[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 01:53:50.237 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:50.237 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:50.237 ThaliTest[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 01:53:53.247 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:53.247 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:53.247 ThaliTest[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 01:53:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:53:54.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:53:54.641 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:8
,2016-03-31 01:53:55.530 ThaliTest[2531:4648767] multipeer session: reset timer
2016-03-31 01:53:55.531 ThaliTest[2531:4648767] server session: connect
2016-03-31 01:53:55.531 ThaliTest[2531:4648767] server session: stateChange:0->1 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:53:55.535 ThaliTest[2531:4648767] server: accepting invitation 9BF3B351-B42F-4B62-994E-93C3F024E3C4
,2016-03-31 01:53:56.254 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:56.254 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:56.255 Thali,Test[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 01:53:57.163 ThaliTest[2531:4649853] server session: p2p link connected
,2016-03-31 01:53:57.173 ThaliTest[2531:4648767] server relay: connected (to port: 56326)
,2016-03-31 01:53:57.174 ThaliTest[2531:4648767] server session: stateChange:1->2 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:53:59.258 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:59.258 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:53:59.258 Thali,Test[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 01:54:02.262 ThaliTest[2531:4648937] jxcore: connect 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:54:02.262 ThaliTest[2531:4648937] client: already connect(ing/ed) to 42E93D78-2507-4BE0-9192-FC412A882204:8
2016-03-31 01:54:02.262 ThaliTest[2531:4648937] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,2016-03-31 01:54:04.313 ThaliTest[2531:4649853] client session: not connected 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:54:04.313 ThaliTest[2531:4649853] client session: onLinkFailure: 42E93D78-2507-4BE0-9192-FC412A882204
2016-03-31 01:54:04.3,14 ThaliTest[2531:4649853] client session: disconnect
2016-03-31 01:54:04.314 ThaliTest[2531:4649853] client session: stateChange:1->0 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:54:04.314 ThaliTest[2531:4649853] client session: no connect callback (server initiated)
,2016-03-31 01:54:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:54:14.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:54:14.641 ThaliTest[2531:4648767] client: found updated peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:54:14.642 ThaliTest[2531:4648937] jxcore: connect 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:54:14.643 ThaliTest[2531:4648937] client: server already connected
,2016-03-31 01:54:14.643 ThaliTest[2531:4648937] jxcore: connect: success
,2016-03-31 01:54:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:54:34.640 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:54:34.641 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:54:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:54:54.645 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:54:54.646 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:55:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:55:14.640 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:55:14.640 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:55:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:55:34.645 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:55:34.646 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:55:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:55:54.640 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:55:54.640 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:56:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:56:14.644 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:56:14.648 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:56:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:56:34.642 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:56:34.642 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:56:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:56:54.640 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:56:54.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:57:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:57:14.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:57:14.642 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:57:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:57:34.645 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:57:34.646 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:57:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:57:54.641 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:57:54.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:58:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:58:14.640 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:58:14.642 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:58:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:58:34.641 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 01:58:34.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:58:54.628 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:58:54.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:58:54.641 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:59:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:59:14.642 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:59:14.642 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:59:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:59:34.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 01:59:34.643 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 01:59:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 01:59:54.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 01:59:54.642 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:00:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:00:14.642 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:00:14.644 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:00:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:00:34.641 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:00:34.642 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:00:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:00:54.641 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:00:54.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:01:14.628 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:01:14.640 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:01:14.640 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:01:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:01:34.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:01:34.643 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:01:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:01:54.642 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:01:54.643 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:02:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:02:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:02:34.636 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:02:34.638 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:02:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:02:54.638 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:02:54.638 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:03:14.628 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:03:14.636 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:03:14.636 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:03:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:03:34.637 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:03:34.637 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:03:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:03:54.637 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:03:54.637 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:04:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:04:14.638 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:04:14.638 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:04:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:04:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:04:54.639 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:04:54.639 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:05:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:05:14.640 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:05:14.640 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:05:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:05:34.638 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:05:34.638 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:05:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:05:54.638 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:05:54.638 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:06:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:06:14.637 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:06:14.637 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:06:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:06:34.637 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:06:34.638 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:06:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:06:54.639 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:06:54.640 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:07:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:07:14.640 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:07:14.640 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:07:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:07:34.641 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:07:34.641 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:07:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:07:54.637 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:07:54.637 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:08:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:08:14.637 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
,2016-03-31 02:08:14.639 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:08:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:08:34.638 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:08:34.638 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:08:54.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:08:54.639 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:08:54.639 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:09:14.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:09:14.638 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9
2016-03-31 02:09:14.638 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
,2016-03-31 02:09:34.629 ThaliTest[2531:4648767] multipeer manager: restart client
,2016-03-31 02:09:34.637 ThaliTest[2531:4648767] client: found existing peer: 9BF3B351-B42F-4B62-994E-93C3F024E3C4:9
2016-03-31 02:09:34.638 ThaliTest[2531:4648767] client: found existing peer: 42E93D78-2507-4BE0-9192-FC412A882204:9

```
