#### Test 64531254841497d_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8FD191FD-4663-4A0E-930F-456EBC5E522B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/8FD191FD-4663-4A0E-930F-456EBC5E522B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56563"
,(lldb)     command script import "/tmp/8FD191FD-4663-4A0E-930F-456EBC5E522B/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-29 23:39:55.220 ThaliTest[1835:4693665] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/73F5905E-FB31-4357-9E9F-70D10DE3A242/Library/Cookies/Cookies.binarycookies
,2016-03-29 23:39:55.325 ThaliTest[1835:4693665] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-29 23:39:55.327 ThaliTest[1835:4693665] Multi-tasking -> Device: YES, App: YES
,2016-03-29 23:39:55.344 ThaliTest[1835:4693665] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 23:39:56.513 ThaliTest[1835:4693665] Using UIWebView
2016-03-29 23:39:56.517 ThaliTest[1835:4693665] [CDVTimer][handleopenurl] 0.231981ms
,2016-03-29 23:39:56.522 ThaliTest[1835:4693665] [CDVTimer][intentandnavigationfilter] 5.465984ms
2016-03-29 23:39:56.523 ThaliTest[1835:4693665] [CDVTimer][gesturehandler] 0.216007ms
2016-03-29 23:39:56.523 ThaliTest[1835:4693665] [CDVTimer][TotalPluginS,tartup] 6.734014ms
,2016-03-29 23:40:01.757 ThaliTest[1835:4693665] Resetting plugins due to page load.
,2016-03-29 23:40:03.862 ThaliTest[1835:4693665] Finished load of: file:///var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/index.html
,2016-03-29 23:40:04.053 ThaliTest[1835:4693665] JXcore Cordova plugin initializing
,2016-03-29 23:40:04.055 ThaliTest[1835:4693808] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-29 23:40:18.197 ThaliTest[1835:4693808] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 23:40:18.198 ThaliTest[1835:4693808] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 23:40:18.198 ThaliTest[1835:4,693808] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 23:40:18.200 ThaliTest[1835:4693808] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FFEAA5C-05ED-4B0F-A489-0B453A84D870/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54928
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54930
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54933
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 54937
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54942
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
DEBUG createNativeListener: listening 54946
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
DEBUG createNativeListener: listening 54950
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: listening 54954
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
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54958
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
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creat,ing incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
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
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
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
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
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
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
,ok 30 incoming has been removed
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
D,EBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55010
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
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
DEBUG createNativeListener: listening 55014
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
# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55024
2016-03-29 23:43:12.002 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:12.003 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
ok 89 error should be null
ok 90 error should be null
,2016-03-29 23:43:12.006 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 23:43:12.009 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,# teardown
,2016-03-29 23:43:12.119 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
,2016-03-29 23:43:12.120 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
,2016-03-29 23:43:12.121 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
,2016-03-29 23:43:12.123 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 23:43:12.124 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55026
,2016-03-29 23:43:12.404 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
,2016-03-29 23:43:12.406 ThaliTest[1835:4693808] multipeer manager: start client restart timer: 0x14ec7470
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:43:12.407 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-29 23:43:12.420 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-29 23:43:12.421 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
# teardown
,2016-03-29 23:43:12.728 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:12.728 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:43:12.728 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 23:43:12.728 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
2016-03-29 23:43:12.729 ThaliTest[1835:4693808] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:12.730 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 99 error should be null
ok 100 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55028
2016-03-29 23:43:13.203 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:43:13.203 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:1
2016-03-29 23:,43:13.204 ThaliTest[1835:4693808] multipeer manager: start client restart timer: 0x14ec7470
2016-03-29 23:43:13.204 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:1
2016-03-29 23:43:13.204 ThaliTest[1835,:4693808] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
2016-03-29 23:43:13.216 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:43:13.216 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:43:13.217, ThaliTest[1835:4693808] multipeer manager: stop client timer
2016-03-29 23:43:13.217 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:2
2016-03-29 23:43:13.217 ThaliTest[1835:4693808] multipeer manager: start client restart ,timer: 0x14ec7470
2016-03-29 23:43:13.218 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:2
2016-03-29 23:43:13.218 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
# teardown
,2016-03-29 23:43:14.932 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:14.932 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:43:14.932 ThaliTest[1835:4693808] multipeer manager: stop client timer
20,16-03-29 23:43:14.932 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
2016-03-29 23:43:14.933 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:14.934 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 105 error should be null
,ok 106 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55033
,2016-03-29 23:43:33.330 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:33.330 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:43:33.331 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: suc,cess
ok 107 error should be null
ok 108 error should be null
2016-03-29 23:43:33.333 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:33.334 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:43:33.334 ,ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
# teardown
,2016-03-29 23:43:35.516 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:35.516 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:43:35.516 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 23:43:35.516 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:35.517 ThaliTest[1835,:4693808] jxcore: stopListeningForAdvertisements: success
ok 111 error should be null
ok 112 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55035
,ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
,# teardown
,2016-03-29 23:43:43.036 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:43.037 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:43:43.037 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 23:43:43.037 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:43.038 ThaliTest[1835,:4693808] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55037
2016-03-29 23:43:43.321 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
2016-03-29 23:43:43.322 ThaliTest[1835:4693808] multipeer manager: start client restart timer: 0x14ec7470
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-29 23:43:43.323 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
,2016-03-29 23:43:43.340 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:43:43.340 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:3
2016-03-29 23:43:43.341 ThaliTest[1835:4693808] THEMultipee,rManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:3
2016-03-29 23:43:43.341 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening: success
,ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
,# teardown
,2016-03-29 23:43:43.690 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:43.690 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:43:43.690 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 23:43:43.691 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
2016-03-29 23:43:43.691 ThaliTest[1835:4693808] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:43.693 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 121 error should be null
,ok 122 error should be null
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
,ok 133 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
,ok 135 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-03-29 23:44:25.429 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
2016-03-29 23:44:25.430 ThaliTest[1835:4693808] multipeer manager: start client restart timer: 0x14ec7470
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:44:25.431 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-29 23:44:25.432 ThaliTes,t[1835:4693808] jxcore: stopListeningForAdvertisements
2016-03-29 23:44:25.432 ThaliTest[1835:4693808] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-29 23:44:25.433 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 23:44:25.704 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:25.705 ThaliTest[1835:46938,08] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:44:25.706 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:44:25.706 ThaliTest[1835:46938,08] THEMultipeerManager stopping peer
2016-03-29 23:44:25.707 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-29 23:44:26.398 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
2016-03-29 23:44:26.398 ThaliTest[1835:4693808] multipeer manager: start client restart timer: 0x14ec7470
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:44:26.400 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-29 23:44:26.401 ThaliTes,t[1835:4693808] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:44:26.402 ThaliTest[1835:4693808] jxcore: startListeningForAdv,ertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-29 23:44:44.560 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
2016-03-29 23:44:44.561 ThaliTest[1835:4693808] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-29 23:44:44.562 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:44:44.562 ThaliTest[1835:4693,808] jxcore: stopAdvertisingAndListening
2016-03-29 23:44:44.563 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:44:44.563 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-03-29 23:44:54.139 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:54.140 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
ok 144 Can call stopListeningForAdvertisements without error
2016-03-29 23:44:54.141 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:54.142 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
ok 145 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 23:44:54.662 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:54.663 ThaliTest[1835:46938,08] jxcore: stopListeningForAdvertisements: success
ok 146 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:44:54.664 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:44:54.664 ThaliTest[1835:46938,08] THEMultipeerManager stopping peer
2016-03-29 23:44:54.664 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 147 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-29 23:45:03.296 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:45:03.296 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:4
2016-03-29 23:45:03.297 ThaliTest[1835:4693808] multipeer m,anager: start client restart timer: 0x14ec7470
2016-03-29 23:45:03.297 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:4
2016-03-29 23:45:03.297 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 148 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:45:03.299 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:03.299 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
,2016-03-29 23:45:03.299 ThaliTest[1835:4693808] multipeer manager: stop client timer
2016-03-29 23:45:03.303 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 149 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-29 23:45:03.634 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:45:03.635 ThaliTest[1835:46938,08] jxcore: stopListeningForAdvertisements: success
ok 150 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:45:03.636 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:03.636 ThaliTest[1835:46938,08] THEMultipeerManager stopping peer
2016-03-29 23:45:03.636 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 151 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-29 23:45:06.607 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:45:06.607 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:5
2016-03-29 23:45:06.608 ThaliTest[1835:4693808] multipeer m,anager: start client restart timer: 0x14ec7470
2016-03-29 23:45:06.608 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:5
2016-03-29 23:45:06.608 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 152 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:45:06.609 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:45:06.609 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
,2016-03-29 23:45:06.610 ThaliTest[1835:4693808] multipeer manager: stop client timer
2016-03-29 23:45:06.623 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:6
2016-03-29 23:45:06.623 ThaliTest[1835:4693808] multipeer manager,: start client restart timer: 0x14ec7470
2016-03-29 23:45:06.623 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:6
,2016-03-29 23:45:06.623 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening: success
ok 153 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-29 23:45:08.567 ThaliTest[1835:4693665] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:6
,2016-03-29 23:45:09.351 ThaliTest[1835:4693665] client: lost peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:45:09.351 ThaliTest[1835:4693665] client session: onPeerLost: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
,2016-03-29 23:45:26.624 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:45:32.672 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:45:32.673 ThaliTest[1835:469380,8] jxcore: stopListeningForAdvertisements: success
ok 154 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:45:32.675 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:32.675 ThaliTest[1835:469380,8] THEMultipeerManager stopping peer
2016-03-29 23:45:32.675 ThaliTest[1835:4693808] multipeer manager: stop client timer
2016-03-29 23:45:32.675 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 155 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-03-29 23:45:51.583 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:51.583 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:45:51.583 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: suc,cess
ok 156 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:45:51.584 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:51.584 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:45,:51.584 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 157 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-29 23:45:59.539 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:45:59.541 ThaliTest[1835:46938,08] jxcore: stopListeningForAdvertisements: success
ok 158 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:45:59.542 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:59.542 ThaliTest[1835:46938,08] THEMultipeerManager stopping peer
2016-03-29 23:45:59.542 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-03-29 23:46:00.039 ThaliTest[1835:4693808] jxcore: connect foo
2016-03-29 23:46:00.039 ThaliTest[1835:4693808] jxcore: connect: fail: Start browsing first
,not ok 160 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
,  ...
# teardown
,2016-03-29 23:46:00.223 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:46:00.224 ThaliTest[1835:46938,08] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:46:00.225 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:46:00.225 ThaliTest[1835:46938,08] THEMultipeerManager stopping peer
2016-03-29 23:46:00.225 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-03-29 23:46:00.551 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:46:00.552 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:00.552 ThaliTest[1835:4693808] multipeer manager: start client restart timer: 0x14ec7470
2016-03-29 23:46:00.552 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:7
2016-03-29 23:46:00.553 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 163 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-29 23:46:00.554 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-29 23:46:00.555 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-29 23:46:02.571 ThaliTest[1835:4693665] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:02.571 ThaliTest[1835:4693665] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:7
ok 165 peers must be an array
o,k 166 peers must not be zero-length
ok 167 peer must have peerIdentifier
ok 168 peerIdentifier must be a string
ok 169 peer must have peerAvailable
ok 170 peer must have pleaseConnect
,# teardown
,2016-03-29 23:46:03.440 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:46:03.441 ThaliTest[1835:469380,8] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:46:03.442 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:46:03.443 ThaliTest[1835:469380,8] THEMultipeerManager stopping peer
2016-03-29 23:46:03.443 ThaliTest[1835:4693808] multipeer manager: stop client timer
2016-03-29 23:46:03.443 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-03-29 23:46:05.425 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:46:05.425 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:46:05.426 ThaliTest[1835:4693808] multipeer m,anager: start client restart timer: 0x14ec7470
2016-03-29 23:46:05.426 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:46:05.426 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:46:05.427 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-29 23:46:05.428 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-29 23:46:06.325 ThaliTest[1835:4693665] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83B,C4F:7","pleaseConnect":0}]
2016-03-29 23:46:06.328 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:06.328 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:46:06.328 ThaliTest[1835:4693808] cli,ent session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:07.980 ThaliTest[1835:4693665] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8","pleaseConnect":0}]
,2016-03-29 23:46:08.071 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:46:08.072 ThaliTest[1835:4693665] server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57,335E3B6:8 != E4612A32-7792-490E-A387-1EC57335E3B6:7)
,2016-03-29 23:46:08.097 ThaliTest[1835:4695330] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:08.098 ThaliTest[1835:4695330] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:08.0,98 ThaliTest[1835:4695330] client session: disconnect
2016-03-29 23:46:08.098 ThaliTest[1835:4695330] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:08.099 ThaliTest[1835:4695330] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:08.099 ThaliTest[1835:4695330] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:46:11.110 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:11.111 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:46:11.111 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:11.184 ThaliTest[1835:4695330] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:11.186 ThaliTest[1835:4695330] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:11.1,86 ThaliTest[1835:4695330] client session: disconnect
2016-03-29 23:46:11.186 ThaliTest[1835:4695330] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:11.188 ThaliTest[1835:4695330] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:11.188 ThaliTest[1835:4695330] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:46:14.194 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:14.195 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:46:14.195 ThaliTest[1835:4693808] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:14.293 ThaliTest[1835:4695330] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:14.293 ThaliTest[1835:4695330] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:14.2,94 ThaliTest[1835:4695330] client session: disconnect
2016-03-29 23:46:14.294 ThaliTest[1835:4695330] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:14.295 ThaliTest[1835:4695330] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:14.296 ThaliTest[1835:4695330] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:46:17.308 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:17.308 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:46:17.308 ThaliTest[1835:4693808] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:17.446 ThaliTest[1835:4695286] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:17.446 ThaliTest[1835:4695286] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:17.4,46 ThaliTest[1835:4695286] client session: disconnect
2016-03-29 23:46:17.446 ThaliTest[1835:4695286] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:17.447 ThaliTest[1835:4695286] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:17.447 ThaliTest[1835:4695286] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 6
,2016-03-29 23:46:19.532 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:46:19.532 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
2016-03-29 23:46:19.533 ThaliTest[1835:4693665], server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:8 != E4612A32-7792-490E-A387-1EC57335E3B6:7)
,2016-03-29 23:46:20.451 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:20.452 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:46:20.452 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:20.578 ThaliTest[1835:4695285] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:20.579 ThaliTest[1835:4695285] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:20.579 ThaliTest[1835:4695285] client session: disconnect
2016-03-29 23:46:20.579 ThaliTest[1835:4695285] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:20.580 ThaliTest[1835:4695285] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:20.581 ThaliTest[1835:4695285] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:46:23.589 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:23.590 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:46:23.590 ThaliTest[1835:4693808] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:23.698 ThaliTest[1835:4695286] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:23.700 ThaliTest[1835:4695286] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:23.7,00 ThaliTest[1835:4695286] client session: disconnect
2016-03-29 23:46:23.700 ThaliTest[1835:4695286] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:23.702 ThaliTest[1835:4695286] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:23.702 ThaliTest[1835:4695286] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:46:25.427 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:46:25.451 ThaliTest[1835:4693665] client: found updated peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:25.452 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8","pleaseConnect":0}]
,2016-03-29 23:46:26.717 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:26.717 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:46:26.717 ThaliTest[1835:4693808] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:26.844 ThaliTest[1835:4695286] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:26.846 ThaliTest[1835:4695286] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:26.8,46 ThaliTest[1835:4695286] client session: disconnect
2016-03-29 23:46:26.846 ThaliTest[1835:4695286] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:26.847 ThaliTest[1835:4695286] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:26.847 ThaliTest[1835:4695286] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:46:29.852 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:29.853 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:46:29.853 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:30.001 ThaliTest[1835:4695330] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:30.001 ThaliTest[1835:4695330] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:30.003 ThaliTest[1835:4695330] client session: disconnect
,2016-03-29 23:46:30.003 ThaliTest[1835:4695330] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:30.004 ThaliTest[1835:4695330] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:30.004 ThaliTest[1835:4695330] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:46:32.587 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:46:32.588 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
2016-03-29 23:46:32.588 ThaliTest[1835:4693665], server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:8 != E4612A32-7792-490E-A387-1EC57335E3B6:7)
,2016-03-29 23:46:33.013 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:33.014 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:46:33.014 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:33.058 ThaliTest[1835:4695330] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:33.059 ThaliTest[1835:4695330] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:33.0,60 ThaliTest[1835:4695330] client session: disconnect
2016-03-29 23:46:33.060 ThaliTest[1835:4695330] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:33.060 ThaliTest[1835:4695330] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:33.061 ThaliTest[1835:4695330] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:46:36.068 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:36.069 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:46:36.069 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:36.307 ThaliTest[1835:4695331] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:36.309 ThaliTest[1835:4695331] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:36.3,09 ThaliTest[1835:4695331] client session: disconnect
2016-03-29 23:46:36.309 ThaliTest[1835:4695331] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:36.309 ThaliTest[1835:4695331] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:36.310 ThaliTest[1835:4695331] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
not ok 175 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-03-29 23:46:45.427 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:46:45.449 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:45.456 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
,2016-03-29 23:47:05.427 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:47:05.454 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:05.455 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
,2016-03-29 23:47:14.766 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:47:14.767 ThaliTest[1835:469380,8] jxcore: stopListeningForAdvertisements: success
ok 176 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:47:14.768 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:47:14.768 ThaliTest[1835:469380,8] THEMultipeerManager stopping peer
2016-03-29 23:47:14.768 ThaliTest[1835:4693808] multipeer manager: stop client timer
2016-03-29 23:47:14.768 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 177 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 43. Can shift large amounts of data
,2016-03-29 23:47:15.286 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:47:15.286 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:9
,2016-03-29 23:47:15.289 ThaliTest[1835:4693808] multipeer manager: start client restart timer: 0x14ec7470
2016-03-29 23:47:15.289 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:9
2016-03-29 23:47:15.289 ,ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening: success
ok 178 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:47:15.290 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeW,rapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 23:47:15.292 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
ok 179 Can call startListeningForAdvertisements without error
,2016-03-29 23:47:16.979 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:47:16.979 ThaliTest[1835:4693665] server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:9 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:47:17.397 ThaliTest[1835:4693665] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:17.397 ThaliTest[1835:4693665] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
2016-03-29 23:47:17.398 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:17.399 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:47:17.403 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:18.327 ThaliTest[1835:4695513] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:18.329 ThaliTest[1835:4695513] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:18.3,29 ThaliTest[1835:4695513] client session: disconnect
2016-03-29 23:47:18.329 ThaliTest[1835:4695513] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:18.330 ThaliTest[1835:4695513] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:18.330 ThaliTest[1835:4695513] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:47:21.341 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:21.342 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:47:21.342 ThaliTest[1835:4693808] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:21.446 ThaliTest[1835:4695512] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:21.447 ThaliTest[1835:4695512] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:21.4,48 ThaliTest[1835:4695512] client session: disconnect
2016-03-29 23:47:21.449 ThaliTest[1835:4695512] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:21.449 ThaliTest[1835:4695512] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:21.449 ThaliTest[1835:4695512] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:47:24.456 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:24.457 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:47:24.457 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:24.540 ThaliTest[1835:4695512] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:24.540 ThaliTest[1835:4695512] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:24.5,40 ThaliTest[1835:4695512] client session: disconnect
2016-03-29 23:47:24.541 ThaliTest[1835:4695512] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:24.543 ThaliTest[1835:4695512] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:24.543 ThaliTest[1835:4695512] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:47:27.548 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:27.549 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:47:27.549 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:27.629 ThaliTest[1835:4695538] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:27.629 ThaliTest[1835:4695538] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:27.629 ThaliTest[1835:4695538] client session: disconnect
2016-03-29 23:47:27.630 ThaliTest[1835:4695538] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:27.631 ThaliTest[1835:4695538] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:27.631 ThaliTest[1835:4695538] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:47:29.721 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:47:29.721 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
2016-03-29 23:47:29.721 ThaliTest[1835:4693665], server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:9 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:47:30.638 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:30.638 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:47:30.638 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:30.699 ThaliTest[1835:4695529] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:30.699 ThaliTest[1835:4695529] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:30.7,00 ThaliTest[1835:4695529] client session: disconnect
2016-03-29 23:47:30.700 ThaliTest[1835:4695529] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:30.703 ThaliTest[1835:4695529] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:30.703 ThaliTest[1835:4695529] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:47:33.713 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:33.713 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:47:33.713 ThaliTest[1835:4693808] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:33.938 ThaliTest[1835:4695512] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:33.940 ThaliTest[1835:4695512] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:33.9,40 ThaliTest[1835:4695512] client session: disconnect
2016-03-29 23:47:33.940 ThaliTest[1835:4695512] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:33.942 ThaliTest[1835:4695512] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:33.942 ThaliTest[1835:4695512] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:47:35.290 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:47:35.316 ThaliTest[1835:4693665] client: found updated peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:35.318 ThaliTest[1835:4693665] client: found updated peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
,2016-03-29 23:47:36.946 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:36.947 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:47:36.947 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:37.101 ThaliTest[1835:4695538] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:37.102 ThaliTest[1835:4695538] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:37.1,02 ThaliTest[1835:4695538] client session: disconnect
2016-03-29 23:47:37.105 ThaliTest[1835:4695538] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:37.106 ThaliTest[1835:4695538] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:37.106 ThaliTest[1835:4695538] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:47:40.111 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:40.111 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:47:40.111 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:40.259 ThaliTest[1835:4695538] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:40.259 ThaliTest[1835:4695538] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:40.2,60 ThaliTest[1835:4695538] client session: disconnect
2016-03-29 23:47:40.260 ThaliTest[1835:4695538] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:40.261 ThaliTest[1835:4695538] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:40.261 ThaliTest[1835:4695538] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:47:42.353 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:47:42.353 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
2016-03-29 23:47:42.354 ThaliTest[1835:4693665], server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:9 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:47:43.275 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:43.275 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:47:43.276 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:43.401 ThaliTest[1835:4695538] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:43.402 ThaliTest[1835:4695538] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:43.402 ThaliTest[1835:4695538] client session: disconnect
2016-03-29 23:47:43.402 ThaliTest[1835:4695538] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:43.403 ThaliTest[1835:4695538] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
,2016-03-29 23:47:43.404 ThaliTest[1835:4695538] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:47:46.409 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:46.410 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:47:46.410 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:46.555 ThaliTest[1835:4695513] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:46.555 ThaliTest[1835:4695513] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:46.5,55 ThaliTest[1835:4695513] client session: disconnect
2016-03-29 23:47:46.555 ThaliTest[1835:4695513] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:46.556 ThaliTest[1835:4695513] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
,2016-03-29 23:47:46.556 ThaliTest[1835:4695513] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 180 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-29 23:47:55.290 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:47:55.313 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:55.319 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
,2016-03-29 23:48:15.290 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:48:15.314 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:15.314 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
,2016-03-29 23:48:23.378 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:48:23.380 ThaliTest[1835:469380,8] jxcore: stopListeningForAdvertisements: success
ok 181 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:48:23.381 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:48:23.381 ThaliTest[1835:469380,8] THEMultipeerManager stopping peer
2016-03-29 23:48:23.381 ThaliTest[1835:4693808] multipeer manager: stop client timer
2016-03-29 23:48:23.381 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 182 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 44. #startUpdateAdvertisingAndListening - killing remote peers connection kills the local connection
,2016-03-29 23:48:24.975 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
,2016-03-29 23:48:24.975 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:48:24.977 ThaliTest[1835:4693808] multipeer manager: start client restart timer: 0x14ec7470
,2016-03-29 23:48:24.989 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:48:24.992 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening: success
,ok 183 Can call startUpdateAdvertisingAndListening without error
,2016-03-29 23:48:24.995 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-29 23:48:24.997 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
,ok 184 Can call startListeningForAdvertisements without error
,2016-03-29 23:48:26.576 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:48:26.576 ThaliTest[1835:4693665] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57,335E3B6:10 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:48:27.463 ThaliTest[1835:4693665] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:27.464 ThaliTest[1835:4693665] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:10
INFO testThaliMobileNative: Rec,eived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9","pleaseConnect":0}]
2016-03-29 23:48:27.465 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 ,23:48:27.466 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:48:27.466 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E75333B-5CA8-4BAB-BD6C-23036DBD2655:10","pleaseConnect":0}]
,2016-03-29 23:48:27.637 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:48:27.637 ThaliTest[1835:4693665] server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:10 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:48:28.021 ThaliTest[1835:4695752] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:28.022 ThaliTest[1835:4695752] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:28.0,22 ThaliTest[1835:4695752] client session: disconnect
2016-03-29 23:48:28.022 ThaliTest[1835:4695752] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:48:28.025 ThaliTest[1835:4695752] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:28.026 ThaliTest[1835:4695752] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:48:31.036 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:31.037 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:48:31.037 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:48:31.580 ThaliTest[1835:4695758] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:31.582 ThaliTest[1835:4695758] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:31.582 ThaliTest[1835:4695758] client session: disconnect
2016-03-29 23:48:31.582 ThaliTest[1835:4695758] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:31.583 ThaliTest[1835:4695758] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:31.583 ThaliTest[1835:4695758] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:48:34.592 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:34.592 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:48:34.592 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:48:34.768 ThaliTest[1835:4695820] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:34.769 ThaliTest[1835:4695820] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:34.7,69 ThaliTest[1835:4695820] client session: disconnect
2016-03-29 23:48:34.770 ThaliTest[1835:4695820] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:34.771 ThaliTest[1835:4695820] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:34.771 ThaliTest[1835:4695820] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-03-29 23:48:37.774 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:37.775 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:48:37.775 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:48:38.379 ThaliTest[1835:4695852] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:38.379 ThaliTest[1835:4695852] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:38.3,79 ThaliTest[1835:4695852] client session: disconnect
2016-03-29 23:48:38.379 ThaliTest[1835:4695852] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:48:38.381 ThaliTest[1835:4695852] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:38.382 ThaliTest[1835:4695852] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:48:39.538 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:48:39.538 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:48:39.538 ThaliTest[1835:4693665], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:10 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:48:39.806 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:48:39.806 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
2016-03-29 23:48:39.806 ThaliTest[1835:4693665], server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:10 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:48:41.390 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:41.391 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:48:41.391 ThaliTest[1835:4693808] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:48:41.589 ThaliTest[1835:4695852] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:41.589 ThaliTest[1835:4695852] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:41.589 ThaliTest[1835:4695852] client session: disconnect
2016-03-29 23:48:41.589 ThaliTest[1835:4695852] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:48:41.591 ThaliTest[1835:4695852] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:41.591 ThaliTest[1835:4695852] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:48:44.599 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:44.599 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:48:44.599 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:48:44.728 ThaliTest[1835:4695852] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:44.728 ThaliTest[1835:4695852] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:44.728 ThaliTest[1835:4695852] client session: disconnect
,2016-03-29 23:48:44.729 ThaliTest[1835:4695852] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:44.731 ThaliTest[1835:4695852] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 2,3:48:44.731 ThaliTest[1835:4695852] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:48:44.990 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:48:45.008 ThaliTest[1835:4693665] client: found updated peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10","pleaseConnect":0}]
,2016-03-29 23:48:45.020 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:10
,2016-03-29 23:48:47.743 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:47.744 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:48:47.744 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:48:47.872 ThaliTest[1835:4695822] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:48:47.874 ThaliTest[1835:4695822] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:47.,874 ThaliTest[1835:4695822] client session: disconnect
2016-03-29 23:48:47.874 ThaliTest[1835:4695822] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:48:47.875 ThaliTest[1835:4695822] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:47.875 ThaliTest[1835:4695822] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:48:50.878 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:50.879 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:48:50.879 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:48:51.023 ThaliTest[1835:4695852] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:48:51.024 ThaliTest[1835:4695852] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:51.,024 ThaliTest[1835:4695852] client session: disconnect
2016-03-29 23:48:51.024 ThaliTest[1835:4695852] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:48:51.025 ThaliTest[1835:4695852] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:51.026 ThaliTest[1835:4695852] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:48:52.146 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:48:52.146 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:48:52.147 ThaliTest[1835:4693665], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:10 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:48:52.206 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:48:52.207 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
,2016-03-29 23:48:52.207 ThaliTest[1835:4693665] server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:10 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:48:54.038 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:54.039 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:48:54.039 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:48:54.169 ThaliTest[1835:4695851] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:48:54.169 ThaliTest[1835:4695851] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:54.,169 ThaliTest[1835:4695851] client session: disconnect
2016-03-29 23:48:54.170 ThaliTest[1835:4695851] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:48:54.172 ThaliTest[1835:4695851] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:54.172 ThaliTest[1835:4695851] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:48:57.174 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:48:57.174 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:48:57.175 ThaliTest[1835:4693808] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:48:57.309 ThaliTest[1835:4695851] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:48:57.309 ThaliTest[1835:4695851] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:57.,309 ThaliTest[1835:4695851] client session: disconnect
2016-03-29 23:48:57.309 ThaliTest[1835:4695851] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:48:57.310 ThaliTest[1835:4695851] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:48:57.310 ThaliTest[1835:4695851] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
not ok 185 Connect failed
  ---
    operator: fail
  ...
