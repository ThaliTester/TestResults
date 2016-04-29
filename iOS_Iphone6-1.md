#### Test 68102130f73255a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/24BC4977-CB7E-4B15-ACCF-4177ED6604DB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/24BC4977-CB7E-4B15-ACCF-4177ED6604DB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55215"
,(lldb)     command script import "/tmp/24BC4977-CB7E-4B15-ACCF-4177ED6604DB/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-29 10:09:42.721 ThaliTest[3809:9063358] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FAF39CC6-3084-4C56-AF50-807EE01677EB/Library/Cookies/Cookies.binarycookies
,2016-04-29 10:09:43.113 ThaliTest[3809:9063358] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-29 10:09:43.115 ThaliTest[3809:9063358] Multi-tasking -> Device: YES, App: YES
,2016-04-29 10:09:43.139 ThaliTest[3809:9063358] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-29 10:09:45.185 ThaliTest[3809:9063358] Using UIWebView
,2016-04-29 10:09:45.192 ThaliTest[3809:9063358] [CDVTimer][handleopenurl] 0.451028ms
,2016-04-29 10:09:45.200 ThaliTest[3809:9063358] [CDVTimer][intentandnavigationfilter] 7.236004ms
2016-04-29 10:09:45.201 ThaliTest[3809:9063358] [CDVTimer][gesturehandler] 0.340044ms
2016-04-29 10:09:45.201 ThaliTest[3809:9063358] [CDVTimer][TotalPluginStartup] 9.760022ms
,2016-04-29 10:09:52.273 ThaliTest[3809:9063358] Resetting plugins due to page load.
,2016-04-29 10:09:55.667 ThaliTest[3809:9063358] Finished load of: file:///var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/index.html
,2016-04-29 10:09:55.887 ThaliTest[3809:9063358] JXcore Cordova plugin initializing
,2016-04-29 10:09:55.889 ThaliTest[3809:9063603] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-29 10:10:03.288 ThaliTest[3809:9063603] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-29 10:10:03.288 ThaliTest[3809:9063603] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-29 10:10:03.289 ThaliTest[3809:9,063603] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-29 10:10:03.291 ThaliTest[3809:9063603] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9A74D31D-550C-4AF3-A0AA-8D88F9E76CAA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-29 10:10:09.226 ThaliTest[3809:9063358] THREAD WARNING: ['JXcore'] took '5629.870850' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60539
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60541
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60544
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
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60548
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
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60553
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
,DEBUG createNativeListener: listening 60557
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
,DEBUG createNativeListener: listening 60561
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
,DEBUG createNativeListener: listening 60565
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
,DEBUG createNativeListener: listening 60569
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
,DEBUG createNativeListener: listening 60621
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
,DEBUG createNativeListener: listening 60625
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
,# teardown
,# setup
,# 13. closeAll with promise
,ok 46 not possible to connect to the server anymore
,# teardown
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
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
,ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# teardown
,# setup
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# teardown
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
,# teardown
,# setup
,# 20. basic
,ok 74 sane
,# teardown
,# setup
,# 21. another
,ok 75 sane
,# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"831652d1-f5dc-4370-9bb4-e736119d075f","data":"custom data"},{"uuid":"b7ccdf89-53fb-4b69-acec-42a4f66f335f","data":"custom data"},{"uuid":"b7cd0fef-ad33-49c5-8781-858c9a5e3542","data":"custom data"},{"uuid":"f94a4309-984a-4df8-a677-f820db7183f0","data":"custom data"}]
,ok 76 test participant has uuid
,ok 77 participant data matches
,ok 78 test participant has uuid
,ok 79 participant data matches
,ok 80 test participant has uuid
,ok 81 participant data matches
,ok 82 test participant has uuid
,ok 83 participant data matches
,ok 84 own UUID is found from the participants list
,# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 85 specific error should be returned
,# teardown
,ok 86 error should be null
,ok 87 error should be null
,# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
,# teardown
,ok 89 error should be null
,ok 90 error should be null
,# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60635
,2016-04-29 10:12:44.035 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:44.036 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-29 10:12:44.038 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:44.038 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-29 10:12:44.223 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:12:44.223 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:12:44.223 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:12:44.224 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:44.225 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60637
,2016-04-29 10:12:44.572 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements
,2016-04-29 10:12:44.575 ThaliTest[3809:9063603] multipeer manager: start client restart timer: 0x16ede750
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-29 10:12:44.578 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-29 10:12:44.595 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-04-29 10:12:44.601 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-29 10:12:44.873 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:12:44.873 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:12:44.874 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
,2016-04-29 10:12:44.876 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
2016-04-29 10:12:44.876 ThaliTest[3809:9063603] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:12:44.880 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60639
,2016-04-29 10:12:45.435 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:12:45.436 ThaliTest[3809:9063603] server: starting DB4A2C0F-6E10-427C-8BF8-66B1948D1539:1
2016-04-29 10:12:45.437 ThaliTest[3809:9063603] multipeer m,anager: start client restart timer: 0x16ede750
2016-04-29 10:12:45.437 ThaliTest[3809:9063603] THEMultipeerManager initialized peer DB4A2C0F-6E10-427C-8BF8-66B1948D1539:1
2016-04-29 10:12:45.437 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,2016-04-29 10:12:45.456 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:12:45.457 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:12:45.457 ThaliTest[3809:9063603] multipeer manager: stop client ti,mer
2016-04-29 10:12:45.458 ThaliTest[3809:9063603] server: starting DB4A2C0F-6E10-427C-8BF8-66B1948D1539:2
2016-04-29 10:12:45.459 ThaliTest[3809:9063603] multipeer manager: start client restart timer: 0x16ede750
2016-04-29 10:12:45.459 ThaliTest[3809:,9063603] THEMultipeerManager initialized peer DB4A2C0F-6E10-427C-8BF8-66B1948D1539:2
2016-04-29 10:12:45.460 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-29 10:12:46.821 ThaliTest[3809:9063358] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:2
,2016-04-29 10:12:48.436 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
,2016-04-29 10:12:48.436 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:12:48.438 ThaliTest[3809:9063603] multipeer manager: stop client timer
2016-04-29 10:12:48.438 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
,2016-04-29 10:12:48.439 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:48.446 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60644
,2016-04-29 10:13:03.700 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:03.700 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:03.701 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-29 10:13:03.709 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:03.709 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:03.709 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-29 10:13:03.814 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:03.814 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:03.815 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:13:03.815 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:03.819 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60646
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-29 10:13:04.306 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:04.307 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:04.307 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:13:04.308 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:04.311 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60648
,2016-04-29 10:13:04.649 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements
2016-04-29 10:13:04.649 ThaliTest[3809:9063603] multipeer manager: start client restart timer: 0x16ede750
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:13:04.659 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements: success
,2016-04-29 10:13:04.677 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening
,2016-04-29 10:13:04.678 ThaliTest[3809:9063603] server: starting DB4A2C0F-6E10-427C-8BF8-66B1948D1539:3
,2016-04-29 10:13:04.680 ThaliTest[3809:9063603] THEMultipeerManager initialized peer DB4A2C0F-6E10-427C-8BF8-66B1948D1539:3
,2016-04-29 10:13:04.683 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-29 10:13:04.786 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
,2016-04-29 10:13:04.787 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
,2016-04-29 10:13:04.791 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
,2016-04-29 10:13:04.793 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
,2016-04-29 10:13:04.797 ThaliTest[3809:9063603] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:04.801 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
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
,# teardown
,ok 130 error should be null
,ok 131 error should be null
,# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
,ok 133 port should match
,ok 134 host address should be null
,ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
,ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-29 10:13:28.528 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements
2016-04-29 10:13:28.529 ThaliTest[3809:9063603] multipeer manager: start client restart timer: 0x16ede750
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-29 10:13:28.531 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
2016-04-29 10:13:28.535 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
2016-04-29 10:13:28.536 ThaliTest[3809:9063603] multipeer manager: stop client timer
DEBUG thaliMobileNa,tiveWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:28.542 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-29 10:13:28.784 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:28.786 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:28.789 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:28.790 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:28.790 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: suc,cess
ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-29 10:13:29.355 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements
2016-04-29 10:13:29.356 ThaliTest[3809:9063603] multipeer manager: start client restart timer: 0x16ede750
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-29 10:13:29.358 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
2016-04-29 10:13:29.362 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:13:29.364 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-29 10:13:29.533 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
2016-04-29 10:13:29.534 ThaliTest[3809:9063603] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:29.536 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-29 10:13:29.540 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:29.540 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:29.541 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-29 10:13:30.354 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:30.356 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-29 10:13:30.359 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:30.361 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-29 10:13:37.012 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:37.014 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:37.017 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:37.017 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:37.018 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: suc,cess
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-29 10:13:46.986 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:46.987 ThaliTest[3809:9063603] server: starting DB4A2C0F-6E10-427C-8BF8-66B1948D1539:4
2016-04-29 10:13:46.987 ThaliTest[3809:9063603] multipeer manager: start client restart timer: 0x16ede750
2016-04-29 10:13:46.988 ThaliTest[3809:9063603] THEMultipeerManager initialized peer DB4A2C0F-6E10-427C-8BF8-66B1948D1539:4
,2016-04-29 10:13:46.988 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-29 10:13:46.993 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:46.994 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:46.99,4 ThaliTest[3809:9063603] multipeer manager: stop client timer
2016-04-29 10:13:46.994 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-29 10:13:47.331 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:47.333 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:47.336 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:47.336 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:47.336 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-29 10:13:47.838 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:47.838 ThaliTest[3809:9063603] server: starting DB4A2C0F-6E10-427C-8BF8-66B1948D1539:5
2016-04-29 10:13:47.839 ThaliTest[3809:9063603] multipeer m,anager: start client restart timer: 0x16ede750
2016-04-29 10:13:47.840 ThaliTest[3809:9063603] THEMultipeerManager initialized peer DB4A2C0F-6E10-427C-8BF8-66B1948D1539:5
2016-04-29 10:13:47.840 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-29 10:13:47.843 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:47.843 ThaliTest[3809:9063603] THEMultipeerManager stopping pee,r
2016-04-29 10:13:47.844 ThaliTest[3809:9063603] multipeer manager: stop client timer
2016-04-29 10:13:47.844 ThaliTest[3809:9063603] server: starting DB4A2C0F-6E10-427C-8BF8-66B1948D1539:6
2016-04-29 10:13:47.845 ThaliTest[3809:9063603] multipeer mana,ger: start client restart timer: 0x16ede750
2016-04-29 10:13:47.851 ThaliTest[3809:9063603] THEMultipeerManager initialized peer DB4A2C0F-6E10-427C-8BF8-66B1948D1539:6
2016-04-29 10:13:47.851 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListe,ning: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-29 10:13:47.876 ThaliTest[3809:9063358] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:2
,2016-04-29 10:13:47.985 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-29 10:13:47.988 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:47.991 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:47.991 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:47.991 ThaliTest[3809:9063603] multipeer manager: stop client timer
2016-04-29 10:13:47.992 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-29 10:13:51.872 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:51.872 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:51.873 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-29 10:13:51.875 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:51.876 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:13:51.876 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-29 10:14:02.066 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:14:02.069 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:02.072 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:02.072 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:14:02.073 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: suc,cess
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-29 10:14:08.404 ThaliTest[3809:9063603] jxcore: connect foo
2016-04-29 10:14:08.405 ThaliTest[3809:9063603] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-29 10:14:08.607 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:14:08.609 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:08.613 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:08.613 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:14:08.613 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: suc,cess
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-29 10:14:08.902 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:14:08.903 ThaliTest[3809:9063603] server: starting DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:08.904 ThaliTest[3809:9063603] multipeer m,anager: start client restart timer: 0x16ede750
2016-04-29 10:14:08.904 ThaliTest[3809:9063603] THEMultipeerManager initialized peer DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:08.904 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-29 10:14:08.906 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-29 10:14:08.910 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-29 10:14:09.679 ThaliTest[3809:9063358] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:2
ok 167 peers must be an array
,ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-29 10:14:10.920 ThaliTest[3809:9063358] client: found new peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:7
2016-04-29 10:14:10.921 ThaliTest[3809:9063358] client: found new peer: EF331042-C426-4B67-BF95-35460DC67D54:7
,2016-04-29 10:14:11.913 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-29 10:14:11.916 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:11.919 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
,2016-04-29 10:14:11.920 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:14:11.920 ThaliTest[3809:9063603] multipeer manager: stop client timer
2016-04-29 10:14:11.921 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: su,ccess
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-29 10:14:31.022 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:14:31.022 ThaliTest[3809:9063603] server: starting DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:14:31.023 ThaliTest[3809:9063603] multipeer m,anager: start client restart timer: 0x16ede750
2016-04-29 10:14:31.024 ThaliTest[3809:9063603] THEMultipeerManager initialized peer DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:14:31.024 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-29 10:14:31.027 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-29 10:14:31.030 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-29 10:14:31.527 ThaliTest[3809:9063358] client: found new peer: EF331042-C426-4B67-BF95-35460DC67D54:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EF331042-C426-4B67-BF95-35460DC67D54:7","pleaseConnect":0}]
,2016-04-29 10:14:31.534 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:14:31.535 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:14:31.535 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:14:31.536 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:7
,2016-04-29 10:14:32.166 ThaliTest[3809:9064190] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:14:32.167 ThaliTest[3809:9064190] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:14:32.167 ThaliTest[3809:9064190] client session: disconnect
,2016-04-29 10:14:32.167 ThaliTest[3809:9064190] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:14:32.169 ThaliTest[3809:9064190] client session: no connect callback (server initiated)
,2016-04-29 10:14:33.605 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:14:33.605 ThaliTest[3809:9063358] server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B19,48D1539:8 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7)
,2016-04-29 10:14:36.773 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:14:36.774 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:14:36.774 ThaliTest[3809:9063358] server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7)
,2016-04-29 10:14:39.963 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:14:39.963 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:14:39.964 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7)
,2016-04-29 10:14:41.537 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-29 10:14:42.456 ThaliTest[3809:9063358] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:2
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:2","pleaseConnect":0}]
,2016-04-29 10:14:43.143 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:14:43.143 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:14:43.144 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7)
,2016-04-29 10:14:43.757 ThaliTest[3809:9063358] client: found new peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A45,2F4:7","pleaseConnect":0}]
,2016-04-29 10:14:44.552 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:14:44.553 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:14:44.553 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:14:44.553 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:7
,2016-04-29 10:14:44.635 ThaliTest[3809:9064206] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:14:44.635 ThaliTest[3809:9064206] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:14:44.635 ThaliTest[3809:9064206] client session: disconnect
,2016-04-29 10:14:44.636 ThaliTest[3809:9064206] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:7
,2016-04-29 10:14:44.639 ThaliTest[3809:9064206] client session: no connect callback (server initiated)
,2016-04-29 10:14:46.686 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:14:46.687 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:14:46.687 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7)
,2016-04-29 10:14:49.815 ThaliTest[3809:9063358] multipeer session: reset timer
,2016-04-29 10:14:49.816 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:14:49.817 ThaliTest[3809:9063358] server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to p,revious generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7)
,2016-04-29 10:14:51.025 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:14:51.046 ThaliTest[3809:9063358] client: found updated peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:14:51.047 ThaliTest[3809:9063358] client: found updated peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:14:51.048 ThaliTest[3809:9063358] client: found updated peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EF331042-C426-4B67-BF95-35460DC67D54:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":0}]
,2016-04-29 10:14:53.261 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:14:53.262 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:14:53.262 ThaliTest[3809:9063358] server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7)
,2016-04-29 10:14:54.363 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:14:54.363 ThaliTest[3809:9063358] server: rejecting invitation for lexical ordering DB1392E4-24A2-460A-8746-25C82246EF25
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":1}]
,2016-04-29 10:14:54.554 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-29 10:14:55.364 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:14:55.365 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
2016-04-29 10:14:55.365 ThaliTest[3809:9063358] server: rejecting invitation for lexical ordering DB1392E4-24A2-460A-8746-25C82246EF25
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":1}]
,2016-04-29 10:14:56.668 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:14:56.669 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:14:56.669 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7)
,2016-04-29 10:14:57.563 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:14:57.564 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:14:57.565 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:14:57.565 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:14:57.645 ThaliTest[3809:9064308] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:14:57.645 ThaliTest[3809:9064308] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:14:57.646 ThaliTest[3809:9064308] client session: disconnect
2016-04-29 10:14:57.646 ThaliTest[3809:9064308] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:14:57.647 ThaliTest[3809:9064308] client session: no connect callback (server initiated)
,2016-04-29 10:14:59.773 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:14:59.774 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:14:59.774 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7)
,2016-04-29 10:15:02.905 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:15:02.905 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:15:02.905 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7)
,2016-04-29 10:15:07.566 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-29 10:15:08.622 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:15:08.622 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
2016-04-29 10:15:08.623 ThaliTest[3809:9063358], server: rejecting invitation for lexical ordering DB1392E4-24A2-460A-8746-25C82246EF25
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":1}]
,2016-04-29 10:15:10.118 ThaliTest[3809:9063358] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"337492EA-97B4-404F-B8FE-E0E7631E59C8:9","pleaseConnect":0}]
,2016-04-29 10:15:10.582 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:15:10.583 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:15:10.583 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:15:10.584 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:10.782 ThaliTest[3809:9064242] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:10.782 ThaliTest[3809:9064242] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
,2016-04-29 10:15:10.783 ThaliTest[3809:9064242] client session: disconnect
2016-04-29 10:15:10.784 ThaliTest[3809:9064242] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:10.786 ThaliTest[3809:9064242] client session: no connect callback (server initiated)
,2016-04-29 10:15:11.024 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:15:11.061 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:11.061 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
2016-04-29 10:15:11.061 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
,2016-04-29 10:15:11.069 ThaliTest[3809:9063358] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-29 10:15:20.584 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-29 10:15:21.488 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:15:21.489 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
2016-04-29 10:15:21.489 ThaliTest[3809:9063358], server: rejecting invitation for lexical ordering DB1392E4-24A2-460A-8746-25C82246EF25
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":1}]
,2016-04-29 10:15:23.594 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:15:23.595 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:15:23.595 ThaliTest[3809:9063603] client session: reverseConn,ect
2016-04-29 10:15:23.596 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:23.922 ThaliTest[3809:9064365] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:23.924 ThaliTest[3809:9064365] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:15:23.9,24 ThaliTest[3809:9064365] client session: disconnect
2016-04-29 10:15:23.925 ThaliTest[3809:9064365] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:23.925 ThaliTest[3809:9064365] client session: no connect callback (server initiated)
,2016-04-29 10:15:24.169 ThaliTest[3809:9063358] client: lost peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8
2016-04-29 10:15:24.170 ThaliTest[3809:9063358] client session: onPeerLost: 337492EA-97B4-404F-B8FE-E0E7631E59C8
,2016-04-29 10:15:31.025 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:15:31.056 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:31.057 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:15:31.059 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:15:33.597 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-29 10:15:34.558 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:15:34.558 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
2016-04-29 10:15:34.558 ThaliTest[3809:9063358], server: rejecting invitation for lexical ordering DB1392E4-24A2-460A-8746-25C82246EF25
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":,1}]
,2016-04-29 10:15:36.603 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:15:36.604 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:15:36.604 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:15:36.605 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:37.031 ThaliTest[3809:9064395] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:37.032 ThaliTest[3809:9064395] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:15:37.032 ThaliTest[3809:9064395] client session: disconnect
,2016-04-29 10:15:37.032 ThaliTest[3809:9064395] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:37.035 ThaliTest[3809:9064395] client session: no connect callback (server initiated)
,2016-04-29 10:15:46.606 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-29 10:15:48.625 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:15:48.626 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
2016-04-29 10:15:48.626 ThaliTest[3809:9063358], server: rejecting invitation for lexical ordering DB1392E4-24A2-460A-8746-25C82246EF25
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":1}]
,2016-04-29 10:15:49.612 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:15:49.613 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:15:49.613 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:15:49.614 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:15:50.204 ThaliTest[3809:9064415] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:50.205 ThaliTest[3809:9064415] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:15:50.2,06 ThaliTest[3809:9064415] client session: disconnect
2016-04-29 10:15:50.206 ThaliTest[3809:9064415] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:50.206 ThaliTest[3809:9064415] client session: no connect callb,ack (server initiated)
,2016-04-29 10:15:51.025 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:15:51.055 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:51.056 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:15:51.05,7 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:15:59.615 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-29 10:16:01.928 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:16:01.928 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
,2016-04-29 10:16:01.929 ThaliTest[3809:9063358] server: rejecting invitation for lexical ordering DB1392E4-24A2-460A-8746-25C82246EF25
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":1}]
,2016-04-29 10:16:02.621 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:16:02.622 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:16:02.622 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:16:02.622 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:02.944 ThaliTest[3809:9064395] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:02.944 ThaliTest[3809:9064395] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:16:02.945 ThaliTest[3809:9064395] client session: disconnect
,2016-04-29 10:16:02.945 ThaliTest[3809:9064395] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:02.948 ThaliTest[3809:9064395] client session: no connect callback (server initiated)
,2016-04-29 10:16:11.025 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:16:11.061 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:16:11.064 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:11.065 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:16:12.623 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-29 10:16:15.638 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:16:15.639 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:16:15.639 ThaliTest[3809:9063603] client session: reverseConn,ect
2016-04-29 10:16:15.639 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:15.860 ThaliTest[3809:9064482] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:15.860 ThaliTest[3809:9064482] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:16:15.8,61 ThaliTest[3809:9064482] client session: disconnect
2016-04-29 10:16:15.861 ThaliTest[3809:9064482] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:15.864 ThaliTest[3809:9064482] client session: no connect callback (server initiated)
,2016-04-29 10:16:25.640 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-29 10:16:28.652 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:16:28.653 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:16:28.653 ThaliTest[3809:9063603] client session: reverseConn,ect
2016-04-29 10:16:28.654 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:29.021 ThaliTest[3809:9064524] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:29.022 ThaliTest[3809:9064524] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:16:29.022 ThaliTest[3809:9064524] client session: disconnect
,2016-04-29 10:16:29.022 ThaliTest[3809:9064524] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:29.025 ThaliTest[3809:9064524] client session: no connect callback (server initiated)
,2016-04-29 10:16:31.025 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:16:31.059 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:31.059 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:16:31.06,1 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:16:38.655 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-04-29 10:16:40.585 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-29 10:16:40.587 ThaliTest[3809:9063603] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:16:40.590 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening
2016-04-29 10:16:40.591 ThaliTest[3809:9063603] THEMultipeerManager stopping peer
2016-04-29 10:16:40.592 ThaliTest[3809:9063603] multipeer manager: stop client timer
2016-04-29 10:16:40.593 ThaliTest[3809:9063603] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-29 10:16:42.964 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening
,2016-04-29 10:16:42.964 ThaliTest[3809:9063603] server: starting DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:16:42.966 ThaliTest[3809:9063603] multipeer manager: start client restart timer: 0x16ede750
2016-04-29 10:16:42.967 ThaliTest[3809:90636,03] THEMultipeerManager initialized peer DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:16:42.967 ThaliTest[3809:9063603] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-,29 10:16:42.970 ThaliTest[3809:9063603] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-29 10:16:42.971 ThaliTest[3809:9063603] jxcor,e: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-29 10:16:43.559 ThaliTest[3809:9063358] client: found new peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:43.560 ThaliTest[3809:9063358] client: found new peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
2016-04-29 10:16:43.561 ThaliTes,t[3809:9063358] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:16:43.563 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:43.564 ThaliTest[3809:9063603] client: server will conn,ect
2016-04-29 10:16:43.564 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:16:43.564 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:43.997 ThaliTest[3809:9063358] multipeer session: reset timer
,2016-04-29 10:16:43.997 ThaliTest[3809:9063358] server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:16:44.058 ThaliTest[3809:9063358] multipeer session: reset timer
,2016-04-29 10:16:44.058 ThaliTest[3809:9063358] server: rejecting invitation from 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:16:44.383 ThaliTest[3809:9064543] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:44.384 ThaliTest[3809:9064543] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:16:44.3,84 ThaliTest[3809:9064543] client session: disconnect
2016-04-29 10:16:44.385 ThaliTest[3809:9064543] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:44.386 ThaliTest[3809:9064543] client session: no connect callback (server initiated)
,2016-04-29 10:16:46.068 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:16:46.069 ThaliTest[3809:9063358] server: rejecting invitation from DB1392E4-24A2-460A-8746-25C82246EF25 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B19,48D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:16:47.774 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:16:47.775 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:16:47.775 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:16:51.450 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:16:51.450 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:16:51.451 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:16:53.565 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-29 10:16:55.094 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:16:55.094 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:16:55.095 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:16:56.299 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:16:56.300 ThaliTest[3809:9063358] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:16:56.300 ThaliTest[3809:9063358] server: rejecting invitation from 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:16:56.573 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:56.574 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:16:56.575 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:16:56.575 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:56.902 ThaliTest[3809:9064544] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:56.903 ThaliTest[3809:9064544] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:16:56.9,03 ThaliTest[3809:9064544] client session: disconnect
2016-04-29 10:16:56.904 ThaliTest[3809:9064544] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:56.905 ThaliTest[3809:9064544] client session: no connect callback (server initiated)
,2016-04-29 10:16:57.750 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:16:57.750 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
,2016-04-29 10:16:57.751 ThaliTest[3809:9063358] server: rejecting invitation from DB1392E4-24A2-460A-8746-25C82246EF25 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:16:58.764 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:16:58.764 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:16:58.764 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:02.424 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:02.425 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:17:02.425 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:17:03.001 ThaliTest[3809:9063358] client: found updated peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:17:03.007 ThaliTest[3809:9063358] client: found updated peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:17:03.942 ThaliTest[3809:9063358] client: found updated peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:17:05.604 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:05.604 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:17:05.605 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:06.576 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-29 10:17:08.712 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:08.713 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:17:08.713 ThaliTest[3809:9063358] server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:09.284 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:09.285 ThaliTest[3809:9063358] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:17:09.285 ThaliTest[3809:9063358], server: rejecting invitation from 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:09.584 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:09.585 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:17:09.585 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:17:09.585 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:17:09.663 ThaliTest[3809:9064544] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:17:09.664 ThaliTest[3809:9064544] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
,2016-04-29 10:17:09.664 ThaliTest[3809:9064544] client session: disconnect
,2016-04-29 10:17:09.665 ThaliTest[3809:9064544] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:17:09.668 ThaliTest[3809:9064544] client session: no connect callback (server initiated)
,2016-04-29 10:17:11.282 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:11.283 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
2016-04-29 10:17:11.283 ThaliTest[3809:9063358], server: rejecting invitation from DB1392E4-24A2-460A-8746-25C82246EF25 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:11.902 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:11.903 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:17:11.903 ThaliTest[3809:9063358] server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:15.565 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:15.565 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:17:15.566 ThaliTest[3809:9063358], server: rejecting invitation from EF331042-C426-4B67-BF95-35460DC67D54 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:19.586 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-29 10:17:22.585 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:22.585 ThaliTest[3809:9063358] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:17:22.585 ThaliTest[3809:9063358], server: rejecting invitation from 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:22.599 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:22.599 ThaliTest[3809:9063603] client: server will connect
2016-04-29 10:17:22.600 ThaliTest[3809:9063603] client session: reverseConnect
2016-04-29 10:17:22.600 ThaliTest[3809:9063603] client session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:17:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:17:23.000 ThaliTest[3809:9063358] client: found updated peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:23.001 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:17:23.001, ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:17:23.930 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:23.931 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
2016-04-29 10:17:23.931 ThaliTest[3809:9063358], server: rejecting invitation from DB1392E4-24A2-460A-8746-25C82246EF25 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:32.601 ThaliTest[3809:9063358] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-29 10:17:35.488 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:35.489 ThaliTest[3809:9063358] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:17:35.489 ThaliTest[3809:9063358], server: rejecting invitation from 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:35.606 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:35.607 ThaliTest[3809:9063603] client: already connect(ing/ed) to EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:35.607 Thali,Test[3809:9063603] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-29 10:17:37.120 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:37.121 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
2016-04-29 10:17:37.121 ThaliTest[3809:9063358], server: rejecting invitation from DB1392E4-24A2-460A-8746-25C82246EF25 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:38.619 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:38.620 ThaliTest[3809:9063603] client: already connect(ing/ed) to EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:38.620 ThaliTest[3809:9063603] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-29 10:17:41.640 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:41.641 ThaliTest[3809:9063603] client: already connect(ing/ed) to EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:41.642 ThaliTest[3809:9063603] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-29 10:17:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:17:42.999 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:42.999 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:17:43.000 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:17:44.655 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:44.655 ThaliTest[3809:9063603] client: already connect(ing/ed) to EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:44.656 Thali,Test[3809:9063603] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-29 10:17:45.977 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:45.978 ThaliTest[3809:9063358] server: disconnecting to refresh session (EF331042-C426-4B67-BF95-35460DC67D54)
2016-04-29 10:17:45.978 ThaliTest[3809:9063358], server session: connect
2016-04-29 10:17:45.978 ThaliTest[3809:9063358] server session: stateChange:0->1 EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:17:45.989 ThaliTest[3809:9063358] server: accepting invitation EF331042-C426-4B67-BF95-35460DC67D54
,2016-04-29 10:17:47.676 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:47.677 ThaliTest[3809:9063603] client: server already connecting
,2016-04-29 10:17:48.738 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:48.739 ThaliTest[3809:9063358] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:17:48.739 ThaliTest[3809:9063358], server: rejecting invitation from 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:49.540 ThaliTest[3809:9064697] server session: p2p link connected
,2016-04-29 10:17:49.550 ThaliTest[3809:9063358] server relay: connected (to port: 60672)
,2016-04-29 10:17:49.553 ThaliTest[3809:9063358] server session: stateChange:1->2 EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:17:49.554 ThaliTest[3809:9063358] jxcore: connect: success
,2016-04-29 10:17:50.361 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:17:50.361 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
2016-04-29 10:17:50.362 ThaliTest[3809:9063358] server: rejecting invitation from DB1392E4-24A2-460A-8746-25C82246EF25 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:17:55.419 ThaliTest[3809:9064722] client session: not connected EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:55.419 ThaliTest[3809:9064722] client session: onLinkFailure: EF331042-C426-4B67-BF95-35460DC67D54
2016-04-29 10:17:55.4,20 ThaliTest[3809:9064722] client session: disconnect
2016-04-29 10:17:55.420 ThaliTest[3809:9064722] client session: stateChange:1->0 EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:17:55.421 ThaliTest[3809:9064722] client session: no connect callback (server initiated)
,2016-04-29 10:18:01.535 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:18:01.535 ThaliTest[3809:9063358] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:18:01.536 ThaliTest[3809:9063358], server: rejecting invitation from 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:18:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:18:03.003 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:18:03.006 ThaliTest[3809:9063358] client: found updated peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:18:03.007, ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:18:03.009 ThaliTest[3809:9063603] jxcore: connect EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:18:03.009 ThaliTest[3809:9063603] client: se,rver already connected
2016-04-29 10:18:03.009 ThaliTest[3809:9063603] jxcore: connect: success
,2016-04-29 10:18:03.224 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:18:03.225 ThaliTest[3809:9063358] server: disconnecting to refresh session (DB1392E4-24A2-460A-8746-25C82246EF25)
2016-04-29 10:18:03.225 ThaliTest[3809:9063358], server: rejecting invitation from DB1392E4-24A2-460A-8746-25C82246EF25 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:18:14.276 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:18:14.277 ThaliTest[3809:9063358] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:18:14.277 ThaliTest[3809:9063358], server: rejecting invitation from 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4 due to previous generation (DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9 != DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8)
,2016-04-29 10:18:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:18:23.003 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:18:23.003 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:18:23.005 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:18:42.967 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:18:43.004 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:18:43.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:18:43.007 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:18:43.170 ThaliTest[3809:9063358] multipeer session: reset timer
2016-04-29 10:18:43.171 ThaliTest[3809:9063358] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:18:43.171 ThaliTest[3809:9063358], server: rejecting invitation for lexical ordering 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4
2016-04-29 10:18:43.173 ThaliTest[3809:9063603] jxcore: connect 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:18:43.174 ThaliTest[3809:9063603] client session:, connect
2016-04-29 10:18:43.175 ThaliTest[3809:9063603] client session: stateChange:0->1 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:18:45.165 ThaliTest[3809:9064802] client session: p2p link connected
,2016-04-29 10:18:45.228 ThaliTest[3809:9064855] client session: stateChange:1->2 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:18:45.228 ThaliTest[3809:9064855] client session: fireConnectCallback: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4
2016-04-29 1,0:18:45.229 ThaliTest[3809:9064855] jxcore: connect: success
,2016-04-29 10:18:45.247 ThaliTest[3809:9063358] client: relay established
2016-04-29 10:18:45.247 ThaliTest[3809:9063603] jxcore: connect 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:18:45.247 ThaliTest[3809:9063358] client: new accepted socket: 0x1a8875f0
2016-04-29 10:18:45.248 ThaliTest[3809:9063603] client: already connect(ing/ed) to 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:18:45.248 ThaliTest[3809:9063603] jxcore: connect: fail: Already connect(ing/ed)
ok 182 Expected error
ok, 183 Null connection as expected
,2016-04-29 10:18:45.251 ThaliTest[3809:9063603] jxcore: connect 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:18:45.252 ThaliTest[3809:9063603] client: already connect(ing/ed) to 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:18:45.253 ThaliTest[3809:9063603] jxcore: connect: fail: Already connect(ing/ed)
,ok 184 Expected error
ok 185 Null connection as expected
,# teardown
,2016-04-29 10:19:02.967 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:19:03.001 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:19:03.001 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:19:03.003 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:19:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:19:23.006 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:19:23.007 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:19:23.013 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:19:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:19:43.001 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:19:43.001 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:19:43.002 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:20:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:20:03.005 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:20:03.006 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:20:03.006 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:20:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:20:23.005 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:20:23.005 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:20:23.672 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:20:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:20:43.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:20:43.008 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:20:43.009 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:21:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:21:03.003 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:21:03.007 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:21:03.007 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:21:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:21:23.002 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:21:23.002 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:21:23.00,4 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:21:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:21:43.004 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:21:43.004 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:21:43.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:22:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:22:03.003 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:22:03.004 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:22:03.008 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:22:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:22:23.005 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:22:23.006 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:22:23.00,6 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:22:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:22:43.003 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:22:43.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:22:43.008 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:23:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:23:03.004 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:23:03.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:23:03.005 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:23:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:23:23.003 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:23:23.007 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:23:23.007 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:23:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:23:43.000 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:23:43.005 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:23:43.006 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:24:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:24:03.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:24:03.008 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:24:03.008 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:24:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:24:23.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:24:23.005 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:24:23.006 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:24:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:24:43.006 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:24:43.006 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:24:43.007 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:25:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:25:03.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:25:03.005 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:25:03.005 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:25:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:25:23.007 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:25:23.007 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:25:23.009 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:25:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:25:43.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:25:43.006 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:25:43.007 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:26:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:26:03.004 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:26:03.005 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:26:03.005 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:26:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:26:23.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:26:23.004 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:26:23.00,6 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:26:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:26:43.004 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:26:43.005 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:26:43.006 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:27:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:27:03.001 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:27:03.002 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:27:03.00,5 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:27:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:27:23.002 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:27:23.003 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:27:23.00,3 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:27:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:27:43.004 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:27:43.005 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:27:43.007 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:28:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:28:03.004 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:28:03.004 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:28:03.005 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:28:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:28:23.006 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:28:23.007 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:28:23.007 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:28:42.969 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:28:43.005 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:28:43.005 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:28:43.006 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:29:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:29:03.005 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:29:03.006 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:29:03.00,6 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:29:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:29:23.006 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:29:23.007 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:29:23.008 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:29:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:29:43.002 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:29:43.003 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:29:43.00,3 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:30:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:30:03.005 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:30:03.006 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:30:03.007 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:30:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:30:23.001 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:30:23.001 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:30:23.005 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:30:42.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:30:43.003 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:30:43.003 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:30:43.00,6 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:31:02.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:31:03.004 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:31:03.004 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:31:03.00,6 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:31:22.968 ThaliTest[3809:9063358] multipeer manager: restart client
,2016-04-29 10:31:23.002 ThaliTest[3809:9063358] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:31:23.002 ThaliTest[3809:9063358] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:31:23.008 ThaliTest[3809:9063358] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9

```
