#### Test 64809936d936b9e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/6C0BEBE9-3AD6-4F57-B74B-3752C0DD548A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6C0BEBE9-3AD6-4F57-B74B-3752C0DD548A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50520"
,(lldb)     command script import "/tmp/6C0BEBE9-3AD6-4F57-B74B-3752C0DD548A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-03 21:07:06.029 ThaliTest[2793:5199245] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/92A9542D-81BD-44A8-B713-90AC129EEA85/Library/Cookies/Cookies.binarycookies
,2016-04-03 21:07:06.282 ThaliTest[2793:5199245] Apache Cordova native platform version 4.1.0 is starting.
2016-04-03 21:07:06.283 ThaliTest[2793:5199245] Multi-tasking -> Device: YES, App: YES
,2016-04-03 21:07:06.299 ThaliTest[2793:5199245] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-03 21:07:07.115 ThaliTest[2793:5199245] Using UIWebView
2016-04-03 21:07:07.117 ThaliTest[2793:5199245] [CDVTimer][handleopenurl] 0.150979ms
2016-04-03 21:07:07.120 ThaliTest[2793:5199245] [CDVTimer][intentandnavigationfilter] 2.597988ms
2016-04,-03 21:07:07.120 ThaliTest[2793:5199245] [CDVTimer][gesturehandler] 0.120997ms
2016-04-03 21:07:07.121 ThaliTest[2793:5199245] [CDVTimer][TotalPluginStartup] 3.421009ms
,2016-04-03 21:07:10.341 ThaliTest[2793:5199245] Resetting plugins due to page load.
,2016-04-03 21:07:11.665 ThaliTest[2793:5199245] Finished load of: file:///var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/index.html
,2016-04-03 21:07:11.863 ThaliTest[2793:5199245] JXcore Cordova plugin initializing
,2016-04-03 21:07:11.866 ThaliTest[2793:5199386] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-03 21:07:20.235 ThaliTest[2793:5199386] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-03 21:07:20.236 ThaliTest[2793:5199386] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-03 21:07:20.236 ThaliTest[2793:5199386] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-03 21:07:20.239 ThaliTest[2793:5199386] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2E6291CE-BEDB-4106-B7B6-F1B1623F37A8/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59156
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59158
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
DEBUG createNativeListener: listening 59161
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 59165
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 59170
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 59174
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
DEBUG createNativeListener: listening 59178
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
,# setup
,DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59182
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
DEBUG createNativeListener: listening 59186
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
DEBUG createNativeListener: listening 59238
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
ok 33 server should be fine
,ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59242
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
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
,# teardown
,ok 89 error should be null
ok 90 error should be null
# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59252
,2016-04-03 21:10:42.331 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:42.333 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-03 21:10:42.336 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:10:42.338 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-03 21:10:42.569 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
,2016-04-03 21:10:42.570 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
,2016-04-03 21:10:42.571 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
,2016-04-03 21:10:42.571 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:10:42.573 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59254
,2016-04-03 21:10:42.838 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements
,2016-04-03 21:10:42.839 ThaliTest[2793:5199386] multipeer manager: start client restart timer: 0x146b2380
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-03 21:10:42.840 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-03 21:10:42.975 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:10:42.976 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-03 21:10:43.299 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:43.300 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:10:43.300 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:43.300 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
2016-04-03 21:10:43.300 ThaliTest[2793:5199386] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:43.301 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59256
,2016-04-03 21:10:43.845 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:10:43.845 ThaliTest[2793:5199386] server: starting 4C7015DA-AE07-4F33-B74F-C43FFD219895:1
2016-04-03 21:10:43.845 ThaliTest[2793:5199386] multipeer manager: start client restart timer: 0x146b2380
2016-04-03 21:10:43.846 ThaliTest[2793:5199386] THEMultipeerManager initialized peer 4C7015DA-AE07-4F33-B74F-C43FFD219895:1
2016-04-03 21:10:43.846 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-03 21:10:43.905 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:10:43.905 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:10:43.906 ThaliTest[2793:5199386] multipeer manager: stop client ti,mer
2016-04-03 21:10:43.906 ThaliTest[2793:5199386] server: starting 4C7015DA-AE07-4F33-B74F-C43FFD219895:2
2016-04-03 21:10:43.906 ThaliTest[2793:5199386] multipeer manager: start client restart timer: 0x146b2380
2016-04-03 21:10:43.906 ThaliTest[2793:,5199386] THEMultipeerManager initialized peer 4C7015DA-AE07-4F33-B74F-C43FFD219895:2
2016-04-03 21:10:43.907 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-03 21:10:44.316 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.316 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:10:44.316 ThaliTest[2793:5199386] multipeer manager: stop client timer
20,16-04-03 21:10:44.316 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
2016-04-03 21:10:44.316 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:44.317 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59261
,2016-04-03 21:10:44.770 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.770 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:10:44.770 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
,2016-04-03 21:10:44.773 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.773 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:10:44.773 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: suc,cess
ok 111 error should be null
ok 112 error should be null
,# teardown
,2016-04-03 21:10:44.891 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.891 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:10:44.891 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:44.892 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:44.892 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59263
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-03 21:10:45.806 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:45.807 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:10:45.807 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
2016-04-03 21:10:45.807 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:45.808 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59265
2016-04-03 21:10:46.791 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements
2016-04-03 21:10:46.791 ThaliTest[2793:5199386] multipeer manager: start client restart timer: 0x146b2380
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:10:46.792 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements: success
,2016-04-03 21:10:46.804 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:10:46.804 ThaliTest[2793:5199386] server: starting 4C7015DA-AE07-4F33-B74F-C43FFD219895:3
2016-04-03 21:10:46.804 ThaliTest[2793:5199386] THEMultipee,rManager initialized peer 4C7015DA-AE07-4F33-B74F-C43FFD219895:3
2016-04-03 21:10:46.804 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
,# teardown
,2016-04-03 21:10:47.234 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:47.235 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:10:47.235 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-03 21:10:47.235 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
2016-04-03 21:10:47.235 ThaliTest[2793:5199386] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-03 21:10:47.236 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 123 error should be null
ok 124 error should be null
# setup
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
,ok 133 port should match
,ok 134 host address should be null
,ok 135 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-03 21:11:48.876 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements
2016-04-03 21:11:48.876 ThaliTest[2793:5199386] multipeer manager: start client restart timer: 0x146b2380
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:11:48.877 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-03 21:11:48.878 ThaliTes,t[2793:5199386] jxcore: stopListeningForAdvertisements
2016-04-03 21:11:48.878 ThaliTest[2793:5199386] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:11:48.878 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-03 21:11:49.203 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:11:49.204 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:11:49.205 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:11:49.205 ThaliTest[2793:51993,86] THEMultipeerManager stopping peer
2016-04-03 21:11:49.205 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-03 21:11:49.656 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements
2016-04-03 21:11:49.656 ThaliTest[2793:5199386] multipeer manager: start client restart timer: 0x146b2380
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:11:49.657 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-03 21:11:49.657 ThaliTes,t[2793:5199386] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:11:49.658 ThaliTest[2793:5199386] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-03 21:11:49.763 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
2016-04-03 21:11:49.764 ThaliTest[2793:5199386] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-03 21:11:49.764 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:11:49.765 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:11:49.765 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:11:49.765 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-03 21:12:19.584 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:19.585 ThaliTest[2793:51993,86] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-03 21:12:19.586 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:19.586 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-03 21:12:19.691 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:19.691 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:12:19.692 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:12:19.692 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:12:19.692 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-03 21:12:20.023 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:12:20.023 ThaliTest[2793:5199386] server: starting 4C7015DA-AE07-4F33-B74F-C43FFD219895:4
2016-04-03 21:12:20.024 ThaliTest[2793:5199386] multipeer m,anager: start client restart timer: 0x146b2380
2016-04-03 21:12:20.024 ThaliTest[2793:5199386] THEMultipeerManager initialized peer 4C7015DA-AE07-4F33-B74F-C43FFD219895:4
2016-04-03 21:12:20.024 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:12:20.025 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:12:20.025 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
,2016-04-03 21:12:20.025 ThaliTest[2793:5199386] multipeer manager: stop client timer
2016-04-03 21:12:20.029 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-03 21:12:24.206 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:12:24.207 ThaliTest[2793:51993,86] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:12:24.208 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:12:24.208 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:12:24.208 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-03 21:13:46.836 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:13:46.836 ThaliTest[2793:5199386] server: starting 4C7015DA-AE07-4F33-B74F-C43FFD219895:5
2016-04-03 21:13:46.837 ThaliTest[2793:5199386] multipeer manager: start client restart timer: 0x146b2380
2016-04-03 21:13:46.837 ThaliTest[2793:5199386] THEMultipeerManager initialized peer 4C7015DA-AE07-4F33-B74F-C43FFD219895:5
2016-04-03 21:13:46.837 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:13:46.838 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:13:46.838 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
,2016-04-03 21:13:46.838 ThaliTest[2793:5199386] multipeer manager: stop client timer
2016-04-03 21:13:46.842 ThaliTest[2793:5199386] server: starting 4C7015DA-AE07-4F33-B74F-C43FFD219895:6
2016-04-03 21:13:46.842 ThaliTest[2793:5199386] multipeer manager: start client restart timer: 0x146b2380
2016-04-03 21:13:46.842 ThaliTest[2793:5199386] THEMultipeerManager initialized peer 4C7015DA-AE07-4F33-B74F-C43FFD219895:6
2016-04-03 21:13:46.843 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-03 21:13:47.282 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-03 21:13:47.283 ThaliTest[2793:519938,6] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:13:47.284 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.284 ThaliTest[2793:519938,6] THEMultipeerManager stopping peer
2016-04-03 21:13:47.284 ThaliTest[2793:5199386] multipeer manager: stop client timer
2016-04-03 21:13:47.284 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-03 21:13:47.748 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.749 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:13:47.749 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:13:47.749 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.749 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:13,:47.750 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-03 21:13:47.863 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:13:47.864 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:13:47.865 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:13:47.865 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:13:47.865 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-03 21:14:31.672 ThaliTest[2793:5199386] jxcore: connect foo
2016-04-03 21:14:31.672 ThaliTest[2793:5199386] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-03 21:14:32.125 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-03 21:14:32.126 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:14:32.127 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:14:32.127 ThaliTest[2793:51993,86] THEMultipeerManager stopping peer
2016-04-03 21:14:32.127 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-03 21:14:32.488 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:14:32.488 ThaliTest[2793:5199386] server: starting 4C7015DA-AE07-4F33-B74F-C43FFD219895:7
2016-04-03 21:14:32.489 ThaliTest[2793:5199386] multipeer m,anager: start client restart timer: 0x146b2380
2016-04-03 21:14:32.489 ThaliTest[2793:5199386] THEMultipeerManager initialized peer 4C7015DA-AE07-4F33-B74F-C43FFD219895:7
2016-04-03 21:14:32.489 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-03 21:14:32.491 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-03 21:14:32.492 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-03 21:14:33.095 ThaliTest[2793:5199245] client: found new peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,ok 167 peers must be an array
,ok 168 peers must not be zero-length
,ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-03 21:14:34.363 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-03 21:14:34.364 ThaliTest[2793:519938,6] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-03 21:14:34.365 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:14:34.365 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
,2016-04-03 21:14:34.365 ThaliTest[2793:5199386] multipeer manager: stop client timer
2016-04-03 21:14:34.366 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-03 21:14:34.999 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:14:34.999 ThaliTest[2793:5199386] server: starting 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
2016-04-03 21:14:35.000 ThaliTest[2793:5199386] multipeer m,anager: start client restart timer: 0x146b2380
2016-04-03 21:14:35.000 ThaliTest[2793:5199386] THEMultipeerManager initialized peer 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
2016-04-03 21:14:35.000 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:14:35.001 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-03 21:14:35.001 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-03 21:14:35.537 ThaliTest[2793:5199245] client: found new peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"569AF1E0-EE92-40BF-918A-581DB52F2,2D0:7","pleaseConnect":0}]
2016-04-03 21:14:35.539 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:35.539 ThaliTest[2793:5199386] client: server will connect
2016-04-03 21:14:35.539 ThaliTest[2793:5199386] client session: reverseConnect
2016-04-03 21:14:35.539 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:36.238 ThaliTest[2793:5199245] client: found new peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:14:36.239 ThaliTest[2793:5199245] client: found new peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9C9DAABD-80A6-487A-AC19-4D6E0668D813:7","pleaseConnect":0}]
,2016-04-03 21:14:36.413 ThaliTest[2793:5200421] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:36.413 ThaliTest[2793:5200421] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
,2016-04-03 21:14:36.414 ThaliTest[2793:5200421] client session: disconnect
2016-04-03 21:14:36.414 ThaliTest[2793:5200421] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:36.415 ThaliTest[2793:5200421] client session: no connect callback (server initiated)
,2016-04-03 21:14:45.540 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 9
,2016-04-03 21:14:48.544 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:48.544 ThaliTest[2793:5199386] client: server will connect
2016-04-03 21:14:48.544 ThaliTest[2793:5199386] client session: reverseConn,ect
2016-04-03 21:14:48.544 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:48.884 ThaliTest[2793:5200465] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:48.884 ThaliTest[2793:5200465] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:14:48.885 ThaliTest[2793:5200465] client session: disconnect
2016-04-03 21:14:48.885 ThaliTest[2793:5200465] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:48.886 ThaliTest[2793:5200465] client session: no connect callback (server initiated)
,2016-04-03 21:14:55.001 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:14:55.021 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:14:55.021 ThaliTest[2793:5199245] client: found updated peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:14:55.022 ThaliTest[2793:5199245] client: found updated peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"569AF1E0-EE92-40BF-918A-581DB52F22D0:8","pleaseConne,ct":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9C9DAABD-80A6-487A-AC19-4D6E0668D813:8","pleaseConnect":0}]
,2016-04-03 21:14:58.545 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-03 21:15:01.555 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:01.556 ThaliTest[2793:5199386] client: server will connect
2016-04-03 21:15:01.556 ThaliTest[2793:5199386] client session: reverseConnect
2016-04-03 21:15:01.556 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:01.872 ThaliTest[2793:5200465] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:01.874 ThaliTest[2793:5200465] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:01.874 ThaliTest[2793:5200465] client session: disconnect
2016-04-03 21:15:01.874 ThaliTest[2793:5200465] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:01.874 ThaliTest[2793:5200465] client session: no connect callback (server initiated)
,2016-04-03 21:15:11.557 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-03 21:15:14.567 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:14.568 ThaliTest[2793:5199386] client: server will connect
2016-04-03 21:15:14.568 ThaliTest[2793:5199386] client session: reverseConnect
2016-04-03 21:15:14.568 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:15:15.001 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:15:15.019 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:15:15.019 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:15.021 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:24.568 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-03 21:15:27.576 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:27.576 ThaliTest[2793:5199386] client: already connect(ing/ed) to 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:27.577 Thali,Test[2793:5199386] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-03 21:15:30.584 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:30.584 ThaliTest[2793:5199386] client: already connect(ing/ed) to 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:30.584 Thali,Test[2793:5199386] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-03 21:15:33.599 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:33.599 ThaliTest[2793:5199386] client: already connect(ing/ed) to 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:33.599 ThaliTest[2793:5199386] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-03 21:15:35.001 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:15:35.023 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:35.024 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:15:35.024 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:36.608 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:36.609 ThaliTest[2793:5199386] client: already connect(ing/ed) to 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:36.609 ThaliTest[2793:5199386] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-03 21:15:39.624 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:39.624 ThaliTest[2793:5199386] client: already connect(ing/ed) to 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:39.624 Thali,Test[2793:5199386] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-03 21:15:42.634 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:42.634 ThaliTest[2793:5199386] client: already connect(ing/ed) to 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:15:42.634 Thali,Test[2793:5199386] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
,  ---
    operator: fail
  ...