,# teardown
,2016-03-29 23:49:04.990 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:49:05.014 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:10
,2016-03-29 23:49:05.018 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:49:24.990 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:49:25.009 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:10
2016-03-29 23:49:25.009 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:49:33.849 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:49:33.850 ThaliTest[1835:469380,8] jxcore: stopListeningForAdvertisements: success
ok 186 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:49:33.851 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:49:33.852 ThaliTest[1835:469380,8] THEMultipeerManager stopping peer
2016-03-29 23:49:33.852 ThaliTest[1835:4693808] multipeer manager: stop client timer
2016-03-29 23:49:33.852 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 187 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 45. #startUpdateAdvertisingAndListening - killing the local connection kills the connection to the remote peer
,2016-03-29 23:49:38.518 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:49:38.518 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:11
2016-03-29 23:49:38.518 ThaliTest[1835:4693808] multipeer manager: start client restart timer: 0x14ec7470
2016-03-29 23:49:38.518 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:11
2016-03-29 23:49:38.519 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 188 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:49:38.520 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertis,ingActive":true,"discoveryActive":true}
2016-03-29 23:49:38.521 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
ok 189 Can call startListeningForAdvertisements without error
,2016-03-29 23:49:38.535 ThaliTest[1835:4693665] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83,BC4F:10","pleaseConnect":0}]
2016-03-29 23:49:38.542 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:38.543 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:49:38.543 ThaliTest[1835:4693808] ,client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:49:40.762 ThaliTest[1835:4693665] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:10
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E75333B-5CA8-4BAB-BD6C-23036DBD2655:10","pleaseConnect":0}]
,2016-03-29 23:49:41.285 ThaliTest[1835:4695851] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:41.285 ThaliTest[1835:4695851] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:49:41.,285 ThaliTest[1835:4695851] client session: disconnect
2016-03-29 23:49:41.285 ThaliTest[1835:4695851] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:41.286 ThaliTest[1835:4695851] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:49:41.286 ThaliTest[1835:4695851] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:49:41.812 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:49:41.812 ThaliTest[1835:4693665] server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:11 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:49:42.319 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:49:42.319 ThaliTest[1835:4693665] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57,335E3B6:11 != E4612A32-7792-490E-A387-1EC57335E3B6:10)
,2016-03-29 23:49:44.296 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:44.297 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:49:44.297 ThaliTest[1835:4693808] client session: stateChange:0-,>1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:49:44.963 ThaliTest[1835:4695851] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:49:44.964 ThaliTest[1835:4695851] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
,2016-03-29 23:49:44.965 ThaliTest[1835:4695851] client session: disconnect
2016-03-29 23:49:44.966 ThaliTest[1835:4695851] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:44.967 ThaliTest[1835:4695851] client ses,sion: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:49:44.967 ThaliTest[1835:4695851] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:49:47.973 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:47.973 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:49:47.973 ThaliTest[1835:4693808] client session: stateChange:0-,>1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:49:50.989 ThaliTest[1835:4696006] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:50.990 ThaliTest[1835:4696006] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:49:50.990 ThaliTest[1835:4696006] client session: disconnect
2016-03-29 23:49:50.990 ThaliTest[1835:4696006] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:50.990 ThaliTest[1835:4696006] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:49:50.990 ThaliTest[1835:4696006] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:49:53.868 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:49:53.868 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
2016-03-29 23:49:53.868 ThaliTest[1835:4693665], server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:11 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:49:53.997 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:49:53.997 ThaliTest[1835:4693808] client session: connect
,2016-03-29 23:49:53.998 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:49:54.215 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:49:54.215 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:49:54.215 ThaliTest[1835:4693665], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:11 != E4612A32-7792-490E-A387-1EC57335E3B6:10)
,2016-03-29 23:49:54.379 ThaliTest[1835:4696028] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:54.380 ThaliTest[1835:4696028] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:49:54.,380 ThaliTest[1835:4696028] client session: disconnect
2016-03-29 23:49:54.382 ThaliTest[1835:4696028] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:54.382 ThaliTest[1835:4696028] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:49:54.382 ThaliTest[1835:4696028] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:49:57.397 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:57.397 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:49:57.397 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
,2016-03-29 23:49:57.596 ThaliTest[1835:4695851] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:57.596 ThaliTest[1835:4695851] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:49:57.,596 ThaliTest[1835:4695851] client session: disconnect
2016-03-29 23:49:57.596 ThaliTest[1835:4695851] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:57.597 ThaliTest[1835:4695851] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:49:57.597 ThaliTest[1835:4695851] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:49:58.519 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:49:58.545 ThaliTest[1835:4693665] client: found updated peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E75333B-5CA8-4BAB-BD6C-2303,6DBD2655:11","pleaseConnect":0}]
2016-03-29 23:49:58.548 ThaliTest[1835:4693665] client: found updated peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentif,ier":"7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11","pleaseConnect":0}]
,2016-03-29 23:50:00.612 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:50:00.613 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:50:00.613 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:50:00.793 ThaliTest[1835:4696007] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:00.793 ThaliTest[1835:4696007] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:50:00.,793 ThaliTest[1835:4696007] client session: disconnect
2016-03-29 23:50:00.793 ThaliTest[1835:4696007] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:00.794 ThaliTest[1835:4696007] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:50:00.794 ThaliTest[1835:4696007] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:50:03.800 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:50:03.800 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:50:03.800 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:50:03.860 ThaliTest[1835:4696028] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:03.861 ThaliTest[1835:4696028] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:50:03.,862 ThaliTest[1835:4696028] client session: disconnect
2016-03-29 23:50:03.862 ThaliTest[1835:4696028] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:03.864 ThaliTest[1835:4696028] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:50:03.864 ThaliTest[1835:4696028] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:50:06.502 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:50:06.503 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:50:06.503 ThaliTest[1835:4693665], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:11 != E4612A32-7792-490E-A387-1EC57335E3B6:10)
,2016-03-29 23:50:06.872 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:50:06.872 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:50:06.872 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:50:07.026 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:50:07.026 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
2016-03-29 23:50:07.028 ThaliTest[1835:4693665] server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:11 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:50:07.035 ThaliTest[1835:4696028] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:07.036 ThaliTest[1835:4696028] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:50:07.,036 ThaliTest[1835:4696028] client session: disconnect
2016-03-29 23:50:07.038 ThaliTest[1835:4696028] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:07.038 ThaliTest[1835:4696028] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:50:07.038 ThaliTest[1835:4696028] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:50:10.042 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:50:10.042 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:50:10.042 ThaliTest[1835:4693808] client session: stateChange:0-,>1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:50:10.125 ThaliTest[1835:4696006] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:10.125 ThaliTest[1835:4696006] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:50:10.,126 ThaliTest[1835:4696006] client session: disconnect
2016-03-29 23:50:10.126 ThaliTest[1835:4696006] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:10.127 ThaliTest[1835:4696006] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:50:10.127 ThaliTest[1835:4696006] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connec,t retry - retries left: 1
,2016-03-29 23:50:13.136 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:50:13.137 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:50:13.137 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:50:13.327 ThaliTest[1835:4696006] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:13.328 ThaliTest[1835:4696006] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:50:13.,329 ThaliTest[1835:4696006] client session: disconnect
2016-03-29 23:50:13.329 ThaliTest[1835:4696006] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:13.329 ThaliTest[1835:4696006] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:50:13.330 ThaliTest[1835:4696006] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 190 Connect failed
  ---
    operator: fail
  ...
