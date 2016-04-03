#### Test 64809936d936b9e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/39BCC26C-77B9-40AD-8023-C946E7C985AA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/39BCC26C-77B9-40AD-8023-C946E7C985AA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50516"
,(lldb)     command script import "/tmp/39BCC26C-77B9-40AD-8023-C946E7C985AA/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-03 21:06:40.313 ThaliTest[2096:5442846] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8CD3B283-EFEC-43CF-8EF4-40E2AAFD5BDE/Library/Cookies/Cookies.binarycookies
,2016-04-03 21:06:40.416 ThaliTest[2096:5442846] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-03 21:06:40.418 ThaliTest[2096:5442846] Multi-tasking -> Device: YES, App: YES
,2016-04-03 21:06:40.441 ThaliTest[2096:5442846] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-03 21:06:41.641 ThaliTest[2096:5442846] Using UIWebView
,2016-04-03 21:06:41.645 ThaliTest[2096:5442846] [CDVTimer][handleopenurl] 0.277996ms
,2016-04-03 21:06:41.651 ThaliTest[2096:5442846] [CDVTimer][intentandnavigationfilter] 4.940033ms
2016-04-03 21:06:41.651 ThaliTest[2096:5442846] [CDVTimer][gesturehandler] 0.331998ms
2016-04-03 21:06:41.651 ThaliTest[2096:5442846] [CDVTimer][TotalPluginStartup] 6.455004ms
,2016-04-03 21:06:46.588 ThaliTest[2096:5442846] Resetting plugins due to page load.
,2016-04-03 21:06:49.029 ThaliTest[2096:5442846] Finished load of: file:///var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/index.html
,2016-04-03 21:06:49.226 ThaliTest[2096:5442846] JXcore Cordova plugin initializing
,2016-04-03 21:06:49.230 ThaliTest[2096:5442995] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-03 21:07:03.418 ThaliTest[2096:5442995] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-03 21:07:03.419 ThaliTest[2096:5442995] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-03 21:07:03.420 ThaliTest[2096:5442995] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-03 21:07:03.423 ThaliTest[2096:5442995] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA2A0BB8-8EB7-4DA3-910C-D985FA7951E1/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58125
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58127
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
DEBUG createNativeListener: listening 58130
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
DEBUG createNativeListener: listening 58134
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58139
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
DEBUG createNativeListener: listening 58143
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
DEBUG createNativeListener: listening 58147
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
DEBUG createNativeListener: listening 58151
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
,ok 23 native server should be closed
,ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58155
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
,DEBUG createNativeListener: listening 58207
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
DEBUG createNativeListener: listening 58211
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
DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
ok 42 incomi,ng has been removed
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
,[{"uuid":"f6d73446-5000-4d78-b1ff-7f7cf59b2a18","data":"custom data"},{"uuid":"09cac296-ea8d-47c3-aafb-b2ba98d948de","data":"custom data"},{"uuid":"7f465dac-b5fc-4fa0-aece-e506c38feb66","data":"custom data"},{"uuid":"24de18a5-460b-493f-8720-a0ac5fddea1c",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
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
# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58221
2016-04-03 21:10:42.403 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:42.405 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-03 21:10:42.407 ThaliTest[2096:5442995] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:42.408 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements: succes,s
,ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-03 21:10:42.590 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:42.590 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:10:42.591 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:42.591 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:42.592 ThaliTest[2096,:5442995] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
,ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58223
2016-04-03 21:10:42.880 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements
,2016-04-03 21:10:42.882 ThaliTest[2096:5442995] multipeer manager: start client restart timer: 0x17dc98a0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-03 21:10:42.903 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-03 21:10:42.936 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-03 21:10:42.938 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-03 21:10:43.330 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:43.330 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:10:43.330 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:43.331 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
2016-04-03 21:10:43.331 ThaliTest[2096:5442995] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:43.332 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58225
2016-04-03 21:10:43.899 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:10:43.899 ThaliTest[2096:5442995] server: starting 9C9DAABD-80A6-487A-AC19-4D6E0668D813:1
2016-04-03 21:,10:43.900 ThaliTest[2096:5442995] multipeer manager: start client restart timer: 0x17dc98a0
2016-04-03 21:10:43.900 ThaliTest[2096:5442995] THEMultipeerManager initialized peer 9C9DAABD-80A6-487A-AC19-4D6E0668D813:1
2016-04-03 21:10:43.902 ThaliTest[2096,:5442995] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-03 21:10:43.918 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:10:43.918 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:10:43.919, ThaliTest[2096:5442995] multipeer manager: stop client timer
2016-04-03 21:10:43.919 ThaliTest[2096:5442995] server: starting 9C9DAABD-80A6-487A-AC19-4D6E0668D813:2
2016-04-03 21:10:43.919 ThaliTest[2096:5442995] multipeer manager: start client restart ,timer: 0x17dc98a0
2016-04-03 21:10:43.920 ThaliTest[2096:5442995] THEMultipeerManager initialized peer 9C9DAABD-80A6-487A-AC19-4D6E0668D813:2
2016-04-03 21:10:43.920 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
# teardown
,2016-04-03 21:10:44.370 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.371 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:10:44.371 ThaliTest[2096:5442995] multipeer manager: stop client timer
20,16-04-03 21:10:44.371 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
2016-04-03 21:10:44.371 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:44.372 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58230
,2016-04-03 21:10:44.820 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.820 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:10:44.820 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: suc,cess
ok 109 error should be null
ok 110 error should be null
2016-04-03 21:10:44.823 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.823 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:10:44.823 ,ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-03 21:10:44.926 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.926 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:10:44.927 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:44.927 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:44.928 ThaliTest[2096,:5442995] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58232
,ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-03 21:10:46.208 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:46.208 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:10:46.208 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:46.209 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:46.210 ThaliTest[2096,:5442995] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58234
2016-04-03 21:10:46.835 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements
,2016-04-03 21:10:46.835 ThaliTest[2096:5442995] multipeer manager: start client restart timer: 0x17dc98a0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:10:46.837 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements: success
,2016-04-03 21:10:46.850 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:10:46.851 ThaliTest[2096:5442995] server: starting 9C9DAABD-80A6-487A-AC19-4D6E0668D813:3
2016-04-03 21:10:46.851 ThaliTest[2096:5442995] THEMultipee,rManager initialized peer 9C9DAABD-80A6-487A-AC19-4D6E0668D813:3
2016-04-03 21:10:46.852 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-03 21:10:47.267 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:47.268 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:10:47.268 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:47.268 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
2016-04-03 21:10:47.268 ThaliTest[2096:5442995] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:47.269 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 123 error should be null
,ok 124 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
ok 126 should not have been called more than once
# teardown
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
,ok 135 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-03 21:11:48.922 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements
2016-04-03 21:11:48.923 ThaliTest[2096:5442995] multipeer manager: start client restart timer: 0x17dc98a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:11:48.924 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-03 21:11:48.925 ThaliTes,t[2096:5442995] jxcore: stopListeningForAdvertisements
2016-04-03 21:11:48.925 ThaliTest[2096:5442995] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-04-03 21:11:48.926 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-03 21:11:49.234 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:11:49.235 ThaliTest[2096:54429,95] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:11:49.236 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:11:49.236 ThaliTest[2096:54429,95] THEMultipeerManager stopping peer
2016-04-03 21:11:49.236 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-03 21:11:49.424 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements
2016-04-03 21:11:49.425 ThaliTest[2096:5442995] multipeer manager: start client restart timer: 0x17dc98a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:11:49.426 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-03 21:11:49.427 ThaliTes,t[2096:5442995] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:11:49.428 ThaliTest[2096:5442995] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-03 21:11:49.809 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
2016-04-03 21:11:49.809 ThaliTest[2096:5442995] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-03 21:11:49.810 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:11:49.811 ThaliTest[2096:5442,995] jxcore: stopAdvertisingAndListening
2016-04-03 21:11:49.811 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:11:49.811 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-03 21:12:17.910 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:17.911 ThaliTest[2096:54429,95] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-03 21:12:17.912 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:17.913 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-03 21:12:19.776 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:19.777 ThaliTest[2096:54429,95] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:12:19.778 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:12:19.778 ThaliTest[2096:54429,95] THEMultipeerManager stopping peer
2016-04-03 21:12:19.778 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-03 21:12:20.076 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:12:20.076 ThaliTest[2096:5442995] server: starting 9C9DAABD-80A6-487A-AC19-4D6E0668D813:4
2016-04-03 21:12:20.077 ThaliTest[2096:5442995] multipeer m,anager: start client restart timer: 0x17dc98a0
2016-04-03 21:12:20.077 ThaliTest[2096:5442995] THEMultipeerManager initialized peer 9C9DAABD-80A6-487A-AC19-4D6E0668D813:4
2016-04-03 21:12:20.077 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:12:20.078 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:12:20.078 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
,2016-04-03 21:12:20.079 ThaliTest[2096:5442995] multipeer manager: stop client timer
2016-04-03 21:12:20.085 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-03 21:12:20.395 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:20.396 ThaliTest[2096:54429,95] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:12:20.397 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:12:20.397 ThaliTest[2096:54429,95] THEMultipeerManager stopping peer
2016-04-03 21:12:20.397 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-03 21:13:46.929 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:13:46.929 ThaliTest[2096:5442995] server: starting 9C9DAABD-80A6-487A-AC19-4D6E0668D813:5
2016-04-03 21:13:46.930 ThaliTest[2096:5442995] multipeer m,anager: start client restart timer: 0x17dc98a0
2016-04-03 21:13:46.930 ThaliTest[2096:5442995] THEMultipeerManager initialized peer 9C9DAABD-80A6-487A-AC19-4D6E0668D813:5
2016-04-03 21:13:46.930 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:13:46.932 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:13:46.932 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
,2016-04-03 21:13:46.932 ThaliTest[2096:5442995] multipeer manager: stop client timer
2016-04-03 21:13:46.937 ThaliTest[2096:5442995] server: starting 9C9DAABD-80A6-487A-AC19-4D6E0668D813:6
2016-04-03 21:13:46.938 ThaliTest[2096:5442995] multipeer manager,: start client restart timer: 0x17dc98a0
2016-04-03 21:13:46.938 ThaliTest[2096:5442995] THEMultipeerManager initialized peer 9C9DAABD-80A6-487A-AC19-4D6E0668D813:6
2016-04-03 21:13:46.938 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-03 21:13:47.326 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-03 21:13:47.327 ThaliTest[2096:544299,5] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:13:47.329 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.329 ThaliTest[2096:544299,5] THEMultipeerManager stopping peer
2016-04-03 21:13:47.329 ThaliTest[2096:5442995] multipeer manager: stop client timer
2016-04-03 21:13:47.329 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-03 21:13:47.781 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.781 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:13:47.781 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:13:47.783 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.783 ThaliTest[2096:5442995] THEMultipeerManager stopping peer
2016-04-03 21:13,:47.783 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-03 21:13:47.903 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:13:47.904 ThaliTest[2096:54429,95] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:13:47.905 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.905 ThaliTest[2096:54429,95] THEMultipeerManager stopping peer
2016-04-03 21:13:47.905 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-03 21:14:06.790 ThaliTest[2096:5442995] jxcore: connect foo
2016-04-03 21:14:06.791 ThaliTest[2096:5442995] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
,# teardown
,2016-04-03 21:14:31.891 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:14:31.892 ThaliTest[2096:54429,95] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:14:31.893 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:14:31.893 ThaliTest[2096:54429,95] THEMultipeerManager stopping peer
2016-04-03 21:14:31.893 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-03 21:14:32.600 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:14:32.601 ThaliTest[2096:5442995] server: starting 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
2016-04-03 21:14:32.601 ThaliTest[2096:5442995] multipeer manager: start client restart timer: 0x17dc98a0
2016-04-03 21:14:32.601 ThaliTest[2096:5442995] THEMultipeerManager initialized peer 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
2016-04-03 21:14:32.601 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-03 21:14:32.603 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-03 21:14:32.603 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-03 21:14:33.311 ThaliTest[2096:5442846] client: found new peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-03 21:14:33.625 ThaliTest[2096:5442846] client: found new peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:7
,2016-04-03 21:14:34.056 ThaliTest[2096:5442846] client: found new peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:7
,2016-04-03 21:14:34.404 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-03 21:14:34.405 ThaliTest[2096:544299,5] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:14:34.406 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:14:34.406 ThaliTest[2096:544299,5] THEMultipeerManager stopping peer
2016-04-03 21:14:34.406 ThaliTest[2096:5442995] multipeer manager: stop client timer
2016-04-03 21:14:34.406 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-03 21:14:35.062 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:14:35.062 ThaliTest[2096:5442995] server: starting 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:14:35.063 ThaliTest[2096:5442995] multipeer m,anager: start client restart timer: 0x17dc98a0
2016-04-03 21:14:35.063 ThaliTest[2096:5442995] THEMultipeerManager initialized peer 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:14:35.063 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:14:35.064 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-03 21:14:35.065 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-03 21:14:35.535 ThaliTest[2096:5442846] client: found new peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:35.535 ThaliTest[2096:5442846] client: found new peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:7
2016-04-03 21:14:35.536 ThaliTes,t[2096:5442846] client: found new peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"569AF1E0-EE92-40BF-918A-581DB52F22D0:7","pleaseConnect":0}]
,2016-04-03 21:14:35.539 ThaliTest[2096:5442995] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:35.540 ThaliTest[2096:5442995] client session: connect
2016-04-03 21:14:35.540 ThaliTest[2096:5442995] client session: stateChange:0->,1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4C7015DA-AE07-4F33-B74F-C43FFD219895:7","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvai,lable":1,"peerIdentifier":"CD9AB027-E5E1-43D4-A70E-56CE01144BF3:7","pleaseConnect":0}]
,2016-04-03 21:14:36.473 ThaliTest[2096:5443937] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:36.474 ThaliTest[2096:5443937] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
,2016-04-03 21:14:36.474 ThaliTest[2096:5443937] client session: disconnect
2016-04-03 21:14:36.475 ThaliTest[2096:5443937] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:36.477 ThaliTest[2096:5443937] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:36.477 ThaliTest[2096:5443937] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-03 21:14:36.802 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:14:36.803 ThaliTest[2096:5442846] server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:8 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7)
,2016-04-03 21:14:39.487 ThaliTest[2096:5442995] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:39.487 ThaliTest[2096:5442995] client session: connect
2016-04-03 21:14:39.487 ThaliTest[2096:5442995] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:39.868 ThaliTest[2096:5443938] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:39.868 ThaliTest[2096:5443938] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:39.8,69 ThaliTest[2096:5443938] client session: disconnect
2016-04-03 21:14:39.869 ThaliTest[2096:5443938] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:39.870 ThaliTest[2096:5443938] client session: fireConnectCallb,ack: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:39.870 ThaliTest[2096:5443938] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-03 21:14:42.873 ThaliTest[2096:5442995] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:42.873 ThaliTest[2096:5442995] client session: connect
2016-04-03 21:14:42.874 ThaliTest[2096:5442995] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:43.019 ThaliTest[2096:5443963] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:43.020 ThaliTest[2096:5443963] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:43.0,21 ThaliTest[2096:5443963] client session: disconnect
2016-04-03 21:14:43.021 ThaliTest[2096:5443963] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:43.022 ThaliTest[2096:5443963] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
,2016-04-03 21:14:43.022 ThaliTest[2096:5443963] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-03 21:14:46.027 ThaliTest[2096:5442995] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:46.028 ThaliTest[2096:5442995] client session: connect
2016-04-03 21:14:46.028 ThaliTest[2096:5442995] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:46.172 ThaliTest[2096:5443937] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:46.173 ThaliTest[2096:5443937] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:46.1,73 ThaliTest[2096:5443937] client session: disconnect
2016-04-03 21:14:46.173 ThaliTest[2096:5443937] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:46.174 ThaliTest[2096:5443937] client session: fireConnectCallb,ack: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:46.174 ThaliTest[2096:5443937] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-03 21:14:49.181 ThaliTest[2096:5442995] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:49.181 ThaliTest[2096:5442995] client session: connect
2016-04-03 21:14:49.181 ThaliTest[2096:5442995] client session: stateChange:0->,1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:49.391 ThaliTest[2096:5443974] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:49.392 ThaliTest[2096:5443974] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:49.3,92 ThaliTest[2096:5443974] client session: disconnect
2016-04-03 21:14:49.392 ThaliTest[2096:5443974] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:49.392 ThaliTest[2096:5443974] client session: fireConnectCallb,ack: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:49.393 ThaliTest[2096:5443974] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-03 21:14:50.365 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:14:50.365 ThaliTest[2096:5442846] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:14:50.365 ThaliTest[2096:5442846], server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:8 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7)
,2016-04-03 21:14:52.406 ThaliTest[2096:5442995] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:52.406 ThaliTest[2096:5442995] client session: connect
2016-04-03 21:14:52.406 ThaliTest[2096:5442995] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:52.471 ThaliTest[2096:5443937] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:52.471 ThaliTest[2096:5443937] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:52.471 ThaliTest[2096:5443937] client session: disconnect
2016-04-03 21:14:52.471 ThaliTest[2096:5443937] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:52.474 ThaliTest[2096:5443937] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:52.474 ThaliTest[2096:5443937] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-03 21:14:55.064 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:14:55.092 ThaliTest[2096:5442846] client: found updated peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:14:55.094 ThaliTest[2096:5442846] client: found updated peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
2016-04-03 21:14:55.095 ,ThaliTest[2096:5442846] client: found updated peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"569AF1E0-EE92-40BF-918A-581DB52F22D0:8","pleaseConnec,t":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4C7015DA-AE07-4F33-B74F-C43FFD219895:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8","pleaseConnect":0}]
,2016-04-03 21:14:55.487 ThaliTest[2096:5442995] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:55.487 ThaliTest[2096:5442995] client session: connect
2016-04-03 21:14:55.487 ThaliTest[2096:5442995] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:14:55.637 ThaliTest[2096:5443938] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:14:55.637 ThaliTest[2096:5443938] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:55.637 ThaliTest[2096:5443938] client session: disconnect
,2016-04-03 21:14:55.638 ThaliTest[2096:5443938] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:14:55.639 ThaliTest[2096:5443938] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
,2016-04-03 21:14:55.639 ThaliTest[2096:5443938] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-03 21:14:58.645 ThaliTest[2096:5442995] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:58.645 ThaliTest[2096:5442995] client session: connect
2016-04-03 21:14:58.646 ThaliTest[2096:5442995] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:14:59.809 ThaliTest[2096:5443963] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:14:59.809 ThaliTest[2096:5443963] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:59.8,10 ThaliTest[2096:5443963] client session: disconnect
2016-04-03 21:14:59.810 ThaliTest[2096:5443963] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:14:59.811 ThaliTest[2096:5443963] client session: fireConnectCallback: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:59.812 ThaliTest[2096:5443963] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-03 21:15:02.245 ThaliTest[2096:5442846] client: lost peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895
2016-04-03 21:15:02.246 ThaliTest[2096:5442846] client session: onPeerLost: 4C7015DA-AE07-4F33-B74F-C43FFD219895
,2016-04-03 21:15:02.373 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:15:02.373 ThaliTest[2096:5442846] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:15:02.373 ThaliTest[2096:5442846] server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:8 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7)
,2016-04-03 21:15:02.817 ThaliTest[2096:5442995] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:02.818 ThaliTest[2096:5442995] client session: connect
2016-04-03 21:15:02.818 ThaliTest[2096:5442995] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:02.944 ThaliTest[2096:5443987] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:02.944 ThaliTest[2096:5443987] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:02.9,45 ThaliTest[2096:5443987] client session: disconnect
2016-04-03 21:15:02.945 ThaliTest[2096:5443987] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:02.947 ThaliTest[2096:5443987] client session: fireConnectCallb,ack: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:02.947 ThaliTest[2096:5443987] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-03 21:15:05.955 ThaliTest[2096:5442995] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:05.956 ThaliTest[2096:5442995] client session: connect
2016-04-03 21:15:05.956 ThaliTest[2096:5442995] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:06.098 ThaliTest[2096:5443963] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:06.100 ThaliTest[2096:5443963] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:06.1,00 ThaliTest[2096:5443963] client session: disconnect
2016-04-03 21:15:06.100 ThaliTest[2096:5443963] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:06.101 ThaliTest[2096:5443963] client session: fireConnectCallb,ack: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:06.101 ThaliTest[2096:5443963] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-04-03 21:15:15.064 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:15:15.097 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:15:15.098 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
2016-04-03 21:15:15.09,8 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4C7015DA-AE07-4F33-B74F-C43FFD219895:8","pleaseCon,nect":0}]
,2016-04-03 21:15:15.557 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:15:15.558 ThaliTest[2096:5442846] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:15:15.558 ThaliTest[2096:5442846] server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:8 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7)
,2016-04-03 21:15:28.658 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:15:28.658 ThaliTest[2096:5442846] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:15:28.659 ThaliTest[2096:5442846], server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:8 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7)
,2016-04-03 21:15:35.064 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:15:35.090 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:35.104 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:15:35.104 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:15:42.296 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:15:42.296 ThaliTest[2096:5442846] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:15:42.297 ThaliTest[2096:5442846] server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:8 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7)
,2016-04-03 21:15:54.376 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:15:54.376 ThaliTest[2096:5442846] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:15:54.376 ThaliTest[2096:5442846] server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:8 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7)
,2016-04-03 21:15:55.064 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:15:55.213 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:55.279 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:15:55.279 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:16:07.487 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:16:07.487 ThaliTest[2096:5442846] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:16:07.487 ThaliTest[2096:5442846], server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:8 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7)
,2016-04-03 21:16:15.064 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:16:15.094 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:15.095 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:16:20.654 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:16:20.655 ThaliTest[2096:5442846] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:16:20.655 ThaliTest[2096:5442846] server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:8 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7)
,2016-04-03 21:16:24.418 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:16:33.596 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:16:33.596 ThaliTest[2096:5442846] server: disconnecting to refresh session (569AF1E0-EE92-40BF-918A-581DB52F22D0)
2016-04-03 21:16:33.597 ThaliTest[2096:5442846], server: rejecting invitation from 569AF1E0-EE92-40BF-918A-581DB52F22D0 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:8 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7)
,2016-04-03 21:16:35.064 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:16:35.100 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:35.100 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:35.10,1 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:16:43.440 ThaliTest[2096:5442995] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-03 21:16:43.441 ThaliTest[2096:544299,5] jxcore: stopListeningForAdvertisements: success
ok 178 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:16:43.442 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening
2016-04-03 21:16:43.443 ThaliTest[2096:544299,5] THEMultipeerManager stopping peer
2016-04-03 21:16:43.443 ThaliTest[2096:5442995] multipeer manager: stop client timer
2016-04-03 21:16:43.443 ThaliTest[2096:5442995] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-03 21:16:43.904 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:16:43.904 ThaliTest[2096:5442995] server: starting 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:16:43.904 ThaliTest[2096:5442995] multipeer m,anager: start client restart timer: 0x17dc98a0
2016-04-03 21:16:43.905 ThaliTest[2096:5442995] THEMultipeerManager initialized peer 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:16:43.905 ThaliTest[2096:5442995] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:16:43.906 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-03 21:16:43.907 ThaliTest[2096:5442995] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-03 21:16:44.975 ThaliTest[2096:5442846] client: found new peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:44.976 ThaliTest[2096:5442995] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:44.977 ThaliTest[2096:5,442995] client: server will connect
2016-04-03 21:16:44.977 ThaliTest[2096:5442995] client session: reverseConnect
2016-04-03 21:16:44.977 ThaliTest[2096:5442995] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:16:45.597 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:16:45.597 ThaliTest[2096:5442846] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:9 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8)
,2016-04-03 21:16:46.039 ThaliTest[2096:5442846] client: found new peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:46.040 ThaliTest[2096:5442846] client: found new peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:16:46.267 ThaliTest[2096:5444539] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:46.267 ThaliTest[2096:5444539] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:16:46.2,68 ThaliTest[2096:5444539] client session: disconnect
2016-04-03 21:16:46.268 ThaliTest[2096:5444539] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:46.269 ThaliTest[2096:5444539] client session: no connect callback (server initiated)
,2016-04-03 21:16:48.828 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:16:48.828 ThaliTest[2096:5442846] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
,2016-04-03 21:16:48.828 ThaliTest[2096:5442846] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:9 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8)
,2016-04-03 21:16:51.919 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:16:51.920 ThaliTest[2096:5442846] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
2016-04-03 21:16:51.920 ThaliTest[2096:5442846] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:9 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8)
,2016-04-03 21:16:54.977 ThaliTest[2096:5442846] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-03 21:16:55.067 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:16:55.068 ThaliTest[2096:5442846] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
2016-04-03 21:16:55.068 ThaliTest[2096:5442846] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:9 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8)
,2016-04-03 21:16:57.984 ThaliTest[2096:5442995] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:57.984 ThaliTest[2096:5442995] client: server will connect
2016-04-03 21:16:57.984 ThaliTest[2096:5442995] client session: reverseConnect
2016-04-03 21:16:57.984 ThaliTest[2096:5442995] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:16:58.221 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:16:58.221 ThaliTest[2096:5442846] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
2016-04-03 21:16:58.221 ThaliTest[2096:5442846], server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:9 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8)
,2016-04-03 21:16:58.229 ThaliTest[2096:5444474] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:58.231 ThaliTest[2096:5444474] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:16:58.2,31 ThaliTest[2096:5444474] client session: disconnect
2016-04-03 21:16:58.231 ThaliTest[2096:5444474] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:58.232 ThaliTest[2096:5444474] client session: no connect callback (server initiated)
,2016-04-03 21:17:01.356 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:17:01.356 ThaliTest[2096:5442846] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
2016-04-03 21:17:01.356 ThaliTest[2096:5442846], server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:9 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8)
,2016-04-03 21:17:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:17:03.936 ThaliTest[2096:5442846] client: found updated peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:03.937 ThaliTest[2096:5442846] client: found updated peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:17:03.944 ThaliTest[2096:5442846] client: found updated peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:17:04.502 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:17:04.502 ThaliTest[2096:5442846] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
2016-04-03 21:17:04.502 ThaliTest[2096:5442846], server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:9 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8)
,2016-04-03 21:17:07.646 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:17:07.646 ThaliTest[2096:5442846] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
2016-04-03 21:17:07.646 ThaliTest[2096:5442846] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:9 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8)
,2016-04-03 21:17:07.985 ThaliTest[2096:5442846] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-03 21:17:10.794 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:17:10.794 ThaliTest[2096:5442846] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
2016-04-03 21:17:10.794 ThaliTest[2096:5442846] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:9 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8)
,2016-04-03 21:17:10.993 ThaliTest[2096:5442995] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:17:10.993 ThaliTest[2096:5442995] client: server will connect
2016-04-03 21:17:10.993 ThaliTest[2096:5442995] client session: reverseConnect
2016-04-03 21:17:10.994 ThaliTest[2096:5442995] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:11.105 ThaliTest[2096:5444553] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:11.105 ThaliTest[2096:5444553] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:17:11.1,05 ThaliTest[2096:5444553] client session: disconnect
2016-04-03 21:17:11.106 ThaliTest[2096:5444553] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:11.106 ThaliTest[2096:5444553] client session: no connect callb,ack (server initiated)
,2016-04-03 21:17:13.938 ThaliTest[2096:5442846] multipeer session: reset timer
2016-04-03 21:17:13.939 ThaliTest[2096:5442846] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
2016-04-03 21:17:13.939 ThaliTest[2096:5442846], server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (9C9DAABD-80A6-487A-AC19-4D6E0668D813:9 != 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8)
,2016-04-03 21:17:20.994 ThaliTest[2096:5442846] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-03 21:17:23.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:17:23.936 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:23.943 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:17:23.943 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:17:24.004 ThaliTest[2096:5442995] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:17:24.005 ThaliTest[2096:5442995] client: server will connect
2016-04-03 21:17:24.005 ThaliTest[2096:5442995] client session: reverseConn,ect
2016-04-03 21:17:24.005 ThaliTest[2096:5442995] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:24.264 ThaliTest[2096:5444639] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:24.265 ThaliTest[2096:5444639] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:17:24.2,67 ThaliTest[2096:5444639] client session: disconnect
2016-04-03 21:17:24.267 ThaliTest[2096:5444639] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:24.267 ThaliTest[2096:5444639] client session: no connect callback (server initiated)
,2016-04-03 21:17:27.285 ThaliTest[2096:5442846] client: lost peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895
2016-04-03 21:17:27.286 ThaliTest[2096:5442846] client session: onPeerLost: 4C7015DA-AE07-4F33-B74F-C43FFD219895
,2016-04-03 21:17:27.602 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:17:34.006 ThaliTest[2096:5442846] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-03 21:17:37.011 ThaliTest[2096:5442995] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:17:37.011 ThaliTest[2096:5442995] client: server will connect
2016-04-03 21:17:37.012 ThaliTest[2096:5442995] client session: reverseConn,ect
2016-04-03 21:17:37.012 ThaliTest[2096:5442995] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:37.660 ThaliTest[2096:5444671] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:37.662 ThaliTest[2096:5444671] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:17:37.6,62 ThaliTest[2096:5444671] client session: disconnect
2016-04-03 21:17:37.662 ThaliTest[2096:5444671] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:37.663 ThaliTest[2096:5444671] client session: no connect callback (server initiated)
,2016-04-03 21:17:43.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:17:43.926 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:43.933 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:17:43.935 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:17:47.013 ThaliTest[2096:5442846] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-03 21:17:50.026 ThaliTest[2096:5442995] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:17:50.026 ThaliTest[2096:5442995] client: server will connect
2016-04-03 21:17:50.026 ThaliTest[2096:5442995] client session: reverseConnect
2016-04-03 21:17:50.027 ThaliTest[2096:5442995] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:50.357 ThaliTest[2096:5444713] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:50.357 ThaliTest[2096:5444713] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:17:50.3,57 ThaliTest[2096:5444713] client session: disconnect
2016-04-03 21:17:50.358 ThaliTest[2096:5444713] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:50.359 ThaliTest[2096:5444713] client session: no connect callback (server initiated)
,2016-04-03 21:18:00.027 ThaliTest[2096:5442846] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-03 21:18:03.038 ThaliTest[2096:5442995] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:18:03.039 ThaliTest[2096:5442995] client: server will connect
2016-04-03 21:18:03.039 ThaliTest[2096:5442995] client session: reverseConnect
2016-04-03 21:18:03.039 ThaliTest[2096:5442995] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:18:03.823 ThaliTest[2096:5444711] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:03.823 ThaliTest[2096:5444711] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:18:03.8,24 ThaliTest[2096:5444711] client session: disconnect
2016-04-03 21:18:03.824 ThaliTest[2096:5444711] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:03.825 ThaliTest[2096:5444711] client session: no connect callback (server initiated)
,2016-04-03 21:18:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:18:03.933 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:18:03.934 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:18:03.947 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:18:13.040 ThaliTest[2096:5442846] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-03 21:18:16.045 ThaliTest[2096:5442995] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:18:16.045 ThaliTest[2096:5442995] client: server will connect
2016-04-03 21:18:16.045 ThaliTest[2096:5442995] client session: reverseConnect
2016-04-03 21:18:16.045 ThaliTest[2096:5442995] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:18:16.493 ThaliTest[2096:5444778] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:16.494 ThaliTest[2096:5444778] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:18:16.4,95 ThaliTest[2096:5444778] client session: disconnect
2016-04-03 21:18:16.495 ThaliTest[2096:5444778] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:16.495 ThaliTest[2096:5444778] client session: no connect callback (server initiated)
,2016-04-03 21:18:23.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:18:23.931 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:18:23.942 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:18:23.943 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:18:26.046 ThaliTest[2096:5442846] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-03 21:18:29.052 ThaliTest[2096:5442995] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:18:29.052 ThaliTest[2096:5442995] client: server will connect
2016-04-03 21:18:29.052 ThaliTest[2096:5442995] client session: reverseConnect
2016-04-03 21:18:29.053 ThaliTest[2096:5442995] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:18:29.475 ThaliTest[2096:5444802] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:29.475 ThaliTest[2096:5444802] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
,2016-04-03 21:18:29.476 ThaliTest[2096:5444802] client session: disconnect
2016-04-03 21:18:29.477 ThaliTest[2096:5444802] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:29.477 ThaliTest[2096:5444802] client sess,ion: no connect callback (server initiated)
,2016-04-03 21:18:39.054 ThaliTest[2096:5442846] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-03 21:18:42.062 ThaliTest[2096:5442995] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:18:42.062 ThaliTest[2096:5442995] client: server will connect
2016-04-03 21:18:42.062 ThaliTest[2096:5442995] client session: reverseConn,ect
2016-04-03 21:18:42.062 ThaliTest[2096:5442995] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:18:42.703 ThaliTest[2096:5444831] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:42.704 ThaliTest[2096:5444831] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:18:42.7,04 ThaliTest[2096:5444831] client session: disconnect
2016-04-03 21:18:42.704 ThaliTest[2096:5444831] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:42.704 ThaliTest[2096:5444831] client session: no connect callb,ack (server initiated)
,2016-04-03 21:18:43.905 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:18:43.929 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:18:43.929 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:43.93,1 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:18:52.063 ThaliTest[2096:5442846] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
WARN testThaliMobileNative: Too many connect retries,!
,2016-04-03 21:19:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:19:03.943 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:19:03.944 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:19:03.946 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:19:23.905 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:19:23.930 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:19:23.930 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:19:23.931 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:19:43.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:19:43.935 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:19:43.935 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:19:43.948 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:20:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:20:03.926 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:20:03.934 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:20:03.936 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:20:23.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:20:23.935 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:20:23.936 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:20:23.947 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:20:43.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:20:43.932 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:20:43.934 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:20:43.935 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:21:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:21:03.942 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:21:03.942 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:21:03.944 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:21:23.905 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:21:23.932 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:21:23.933 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:21:23.934 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:21:43.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:21:43.938 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:21:43.938 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:21:43.945 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:22:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:22:03.931 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:22:03.933 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:22:03.933 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:22:23.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:22:23.933 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:22:23.934 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:22:23.935 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:22:43.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:22:43.935 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:22:43.935 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:22:43.936 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:23:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:23:03.932 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:23:03.934 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:23:03.935 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:23:23.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:23:23.935 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:23:23.935 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:23:23.937 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:23:43.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:23:43.935 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:23:43.935 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:23:43.935 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:24:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:24:03.941 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:24:03.941 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:24:03.942 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:24:23.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:24:23.942 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:24:23.945 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:24:23.945 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:24:43.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:24:43.932 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:24:43.933 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:24:43.933 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:25:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:25:03.933 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:25:03.934 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:25:03.93,5 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:25:23.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:25:23.942 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:25:23.942 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:25:23.943 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:25:43.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:26:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:26:03.928 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:26:03.929 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:26:03.929 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:26:23.905 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:26:23.929 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:26:23.929 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:26:23.93,0 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:26:43.905 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:26:43.923 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:26:43.924 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:26:43.928 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:27:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:27:03.930 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:27:03.930 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:27:03.93,0 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:27:23.905 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:27:23.929 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:27:23.929 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:27:23.92,9 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:27:43.905 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:27:43.927 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:27:43.927 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:27:43.928 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:28:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:28:03.927 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:28:03.928 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:28:03.928 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:28:23.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:28:23.926 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:28:23.926 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:28:23.928 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:28:43.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:28:43.923 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:28:43.925 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:28:43.925 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:29:03.906 ThaliTest[2096:5442846] multipeer manager: restart client
,2016-04-03 21:29:03.926 ThaliTest[2096:5442846] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:29:03.926 ThaliTest[2096:5442846] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:29:03.928 ThaliTest[2096:5442846] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9

```
