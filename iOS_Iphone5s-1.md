#### Test 6480993629f6128_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/6FB276FE-A88E-4418-A62E-3A2F2AB340A6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6FB276FE-A88E-4418-A62E-3A2F2AB340A6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50399"
,(lldb)     command script import "/tmp/6FB276FE-A88E-4418-A62E-3A2F2AB340A6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 23:47:09.108 ThaliTest[2711:4934030] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/621C2204-C77B-4A91-8C46-DE02CEF5138C/Library/Cookies/Cookies.binarycookies
,2016-04-01 23:47:09.356 ThaliTest[2711:4934030] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 23:47:09.357 ThaliTest[2711:4934030] Multi-tasking -> Device: YES, App: YES
,2016-04-01 23:47:09.376 ThaliTest[2711:4934030] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 23:47:10.177 ThaliTest[2711:4934030] Using UIWebView
2016-04-01 23:47:10.180 ThaliTest[2711:4934030] [CDVTimer][handleopenurl] 0.167012ms
,2016-04-01 23:47:10.185 ThaliTest[2711:4934030] [CDVTimer][intentandnavigationfilter] 4.275024ms
2016-04-01 23:47:10.185 ThaliTest[2711:4934030] [CDVTimer][gesturehandler] 0.149012ms
2016-04-01 23:47:10.185 ThaliTest[2711:4934030] [CDVTimer][TotalPluginS,tartup] 5.203962ms
,2016-04-01 23:47:13.398 ThaliTest[2711:4934030] Resetting plugins due to page load.
,2016-04-01 23:47:14.720 ThaliTest[2711:4934030] Finished load of: file:///var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/index.html
,2016-04-01 23:47:14.915 ThaliTest[2711:4934030] JXcore Cordova plugin initializing
,2016-04-01 23:47:14.916 ThaliTest[2711:4934196] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 23:47:23.271 ThaliTest[2711:4934196] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 23:47:23.272 ThaliTest[2711:4934196] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 23:47:23.272 ThaliTest[2711:4,934196] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 23:47:23.275 ThaliTest[2711:4934196] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/20BD5D22-3EAA-4930-9A0A-48611C7B741C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58583
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58585
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58588
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 58592
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
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58597
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
,DEBUG createNativeListener: listening 58601
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
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58605
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
ok 18 incoming should survive
,ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58609
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
DEBUG createNativeListener: listening 58613
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 58665
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 58669
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
,ok 62 firstPromise - in then
,ok 63 testing promises
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
,[{"uuid":"8f481545-2d3c-4c34-90c0-6602bf93a785","data":"custom data"},{"uuid":"7299c1cd-4325-4a34-90c1-c1db833eeee1","data":"custom data"},{"uuid":"c7e38397-c90d-4e48-845d-977d1574ba6e","data":"custom data"},{"uuid":"3559cc27-6402-432b-bcfd-c285802596a6",",data":"custom data"}]
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
DEBUG createNativeListener: listening 58679
2016-04-01 23:50:18.015 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:18.016 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
,2016-04-01 23:50:18.019 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:18.021 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-01 23:50:18.324 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:18.325 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:50:18.325 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 23:50:18.325 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:18.326 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58681
2016-04-01 23:50:18.539 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements
,2016-04-01 23:50:18.541 ThaliTest[2711:4934196] multipeer manager: start client restart timer: 0x146d0df0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:50:18.542 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-01 23:50:18.677 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-04-01 23:50:18.678 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-01 23:50:19.414 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:19.414 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:50:19.414 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
2016-04-01 23:50:19.414 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
2016-04-01 23:50:19.415 ThaliTest[2711:4934196] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:19.415 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58683
,2016-04-01 23:50:37.852 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:50:37.852 ThaliTest[2711:4934196] server: starting EEA4391C-4C5F-40D5-B71D-C147ED7B0517:1
2016-04-01 23:50:37.853 ThaliTest[2711:4934196] multipeer m,anager: start client restart timer: 0x146d0df0
2016-04-01 23:50:37.853 ThaliTest[2711:4934196] THEMultipeerManager initialized peer EEA4391C-4C5F-40D5-B71D-C147ED7B0517:1
2016-04-01 23:50:37.853 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-01 23:50:37.865 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:50:37.865 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:50:37.865, ThaliTest[2711:4934196] multipeer manager: stop client timer
2016-04-01 23:50:37.866 ThaliTest[2711:4934196] server: starting EEA4391C-4C5F-40D5-B71D-C147ED7B0517:2
2016-04-01 23:50:37.866 ThaliTest[2711:4934196] multipeer manager: start client restart timer: 0x146d0df0
2016-04-01 23:50:37.866 ThaliTest[2711:4934196] THEMultipeerManager initialized peer EEA4391C-4C5F-40D5-B71D-C147ED7B0517:2
2016-04-01 23:50:37.866 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
# teardown
,2016-04-01 23:50:38.771 ThaliTest[2711:4934030] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:2
,2016-04-01 23:50:39.614 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:39.614 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:50:39.615 ThaliTest[2711:4934196] multipeer manager: stop client timer
2016-04-01 23:50:39.615 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
2016-04-01 23:50:39.615 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:39.616 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58688
2016-04-01 23:50:56.149 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:56.149 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:50:56.150 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
,2016-04-01 23:50:56.153 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:56.153 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:50:56.153 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-01 23:50:56.464 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:56.464 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:50:56.464 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 23:50:56.464 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:50:56.465 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58690
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-01 23:50:57.008 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:57.009 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:50:57.009 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
2016-04-01 23:50:57.009 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:57.010 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58692
,2016-04-01 23:50:57.958 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements
,2016-04-01 23:50:57.959 ThaliTest[2711:4934196] multipeer manager: start client restart timer: 0x146d0df0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:50:57.960 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements: success
,2016-04-01 23:50:57.991 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:50:57.991 ThaliTest[2711:4934196] server: starting EEA4391C-4C5F-40D5-B71D-C147ED7B0517:3
2016-04-01 23:50:57.991 ThaliTest[2711:4934196] THEMultipee,rManager initialized peer EEA4391C-4C5F-40D5-B71D-C147ED7B0517:3
2016-04-01 23:50:57.992 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-01 23:50:58.094 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:58.094 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:50:58.094 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
2016-04-01 23:50:58.095 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
2016-04-01 23:50:58.095 ThaliTest[2711:4934196] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:50:58.096 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 123 error should be null
,ok 124 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
,ok 126 should not have been called more than once
,# teardown
,ok 127 error should be null
,ok 128 error should be null
,# setup
,# 32. can get the network status
,ok 129 network status should have certain non-empty properties
# teardown
,ok 130 error should be null
,ok 131 error should be null
# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
ok 133 port should match
,ok 134 host address should be null
ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-01 23:51:27.750 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements
2016-04-01 23:51:27.751 ThaliTest[2711:4934196] multipeer manager: start client restart timer: 0x146d0df0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:51:27.752 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-01 23:51:27.752 ThaliTes,t[2711:4934196] jxcore: stopListeningForAdvertisements
2016-04-01 23:51:27.753 ThaliTest[2711:4934196] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:27.753 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 23:51:28.018 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:28.019 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:28.019 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:28.020 ThaliTest[2711:49341,96] THEMultipeerManager stopping peer
2016-04-01 23:51:28.020 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-01 23:51:28.541 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements
2016-04-01 23:51:28.541 ThaliTest[2711:4934196] multipeer manager: start client restart timer: 0x146d0df0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:51:28.542 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-01 23:51:28.543 ThaliTes,t[2711:4934196] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:51:28.543 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-01 23:51:28.552 ThaliTest[2711:4934030] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:2
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
,2016-04-01 23:51:28.662 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
2016-04-01 23:51:28.663 ThaliTest[2711:4934196] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:28.664 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:28.664 ThaliTest[2711:4934,196] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:28.665 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:51:28.665 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-01 23:51:31.818 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:31.819 ThaliTest[2711:49341,96] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-01 23:51:31.820 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:31.820 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 23:51:52.011 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:52.011 ThaliTest[2711:49341,96] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:52.012 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:52.012 ThaliTest[2711:49341,96] THEMultipeerManager stopping peer
2016-04-01 23:51:52.012 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-01 23:51:52.362 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:52.362 ThaliTest[2711:4934196] server: starting EEA4391C-4C5F-40D5-B71D-C147ED7B0517:4
2016-04-01 23:51:52.362 ThaliTest[2711:4934196] multipeer m,anager: start client restart timer: 0x146d0df0
2016-04-01 23:51:52.363 ThaliTest[2711:4934196] THEMultipeerManager initialized peer EEA4391C-4C5F-40D5-B71D-C147ED7B0517:4
2016-04-01 23:51:52.363 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:51:52.363 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:52.364 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
,2016-04-01 23:51:52.364 ThaliTest[2711:4934196] multipeer manager: stop client timer
2016-04-01 23:51:52.367 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
,ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-01 23:51:52.457 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:51:52.458 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:52.459 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:52.459 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:51:52.459 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: suc,cess
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-01 23:51:53.214 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:53.214 ThaliTest[2711:4934196] server: starting EEA4391C-4C5F-40D5-B71D-C147ED7B0517:5
2016-04-01 23:51:53.215 ThaliTest[2711:4934196] multipeer manager: start client restart timer: 0x146d0df0
2016-04-01 23:51:53.215 ThaliTest[2711:4934196] THEMultipeerManager initialized peer EEA4391C-4C5F-40D5-B71D-C147ED7B0517:5
2016-04-01 23:51:53.215 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:51:53.216 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:53.216 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
,2016-04-01 23:51:53.216 ThaliTest[2711:4934196] multipeer manager: stop client timer
2016-04-01 23:51:53.220 ThaliTest[2711:4934196] server: starting EEA4391C-4C5F-40D5-B71D-C147ED7B0517:6
2016-04-01 23:51:53.221 ThaliTest[2711:4934196] multipeer manager: start client restart timer: 0x146d0df0
2016-04-01 23:51:53.221 ThaliTest[2711:4934196] THEMultipeerManager initialized peer EEA4391C-4C5F-40D5-B71D-C147ED7B0517:6
2016-04-01 23:51:53.221 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-01 23:51:53.234 ThaliTest[2711:4934030] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:2
,2016-04-01 23:51:53.378 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 23:51:53.379 ThaliTest[2711:493419,6] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:53.380 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:53.380 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:51:53.380 ThaliTest[2711:4934196] multipeer manager: stop client timer
2016-04-01 23:51:53.380 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-01 23:51:56.191 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:56.191 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:51:56.191 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:51:56.192 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:56.192 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:51:56.192 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-01 23:51:56.291 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:56.292 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:56.292 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:56.292 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:51:56.292 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-01 23:51:56.842 ThaliTest[2711:4934196] jxcore: connect foo
2016-04-01 23:51:56.843 ThaliTest[2711:4934196] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-01 23:51:57.748 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:57.749 ThaliTest[2711:49341,96] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:57.750 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:57.750 ThaliTest[2711:49341,96] THEMultipeerManager stopping peer
2016-04-01 23:51:57.750 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-01 23:51:58.051 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:58.051 ThaliTest[2711:4934196] server: starting EEA4391C-4C5F-40D5-B71D-C147ED7B0517:7
2016-04-01 23:51:58.051 ThaliTest[2711:4934196] multipeer manager: start client restart timer: 0x146d0df0
2016-04-01 23:51:58.052 ThaliTest[2711:4934196] THEMultipeerManager initialized peer EEA4391C-4C5F-40D5-B71D-C147ED7B0517:7
2016-04-01 23:51:58.052 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-01 23:51:58.052 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 23:51:58.054 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-01 23:51:58.066 ThaliTest[2711:4934030] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:2
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a strin,g
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-01 23:51:59.048 ThaliTest[2711:4934030] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,2016-04-01 23:51:59.057 ThaliTest[2711:4934030] client: found new peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:7
,2016-04-01 23:52:05.054 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 23:52:05.055 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:52:05.056 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:52:05.056 ThaliTest[2711:493419,6] THEMultipeerManager stopping peer
2016-04-01 23:52:05.056 ThaliTest[2711:4934196] multipeer manager: stop client timer
2016-04-01 23:52:05.056 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-01 23:52:23.750 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:52:23.751 ThaliTest[2711:4934196] server: starting EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:23.751 ThaliTest[2711:4934196] multipeer m,anager: start client restart timer: 0x146d0df0
2016-04-01 23:52:23.751 ThaliTest[2711:4934196] THEMultipeerManager initialized peer EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:23.751 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:52:23.752 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-01 23:52:23.753 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-01 23:52:24.727 ThaliTest[2711:4934030] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"53FC597F-8F79-47DA-ABAE-0C427F412EFF:7","pleaseConnect":0}]
2016-04-01 23:52:24.730 ThaliTest[2711:4934196] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,2016-04-01 23:52:24.730 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:52:24.733 ThaliTest[2711:4934196] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,2016-04-01 23:52:24.821 ThaliTest[2711:4934030] client: found new peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0B8B74BF-D366-4FF8-B07A-13C8262BA05D:7","pleaseConnect":0}]
,2016-04-01 23:52:26.541 ThaliTest[2711:4934842] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:26.541 ThaliTest[2711:4934842] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:26.542 ThaliTest[2711:4934842] client session: disconnect
2016-04-01 23:52:26.542 ThaliTest[2711:4934842] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:26.542 ThaliTest[2711:4934842] client session: fireConnectCallb,ack: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:26.542 ThaliTest[2711:4934842] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 23:52:26.911 ThaliTest[2711:4934030] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BC3134AD-A0D1-47B0-885A-5F5313680802:7","pleaseConnect":0}]
,2016-04-01 23:52:28.088 ThaliTest[2711:4934030] multipeer session: reset timer
2016-04-01 23:52:28.088 ThaliTest[2711:4934030] server: rejecting invitation for lexical ordering BC3134AD-A0D1-47B0-885A-5F5313680802
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BC3134AD-A0D1-47B0-885A-5F5313680802:8","pleaseConnect":1}]
,2016-04-01 23:52:29.555 ThaliTest[2711:4934196] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:29.555 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:52:29.555 ThaliTest[2711:4934196] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,2016-04-01 23:52:29.860 ThaliTest[2711:4934865] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:29.861 ThaliTest[2711:4934865] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:29.861 ThaliTest[2711:4934865] client session: disconnect
2016-04-01 23:52:29.861 ThaliTest[2711:4934865] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:29.862 ThaliTest[2711:4934865] client session: fireConnectCallb,ack: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:29.862 ThaliTest[2711:4934865] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 23:52:32.866 ThaliTest[2711:4934196] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:32.866 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:52:32.866 ThaliTest[2711:4934196] client session: stateChange:0->,1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,2016-04-01 23:52:33.194 ThaliTest[2711:4934865] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:33.195 ThaliTest[2711:4934865] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:33.195 ThaliTest[2711:4934865] client session: disconnect
2016-04-01 23:52:33.196 ThaliTest[2711:4934865] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:33.196 ThaliTest[2711:4934865] client session: fireConnectCallb,ack: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:33.196 ThaliTest[2711:4934865] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 23:52:36.199 ThaliTest[2711:4934196] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:36.200 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:52:36.200 ThaliTest[2711:4934196] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,2016-04-01 23:52:36.339 ThaliTest[2711:4934866] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:36.340 ThaliTest[2711:4934866] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:36.340 ThaliTest[2711:4934866] client session: disconnect
2016-04-01 23:52:36.340 ThaliTest[2711:4934866] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:36.340 ThaliTest[2711:4934866] client session: fireConnectCallb,ack: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
,2016-04-01 23:52:36.340 ThaliTest[2711:4934866] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-01 23:52:39.347 ThaliTest[2711:4934196] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:39.348 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:52:39.348 ThaliTest[2711:4934196] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,2016-04-01 23:52:39.481 ThaliTest[2711:4934866] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:39.482 ThaliTest[2711:4934866] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:39.4,82 ThaliTest[2711:4934866] client session: disconnect
2016-04-01 23:52:39.482 ThaliTest[2711:4934866] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:39.483 ThaliTest[2711:4934866] client session: fireConnectCallb,ack: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:39.483 ThaliTest[2711:4934866] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 23:52:39.751 ThaliTest[2711:4934030] multipeer session: reset timer
2016-04-01 23:52:39.751 ThaliTest[2711:4934030] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
2016-04-01 23:52:39.751 ThaliTest[2711:4934030], server: rejecting invitation for lexical ordering BC3134AD-A0D1-47B0-885A-5F5313680802
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BC3134AD-A0D1-47B0-885A-5F5313680802:8","pleaseConnect":1}]
,2016-04-01 23:52:42.143 ThaliTest[2711:4934030] client: found new peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7A3E2FC9-9ECE-4B84-83EC-3B5A7BABE,B7A:2","pleaseConnect":0}]
,2016-04-01 23:52:42.485 ThaliTest[2711:4934196] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:42.486 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:52:42.486 ThaliTest[2711:4934196] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
,2016-04-01 23:52:42.627 ThaliTest[2711:4934844] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:42.627 ThaliTest[2711:4934844] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:42.6,27 ThaliTest[2711:4934844] client session: disconnect
2016-04-01 23:52:42.627 ThaliTest[2711:4934844] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:42.628 ThaliTest[2711:4934844] client session: fireConnectCallback: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:42.628 ThaliTest[2711:4934844] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 23:52:43.752 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:52:43.768 ThaliTest[2711:4934030] client: found updated peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"53FC597F-8F79-47DA-ABAE-0C427F412EFF:8","pleaseConnect":0}]
,2016-04-01 23:52:43.774 ThaliTest[2711:4934030] client: found updated peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8","pleaseConnect":0}]
,2016-04-01 23:52:43.777 ThaliTest[2711:4934030] client: found updated peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:52:43.778 ThaliTest[2711:4934030] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BC3134AD-A0D1-47B0-885A-5F5313680802:8","pleaseConnect":0}]
,2016-04-01 23:52:45.638 ThaliTest[2711:4934196] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:45.638 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:52:45.638 ThaliTest[2711:4934196] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:52:45.783 ThaliTest[2711:4934866] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:52:45.783 ThaliTest[2711:4934866] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:45.783 ThaliTest[2711:4934866] client session: disconnect
2016-04-01 23:52:45.783 ThaliTest[2711:4934866] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:52:45.784 ThaliTest[2711:4934866] client session: fireConnectCallb,ack: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:45.784 ThaliTest[2711:4934866] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 23:52:48.793 ThaliTest[2711:4934196] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:48.794 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:52:48.794 ThaliTest[2711:4934196] client session: stateChange:0->,1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:52:48.992 ThaliTest[2711:4934865] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:52:48.993 ThaliTest[2711:4934865] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:48.993 ThaliTest[2711:4934865] client session: disconnect
2016-04-01 23:52:48.993 ThaliTest[2711:4934865] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:52:48.994 ThaliTest[2711:4934865] client session: fireConnectCallb,ack: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:48.994 ThaliTest[2711:4934865] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 23:52:50.713 ThaliTest[2711:4934030] client: lost peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A
2016-04-01 23:52:50.713 ThaliTest[2711:4934030] client session: onPeerLost: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A
,2016-04-01 23:52:51.997 ThaliTest[2711:4934196] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:51.998 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:52:51.998 ThaliTest[2711:4934196] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:52:52.136 ThaliTest[2711:4934866] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:52:52.137 ThaliTest[2711:4934866] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:52.137 ThaliTest[2711:4934866] client session: disconnect
,2016-04-01 23:52:52.138 ThaliTest[2711:4934866] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:52:52.138 ThaliTest[2711:4934866] client session: fireConnectCallback: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
,2016-04-01 23:52:52.138 ThaliTest[2711:4934866] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 23:52:52.731 ThaliTest[2711:4934030] multipeer session: reset timer
2016-04-01 23:52:52.731 ThaliTest[2711:4934030] server: disconnecting to refresh session (BC3134AD-A0D1-47B0-885A-5F5313680802)
2016-04-01 23:52:52.731 ThaliTest[2711:4934030] server: rejecting invitation for lexical ordering BC3134AD-A0D1-47B0-885A-5F5313680802
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BC3134AD-A0D1-47B0-885A-5F5313680802:8","pleaseConnect":1}]
,2016-04-01 23:52:55.151 ThaliTest[2711:4934196] jxcore: connect 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:52:55.151 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:52:55.151 ThaliTest[2711:4934196] client session: stateChange:0->1 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:52:55.607 ThaliTest[2711:4934865] client session: not connected 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:52:55.607 ThaliTest[2711:4934865] client session: onLinkFailure: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:55.608 ThaliTest[2711:4934865] client session: disconnect
2016-04-01 23:52:55.608 ThaliTest[2711:4934865] client session: stateChange:1->0 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:52:55.609 ThaliTest[2711:4934865] client session: fireConnectCallback: 53FC597F-8F79-47DA-ABAE-0C427F412EFF
2016-04-01 23:52:55.609 ThaliTest[2711:4934865] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
    operator: fail