,# teardown
,2016-03-29 23:50:18.520 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:50:18.537 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
2016-03-29 23:50:18.539 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:50:19.675 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:50:19.676 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:50:19.676 ThaliTest[1835:4693665] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:11 != E4612A32-7792-490E-A387-1EC57335E3B6:10)
,2016-03-29 23:50:20.078 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:50:20.079 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
2016-03-29 23:50:20.079 ThaliTest[1835:4693665] server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:11 != E4612A32-7792-490E-A387-1EC57335E3B6:8)
,2016-03-29 23:50:32.710 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:50:32.711 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:50:32.711 ThaliTest[1835:4693665], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:11 != E4612A32-7792-490E-A387-1EC57335E3B6:10)
,2016-03-29 23:50:38.520 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:50:38.541 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:38.541 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
,2016-03-29 23:50:45.717 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:50:45.718 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:50:45.718 ThaliTest[1835:4693665], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:11 != E4612A32-7792-490E-A387-1EC57335E3B6:10)
,2016-03-29 23:50:58.519 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:50:58.540 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
,2016-03-29 23:50:58.542 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:51:18.520 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:51:18.576 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-29 23:51:18.577 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
ok 191 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:51:18.579 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:51:18.579 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:51:18.580 ThaliTest[1835:4693808] multipeer manager: stop client timer
20,16-03-29 23:51:18.580 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 192 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 46. We do not emit peerAvailabilityChanged events until one of the start methods is called
,2016-03-29 23:51:22.616 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:51:22.616 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:12
2016-03-29 23:51:22.616 ThaliTest[1835:4693808] multipeer manager: start client restart timer: 0x14ec7470
2016-03-29 23:51:22.617 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:12
2016-03-29 23:51:22.617 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 193 Ready to advertise
2016-03-29 23:51:22.618 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 23:51:22.620 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
,ok 194 Ready to listen
,2016-03-29 23:51:22.635 ThaliTest[1835:4693665] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:22.637 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
2016-03-29 23:51:22.637 ThaliTest[1835:4693808] THEMultipe,erManager stopping peer
2016-03-29 23:51:22.638 ThaliTest[1835:4693665] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
,2016-03-29 23:51:22.638 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
ok 195 stop ads worked
,2016-03-29 23:51:22.641 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
2016-03-29 23:51:22.642 ThaliTest[1835:4693808] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:51:22.646 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
ok 196 test stop worked
,# teardown
,2016-03-29 23:51:26.088 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 23:51:26.090 ThaliTest[1835:4693808] jxcore: stopListeningForAdvertisements: success
,ok 197 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:51:26.091 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening
,2016-03-29 23:51:26.091 ThaliTest[1835:4693808] THEMultipeerManager stopping peer
2016-03-29 23:51:26.092 ThaliTest[1835:4693808] jxcore: stopAdvertisingAndListening: success
,ok 198 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 47. Test updating advertising and parallel data transfer
,2016-03-29 23:51:28.413 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:51:28.414 ThaliTest[1835:4693808] server: starting E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:28.414 ThaliTest[1835:4693808] multipeer ,manager: start client restart timer: 0x14ec7470
2016-03-29 23:51:28.414 ThaliTest[1835:4693808] THEMultipeerManager initialized peer E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:28.414 ThaliTest[1835:4693808] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 199 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:51:28.416 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertis,ingActive":true,"discoveryActive":true}
2016-03-29 23:51:28.417 ThaliTest[1835:4693808] jxcore: startListeningForAdvertisements: success
ok 200 Can call startListeningForAdvertisements without error
,2016-03-29 23:51:29.331 ThaliTest[1835:4693665] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:29.333 ThaliTest[1835:4693665] client: found new peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:29.333 ThaliT,est[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:29.334 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:51:29.334 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
,2016-03-29 23:51:29.346 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:29.347 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:51:29.347 ThaliTest[1835:4693808] client session: stateChange:0-,>1 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:30.774 ThaliTest[1835:4696216] client session: not connected 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:30.775 ThaliTest[1835:4696216] client session: onLinkFailure: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:30.777 ThaliTest[1835:4696216] client session: disconnect
2016-03-29 23:51:30.777 ThaliTest[1835:4696216] client session:, stateChange:1->0 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:30.777 ThaliTest[1835:4696216] client session: fireConnectCallback: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:30.778 ThaliTest[1835:4696216] jxcore: connect: fail: Pee,r disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:51:30.795 ThaliTest[1835:4696229] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:30.796 ThaliTest[1835:4696229] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:30.796 ThaliTest[1835:4696229] client session: disconnect
2016-03-29 23:51:30.796 ThaliTest[1835:4696229] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:30.798 ThaliTest[1835:4696229] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:30.798 ThaliTest[1835:4696229] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:51:31.088 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:51:31.088 ThaliTest[1835:4693665] server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:13 != E4612A32-7792-490E-A387-1EC57335E3B6:10)
,2016-03-29 23:51:31.810 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:51:31.811 ThaliTest[1835:4693665] server: rejecting invitation for lexical ordering 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:31.812 ThaliTest[1835:4,693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:51:31.813 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:51:31.815 ThaliTest[1835:4693808] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
,2016-03-29 23:51:33.782 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:33.782 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:51:33.782 ThaliTest[1835:4693808] client session: stateChange:0->1 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:33.820 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
,2016-03-29 23:51:33.823 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
,2016-03-29 23:51:33.825 ThaliTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:51:34.039 ThaliTest[1835:4696151] client session: not connected 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:34.040 ThaliTest[1835:4696151] client session: onLinkFailure: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:34.,040 ThaliTest[1835:4696151] client session: disconnect
2016-03-29 23:51:34.040 ThaliTest[1835:4696151] client session: stateChange:1->0 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:34.041 ThaliTest[1835:4696151] client session: fireConnectCal,lback: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:34.041 ThaliTest[1835:4696151] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connec,t retry - retries left: 8
,2016-03-29 23:51:34.513 ThaliTest[1835:4696229] client session: p2p link connected
,2016-03-29 23:51:34.648 ThaliTest[1835:4696216] client session: stateChange:1->2 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:34.648 ThaliTest[1835:4696216] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:34.649 ThaliTest[1835:4696216] jxcore: connect: success
,2016-03-29 23:51:34.666 ThaliTest[1835:4693665] client: relay established
2016-03-29 23:51:34.666 ThaliTest[1835:4693665] client: new accepted socket: 0x1b3f6ce0
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,2016-03-29 23:51:36.845 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:36.845 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:36.846 ThaliTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:51:37.047 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:37.047 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:51:37.047 ThaliTest[1835:4693808] client session: stateChange:0->1 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:37.153 ThaliTest[1835:4696209] client session: not connected 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:37.153 ThaliTest[1835:4696209] client session: onLinkFailure: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:37.154 ThaliTest[1835:4696209] client session: disconnect
2016-03-29 23:51:37.154 ThaliTest[1835:4696209] client session: stateChange:1->0 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:37.156 ThaliTest[1835:4696209] client session: fireConnectCallback: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:37.156 ThaliTest[1835:4696209] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:51:39.855 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:39.856 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:39.856 Tha,liTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:51:40.165 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:40.166 ThaliTest[1835:4693808] client session: connect
,2016-03-29 23:51:40.167 ThaliTest[1835:4693808] client session: stateChange:0->1 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:40.300 ThaliTest[1835:4696229] client session: not connected 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:40.300 ThaliTest[1835:4696229] client session: onLinkFailure: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:40.301 ThaliTest[1835:4696229] client session: disconnect
,2016-03-29 23:51:40.301 ThaliTest[1835:4696229] client session: stateChange:1->0 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:40.303 ThaliTest[1835:4696229] client session: fireConnectCallback: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:40.304 ThaliTest[1835:4696229] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:51:42.862 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:42.862 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:42.862 Tha,liTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:51:43.314 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:43.315 ThaliTest[1835:4693808] client session: connect
,2016-03-29 23:51:43.315 ThaliTest[1835:4693808] client session: stateChange:0->1 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:43.487 ThaliTest[1835:4696151] client session: not connected 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:43.490 ThaliTest[1835:4696151] client session: onLinkFailure: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:43.490 ThaliTest[1835:4696151] client session: disconnect
2016-03-29 23:51:43.490 ThaliTest[1835:4696151] client session:, stateChange:1->0 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:43.491 ThaliTest[1835:4696151] client session: fireConnectCallback: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:51:43.491 ThaliTest[1835:4696151] jxcore: connect: fail: Pee,r disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:51:43.523 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:51:43.523 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:51:43.523 ThaliTest[1835:4693665], server: rejecting invitation from 7E75333B-5CA8-4BAB-BD6C-23036DBD2655 due to previous generation (E4612A32-7792-490E-A387-1EC57335E3B6:13 != E4612A32-7792-490E-A387-1EC57335E3B6:10)
,2016-03-29 23:51:45.868 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:45.869 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:45.869 Tha,liTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:51:46.506 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:46.507 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:51:46.507 ThaliTest[1835:4693808] client session: stateChange:0-,>1 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:46.586 ThaliTest[1835:4696209] client session: not connected 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:46.588 ThaliTest[1835:4696209] client session: onLinkFailure: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
,2016-03-29 23:51:46.588 ThaliTest[1835:4696209] client session: disconnect
,2016-03-29 23:51:46.589 ThaliTest[1835:4696209] client session: stateChange:1->0 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:46.591 ThaliTest[1835:4696209] client session: fireConnectCallback: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
,2016-03-29 23:51:46.591 ThaliTest[1835:4696209] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:51:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:51:48.437 ThaliTest[1835:4693665] client: found updated peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:51:48.438 ThaliTest[1835:4693665] client: found updated peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:51:48.439 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:51:48.440 ThaliTest[1835:4693808] client session: connect
2016-03-29 23:51:48.445 ThaliTest[1835:4693808] client session: stateChange:0->1 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:51:48.879 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:48.879 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:48.879 Tha,liTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:51:48.949 ThaliTest[1835:4693665] multipeer session: reset timer
2016-03-29 23:51:48.949 ThaliTest[1835:4693665] server: disconnecting to refresh session (7E75333B-5CA8-4BAB-BD6C-23036DBD2655)
2016-03-29 23:51:48.949 ThaliTest[1835:4693665] server: rejecting invitation for lexical ordering 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
,2016-03-29 23:51:49.603 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:49.603 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:49.604 Tha,liTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:51:51.508 ThaliTest[1835:4696209] client session: p2p link connected
,2016-03-29 23:51:51.535 ThaliTest[1835:4696228] client session: stateChange:1->2 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:51:51.537 ThaliTest[1835:4696228] client session: fireConnectCallback: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
,2016-03-29 23:51:51.538 ThaliTest[1835:4696228] jxcore: connect: success
,2016-03-29 23:51:51.553 ThaliTest[1835:4693665] client: relay established
2016-03-29 23:51:51.554 ThaliTest[1835:4693665] client: new accepted socket: 0x1b30bb50
,2016-03-29 23:51:51.890 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
,2016-03-29 23:51:51.891 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
,2016-03-29 23:51:51.891 ThaliTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,2016-03-29 23:51:52.618 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:52.618 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:52.618 Tha,liTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:51:54.904 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:54.904 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:54.905 Tha,liTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:51:55.632 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:55.633 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:55.633 Tha,liTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:51:57.910 ThaliTest[1835:4693808] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:57.911 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:12
2016-03-29 23:51:57.911 Tha,liTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,DEBUG testThaliMobileNative: Got recoverable client error Already connect(ing/ed)
,2016-03-29 23:51:58.640 ThaliTest[1835:4693808] jxcore: connect 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:58.640 ThaliTest[1835:4693808] client: already connect(ing/ed) to 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:58.640 Tha,liTest[1835:4693808] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
DEBUG testThaliMobileNative: Got recoverable client error Already connect(ing/ed)
,2016-03-29 23:52:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:52:08.437 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:52:08.439 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:52:28.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:52:28.442 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:52:28.442 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:52:39.734 ThaliTest[1835:4693665] client: socket closed
DEBUG testThaliMobileNative: Got recoverable client error Error: We timed out
2016-03-29 23:52:39.735 ThaliTest[1835:4693665] client relay: socket disconnected
2016-03-29 23:52:39.735, ThaliTest[1835:4693665] client relay: 0x1b3f6ce0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-03-29 23:52:39.735 ThaliTest[1835:4,693665] client session: socket closed: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:52:39.735 ThaliTest[1835:4693665] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:52:39.735 ThaliTest[1835:4693665] client session,: disconnect
2016-03-29 23:52:39.736 ThaliTest[1835:4693665] client session: stateChange:2->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
DEBUG testThaliMobileNative: Got to close without error or end!
not ok 201 At least one should fire before we hit close,
  ---
    operator: ok
    expected: true
    actual:   false
  ...
,2016-03-29 23:52:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:52:48.431 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:52:54.740 ThaliTest[1835:4693665] client: socket closed
2016-03-29 23:52:54.741 ThaliTest[1835:4693665] client relay: socket disconnected
2016-03-29 23:52:54.741 ThaliTest[1835:4693665] client relay: 0x1b30bb50 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-03-29 23:52:54.741 ThaliTest[1835:4693665] client session: socket closed: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
DE,BUG testThaliMobileNative: Got recoverable client error Error: We timed out
2016-03-29 23:52:54.741 ThaliTest[1835:4693665] client session: onLinkFailure: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655
2016-03-29 23:52:54.741 ThaliTest[1835:4693665] client session,: disconnect
2016-03-29 23:52:54.742 ThaliTest[1835:4693665] client session: stateChange:2->0 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
DEBUG testThaliMobileNative: Got to close without error or end!
not ok 202 At least one should fire before we hit clos,e
  ---
    operator: ok
    expected: true
    actual:   false
  ...
,2016-03-29 23:53:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:53:08.437 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:53:08.443 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:53:28.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:53:28.440 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:53:28.441 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:53:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:53:48.443 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:53:48.444 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:54:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:54:08.444 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:54:08.446 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:54:28.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:54:28.434 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:54:28.435 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:54:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:54:48.439 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:54:48.440 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:55:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:55:08.437 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:55:08.438 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:55:28.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:55:28.440 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:55:28.441 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:55:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:55:48.441 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:55:48.445 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:56:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:56:08.436 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:56:08.438 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:56:28.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:56:28.433 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:56:28.435 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:56:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:56:48.442 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:56:48.443 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:57:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:57:08.442 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:57:08.443 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:57:28.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:57:28.443 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:57:28.444 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:57:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:57:48.444 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:57:48.445 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:58:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:58:08.433 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:58:08.434 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:58:28.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:58:28.439 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:58:28.441 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:58:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:58:48.443 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:58:48.444 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:59:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:59:08.436 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:59:08.436 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:59:28.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:59:28.442 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:59:28.443 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:59:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-29 23:59:48.438 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:59:48.438 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-30 00:00:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-30 00:00:08.442 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-30 00:00:08.444 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-30 00:00:28.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-30 00:00:28.435 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-30 00:00:28.436 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-30 00:00:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-30 00:00:48.434 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-30 00:00:48.438 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-30 00:01:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-30 00:01:28.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-30 00:01:28.432 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-30 00:01:28.432 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-30 00:01:48.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-30 00:01:48.427 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-30 00:01:48.428 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-30 00:02:08.415 ThaliTest[1835:4693665] multipeer manager: restart client
,2016-03-30 00:02:08.432 ThaliTest[1835:4693665] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-30 00:02:08.433 ThaliTest[1835:4693665] client: found existing peer: 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13

```
