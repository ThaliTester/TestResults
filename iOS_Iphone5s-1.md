#### Test 646138038b5bc7c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/5E844D0E-B496-41C5-BC23-3CA85CD1CEEE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5E844D0E-B496-41C5-BC23-3CA85CD1CEEE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49914"
,(lldb)     command script import "/tmp/5E844D0E-B496-41C5-BC23-3CA85CD1CEEE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 17:38:47.922 ThaliTest[2604:4749860] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D6D319CB-CC1E-4C3E-AF66-D93205C084F3/Library/Cookies/Cookies.binarycookies
,2016-03-31 17:38:48.178 ThaliTest[2604:4749860] Apache Cordova native platform version 4.1.0 is starting.
2016-03-31 17:38:48.179 ThaliTest[2604:4749860] Multi-tasking -> Device: YES, App: YES
,2016-03-31 17:38:48.197 ThaliTest[2604:4749860] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 17:38:49.019 ThaliTest[2604:4749860] Using UIWebView
,2016-03-31 17:38:49.023 ThaliTest[2604:4749860] [CDVTimer][handleopenurl] 0.180960ms
2016-03-31 17:38:49.026 ThaliTest[2604:4749860] [CDVTimer][intentandnavigationfilter] 2.611995ms
2016-03-31 17:38:49.026 ThaliTest[2604:4749860] [CDVTimer][gesturehandle,r] 0.118017ms
2016-03-31 17:38:49.026 ThaliTest[2604:4749860] [CDVTimer][TotalPluginStartup] 3.527999ms
,2016-03-31 17:38:52.211 ThaliTest[2604:4749860] Resetting plugins due to page load.
,2016-03-31 17:38:53.621 ThaliTest[2604:4749860] Finished load of: file:///var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/index.html
,2016-03-31 17:38:53.803 ThaliTest[2604:4749860] JXcore Cordova plugin initializing
2016-03-31 17:38:53.804 ThaliTest[2604:4750010] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 17:39:02.176 ThaliTest[2604:4750010] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:39:02.177 ThaliTest[2604:4750010] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:39:02.177 ThaliTest[2604:4,750010] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 17:39:02.179 ThaliTest[2604:4750010] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07CF1881-7D60-4399-B927-92836B46F4F0/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57137
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57139
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57142
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
DEBUG createNativeListener: listening 57146
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
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57151
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57155
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 57159
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 57163
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 57167
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
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
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
DEBUG createNativeL,istener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNat,iveListener: new outgoing socket
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
DEBUG createNat,iveListener: new outgoing socket
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
DEBUG createNat,iveListener: new outgoing socket
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
DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: listening 57219
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 57223
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
,ok 50 firstPromise result
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
ok 60 secondPromise - second to run
ok 61 secondPromise - in catch
ok 62 firstPromise - third to run
ok 63 firstPromise - in then
ok 64 testing promises
# teardown
,# setup
,# 19. mix enqueue and enqueueAtTop
,ok 65 fourth
ok 66 fourth
,ok 67 second
ok 68 secondPromise - in then
,ok 69 first
ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises
,# teardown
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
,[{"uuid":"93b06dd5-4156-4a62-b430-5e379b5bf668","data":"custom data"},{"uuid":"d360614e-eafc-47a4-b232-9db4049e83cd","data":"custom data"},{"uuid":"2d44cdcc-6331-4fd1-8321-40772b7965dd","data":"custom data"},{"uuid":"5a159754-f32d-49c6-9977-dc42c1fa4a99",",data":"custom data"}]
ok 77 test participant has uuid
ok 78 participant data matches
ok 79 test participant has uuid
ok 80 participant data matches
ok 81 test participant has uuid
ok 82 participant data matches
ok 83 test participant has uuid
ok 84, participant data matches
ok 85 own UUID is found from the participants list
# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 86 specific error should be returned
# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 89 specific error should be returned
# teardown
,ok 90 error should be null
ok 91 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57235
2016-03-31 17:41:32.803 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false},
2016-03-31 17:41:32.804 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
2016-03-31 17:41:32.806 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMob,ileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:32.806 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
ok 94 error should be null
ok 95 error should be, null
# teardown
,2016-03-31 17:41:32.970 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:32.970 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:41:32.970 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:41:32.971 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:32.971 ThaliTest[2604,:4750010] jxcore: stopListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57237
2016-03-31 17:41:33.296 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements
,2016-03-31 17:41:33.298 ThaliTest[2604:4750010] multipeer manager: start client restart timer: 0x145d5b10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:41:33.298 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
,ok 98 error should be null
ok 99 error should be null
2016-03-31 17:41:33.432 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-31 17:41:33.433 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
ok 100 error should be null
ok 101 error should be null
# teardown
,2016-03-31 17:41:33.642 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:33.642 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:41:33.642 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:41:33.642 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
2016-03-31 17:41:33.643 ThaliTest[2604:4750010] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:41:33.644 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 102 error should be null
,ok 103 error should be null
,# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57239
,2016-03-31 17:41:34.244 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
,2016-03-31 17:41:34.245 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:1
,2016-03-31 17:41:34.245 ThaliTest[2604:4750010] multipeer manager: start client restart timer: 0x145d5b10
,2016-03-31 17:41:34.246 ThaliTest[2604:4750010] THEMultipeerManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:1
2016-03-31 17:41:34.246 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
ok 105 error should be null
2016-03-31 17:41:34.303 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:41:34.304 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:41:34.304, ThaliTest[2604:4750010] multipeer manager: stop client timer
2016-03-31 17:41:34.304 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
2016-03-31 17:41:34.304 ThaliTest[2604:4750010] multipeer manager: start client restart ,timer: 0x145d5b10
2016-03-31 17:41:34.304 ThaliTest[2604:4750010] THEMultipeerManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
2016-03-31 17:41:34.305 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening: success
,ok 106 error should be null
ok 107 error should be null
# teardown
,2016-03-31 17:41:35.375 ThaliTest[2604:4749860] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:2
,2016-03-31 17:41:35.522 ThaliTest[2604:4749860] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:2
,2016-03-31 17:41:38.080 ThaliTest[2604:4749860] client: lost peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498
2016-03-31 17:41:38.081 ThaliTest[2604:4749860] client session: onPeerLost: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498
,2016-03-31 17:41:38.480 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:38.480 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:41:38.480 ThaliTest[2604:4750010] multipeer manager: stop client timer
20,16-03-31 17:41:38.481 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:41:38.481 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:38.481 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 108 error should be null
,ok 109 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57244
2016-03-31 17:41:40.525 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:40.525 ThaliTest[2604:4750010] THEMultipeerManager stoppi,ng peer
2016-03-31 17:41:40.525 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
ok 110 error should be null
ok 111 error should be null
2016-03-31 17:41:40.527 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
,2016-03-31 17:41:40.528 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:41:40.529 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
ok 112 error should be null
ok 113 error should be null
# teardown
,2016-03-31 17:41:40.827 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:40.827 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:41:40.827 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:41:40.828 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:40.828 ThaliTest[2604,:4750010] jxcore: stopListeningForAdvertisements: success
ok 114 error should be null
ok 115 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57246
ok 116 first call should succeed
ok 117 first call should succeed
ok 118 specific error should be returned
# teardown
,2016-03-31 17:41:56.022 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:56.022 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:41:56.022 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:41:56.022 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:56.023 ThaliTest[2604,:4750010] jxcore: stopListeningForAdvertisements: success
ok 119 error should be null
ok 120 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57248
2016-03-31 17:41:56.291 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements
,2016-03-31 17:41:56.292 ThaliTest[2604:4750010] multipeer manager: start client restart timer: 0x145d5b10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:41:56.293 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
,2016-03-31 17:41:56.324 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:41:56.324 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:3
2016-03-31 17:41:56.324 ThaliTest[2604:4750010] THEMultipee,rManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:3
2016-03-31 17:41:56.325 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening: success
ok 121 called only once
ok 122 discovery state matches
ok 123 advertising state matches
# teardown
,2016-03-31 17:41:56.505 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:56.505 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:41:56.505 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:41:56.505 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
2016-03-31 17:41:56.505 ThaliTest[2604:4750010] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:56.506 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 124 error should be null
ok 125 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 126 should be called once
ok 127 should not have been called more than once
# teardown
,ok 128 error should be null
ok 129 error should be null
# setup
,# 33. can get the network status
,ok 130 network status should have certain non-empty properties
# teardown
,ok 131 error should be null
ok 132 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 133 host address should match
ok 134 port should match
,ok 135 host address should be null
ok 136 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 137 error should be null
ok 138 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-31 17:42:39.454 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements
2016-03-31 17:42:39.454 ThaliTest[2604:4750010] multipeer manager: start client restart timer: 0x145d5b10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:42:39.455 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-31 17:42:39.456 ThaliTes,t[2604:4750010] jxcore: stopListeningForAdvertisements
2016-03-31 17:42:39.456 ThaliTest[2604:4750010] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:42:39.456 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
ok 140 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 17:42:39.791 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:42:39.792 ThaliTest[2604:47500,10] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:42:39.793 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:39.793 ThaliTest[2604:475001,0] THEMultipeerManager stopping peer
2016-03-31 17:42:39.794 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 17:42:45.204 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements
2016-03-31 17:42:45.204 ThaliTest[2604:4750010] multipeer manager: start client restart timer: 0x145d5b10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:42:45.205 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements without error
2016-03-31 17:42:45.206 ThaliTes,t[2604:4750010] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:42:45.206 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
ok 144 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-31 17:42:48.347 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
2016-03-31 17:42:48.347 ThaliTest[2604:4750010] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:42:48.348 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:42:48.352 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:48.352 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:4,2:48.352 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 17:42:51.330 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:42:51.330 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:4
2016-03-31 17:42:51.331 ThaliTest[2604:4750010] multipeer m,anager: start client restart timer: 0x145d5b10
2016-03-31 17:42:51.331 ThaliTest[2604:4750010] THEMultipeerManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:4
2016-03-31 17:42:51.331 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-31 17:42:51.332 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:51.332 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:42:51.332 ThaliTest[2604:4750010] multipeer manager: stop client timer
2016-03-31 17:42:51.334 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
ok 148 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-31 17:42:51.450 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:42:51.451 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
ok 149 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:42:51.451 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:51.452 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:42:51.452 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 17:42:59.161 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:42:59.167 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:5
2016-03-31 17:42:59.167 ThaliTest[2604:4750010] multipeer manager: start client restart timer: 0x145d5b10
2016-03-31 17:42:59.168 ThaliTest[2604:4750010] THEMultipeerManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:5
2016-03-31 17:42:59.168 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 151 Can call startUpdateAdvertisingAndListening without error
2016-03-31 17:42:59.169 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:42:59.169 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:42:59.169 ThaliTest[2604:4750010] multipeer manager: stop client timer
,2016-03-31 17:42:59.170 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:6
2016-03-31 17:42:59.177 ThaliTest[2604:4750010] multipeer manager: start client restart timer: 0x145d5b10
2016-03-31 17:42:59.177 ThaliTest[2604:47500,10] THEMultipeerManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:6
2016-03-31 17:42:59.177 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening: success
ok 152 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-03-31 17:42:59.496 ThaliTest[2604:4749860] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:6
,2016-03-31 17:42:59.498 ThaliTest[2604:4749860] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:6
,2016-03-31 17:43:00.012 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 17:43:00.013 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:43:00.014 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:43:00.014 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:43:00.015 ThaliTest[2604:4750010] multipeer manager: stop client timer
20,16-03-31 17:43:00.015 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. peerAvailabilityChange is called
,2016-03-31 17:43:19.034 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:43:19.035 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:19.035 ThaliTest[2604:4750010] multipeer manager: start client restart timer: 0x145d5b10
2016-03-31 17:43:19.035 ThaliTest[2604:4750010] THEMultipeerManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:19.035 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 17:43:19.036 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-31 17:43:19.037 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-31 17:43:20.345 ThaliTest[2604:4749860] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:7
ok 157 peers must be an array
ok 158 peers must not be zero-length
ok 159 peer must have peerIdentifier
ok 160 peerIdentifier must be a string
ok 161 peer must have peerAvailable
ok 162 peer must have pleaseConnect
2016-03-31 17:43:20.351 ThaliTest[2604:4749860] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
# teardown
,2016-03-31 17:43:20.599 ThaliTest[2604:4749860] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:7
,2016-03-31 17:43:21.141 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 17:43:21.142 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:43:21.143 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:43:21.143 ThaliTest[2604:4750010,] THEMultipeerManager stopping peer
2016-03-31 17:43:21.143 ThaliTest[2604:4750010] multipeer manager: stop client timer
2016-03-31 17:43:21.143 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. Can connect to a remote peer
,2016-03-31 17:43:21.793 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:43:21.793 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:21.794 ThaliTest[2604:4750010] multipeer m,anager: start client restart timer: 0x145d5b10
2016-03-31 17:43:21.794 ThaliTest[2604:4750010] THEMultipeerManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:21.794 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListening without error
2016-03-31 17:43:21.795 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 17:43:21.795 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-03-31 17:43:22.783 ThaliTest[2604:4749860] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7","pleaseConnect":0}]
2016-03-31 17:43:22.785 ThaliTest[2604:4750010] jxcore: connect 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:43:22.785 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:43:22.785 ThaliTest[2604:4750010] client session: reverseConnect
2016-03-31 17:43:22.785 ThaliTest[2604:4750010] client session: stateChange:0->1 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
,2016-03-31 17:43:22.836 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:22.836 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA,2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
2016-03-31 17:43:22.843 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:22.843 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:23.435 ThaliTest[2604:4750545] client session: not connected 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:43:23.435 ThaliTest[2604:4750545] client session: onLinkFailure: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:43:23.4,35 ThaliTest[2604:4750545] client session: disconnect
2016-03-31 17:43:23.435 ThaliTest[2604:4750545] client session: stateChange:1->0 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
,2016-03-31 17:43:23.436 ThaliTest[2604:4750545] client session: no connect callback (server initiated)
,2016-03-31 17:43:23.894 ThaliTest[2604:4749860] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:7","pleaseConnect":0}]
,2016-03-31 17:43:24.673 ThaliTest[2604:4749860] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4F791D6C-3E6B-4315-830D-E0F106215081:7","pleaseConnect":0}]
,2016-03-31 17:43:25.196 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:25.196 ThaliTest[2604:4749860] server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA,2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2)
,2016-03-31 17:43:26.246 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:26.246 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:43:26.246 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:26.247 ThaliTest[2604:4749860] multipeer session: reset timer
,2016-03-31 17:43:26.247 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
,2016-03-31 17:43:26.247 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:28.818 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:28.819 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
2016-03-31 17:43:28.819 ThaliTest[2604:4749860] server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2)
,2016-03-31 17:43:29.342 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:29.342 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
,2016-03-31 17:43:29.343 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:29.346 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:29.346 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:43:29.346 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:32.263 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:32.263 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
2016-03-31 17:43:32.263 ThaliTest[2604:4749860], server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2)
,2016-03-31 17:43:32.486 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:32.487 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:43:32.487 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:32.530 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:32.530 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:43:32.530 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:32.786 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 17:43:35.625 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:35.625 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:43:35.625 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:35.671 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:35.671 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:43:35.671 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:35.789 ThaliTest[2604:4750010] jxcore: connect 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:43:35.789 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:43:35.790 ThaliTest[2604:4750010] client session: reverseConnect
2016-03-31 17:43:35.790 ThaliTest[2604:4750010] client session: stateChange:0->1 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
,2016-03-31 17:43:36.192 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:36.192 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
2016-03-31 17:43:36.192 ThaliTest[2604:4749860], server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2)
,2016-03-31 17:43:36.211 ThaliTest[2604:4750544] client session: not connected 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
,2016-03-31 17:43:36.211 ThaliTest[2604:4750544] client session: onLinkFailure: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:43:36.212 ThaliTest[2604:4750544] client session: disconnect
2016-03-31 17:43:36.212 ThaliTest[2604:4750544] client session: stateChange:1->0 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:43:36.212 ThaliTest[2604:4750544] client session: no connect callback (server initiated)
,2016-03-31 17:43:38.769 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:38.770 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
,2016-03-31 17:43:38.770 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:38.774 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:38.774 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:43:38.774 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:40.457 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:40.457 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
,2016-03-31 17:43:40.457 ThaliTest[2604:4749860] server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2)
,2016-03-31 17:43:41.795 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:43:41.810 ThaliTest[2604:4749860] client: found updated peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:43:41.810 ThaliTest[2604:4749860] client: found updated peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
2016-03-31 17:43:41.810 ,ThaliTest[2604:4749860] client: found updated peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8","pleaseConnec,t":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4F791D6C-3E6B-4315-830D-E0F106215081:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{",peerAvailable":1,"peerIdentifier":"B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8","pleaseConnect":0}]
,2016-03-31 17:43:41.965 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:41.965 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:43:41.966 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:42.424 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:42.424 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:43:42.424 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:44.648 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:44.648 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
2016-03-31 17:43:44.649 ThaliTest[2604:4749860] server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2)
,2016-03-31 17:43:45.054 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:45.054 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:43:45.054 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:45.712 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:45.712 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:43:45.712 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:45.791 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 17:43:48.200 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:48.201 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:43:48.201 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:48.738 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:48.738 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
2016-03-31 17:43:48.739 ThaliTest[2604:4749860] server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2)
,2016-03-31 17:43:48.796 ThaliTest[2604:4750010] jxcore: connect 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:43:48.796 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:43:48.797 ThaliTest[2604:4750010] client session: reverseConn,ect
2016-03-31 17:43:48.797 ThaliTest[2604:4750010] client session: stateChange:0->1 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:43:48.879 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:48.879 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:43:48.879 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:48.914 ThaliTest[2604:4750544] client session: not connected 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:43:48.914 ThaliTest[2604:4750544] client session: onLinkFailure: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:43:48.914 ThaliTest[2604:4750544] client session: disconnect
,2016-03-31 17:43:48.914 ThaliTest[2604:4750544] client session: stateChange:1->0 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:43:48.916 ThaliTest[2604:4750544] client session: no connect callback (server initiated)
,2016-03-31 17:43:51.346 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:51.346 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:43:51.346 ThaliTest[2604:4749860], server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:51.996 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:51.996 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:43:51.996 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7)
,2016-03-31 17:43:53.886 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:53.886 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
2016-03-31 17:43:53.886 ThaliTest[2604:4749860], server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2)
,2016-03-31 17:43:58.714 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:43:58.715 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
2016-03-31 17:43:58.715 ThaliTest[2604:4749860] server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2)
,2016-03-31 17:43:58.798 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 17:44:01.795 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:44:01.802 ThaliTest[2604:4750010] jxcore: connect 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:44:01.802 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:44:01.803 ThaliTest[2604:4750010] client session: reverseConnect
2016-03-31 17:44:01.803 ThaliTest[2604:4750010] client session: stateChange:0->1 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:44:01.817 ThaliTest[2604:4749860] client: lost peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:44:01.817 ThaliTest[2604:4749860] client session: onPeerLost: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:44:01.817 ThaliTest[260,4:4749860] client session: onLinkFailure: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:44:01.817 ThaliTest[2604:4749860] client session: disconnect
2016-03-31 17:44:01.817 ThaliTest[2604:4749860] client session: stateChange:1->0 501F3ADB-B1BD-4ACF-,9A35-61B1D6196FBA:8
2016-03-31 17:44:01.818 ThaliTest[2604:4749860] client session: no connect callback (server initiated)
2016-03-31 17:44:01.819 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:44:01.820 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:01.820 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8","pleaseConnect":0}]
,2016-03-31 17:44:11.818 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 17:44:14.829 ThaliTest[2604:4750010] jxcore: connect 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:44:14.830 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:44:14.830 ThaliTest[2604:4750010] client session: reverseConn,ect
2016-03-31 17:44:14.830 ThaliTest[2604:4750010] client session: stateChange:0->1 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:44:15.126 ThaliTest[2604:4750545] client session: not connected 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:15.126 ThaliTest[2604:4750545] client session: onLinkFailure: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:44:15.1,26 ThaliTest[2604:4750545] client session: disconnect
2016-03-31 17:44:15.126 ThaliTest[2604:4750545] client session: stateChange:1->0 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:15.127 ThaliTest[2604:4750545] client session: no connect callback (server initiated)
,2016-03-31 17:44:21.794 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:44:21.810 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:21.812 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:44:21.814 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:44:24.831 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 17:44:27.844 ThaliTest[2604:4750010] jxcore: connect 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:44:27.845 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:44:27.845 ThaliTest[2604:4750010] client session: reverseConnect
2016-03-31 17:44:27.845 ThaliTest[2604:4750010] client session: stateChange:0->1 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:44:28.097 ThaliTest[2604:4750545] client session: not connected 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:28.098 ThaliTest[2604:4750545] client session: onLinkFailure: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
,2016-03-31 17:44:28.098 ThaliTest[2604:4750545] client session: disconnect
,2016-03-31 17:44:28.099 ThaliTest[2604:4750545] client session: stateChange:1->0 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:28.099 ThaliTest[2604:4750545] client session: no connect callback (server initiated)
,2016-03-31 17:44:37.846 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 17:44:40.849 ThaliTest[2604:4750010] jxcore: connect 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:44:40.849 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:44:40.850 ThaliTest[2604:4750010] client session: reverseConnect
2016-03-31 17:44:40.850 ThaliTest[2604:4750010] client session: stateChange:0->1 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:44:41.531 ThaliTest[2604:4750752] client session: not connected 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:41.531 ThaliTest[2604:4750752] client session: onLinkFailure: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:44:41.531 ThaliTest[2604:4750752] client session: disconnect
2016-03-31 17:44:41.531 ThaliTest[2604:4750752] client session: stateChange:1->0 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:41.531 ThaliTest[2604:4750752] client session: no connect callb,ack (server initiated)
,2016-03-31 17:44:41.795 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:44:41.809 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:44:41.812 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:44:41.814 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:44:50.851 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 17:44:53.861 ThaliTest[2604:4750010] jxcore: connect 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:44:53.862 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:44:53.862 ThaliTest[2604:4750010] client session: reverseConnect
2016-03-31 17:44:53.862 ThaliTest[2604:4750010] client session: stateChange:0->1 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:44:54.758 ThaliTest[2604:4750829] client session: not connected 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:44:54.758 ThaliTest[2604:4750829] client session: onLinkFailure: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:44:54.758 ThaliTest[2604:4750829] client session: disconnect
2016-03-31 17:44:54.760 ThaliTest[2604:4750829] client session: stateChange:1->0 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:44:54.760 ThaliTest[2604:4750829] client session: no connect callback (server initiated)
,2016-03-31 17:45:01.772 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:45:01.786 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:45:01.787 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
2016-03-31 17:45:01.787 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:03.840 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 17:45:06.852 ThaliTest[2604:4750010] jxcore: connect 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:45:06.852 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:45:06.853 ThaliTest[2604:4750010] client session: reverseConnect
2016-03-31 17:45:06.853 ThaliTest[2604:4750010] client session: stateChange:0->1 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:45:07.509 ThaliTest[2604:4750752] client session: not connected 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:45:07.509 ThaliTest[2604:4750752] client session: onLinkFailure: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
2016-03-31 17:45:07.509 ThaliTest[2604:4750752] client session: disconnect
2016-03-31 17:45:07.509 ThaliTest[2604:4750752] client session: stateChange:1->0 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:45:07.511 ThaliTest[2604:4750752] client session: no connect callback (server initiated)
,2016-03-31 17:45:16.854 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 17:45:19.856 ThaliTest[2604:4750010] jxcore: connect 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:45:19.857 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:45:19.857 ThaliTest[2604:4750010] client session: reverseConn,ect
2016-03-31 17:45:19.857 ThaliTest[2604:4750010] client session: stateChange:0->1 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:45:20.034 ThaliTest[2604:4750903] client session: not connected 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:45:20.034 ThaliTest[2604:4750903] client session: onLinkFailure: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA
,2016-03-31 17:45:20.034 ThaliTest[2604:4750903] client session: disconnect
2016-03-31 17:45:20.036 ThaliTest[2604:4750903] client session: stateChange:1->0 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:45:20.036 ThaliTest[2604:4750903] client session: no connect callback (server initiated)
,2016-03-31 17:45:21.772 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:45:21.793 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:45:21.794 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
2016-03-31 17:45:21.79,5 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:29.858 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 167 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-03-31 17:45:31.073 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 17:45:31.074 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
,ok 168 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:45:31.076 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:45:31.076 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:45:31.076 ThaliTest[2604:4750010] multipeer manager: stop client timer
2016-03-31 17:45:31.076 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
,ok 169 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. Can shift large amounts of data
,2016-03-31 17:45:34.463 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:45:34.463 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:45:34.464 ThaliTest[2604:4750010] multipeer m,anager: start client restart timer: 0x145d5b10
2016-03-31 17:45:34.464 ThaliTest[2604:4750010] THEMultipeerManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:45:34.464 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening: success
,ok 170 Can call startUpdateAdvertisingAndListening without error
,2016-03-31 17:45:34.466 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 17:45:34.467 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
ok 171 Can call startListeningForAdvertisements without error
,2016-03-31 17:45:34.481 ThaliTest[2604:4749860] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:45:34.482 ThaliTest[2604:4749860] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
2016-03-31 17:45:34.482 ThaliTest[2604:4749860] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:45:34.486 ThaliTest[2604:4750010] jxcore: connect B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:34.487 ThaliTest[2604:4750010] client: server will connect
,2016-03-31 17:45:34.488 ThaliTest[2604:4750010] client session: reverseConnect
,2016-03-31 17:45:34.488 ThaliTest[2604:4750010] client session: stateChange:0->1 B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:35.765 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:35.765 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:36.680 ThaliTest[2604:4750927] client session: not connected B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:45:36.680 ThaliTest[2604:4750927] client session: onLinkFailure: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498
2016-03-31 17:45:36.6,80 ThaliTest[2604:4750927] client session: disconnect
2016-03-31 17:45:36.680 ThaliTest[2604:4750927] client session: stateChange:1->0 B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:45:36.680 ThaliTest[2604:4750927] client session: no connect callback (server initiated)
,2016-03-31 17:45:38.560 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:38.560 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA,2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:38.644 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:38.644 ThaliTest[2604:4749860] server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA,2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:38.921 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:38.921 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:45:38.922 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:41.991 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:41.991 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:45:41.992 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:42.859 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:42.859 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
2016-03-31 17:45:42.860 ThaliTest[2604:4749860] server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:43.151 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:43.151 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:45:43.151 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:44.488 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 17:45:45.068 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:45.068 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:45:45.068 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:47.028 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:47.028 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:45:47.028 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:47.496 ThaliTest[2604:4750010] jxcore: connect B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:45:47.496 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:45:47.497 ThaliTest[2604:4750010] client session: reverseConnect
2016-03-31 17:45:47.497 ThaliTest[2604:4750010] client session: stateChange:0->1 B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:48.111 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:48.111 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
2016-03-31 17:45:48.111 ThaliTest[2604:4749860] server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:48.223 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:48.225 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:45:48.225 ThaliTest[2604:4749860], server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:48.239 ThaliTest[2604:4750933] client session: not connected B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:45:48.240 ThaliTest[2604:4750933] client session: onLinkFailure: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498
2016-03-31 17:45:48.240 ThaliTest[2604:4750933] client session: disconnect
,2016-03-31 17:45:48.240 ThaliTest[2604:4750933] client session: stateChange:1->0 B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:48.243 ThaliTest[2604:4750933] client session: no connect callback (server initiated)
,2016-03-31 17:45:50.934 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:50.934 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:45:50.935 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:51.357 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:51.357 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:45:51.357 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:54.181 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:54.182 ThaliTest[2604:4749860] server: disconnecting to refresh session (4F791D6C-3E6B-4315-830D-E0F106215081)
2016-03-31 17:45:54.182 ThaliTest[2604:4749860], server: rejecting invitation from 4F791D6C-3E6B-4315-830D-E0F106215081 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:54.376 ThaliTest[2604:4749860] multipeer session: reset timer
,2016-03-31 17:45:54.376 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:45:54.377 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:45:54.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:45:54.478 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:45:54.479 ThaliTest[2604:4749860] client: found updated peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:45:54.480 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:45:57.498 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 8
,2016-03-31 17:45:58.181 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:45:58.181 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:45:58.181 ThaliTest[2604:4749860], server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:46:00.504 ThaliTest[2604:4750010] jxcore: connect B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:00.505 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:46:00.505 ThaliTest[2604:4750010] client session: reverseConn,ect
2016-03-31 17:46:00.505 ThaliTest[2604:4750010] client session: stateChange:0->1 B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:46:00.913 ThaliTest[2604:4750927] client session: not connected B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:00.914 ThaliTest[2604:4750927] client session: onLinkFailure: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498
2016-03-31 17:46:00.914 ThaliTest[2604:4750927] client session: disconnect
,2016-03-31 17:46:00.914 ThaliTest[2604:4750927] client session: stateChange:1->0 B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:00.916 ThaliTest[2604:4750927] client session: no connect callback (server initiated)
,2016-03-31 17:46:02.706 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:46:02.706 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:46:02.706 ThaliTest[2604:4749860], server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:46:06.657 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:46:06.657 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:46:06.657 ThaliTest[2604:4749860], server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:46:10.506 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 17:46:10.720 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:46:10.721 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:46:10.721 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:46:13.516 ThaliTest[2604:4750010] jxcore: connect B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:13.517 ThaliTest[2604:4750010] client: server will connect
2016-03-31 17:46:13.517 ThaliTest[2604:4750010] client session: reverseConnect
2016-03-31 17:46:13.517 ThaliTest[2604:4750010] client session: stateChange:0->1 B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:46:14.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:46:14.484 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:46:14.484 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:14.48,5 ThaliTest[2604:4749860] client: found updated peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:46:14.572 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:46:14.572 ThaliTest[2604:4749860] server: disconnecting to refresh session (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA)
2016-03-31 17:46:14.572 ThaliTest[2604:4749860] server: rejecting invitation from 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:46:23.518 ThaliTest[2604:4749860] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 17:46:26.531 ThaliTest[2604:4750010] jxcore: connect B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:26.532 ThaliTest[2604:4750010] client: already connect(ing/ed) to B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:26.532 ThaliTest[2604:4750010] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 17:46:29.539 ThaliTest[2604:4750010] jxcore: connect B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:29.539 ThaliTest[2604:4750010] client: already connect(ing/ed) to B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:29.539 Thali,Test[2604:4750010] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 17:46:30.791 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:46:30.791 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:46:30.792 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:46:32.543 ThaliTest[2604:4750010] jxcore: connect B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:32.543 ThaliTest[2604:4750010] client: already connect(ing/ed) to B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:32.543 Thali,Test[2604:4750010] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 17:46:33.867 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:46:33.868 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:46:33.868 ThaliTest[2604:4749860], server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:46:34.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:46:34.479 ThaliTest[2604:4749860] client: found updated peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
,2016-03-31 17:46:34.481 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:46:34.482 ThaliTest[2604:4749860] client: found updated peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:46:35.553 ThaliTest[2604:4750010] jxcore: connect B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:35.553 ThaliTest[2604:4750010] client: already connect(ing/ed) to B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:35.553 Thali,Test[2604:4750010] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 17:46:36.962 ThaliTest[2604:4749860] multipeer session: reset timer
2016-03-31 17:46:36.962 ThaliTest[2604:4749860] server: disconnecting to refresh session (B9470F4B-F8C4-427A-8DC9-3B3E0B52B498)
2016-03-31 17:46:36.962 ThaliTest[2604:4749860] server: rejecting invitation from B9470F4B-F8C4-427A-8DC9-3B3E0B52B498 due to previous generation (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9 != 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8)
,2016-03-31 17:46:38.565 ThaliTest[2604:4750010] jxcore: connect B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:38.566 ThaliTest[2604:4750010] client: already connect(ing/ed) to B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:38.566 ThaliTest[2604:4750010] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 17:46:41.579 ThaliTest[2604:4750010] jxcore: connect B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:41.579 ThaliTest[2604:4750010] client: already connect(ing/ed) to B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:46:41.579 ThaliTest[2604:4750010] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 172 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-31 17:46:46.516 ThaliTest[2604:4751106] client session: not connected B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:46:46.516 ThaliTest[2604:4751106] client session: onLinkFailure: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498
2016-03-31 17:46:46.5,16 ThaliTest[2604:4751106] client session: disconnect
2016-03-31 17:46:46.517 ThaliTest[2604:4751106] client session: stateChange:1->0 B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:46:46.517 ThaliTest[2604:4751106] client session: no connect callback (server initiated)
,2016-03-31 17:46:54.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:46:54.483 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:46:54.484 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:46:54.48,4 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
,2016-03-31 17:47:14.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:47:14.482 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:47:14.482 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:47:14.482 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:47:34.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:47:34.482 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:47:34.482 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:47:34.48,2 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:47:54.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:47:54.480 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:47:54.480 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:47:54.481 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
,2016-03-31 17:48:14.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:48:14.480 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
,2016-03-31 17:48:14.482 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:48:14.483 ThaliTest[2604:4749860] client: found updated peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
,2016-03-31 17:48:34.464 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:48:34.480 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:48:34.481 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
,2016-03-31 17:48:34.484 ThaliTest[2604:4749860] client: found updated peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:48:54.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:48:54.489 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:48:54.489 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:48:54.489 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
,2016-03-31 17:49:14.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:49:14.481 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:49:14.481 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:49:14.482 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:49:34.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:49:34.483 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:49:34.483 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:49:34.483 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
,2016-03-31 17:49:54.465 ThaliTest[2604:4749860] multipeer manager: restart client
,2016-03-31 17:49:54.481 ThaliTest[2604:4749860] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:49:54.481 ThaliTest[2604:4749860] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:49:54.48,1 ThaliTest[2604:4749860] client: found existing peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:50:09.912 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 17:50:09.913 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:50:09.915 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:50:09.915 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
,2016-03-31 17:50:09.915 ThaliTest[2604:4750010] multipeer manager: stop client timer
2016-03-31 17:50:09.916 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-31 17:50:21.509 ThaliTest[2604:4750010] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:21.509 ThaliTest[2604:4750010] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:21.509 ThaliTest[2604:4,750010] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 17:50:21.510 ThaliTest[2604:4750010] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 175 specific error should be returned
,# teardown
,ok 176 must be stopped
,# setup
,2016-03-31 17:50:23.711 ThaliTest[2604:4750010] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:23.712 ThaliTest[2604:4750010] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:23.712 ThaliTest[2604:4,750010] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 17:50:23.713 ThaliTest[2604:4750010] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 177 specific error should be returned
,# teardown
,ok 178 must be stopped
,# setup
,2016-03-31 17:50:24.961 ThaliTest[2604:4750010] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:24.961 ThaliTest[2604:4750010] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:24.961 ThaliTest[2604:4750010] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:24.962 ThaliTest[2604:4750010] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57292
,2016-03-31 17:50:25.393 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:50:25.394 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
,ok 179 no errors
,2016-03-31 17:50:25.396 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 17:50:25.397 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
,ok 180 still no errors
,# teardown
,2016-03-31 17:50:31.758 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:50:31.758 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:50:31.758 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:50:31.758 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:50:31.759 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
,ok 181 must be stopped
,# setup
,2016-03-31 17:50:33.385 ThaliTest[2604:4750010] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:33.385 ThaliTest[2604:4750010] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:33.386 ThaliTest[2604:4,750010] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:33.387 ThaliTest[2604:4750010] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57294
,2016-03-31 17:50:58.306 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements
2016-03-31 17:50:58.307 ThaliTest[2604:4750010] multipeer manager: start client restart timer: 0x145d5b10
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 17:50:58.308 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
,ok 182 no errors
,2016-03-31 17:50:58.314 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-31 17:50:58.316 ThaliTest[2604:4750010] jxcore: startListeningForAdvertisements: success
,ok 183 still no errors
,# teardown
,2016-03-31 17:50:58.564 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:50:58.565 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:50:58.565 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:50:58.565 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
2016-03-31 17:50:58.565 ThaliTest[2604:4750010] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
,2016-03-31 17:50:58.566 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
,ok 184 must be stopped
# setup
,2016-03-31 17:51:15.395 ThaliTest[2604:4750010] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:51:15.396 ThaliTest[2604:4750010] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:51:15.396 ThaliTest[2604:4750010] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:51:15.397 ThaliTest[2604:4750010] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57296
,2016-03-31 17:51:20.051 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:51:20.052 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:10
2016-03-31 17:51:20.052 ThaliTest[2604:4750010] multipeer ,manager: start client restart timer: 0x145d5b10
2016-03-31 17:51:20.052 ThaliTest[2604:4750010] THEMultipeerManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:10
2016-03-31 17:51:20.052 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 185 no errors
2016-03-31 17:51:20.053 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:51:20.054 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:51:20.054 ThaliTest[2604:4750,010] multipeer manager: stop client timer
2016-03-31 17:51:20.054 ThaliTest[2604:4750010] server: starting 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:11
,2016-03-31 17:51:20.054 ThaliTest[2604:4750010] multipeer manager: start client restart timer: 0x145d5b10
,2016-03-31 17:51:20.055 ThaliTest[2604:4750010] THEMultipeerManager initialized peer 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:11
2016-03-31 17:51:20.056 ThaliTest[2604:4750010] jxcore: startUpdateAdvertisingAndListening: success
ok 186 still no errors
# teardown
,2016-03-31 17:51:20.072 ThaliTest[2604:4749860] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:51:20.072 ThaliTest[2604:4749860] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:51:20.073 ThaliTest[2604:4749860] client: found new peer: 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
,2016-03-31 17:51:31.354 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening
2016-03-31 17:51:31.354 ThaliTest[2604:4750010] THEMultipeerManager stopping peer
2016-03-31 17:51:31.354 ThaliTest[2604:4750010] multipeer manager: stop client timer
2016-03-31 17:51:31.354 ThaliTest[2604:4750010] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:51:31.355 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:51:31.356 ThaliTest[2604:4750010] jxcore: stopListeningForAdvertisements: success
,ok 187 must be stopped
# setup

```
