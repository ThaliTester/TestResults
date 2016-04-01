#### Test 64941069b7d3db0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64941069b7d3db0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/EE60E214-FCBA-4730-A632-1952B948214C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/EE60E214-FCBA-4730-A632-1952B948214C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64941069b7d3db0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64941069b7d3db0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50259"
,(lldb)     command script import "/tmp/EE60E214-FCBA-4730-A632-1952B948214C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 15:26:23.617 ThaliTest[298:117714] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FDD5600D-18A4-4C14-AC77-69376256DE39/Library/Cookies/Cookies.binarycookies
,2016-04-01 15:26:24.011 ThaliTest[298:117714] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 15:26:24.012 ThaliTest[298:117714] Multi-tasking -> Device: YES, App: YES
,2016-04-01 15:26:24.031 ThaliTest[298:117714] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 15:26:26.407 ThaliTest[298:117714] Using UIWebView
,2016-04-01 15:26:26.416 ThaliTest[298:117714] [CDVTimer][handleopenurl] 0.416994ms
,2016-04-01 15:26:26.424 ThaliTest[298:117714] [CDVTimer][intentandnavigationfilter] 7.120967ms
,2016-04-01 15:26:26.425 ThaliTest[298:117714] [CDVTimer][gesturehandler] 0.351012ms
,2016-04-01 15:26:26.425 ThaliTest[298:117714] [CDVTimer][TotalPluginStartup] 9.531975ms
,2016-04-01 15:26:34.646 ThaliTest[298:117714] Resetting plugins due to page load.
,2016-04-01 15:26:38.943 ThaliTest[298:117714] Finished load of: file:///var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/index.html
,2016-04-01 15:26:39.149 ThaliTest[298:117714] JXcore Cordova plugin initializing
,2016-04-01 15:26:39.150 ThaliTest[298:117940] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 15:26:45.644 ThaliTest[298:117940] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-01 15:26:45.644 ThaliTest[298:117940] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 15:26:45.645 ThaliTest[298:117940] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-01 15:26:45.646 ThaliTest[298:117940] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DAF71925-C86C-49AC-B69C-254DB34B26F4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-01 15:26:50.872 ThaliTest[298:117714] THREAD WARNING: ['JXcore'] took '4952.002930' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50151
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50153
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
,DEBUG createNativeListener: listening 50156
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
,DEBUG createNativeListener: listening 50160
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
,DEBUG createNativeListener: listening 50165
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
,DEBUG createNativeListener: listening 50169
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
,DEBUG createNativeListener: listening 50173
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
,DEBUG createNativeListener: listening 50177
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
,DEBUG createNativeListener: listening 50181
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
,DEBUG createNativeListener: listening 50233
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
,DEBUG createNativeListener: listening 50237
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
,[{"uuid":"00808060-5bbe-4b5b-bcc4-94f4c6c425a9","data":"custom data"},{"uuid":"9268d93e-6496-4daa-a1e8-946cc4e33b31","data":"custom data"},{"uuid":"2be5ebec-a935-4f30-8b82-7039b8b8a0e2","data":"custom data"},{"uuid":"bd0104a2-12f2-49a9-9a5a-2c37d046ad3e","data":"custom data"}]
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
,DEBUG createNativeListener: listening 50247
,2016-04-01 15:29:01.600 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 15:29:01.601 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-01 15:29:01.603 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 15:29:01.604 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-01 15:29:01.723 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening
2016-04-01 15:29:01.724 ThaliTest[298:117940] THEMultipeerManager stopping peer
2016-04-01 15:29:01.724 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening: success
,2016-04-01 15:29:01.724 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 15:29:01.725 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50249
,2016-04-01 15:29:02.057 ThaliTest[298:117940] jxcore: startListeningForAdvertisements
,2016-04-01 15:29:02.058 ThaliTest[298:117940] multipeer manager: start client restart timer: 0x1568bba0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 15:29:02.063 ThaliTest[298:117940] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-01 15:29:02.084 ThaliTest[298:117940] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 15:29:02.087 ThaliTest[298:117940] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-01 15:29:02.481 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening
,2016-04-01 15:29:02.481 ThaliTest[298:117940] THEMultipeerManager stopping peer
,2016-04-01 15:29:02.482 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening: success
,2016-04-01 15:29:02.483 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
,2016-04-01 15:29:02.484 ThaliTest[298:117940] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:29:02.487 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50251
,2016-04-01 15:29:50.919 ThaliTest[298:117940] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 15:29:50.919 ThaliTest[298:117940] server: starting 1F96C0C1-CD9C-4587-8DB3-FC175CC81D75:1
,2016-04-01 15:29:50.922 ThaliTest[298:117940] multipeer manager: start client restart timer: 0x1568bba0
2016-04-01 15:29:50.923 ThaliTest[298:117940] THEMultipeerManager initialized peer 1F96C0C1-CD9C-4587-8DB3-FC175CC81D75:1
2016-04-01 15:29:50.923 ThaliTest[298:117940] jxcore: startUpdateAdvertisingAndListening: success
,2016-04-01 15:29:50.939 ThaliTest[298:117714] client: found new peer: C0EDA9A5-6F9A-4176-9A72-FB0AA9B3A8C2:2
,ok 103 error should be null
,ok 104 error should be null
,2016-04-01 15:29:50.947 ThaliTest[298:117940] jxcore: startUpdateAdvertisingAndListening
2016-04-01 15:29:50.947 ThaliTest[298:117940] THEMultipeerManager stopping peer
2016-04-01 15:29:50.948 ThaliTest[298:117940] multipeer manager: stop client timer
2016-04-01 15:29:50.948 ThaliTest[298:117940] server: starting 1F96C0C1-CD9C-4587-8DB3-FC175CC81D75:2
,2016-04-01 15:29:50.953 ThaliTest[298:117940] multipeer manager: start client restart timer: 0x1568bba0
2016-04-01 15:29:50.954 ThaliTest[298:117940] THEMultipeerManager initialized peer 1F96C0C1-CD9C-4587-8DB3-FC175CC81D75:2
2016-04-01 15:29:50.954 Thal,iTest[298:117940] jxcore: startUpdateAdvertisingAndListening: success
,2016-04-01 15:29:50.960 ThaliTest[298:117714] client: found new peer: C0EDA9A5-6F9A-4176-9A72-FB0AA9B3A8C2:2
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-01 15:29:51.193 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening
2016-04-01 15:29:51.194 ThaliTest[298:117940] THEMultipeerManager stopping peer
,2016-04-01 15:29:51.195 ThaliTest[298:117940] multipeer manager: stop client timer
,2016-04-01 15:29:51.196 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening: success
,2016-04-01 15:29:51.197 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 15:29:51.202 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50256
,2016-04-01 15:29:51.861 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening
,2016-04-01 15:29:51.861 ThaliTest[298:117940] THEMultipeerManager stopping peer
,2016-04-01 15:29:51.862 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-01 15:29:51.868 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening
,2016-04-01 15:29:51.869 ThaliTest[298:117940] THEMultipeerManager stopping peer
,2016-04-01 15:29:51.869 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-01 15:29:52.691 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening
2016-04-01 15:29:52.692 ThaliTest[298:117940] THEMultipeerManager stopping peer
,2016-04-01 15:29:52.692 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening: success
,2016-04-01 15:29:52.693 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 15:29:52.696 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50258
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-01 15:30:23.994 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening
2016-04-01 15:30:23.994 ThaliTest[298:117940] THEMultipeerManager stopping peer
,2016-04-01 15:30:23.995 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening: success
,2016-04-01 15:30:23.996 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 15:30:23.999 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50260
,2016-04-01 15:30:24.563 ThaliTest[298:117940] jxcore: startListeningForAdvertisements
,2016-04-01 15:30:24.564 ThaliTest[298:117940] multipeer manager: start client restart timer: 0x1568bba0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 15:30:24.569 ThaliTest[298:117940] jxcore: startListeningForAdvertisements: success
,2016-04-01 15:30:24.593 ThaliTest[298:117940] jxcore: startUpdateAdvertisingAndListening
2016-04-01 15:30:24.594 ThaliTest[298:117940] server: starting 1F96C0C1-CD9C-4587-8DB3-FC175CC81D75:3
,2016-04-01 15:30:24.595 ThaliTest[298:117940] THEMultipeerManager initialized peer 1F96C0C1-CD9C-4587-8DB3-FC175CC81D75:3
2016-04-01 15:30:24.595 ThaliTest[298:117940] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-01 15:30:24.847 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening
2016-04-01 15:30:24.847 ThaliTest[298:117940] THEMultipeerManager stopping peer
,2016-04-01 15:30:24.848 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening: success
2016-04-01 15:30:24.849 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
2016-04-01 15:30:24.850 ThaliTest[298:117940] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:30:24.853 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
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
,2016-04-01 15:31:12.240 ThaliTest[298:117940] jxcore: startListeningForAdvertisements
,2016-04-01 15:31:12.241 ThaliTest[298:117940] multipeer manager: start client restart timer: 0x1568bba0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 15:31:12.246 ThaliTest[298:117940] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-01 15:31:12.249 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
,2016-04-01 15:31:12.250 ThaliTest[298:117940] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 15:31:12.253 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-01 15:31:12.582 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 15:31:12.584 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 15:31:12.587 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening
2016-04-01 15:31:12.587 ThaliTest[298:117940] THEMultipeerManager stopping peer
,2016-04-01 15:31:12.588 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening: success
,ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-01 15:31:15.266 ThaliTest[298:117940] jxcore: startListeningForAdvertisements
,2016-04-01 15:31:15.267 ThaliTest[298:117940] multipeer manager: start client restart timer: 0x1568bba0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 15:31:15.270 ThaliTest[298:117940] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
,2016-04-01 15:31:15.272 ThaliTest[298:117940] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 15:31:15.275 ThaliTest[298:117940] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-01 15:31:35.269 ThaliTest[298:117714] multipeer manager: restart client
,2016-04-01 15:31:55.269 ThaliTest[298:117714] multipeer manager: restart client
,2016-04-01 15:31:55.677 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements
2016-04-01 15:31:55.677 ThaliTest[298:117940] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 15:31:55.682 ThaliTest[298:117940] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 15:31:55.684 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening
,2016-04-01 15:31:55.685 ThaliTest[298:117940] THEMultipeerManager stopping peer
,2016-04-01 15:31:55.685 ThaliTest[298:117940] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup

```