,  ...
,# teardown
,2016-04-01 23:53:03.752 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:53:03.768 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:03.768 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:03.770 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
,2016-04-01 23:53:23.752 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:53:23.767 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:23.767 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
,2016-04-01 23:53:23.769 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
,2016-04-01 23:53:34.139 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 23:53:34.140 ThaliTest[2711:4934196] jxcore: stopListeningForAdvertisements: success
ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:53:34.141 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening
2016-04-01 23:53:34.141 ThaliTest[2711:4934196] THEMultipeerManager stopping peer
2016-04-01 23:53:34.142 ThaliTest[2711:4934196] multipeer manager: stop client timer
2016-04-01 23:53:34.142 ThaliTest[2711:4934196] jxcore: stopAdvertisingAndListening: success
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-01 23:53:34.929 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:53:34.929 ThaliTest[2711:4934196] server: starting EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:53:34.929 ThaliTest[2711:4934196] multipeer m,anager: start client restart timer: 0x146d0df0
2016-04-01 23:53:34.929 ThaliTest[2711:4934196] THEMultipeerManager initialized peer EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:53:34.929 ThaliTest[2711:4934196] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:53:34.931 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 23:53:34.931 ThaliTest[2711:4934196] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-01 23:53:35.945 ThaliTest[2711:4934030] client: found new peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:35.946 ThaliTest[2711:4934030] client: found new peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:53:35.947 ThaliTest[2711:4934030] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
,2016-04-01 23:53:35.949 ThaliTest[2711:4934196] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:35.950 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:53:35.950 ThaliTest[2711:4934196] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:36.801 ThaliTest[2711:4935067] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:36.802 ThaliTest[2711:4935067] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:36.8,02 ThaliTest[2711:4935067] client session: disconnect
2016-04-01 23:53:36.803 ThaliTest[2711:4935067] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:36.803 ThaliTest[2711:4935067] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:36.803 ThaliTest[2711:4935067] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 23:53:39.811 ThaliTest[2711:4934196] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:39.811 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:53:39.812 ThaliTest[2711:4934196] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:40.220 ThaliTest[2711:4935079] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:40.220 ThaliTest[2711:4935079] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:40.222 ThaliTest[2711:4935079] client session: disconnect
,2016-04-01 23:53:40.222 ThaliTest[2711:4935079] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:40.222 ThaliTest[2711:4935079] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:40.222 ThaliTest[2711:4935079] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 23:53:43.231 ThaliTest[2711:4934196] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:43.231 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:53:43.231 ThaliTest[2711:4934196] client session: stateChange:0->,1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:43.900 ThaliTest[2711:4935079] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:43.902 ThaliTest[2711:4935079] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:43.902 ThaliTest[2711:4935079] client session: disconnect
2016-04-01 23:53:43.902 ThaliTest[2711:4935079] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:43.903 ThaliTest[2711:4935079] client session: fireConnectCallb,ack: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:43.903 ThaliTest[2711:4935079] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-04-01 23:53:46.908 ThaliTest[2711:4934196] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:46.909 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:53:46.909 ThaliTest[2711:4934196] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:47.096 ThaliTest[2711:4935061] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:47.096 ThaliTest[2711:4935061] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:47.096 ThaliTest[2711:4935061] client session: disconnect
2016-04-01 23:53:47.096 ThaliTest[2711:4935061] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:47.097 ThaliTest[2711:4935061] client session: fireConnectCallb,ack: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:47.097 ThaliTest[2711:4935061] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-01 23:53:50.111 ThaliTest[2711:4934196] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:50.111 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:53:50.111 ThaliTest[2711:4934196] client session: stateChange:0->,1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:50.244 ThaliTest[2711:4935067] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:50.244 ThaliTest[2711:4935067] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:50.2,44 ThaliTest[2711:4935067] client session: disconnect
2016-04-01 23:53:50.244 ThaliTest[2711:4935067] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:50.246 ThaliTest[2711:4935067] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:50.246 ThaliTest[2711:4935067] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 23:53:53.251 ThaliTest[2711:4934196] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:53.251 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:53:53.251 ThaliTest[2711:4934196] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:53.441 ThaliTest[2711:4935061] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:53.441 ThaliTest[2711:4935061] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:53.442 ThaliTest[2711:4935061] client session: disconnect
2016-04-01 23:53:53.442 ThaliTest[2711:4935061] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:53.443 ThaliTest[2711:4935061] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:53.443 ThaliTest[2711:4935061] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 23:53:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:53:54.943 ThaliTest[2711:4934030] client: found updated peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:53:54.943 ThaliTest[2711:4934030] client: found updated peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:53:54.945 ThaliTest[2711:4934030] client: found updated peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:53:56.455 ThaliTest[2711:4934196] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:56.456 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:53:56.456 ThaliTest[2711:4934196] client session: stateChange:0->,1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:53:56.597 ThaliTest[2711:4935067] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:53:56.597 ThaliTest[2711:4935067] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:56.597 ThaliTest[2711:4935067] client session: disconnect
2016-04-01 23:53:56.597 ThaliTest[2711:4935067] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:53:56.599 ThaliTest[2711:4935067] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:56.599 ThaliTest[2711:4935067] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 23:53:59.610 ThaliTest[2711:4934196] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:59.610 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:53:59.610 ThaliTest[2711:4934196] client session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:53:59.690 ThaliTest[2711:4935067] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:53:59.690 ThaliTest[2711:4935067] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:59.6,90 ThaliTest[2711:4935067] client session: disconnect
2016-04-01 23:53:59.690 ThaliTest[2711:4935067] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:53:59.691 ThaliTest[2711:4935067] client session: fireConnectCallb,ack: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:53:59.691 ThaliTest[2711:4935067] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 23:54:02.696 ThaliTest[2711:4934196] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:54:02.696 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:54:02.697 ThaliTest[2711:4934196] client session: stateChange:0->,1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:54:02.815 ThaliTest[2711:4935061] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:02.815 ThaliTest[2711:4935061] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
,2016-04-01 23:54:02.816 ThaliTest[2711:4935061] client session: disconnect
,2016-04-01 23:54:02.816 ThaliTest[2711:4935061] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:54:02.817 ThaliTest[2711:4935061] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:54:02.817 ThaliTest[2711:4935061] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 23:54:06.101 ThaliTest[2711:4934196] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:54:06.102 ThaliTest[2711:4934196] client session: connect
2016-04-01 23:54:06.102 ThaliTest[2711:4934196] client session: stateChange:0->,1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:54:06.561 ThaliTest[2711:4935067] client session: not connected 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:06.562 ThaliTest[2711:4935067] client session: onLinkFailure: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:54:06.562 ThaliTest[2711:4935067] client session: disconnect
,2016-04-01 23:54:06.562 ThaliTest[2711:4935067] client session: stateChange:1->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:54:06.563 ThaliTest[2711:4935067] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:54:06.563 ThaliTest[2711:4935067] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,2016-04-01 23:54:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:54:14.945 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:54:14.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:14.946 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:54:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:54:34.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:34.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:54:34.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:54:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:54:54.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:54.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:54:54.947 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:55:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:55:14.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:55:14.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:55:14.948 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:55:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:55:34.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:55:34.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:55:34.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:55:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:55:54.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:55:54.948 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:55:54.950 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:56:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:56:14.948 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:56:14.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:56:14.949 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:56:34.929 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:56:34.945 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:56:34.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:56:34.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:56:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:56:54.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:56:54.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:56:54.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:57:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:57:14.945 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:57:14.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:57:14.946 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:57:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:57:34.954 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:57:34.955 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:57:34.955 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:57:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:57:54.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-01 23:57:54.949 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:57:54.949 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:58:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:58:14.947 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:58:14.948 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:58:14.950 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:58:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:58:34.948 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:58:34.949 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:58:34.949 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:58:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:58:54.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:58:54.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:58:54.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:59:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:59:14.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:59:14.948 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:59:14.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:59:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:59:34.945 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:59:34.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:59:34.946 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:59:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-01 23:59:54.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:59:54.948 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:59:54.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:00:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:00:14.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:00:14.949 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:00:14.949 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:00:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:00:34.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:00:34.947 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:00:34.950 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:00:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:00:54.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:00:54.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:00:54.949 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:01:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:01:14.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:01:14.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:01:14.94,7 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:01:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:01:34.949 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:01:34.950 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:01:34.95,0 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:01:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:01:54.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:01:54.947 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:01:54.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:02:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:02:14.952 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:02:14.952 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:02:14.959 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:02:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:02:34.945 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:02:34.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:02:34.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:02:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:02:54.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:02:54.947 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:02:54.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:03:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:03:14.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:03:14.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:03:14.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:03:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:03:34.947 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:03:34.948 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:03:34.949 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:03:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:03:54.945 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:03:54.945 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:03:54.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:04:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:04:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:04:34.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:04:34.947 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:04:34.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:04:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:04:54.947 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:04:54.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:04:54.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:05:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:05:14.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:05:14.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:05:14.946 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:05:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:05:34.947 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:05:34.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:05:34.949 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:05:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:05:54.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:05:54.946 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:05:54.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:06:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:06:14.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:06:14.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:06:14.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:06:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:06:34.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:06:34.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:06:34.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:06:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:06:54.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:06:54.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:06:54.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:07:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:07:14.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:07:14.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:07:14.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:07:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:07:34.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:07:34.948 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:07:34.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:07:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:07:54.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:07:54.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:07:54.94,7 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:08:14.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:08:14.945 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:08:14.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:08:14.951 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:08:34.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:08:34.947 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:08:34.947 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:08:34.948 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
,2016-04-02 00:08:54.930 ThaliTest[2711:4934030] multipeer manager: restart client
,2016-04-02 00:08:54.946 ThaliTest[2711:4934030] client: found existing peer: 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-02 00:08:54.946 ThaliTest[2711:4934030] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:08:54.948 ThaliTest[2711:4934030] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9

```