,# teardown
,2016-04-03 21:15:47.549 ThaliTest[2793:5200608] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:47.549 ThaliTest[2793:5200608] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:15:47.5,49 ThaliTest[2793:5200608] client session: disconnect
2016-04-03 21:15:47.549 ThaliTest[2793:5200608] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:15:47.549 ThaliTest[2793:5200608] client session: no connect callback (server initiated)
,2016-04-03 21:15:55.001 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:15:55.023 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:15:55.023 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:15:55.023 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:16:15.001 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:16:15.017 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:15.017 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:15.018 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:16:35.001 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:16:35.017 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:35.017 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:35.018 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:16:43.351 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-03 21:16:43.352 ThaliTest[2793:5199386] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:16:43.353 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening
2016-04-03 21:16:43.354 ThaliTest[2793:5199386] THEMultipeerManager stopping peer
2016-04-03 21:16:43.354 ThaliTest[2793:5199386] multipeer manager: stop client timer
20,16-04-03 21:16:43.354 ThaliTest[2793:5199386] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-03 21:16:43.854 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:16:43.855 ThaliTest[2793:5199386] server: starting 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:16:43.855 ThaliTest[2793:5199386] multipeer manager: start client restart timer: 0x146b2380
2016-04-03 21:16:43.855 ThaliTest[2793:5199386] THEMultipeerManager initialized peer 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:16:43.855 ThaliTest[2793:5199386] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:16:43.856 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-03 21:16:43.858 ThaliTest[2793:5199386] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-03 21:16:44.832 ThaliTest[2793:5199245] client: found new peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:44.833 ThaliTest[2793:5199245] client: found new peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:44.835 ThaliTest[2793:5199245] client: found new peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:44.835 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:44.835 ThaliTest[2793:5199386] client: server will conn,ect
2016-04-03 21:16:44.835 ThaliTest[2793:5199386] client session: reverseConnect
2016-04-03 21:16:44.836 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:16:46.367 ThaliTest[2793:5200744] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:46.369 ThaliTest[2793:5200744] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
,2016-04-03 21:16:46.369 ThaliTest[2793:5200744] client session: disconnect
2016-04-03 21:16:46.370 ThaliTest[2793:5200744] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:46.370 ThaliTest[2793:5200744] client session: no connect callback (server initiated)
,2016-04-03 21:16:54.836 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-03 21:16:57.848 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:57.848 ThaliTest[2793:5199386] client: server will connect
2016-04-03 21:16:57.848 ThaliTest[2793:5199386] client session: reverseConn,ect
2016-04-03 21:16:57.848 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:16:58.665 ThaliTest[2793:5200744] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:58.665 ThaliTest[2793:5200744] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:16:58.6,65 ThaliTest[2793:5200744] client session: disconnect
2016-04-03 21:16:58.666 ThaliTest[2793:5200744] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:16:58.666 ThaliTest[2793:5200744] client session: no connect callback (server initiated)
,2016-04-03 21:17:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:17:03.872 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:17:03.872 ThaliTest[2793:5199245] client: found updated peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:03.872 ThaliTest[2793:5199245] client: found updated peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:17:07.849 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-03 21:17:10.854 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:17:10.854 ThaliTest[2793:5199386] client: server will connect
2016-04-03 21:17:10.855 ThaliTest[2793:5199386] client session: reverseConnect
2016-04-03 21:17:10.855 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:17:11.090 ThaliTest[2793:5200744] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:17:11.091 ThaliTest[2793:5200744] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:17:11.091 ThaliTest[2793:5200744] client session: disconnect
2016-04-03 21:17:11.091 ThaliTest[2793:5200744] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:17:11.092 ThaliTest[2793:5200744] client session: no connect callback (server initiated)
,2016-04-03 21:17:20.856 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-03 21:17:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:17:23.867 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:17:23.869 ThaliTest[2793:5199386] client: server will connect
2016-04-03 21:17:23.869 ThaliTest[2793:5199386] client session: reverseConnect
2016-04-03 21:17:23.870 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:17:23.882 ThaliTest[2793:5199245] client: lost peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:17:23.882 ThaliTest[2793:5199245] client session: onPeerLost: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:17:23.882 ThaliTest[2793:5199245] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:17:23.882 ThaliTest[2793:5199245] client session: disconnect
2016-04-03 21:17:23.882 ThaliTest[2793:5199245] client session: stateChange:1->0 569AF1E0-EE92-40BF-,918A-581DB52F22D0:9
2016-04-03 21:17:23.882 ThaliTest[2793:5199245] client session: no connect callback (server initiated)
2016-04-03 21:17:23.885 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:17:23.885 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:23.886 ThaliTest[2793:5199245] client: found updated peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:33.883 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-03 21:17:36.892 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:17:36.893 ThaliTest[2793:5199386] client: server will connect
2016-04-03 21:17:36.893 ThaliTest[2793:5199386] client session: reverseConnect
2016-04-03 21:17:36.893 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:17:38.030 ThaliTest[2793:5200864] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:17:38.031 ThaliTest[2793:5200864] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:17:38.0,31 ThaliTest[2793:5200864] client session: disconnect
2016-04-03 21:17:38.031 ThaliTest[2793:5200864] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:17:38.031 ThaliTest[2793:5200864] client session: no connect callback (server initiated)
,2016-04-03 21:17:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:17:43.878 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:43.878 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:17:43.87,8 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:46.894 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-03 21:17:49.899 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:17:49.899 ThaliTest[2793:5199386] client: server will connect
2016-04-03 21:17:49.899 ThaliTest[2793:5199386] client session: reverseConn,ect
2016-04-03 21:17:49.900 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:17:50.208 ThaliTest[2793:5200861] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:17:50.208 ThaliTest[2793:5200861] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:17:50.210 ThaliTest[2793:5200861] client session: disconnect
2016-04-03 21:17:50.210 ThaliTest[2793:5200861] client session:, stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:17:50.210 ThaliTest[2793:5200861] client session: no connect callback (server initiated)
,2016-04-03 21:17:59.900 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-03 21:18:02.911 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:18:02.911 ThaliTest[2793:5199386] client: server will connect
2016-04-03 21:18:02.911 ThaliTest[2793:5199386] client session: reverseConnect
2016-04-03 21:18:02.911 ThaliTest[2793:5199386] client session: stateChange:0->1 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:18:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:18:03.873 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:18:03.874 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:18:03.874 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:18:12.912 ThaliTest[2793:5199245] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 3
,2016-04-03 21:18:15.924 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:18:15.924 ThaliTest[2793:5199386] client: already connect(ing/ed) to 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:18:15.925 ThaliTest[2793:5199386] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-03 21:18:18.935 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:18:18.935 ThaliTest[2793:5199386] client: already connect(ing/ed) to 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:18:18.935 Thali,Test[2793:5199386] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-03 21:18:21.945 ThaliTest[2793:5199386] jxcore: connect 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:18:21.945 ThaliTest[2793:5199386] client: already connect(ing/ed) to 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:18:21.945 Thali,Test[2793:5199386] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,2016-04-03 21:18:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:18:23.872 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:18:23.872 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:23.872 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:18:35.909 ThaliTest[2793:5200864] client session: not connected 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:18:35.909 ThaliTest[2793:5200864] client session: onLinkFailure: 569AF1E0-EE92-40BF-918A-581DB52F22D0
2016-04-03 21:18:35.9,09 ThaliTest[2793:5200864] client session: disconnect
2016-04-03 21:18:35.909 ThaliTest[2793:5200864] client session: stateChange:1->0 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:18:35.909 ThaliTest[2793:5200864] client session: no connect callback (server initiated)
,2016-04-03 21:18:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:18:43.872 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:43.872 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:18:43.872 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:19:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:19:03.872 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:19:03.872 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:19:03.873 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:19:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:19:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:19:43.871 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:19:43.872 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:19:43.873 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:20:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:20:03.874 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:20:03.875 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:20:03.87,6 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:20:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:20:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:20:43.867 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:20:43.867 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:20:43.86,7 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:21:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:21:03.870 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:21:03.870 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:21:03.870 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:21:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:21:23.869 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:21:23.869 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:21:23.86,9 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:21:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:22:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:22:03.866 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:22:03.867 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:22:03.869 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:22:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:22:23.869 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:22:23.869 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:22:23.869 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:22:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:22:43.867 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:22:43.870 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:22:43.870 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:23:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:23:03.868 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:23:03.869 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:23:03.869 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:23:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:23:23.869 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:23:23.869 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:23:23.86,9 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:23:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:23:43.870 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:23:43.870 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:23:43.870 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:24:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:24:03.869 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:24:03.870 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:24:03.870 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:24:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:24:23.868 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:24:23.868 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:24:23.872 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:24:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:24:43.870 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:24:43.870 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:24:43.870 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:25:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:25:03.869 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:25:03.870 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:25:03.870 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:25:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:25:23.869 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:25:23.869 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:25:23.870 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:25:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:25:43.868 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:25:43.868 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:25:43.871 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:26:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:26:03.868 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:26:03.868 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:26:03.871 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:26:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:26:23.870 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:26:23.871 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:26:23.87,1 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:26:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:26:43.871 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:26:43.872 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:26:43.877 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:27:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:27:03.872 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:27:03.872 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:27:03.872 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:27:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:27:23.870 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:27:23.870 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:27:23.871 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:27:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:27:43.869 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:27:43.869 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:27:43.870 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:28:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:28:03.867 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:28:03.868 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:28:03.868 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:28:23.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:28:23.869 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:28:23.869 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:28:23.870 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:28:43.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:28:43.867 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:28:43.867 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:28:43.869 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:29:03.856 ThaliTest[2793:5199245] multipeer manager: restart client
,2016-04-03 21:29:03.869 ThaliTest[2793:5199245] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:29:03.869 ThaliTest[2793:5199245] client: found existing peer: 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
2016-04-03 21:29:03.871 ThaliTest[2793:5199245] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9

```
