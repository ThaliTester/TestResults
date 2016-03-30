#### Test 646862831c69957_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646862831c69957/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/86FA803A-055F-41EA-B610-339DC0633427/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/86FA803A-055F-41EA-B610-339DC0633427/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/646862831c69957/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646862831c69957/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49425"
,(lldb)     command script import "/tmp/86FA803A-055F-41EA-B610-339DC0633427/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-30 22:17:08.771 ThaliTest[2518:4627380] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/321140D8-1E33-47F0-B4B9-A4F4C5A028C9/Library/Cookies/Cookies.binarycookies
,2016-03-30 22:17:09.023 ThaliTest[2518:4627380] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-30 22:17:09.025 ThaliTest[2518:4627380] Multi-tasking -> Device: YES, App: YES
,2016-03-30 22:17:09.043 ThaliTest[2518:4627380] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-30 22:17:09.847 ThaliTest[2518:4627380] Using UIWebView
2016-03-30 22:17:09.849 ThaliTest[2518:4627380] [CDVTimer][handleopenurl] 0.150025ms
,2016-03-30 22:17:09.854 ThaliTest[2518:4627380] [CDVTimer][intentandnavigationfilter] 4.225016ms
2016-03-30 22:17:09.854 ThaliTest[2518:4627380] [CDVTimer][gesturehandler] 0.144005ms
2016-03-30 22:17:09.854 ThaliTest[2518:4627380] [CDVTimer][TotalPluginStartup] 5.135000ms
,2016-03-30 22:17:13.088 ThaliTest[2518:4627380] Resetting plugins due to page load.
,2016-03-30 22:17:14.564 ThaliTest[2518:4627380] Finished load of: file:///var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/index.html
,2016-03-30 22:17:14.751 ThaliTest[2518:4627380] JXcore Cordova plugin initializing
,2016-03-30 22:17:14.753 ThaliTest[2518:4627536] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-30 22:17:23.046 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:17:23.046 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:17:23.047 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:17:23.050 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E931D79F-766C-4ABA-848A-1533E84C217E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55938
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55940
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
DEBUG createNativeListener: listening 55943
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: listening 55947
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
DEBUG createNativeListener: listening 55952
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
DEBUG createNativeListener: listening 55956
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
DEBUG createNativeListener: listening 55960
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 55964
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 55968
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
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
ok 29 native server should be closed
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
,DEBUG createNativeListener: listening 56020
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
DEBUG createNativeListener: listening 56024
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
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
ok 50 firstPromise result
ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
ok 53 secondPromise result
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
ok 67 second
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
,ok 77 test participant has uuid
ok 78 participant data matches
ok 79 test participant has uuid
ok 80 participant data matches
ok 81 test participant has uuid
ok 82 participant data matches
ok 83 own UUID is found from the participants list
# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 84 specific error should be returned
# teardown
,ok 85 error should be null
ok 86 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 87 specific error should be returned
# teardown
,ok 88 error should be null
ok 89 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56036
2016-03-30 22:19:45.274 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:45.275 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
2016-03-30 22:19:45.276 ThaliTest[2518:4627536] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:45.277 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
,ok 93 error should be null
,# teardown
,2016-03-30 22:19:45.455 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:45.455 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:19:45.455 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:19:45.455 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:45.456 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
,# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56038
,2016-03-30 22:19:45.814 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
,2016-03-30 22:19:45.816 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:19:45.817 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,2016-03-30 22:19:45.861 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-30 22:19:45.862 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
,ok 98 error should be null
,ok 99 error should be null
,# teardown
,2016-03-30 22:19:46.141 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:46.141 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:19:46.141 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:19:46.141 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
2016-03-30 22:19:46.142 ThaliTest[2518:4627536] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:46.142 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 100 error should be null
ok 101 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56040
,2016-03-30 22:19:46.793 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:19:46.793 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:1
2016-03-30 22:19:46.794 ThaliTest[2518:4627536] multipeer m,anager: start client restart timer: 0x165c2260
2016-03-30 22:19:46.794 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:1
2016-03-30 22:19:46.794 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,2016-03-30 22:19:46.810 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
,2016-03-30 22:19:46.811 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
,2016-03-30 22:19:46.815 ThaliTest[2518:4627536] multipeer manager: stop client timer
,2016-03-30 22:19:46.816 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:2
,2016-03-30 22:19:46.820 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
,2016-03-30 22:19:46.822 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:2
,2016-03-30 22:19:46.822 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
ok 105 error should be null
,# teardown
,2016-03-30 22:19:47.779 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:47.779 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:19:47.779 ThaliTest[2518:4627536] multipeer manager: stop client timer
20,16-03-30 22:19:47.780 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:19:47.780 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:47.781 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 106 error should be null
ok 107 error should be null
# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56045
,2016-03-30 22:19:49.324 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:49.325 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:19:49.325 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: suc,cess
ok 108 error should be null
ok 109 error should be null
,2016-03-30 22:19:49.327 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:49.327 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:19:49.327 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
ok 110 error should be null
,ok 111 error should be null
,# teardown
,2016-03-30 22:19:49.761 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:49.761 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:19:49.762 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:19:49.762 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:49.762 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
ok 112 error should be null
ok 113 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56047
ok 114 first call should succeed
ok 115 first call should succeed
ok 116 specific error should be returned
# teardown
,2016-03-30 22:19:50.324 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:50.324 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:19:50.324 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:19:50.324 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:50.325 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
ok 117 error should be null
ok 118 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56049
2016-03-30 22:19:51.249 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
,2016-03-30 22:19:51.249 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:19:51.250 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
,2016-03-30 22:19:51.281 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:19:51.281 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:3
2016-03-30 22:19:51.281 ThaliTest[2518:4627536] THEMultipee,rManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:3
2016-03-30 22:19:51.281 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening: success
ok 119 called only once
ok 120 discovery state matches
ok 121 advertising state matches
# teardown
,2016-03-30 22:19:51.476 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:19:51.476 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:19:51.477 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:19:51.477 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
2016-03-30 22:19:51.477 ThaliTest[2518:4627536] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:19:51.478 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 122 error should be null
ok 123 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 124 should be called once
ok 125 should not have been called more than once
# teardown
,ok 126 error should be null
ok 127 error should be null
# setup
,# 33. can get the network status
,ok 128 network status should have certain non-empty properties
# teardown
,ok 129 error should be null
ok 130 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 131 host address should match
ok 132 port should match
,ok 133 host address should be null
ok 134 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 135 error should be null
ok 136 error should be null
,# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-30 22:20:16.456 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
2016-03-30 22:20:16.456 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:20:16.457 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
2016-03-30 22:20:16.458 ThaliTes,t[2518:4627536] jxcore: stopListeningForAdvertisements
2016-03-30 22:20:16.458 ThaliTest[2518:4627536] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:20:16.459 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
ok 138 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-30 22:20:16.647 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:20:16.648 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
ok 139 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:16.649 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:16.649 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:20:16.649 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-30 22:20:17.111 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
2016-03-30 22:20:17.111 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:20:17.112 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements without error
2016-03-30 22:20:17.113 ThaliTes,t[2518:4627536] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:20:17.113 ThaliTest[2518:4627536] jxcore: startListeningForAdv,ertisements: success
ok 142 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-30 22:20:17.353 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
2016-03-30 22:20:17.353 ThaliTest[2518:4627536] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:20:17.354 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
ok 143 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:17.354 ThaliTest[2518:46275,36] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:17.354 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:20:17.354 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-30 22:20:18.373 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:18.373 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:4
2016-03-30 22:20:18.373 ThaliTest[2518:4627536] multipeer m,anager: start client restart timer: 0x165c2260
2016-03-30 22:20:18.374 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:4
2016-03-30 22:20:18.374 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening: success
ok 145 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:20:18.374 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:18.375 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
,2016-03-30 22:20:18.375 ThaliTest[2518:4627536] multipeer manager: stop client timer
2016-03-30 22:20:18.379 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
ok 146 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-30 22:20:18.558 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:20:18.558 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
ok 147 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:18.559 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:18.559 ThaliTest[2518:462753,6] THEMultipeerManager stopping peer
2016-03-30 22:20:18.559 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-30 22:20:19.030 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:19.031 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:5
2016-03-30 22:20:19.031 ThaliTest[2518:4627536] multipeer m,anager: start client restart timer: 0x165c2260
2016-03-30 22:20:19.031 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:5
2016-03-30 22:20:19.031 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening: success
ok 149 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:20:19.032 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:19.032 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
,2016-03-30 22:20:19.032 ThaliTest[2518:4627536] multipeer manager: stop client timer
2016-03-30 22:20:19.036 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:6
2016-03-30 22:20:19.036 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
2016-03-30 22:20:19.036 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:6
2016-03-30 22:20:19.038 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 150 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-30 22:20:19.204 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-30 22:20:19.205 ThaliTest[2518:462753,6] jxcore: stopListeningForAdvertisements: success
ok 151 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-30 22:20:19.205 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:19.206 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:20:19.206 ThaliTest[2518:4627536] multipeer manager: stop client timer
2016-03-30 22:20:19.206 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-30 22:20:19.599 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:19.599 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:20:19.599 ThaliTest[2518:4627536] multipeer m,anager: start client restart timer: 0x165c2260
2016-03-30 22:20:19.600 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:7
2016-03-30 22:20:19.601 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 153 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-30 22:20:19.602 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-30 22:20:19.602 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error
,2016-03-30 22:20:20.878 ThaliTest[2518:4627380] client: found new peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
ok 155 peers must be an array
ok 156 peers must not be zero-length
ok 157 peer must have peerIdentifier
ok 158 peerIdentifier must be a strin,g
ok 159 peer must have peerAvailable
ok 160 peer must have pleaseConnect
,# teardown
,2016-03-30 22:20:21.012 ThaliTest[2518:4627380] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:7
,2016-03-30 22:20:21.696 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-30 22:20:21.697 ThaliTest[2518:462753,6] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisments in teardown
2016-03-30 22:20:21.697 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:20:21.697 ThaliTest[2518:4627536,] THEMultipeerManager stopping peer
2016-03-30 22:20:21.698 ThaliTest[2518:4627536] multipeer manager: stop client timer
2016-03-30 22:20:21.698 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. Can connect to a remote peer
,2016-03-30 22:20:23.479 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:20:23.479 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:8
2016-03-30 22:20:23.479 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
2016-03-30 22:20:23.479 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:8
,2016-03-30 22:20:23.479 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening: success
ok 163 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:20:23.483 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-30 22:20:23.484 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-30 22:20:23.494 ThaliTest[2518:4627380] client: found new peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7","pleaseConnect":0}]
2016-03-30 22:20:23.496 ThaliTest[2518:4627536] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:23.497 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:20:23.497 ThaliTest[2518:4627536] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:23.508 ThaliTest[2518:4627380] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"10864D2D-6C65-445D-AFFE-A77AB0B7C,823:7","pleaseConnect":0}]
,2016-03-30 22:20:24.781 ThaliTest[2518:4627904] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:24.781 ThaliTest[2518:4627904] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:24.781 ThaliTest[2518:4627904] client session: disconnect
2016-03-30 22:20:24.781 ThaliTest[2518:4627904] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:24.781 ThaliTest[2518:4627904] client session: fireConnectCallb,ack: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:24.782 ThaliTest[2518:4627904] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-30 22:20:25.664 ThaliTest[2518:4627380] multipeer session: reset timer
2016-03-30 22:20:25.664 ThaliTest[2518:4627380] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (A3E18F7B-F512-41AB-86C7-5683F62667F5:8 != A3E18F7B-F512-41AB-86C7-5683F62667F5:7)
,2016-03-30 22:20:27.798 ThaliTest[2518:4627536] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:27.799 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:20:27.799 ThaliTest[2518:4627536] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:28.383 ThaliTest[2518:4627905] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:28.384 ThaliTest[2518:4627905] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:28.384 ThaliTest[2518:4627905] client session: disconnect
2016-03-30 22:20:28.384 ThaliTest[2518:4627905] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:28.385 ThaliTest[2518:4627905] client session: fireConnectCallb,ack: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:28.385 ThaliTest[2518:4627905] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-30 22:20:31.388 ThaliTest[2518:4627536] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:31.389 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:20:31.389 ThaliTest[2518:4627536] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:31.943 ThaliTest[2518:4627904] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:31.945 ThaliTest[2518:4627904] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:31.945 ThaliTest[2518:4627904] client session: disconnect
2016-03-30 22:20:31.945 ThaliTest[2518:4627904] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:31.945 ThaliTest[2518:4627904] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:31.945 ThaliTest[2518:4627904] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-03-30 22:20:34.949 ThaliTest[2518:4627536] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:34.949 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:20:34.949 ThaliTest[2518:4627536] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:35.668 ThaliTest[2518:4627905] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:35.668 ThaliTest[2518:4627905] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:35.6,68 ThaliTest[2518:4627905] client session: disconnect
2016-03-30 22:20:35.669 ThaliTest[2518:4627905] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:35.669 ThaliTest[2518:4627905] client session: fireConnectCallb,ack: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:35.669 ThaliTest[2518:4627905] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-30 22:20:36.192 ThaliTest[2518:4627380] multipeer session: reset timer
2016-03-30 22:20:36.192 ThaliTest[2518:4627380] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:20:36.192 ThaliTest[2518:4627380] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (A3E18F7B-F512-41AB-86C7-5683F62667F5:8 != A3E18F7B-F512-41AB-86C7-5683F62667F5:7)
,2016-03-30 22:20:38.673 ThaliTest[2518:4627536] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:38.674 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:20:38.674 ThaliTest[2518:4627536] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:39.401 ThaliTest[2518:4627908] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:39.401 ThaliTest[2518:4627908] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
,2016-03-30 22:20:39.401 ThaliTest[2518:4627908] client session: disconnect
2016-03-30 22:20:39.402 ThaliTest[2518:4627908] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:39.403 ThaliTest[2518:4627908] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:39.403 ThaliTest[2518:4627908] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-30 22:20:42.405 ThaliTest[2518:4627536] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:42.406 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:20:42.406 ThaliTest[2518:4627536] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:43.092 ThaliTest[2518:4627904] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:43.092 ThaliTest[2518:4627904] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:43.092 ThaliTest[2518:4627904] client session: disconnect
2016-03-30 22:20:43.093 ThaliTest[2518:4627904] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:43.094 ThaliTest[2518:4627904] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:43.094 ThaliTest[2518:4627904] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-30 22:20:43.481 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:20:43.498 ThaliTest[2518:4627380] client: found updated peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:20:43.498 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"10864D2D-6C65-445D-AFFE-A77AB0B7C823:8","pleaseConnect":0}]
,2016-03-30 22:20:46.107 ThaliTest[2518:4627536] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:46.107 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:20:46.108 ThaliTest[2518:4627536] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:47.122 ThaliTest[2518:4627908] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:47.123 ThaliTest[2518:4627908] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:47.1,23 ThaliTest[2518:4627908] client session: disconnect
2016-03-30 22:20:47.123 ThaliTest[2518:4627908] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:47.124 ThaliTest[2518:4627908] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:47.125 ThaliTest[2518:4627908] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-30 22:20:49.350 ThaliTest[2518:4627380] multipeer session: reset timer
2016-03-30 22:20:49.350 ThaliTest[2518:4627380] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:20:49.350 ThaliTest[2518:4627380], server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (A3E18F7B-F512-41AB-86C7-5683F62667F5:8 != A3E18F7B-F512-41AB-86C7-5683F62667F5:7)
,2016-03-30 22:20:50.131 ThaliTest[2518:4627536] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:50.131 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:20:50.131 ThaliTest[2518:4627536] client session: stateChange:0->1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:51.400 ThaliTest[2518:4627998] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:51.401 ThaliTest[2518:4627998] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:51.4,02 ThaliTest[2518:4627998] client session: disconnect
2016-03-30 22:20:51.402 ThaliTest[2518:4627998] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:51.402 ThaliTest[2518:4627998] client session: fireConnectCallb,ack: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:51.402 ThaliTest[2518:4627998] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-30 22:20:54.407 ThaliTest[2518:4627536] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:54.408 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:20:54.408 ThaliTest[2518:4627536] client session: stateChange:0->,1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:55.115 ThaliTest[2518:4627895] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:55.116 ThaliTest[2518:4627895] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:55.1,16 ThaliTest[2518:4627895] client session: disconnect
2016-03-30 22:20:55.116 ThaliTest[2518:4627895] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:55.116 ThaliTest[2518:4627895] client session: fireConnectCallb,ack: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:55.116 ThaliTest[2518:4627895] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 1
,2016-03-30 22:20:58.125 ThaliTest[2518:4627536] jxcore: connect 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:58.126 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:20:58.126 ThaliTest[2518:4627536] client session: stateChange:0->,1 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:58.687 ThaliTest[2518:4627909] client session: not connected 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:20:58.687 ThaliTest[2518:4627909] client session: onLinkFailure: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:58.687 ThaliTest[2518:4627909] client session: disconnect
2016-03-30 22:20:58.687 ThaliTest[2518:4627909] client session: stateChange:1->0 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:20:58.689 ThaliTest[2518:4627909] client session: fireConnectCallback: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C
2016-03-30 22:20:58.690 ThaliTest[2518:4627909] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 165 Connect failed!
,  ---
    operator: fail
,  ...
,# teardown
,2016-03-30 22:21:02.453 ThaliTest[2518:4627380] multipeer session: reset timer
2016-03-30 22:21:02.453 ThaliTest[2518:4627380] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:21:02.453 ThaliTest[2518:4627380] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (A3E18F7B-F512-41AB-86C7-5683F62667F5:8 != A3E18F7B-F512-41AB-86C7-5683F62667F5:7)
,2016-03-30 22:21:03.481 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:21:03.492 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:21:03.492 ThaliTest[2518:4627380] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:21:19.623 ThaliTest[2518:4627380] multipeer session: reset timer
2016-03-30 22:21:19.624 ThaliTest[2518:4627380] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:21:19.624 ThaliTest[2518:4627380] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (A3E18F7B-F512-41AB-86C7-5683F62667F5:8 != A3E18F7B-F512-41AB-86C7-5683F62667F5:7)
,2016-03-30 22:21:23.481 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:21:23.492 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:21:23.494 ThaliTest[2518:4627380] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:21:28.807 ThaliTest[2518:4627380] multipeer session: reset timer
2016-03-30 22:21:28.807 ThaliTest[2518:4627380] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:21:28.807 ThaliTest[2518:4627380] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (A3E18F7B-F512-41AB-86C7-5683F62667F5:8 != A3E18F7B-F512-41AB-86C7-5683F62667F5:7)
,2016-03-30 22:21:41.776 ThaliTest[2518:4627380] multipeer session: reset timer
2016-03-30 22:21:41.777 ThaliTest[2518:4627380] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:21:41.777 ThaliTest[2518:4627380] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (A3E18F7B-F512-41AB-86C7-5683F62667F5:8 != A3E18F7B-F512-41AB-86C7-5683F62667F5:7)
,2016-03-30 22:21:43.481 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:21:43.493 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:21:43.493 ThaliTest[2518:4627380] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:21:54.549 ThaliTest[2518:4627380] multipeer session: reset timer
2016-03-30 22:21:54.549 ThaliTest[2518:4627380] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:21:54.549 ThaliTest[2518:4627380] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (A3E18F7B-F512-41AB-86C7-5683F62667F5:8 != A3E18F7B-F512-41AB-86C7-5683F62667F5:7)
,2016-03-30 22:22:03.481 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:22:03.492 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:22:03.495 ThaliTest[2518:4627380] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:07.386 ThaliTest[2518:4627380] multipeer session: reset timer
2016-03-30 22:22:07.387 ThaliTest[2518:4627380] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:22:07.387 ThaliTest[2518:4627380] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (A3E18F7B-F512-41AB-86C7-5683F62667F5:8 != A3E18F7B-F512-41AB-86C7-5683F62667F5:7)
,2016-03-30 22:22:20.556 ThaliTest[2518:4627380] multipeer session: reset timer
2016-03-30 22:22:20.556 ThaliTest[2518:4627380] server: disconnecting to refresh session (10864D2D-6C65-445D-AFFE-A77AB0B7C823)
2016-03-30 22:22:20.556 ThaliTest[2518:4627380] server: rejecting invitation from 10864D2D-6C65-445D-AFFE-A77AB0B7C823 due to previous generation (A3E18F7B-F512-41AB-86C7-5683F62667F5:8 != A3E18F7B-F512-41AB-86C7-5683F62667F5:7)
,2016-03-30 22:22:23.481 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:22:23.492 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:22:23.492 ThaliTest[2518:4627380] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:32.370 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-30 22:22:32.371 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
ok 166 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-30 22:22:32.372 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:22:32.372 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:22:32.373 ThaliTest[2518:4627536] multipeer manager: stop client timer
2016-03-30 22:22:32.373 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
ok 167 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. Can shift large amounts of data
,2016-03-30 22:22:35.330 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:22:35.330 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:9
2016-03-30 22:22:35.331 ThaliTest[2518:4627536] multipeer m,anager: start client restart timer: 0x165c2260
2016-03-30 22:22:35.331 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:9
2016-03-30 22:22:35.331 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening: success
ok 168 Can call startUpdateAdvertisingAndListening without error
2016-03-30 22:22:35.332 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-30 22:22:35.332 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
ok 169 Can call startListeningForAdvertisements without error
,2016-03-30 22:22:36.174 ThaliTest[2518:4627380] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:36.175 ThaliTest[2518:4627536] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:36.176 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:22:36.176 ThaliTest[2518:4627536] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:37.429 ThaliTest[2518:4627380] client: found new peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:22:37.535 ThaliTest[2518:4628308] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:37.536 ThaliTest[2518:4628308] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:37.537 ThaliTest[2518:4628308] client session: disconnect
2016-03-30 22:22:37.537 ThaliTest[2518:4628308] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:37.537 ThaliTest[2518:4628308] client session: fireConnectCallb,ack: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:37.537 ThaliTest[2518:4628308] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-30 22:22:40.546 ThaliTest[2518:4627536] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:40.546 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:22:40.546 ThaliTest[2518:4627536] client session: stateChange:0->,1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:40.885 ThaliTest[2518:4628308] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:40.885 ThaliTest[2518:4628308] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:40.885 ThaliTest[2518:4628308] client session: disconnect
,2016-03-30 22:22:40.885 ThaliTest[2518:4628308] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:40.887 ThaliTest[2518:4628308] client session: fireConnectCallback: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 2,2:22:40.887 ThaliTest[2518:4628308] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-30 22:22:43.891 ThaliTest[2518:4627536] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:43.891 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:22:43.891 ThaliTest[2518:4627536] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:44.062 ThaliTest[2518:4628309] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:44.062 ThaliTest[2518:4628309] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:44.062 ThaliTest[2518:4628309] client session: disconnect
,2016-03-30 22:22:44.062 ThaliTest[2518:4628309] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:44.064 ThaliTest[2518:4628309] client session: fireConnectCallback: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
,2016-03-30 22:22:44.064 ThaliTest[2518:4628309] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-30 22:22:47.077 ThaliTest[2518:4627536] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:47.078 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:22:47.078 ThaliTest[2518:4627536] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:47.288 ThaliTest[2518:4628309] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:47.288 ThaliTest[2518:4628309] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:47.289 ThaliTest[2518:4628309] client session: disconnect
,2016-03-30 22:22:47.289 ThaliTest[2518:4628309] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:47.290 ThaliTest[2518:4628309] client session: fireConnectCallback: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:47.290 ThaliTest[2518:4628309] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-30 22:22:50.298 ThaliTest[2518:4627536] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:50.299 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:22:50.299 ThaliTest[2518:4627536] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:50.436 ThaliTest[2518:4628319] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:50.436 ThaliTest[2518:4628319] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:50.4,36 ThaliTest[2518:4628319] client session: disconnect
2016-03-30 22:22:50.436 ThaliTest[2518:4628319] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:50.438 ThaliTest[2518:4628319] client session: fireConnectCallback: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:50.438 ThaliTest[2518:4628319] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-30 22:22:53.446 ThaliTest[2518:4627536] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:53.446 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:22:53.446 ThaliTest[2518:4627536] client session: stateChange:0->1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:53.545 ThaliTest[2518:4628308] client session: not connected 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:53.547 ThaliTest[2518:4628308] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
,2016-03-30 22:22:53.548 ThaliTest[2518:4628308] client session: disconnect
2016-03-30 22:22:53.548 ThaliTest[2518:4628308] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:53.549 ThaliTest[2518:4628308] client session: fireConnectCallback: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:53.549 ThaliTest[2518:4628308] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-30 22:22:55.332 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:22:56.553 ThaliTest[2518:4627536] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:56.554 ThaliTest[2518:4627536] client session: connect
2016-03-30 22:22:56.554 ThaliTest[2518:4627536] client session: stateChange:0->,1 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:56.560 ThaliTest[2518:4627380] client: lost peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
,2016-03-30 22:22:56.560 ThaliTest[2518:4627380] client session: onPeerLost: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:56.560 ThaliTest[2518:4627380] client session: onLinkFailure: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:56.560 T,haliTest[2518:4627380] client session: disconnect
2016-03-30 22:22:56.560 ThaliTest[2518:4627380] client session: stateChange:1->0 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
,2016-03-30 22:22:56.561 ThaliTest[2518:4627380] client session: fireConnectCallback: 10864D2D-6C65-445D-AFFE-A77AB0B7C823
,2016-03-30 22:22:56.561 ThaliTest[2518:4627380] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-30 22:22:59.568 ThaliTest[2518:4627536] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:22:59.568 ThaliTest[2518:4627536] client: connect: unreachable 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:22:59.568 ThaliTest[251,8:4627536] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-30 22:23:02.576 ThaliTest[2518:4627536] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:23:02.576 ThaliTest[2518:4627536] client: connect: unreachable 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:23:02.576 ThaliTest[2518:4627536] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-30 22:23:05.588 ThaliTest[2518:4627536] jxcore: connect 10864D2D-6C65-445D-AFFE-A77AB0B7C823:8
2016-03-30 22:23:05.588 ThaliTest[2518:4627536] client: connect: unreachable 10864D2D-6C65-445D-AFFE-A77AB0B7C823
2016-03-30 22:23:05.589 ThaliTest[2518:4627536] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
WARN testThaliMobileNative: Too many connect retries!
,not ok 170 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-30 22:23:15.332 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:23:15.341 ThaliTest[2518:4627380] client: found updated peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:23:15.341 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:23:35.332 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:23:35.340 ThaliTest[2518:4627380] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:23:35.341 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:23:55.332 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:23:55.341 ThaliTest[2518:4627380] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:23:55.341 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:24:15.332 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:24:15.343 ThaliTest[2518:4627380] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:24:15.343 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
,2016-03-30 22:24:35.332 ThaliTest[2518:4627380] multipeer manager: restart client
,2016-03-30 22:24:35.340 ThaliTest[2518:4627380] client: found existing peer: 0D4FB91C-5072-4219-BFC9-CC10DE895F2C:7
2016-03-30 22:24:35.340 ThaliTest[2518:4627380] client: found existing peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:24:55.168 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-30 22:24:55.169 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,ok 171 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-30 22:24:55.170 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
,2016-03-30 22:24:55.170 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:24:55.171 ThaliTest[2518:4627536] multipeer manager: stop client timer
2016-03-30 22:24:55.171 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: su,ccess
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-30 22:24:57.370 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:24:57.370 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:24:57.371 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:24:57.372 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 173 specific error should be returned
,# teardown
,ok 174 must be stopped
,# setup
,2016-03-30 22:25:04.446 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-30 22:25:04.446 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:04.446 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:25:04.447 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 175 specific error should be returned
,# teardown
,ok 176 must be stopped
,# setup
,2016-03-30 22:25:24.791 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:24.791 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:24.791 ThaliTest[2518:4,627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:25:24.792 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56097
,2016-03-30 22:25:25.311 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:25.312 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,ok 177 no errors
,2016-03-30 22:25:25.313 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:25:25.314 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
ok 178 still no errors
,# teardown
,2016-03-30 22:25:25.658 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:25.658 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:25:25.658 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:25:25.659 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:25.659 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,ok 179 must be stopped
,# setup
,2016-03-30 22:25:25.863 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:25.863 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:25.864 ThaliTest[2518:4,627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:25:25.865 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56099
,2016-03-30 22:25:26.340 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
2016-03-30 22:25:26.341 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:25:26.341 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
ok 180 no errors
,2016-03-30 22:25:26.342 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:25:26.344 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
,ok 181 still no errors
,# teardown
,2016-03-30 22:25:26.348 ThaliTest[2518:4627380] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,2016-03-30 22:25:26.579 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:26.580 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:25:26.580 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:25:26.580 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
2016-03-30 22:25:26.580 ThaliTest[2518:4627536] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:25:26.581 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,ok 182 must be stopped
,# setup
,2016-03-30 22:25:27.066 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:27.066 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:27.066 ThaliTest[2518:4,627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:25:27.068 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56102
,2016-03-30 22:25:27.956 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:25:27.956 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:10
2016-03-30 22:25:27.957 ThaliTest[2518:4627536] multipeer ,manager: start client restart timer: 0x165c2260
2016-03-30 22:25:27.957 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:10
2016-03-30 22:25:27.957 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 183 no errors
2016-03-30 22:25:27.958 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
,2016-03-30 22:25:27.958 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:25:27.959 ThaliTest[2518:4627536] multipeer manager: stop client timer
2016-03-30 22:25:27.959 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C,7-5683F62667F5:11
2016-03-30 22:25:27.959 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
2016-03-30 22:25:27.960 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:11
2016-03-30 22:25:27.960 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening: success
ok 184 still no errors
# teardown
,2016-03-30 22:25:28.625 ThaliTest[2518:4627380] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,2016-03-30 22:25:28.833 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:28.833 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:25:28.833 ThaliTest[2518:4627536] multipeer manager: stop client timer
2016-03-30 22:25:28.834 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
2016-03-30 22:25:28.834 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:28.835 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,ok 185 must be stopped
# setup
,2016-03-30 22:25:29.498 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:29.498 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:29.499 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:25:29.500 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56106
,2016-03-30 22:25:30.469 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:30.468 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:30.468 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:25:30.468 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
ok 186 no errors
,2016-03-30 22:25:30.470 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:25:30.470 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
ok 187 still no errors
,# teardown
,2016-03-30 22:25:30.681 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:25:30.681 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:25:30.681 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:25:30.681 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-30 22:25:30.682 ThaliTest[2518,:4627536] jxcore: stopListeningForAdvertisements: success
,ok 188 must be stopped
,# setup
,2016-03-30 22:25:31.645 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:25:31.645 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:25:31.646 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:25:31.647 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 48. can get the network status before starting
,ok 189 network status should have certain non-empty properties
,# teardown
,ok 190 must be stopped
,# setup
,2016-03-30 22:26:02.019 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:02.019 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:02.019 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:02.021 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 49. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 191 specific error expected
,# teardown
,ok 192 must be stopped
,# setup
,2016-03-30 22:26:08.305 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:08.306 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:08.306 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:08.307 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 50. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56108
,2016-03-30 22:26:08.592 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
2016-03-30 22:26:08.592 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-30 22:26:08.593 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success
2016-03-30 22:26:08.595 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening
2016-03-30 22:26:08.595 ThaliTest[2518:4627536] server: starting A3E18F7B-F512-41AB-86C7-5683F62667F5:12
,2016-03-30 22:26:08.595 ThaliTest[2518:4627536] THEMultipeerManager initialized peer A3E18F7B-F512-41AB-86C7-5683F62667F5:12
2016-03-30 22:26:08.595 ThaliTest[2518:4627536] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-30 22:26:08.602 ThaliTest[2518:4627380] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 193 connection to servers manager should succeed after starting
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,ok 194 connection to router server should succeed after starting
,2016-03-30 22:26:08.630 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:26:08.631 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:26:08.631 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:26:08.631 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
2016-03-30 22:26:08.632 ThaliTest[2518:4627536] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:26:08.634 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 195 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 196 connection to servers manager should fail after stopping
,ok 197 connection to router server should fail after stopping
,# teardown
,ok 198 must be stopped
,# setup
,2016-03-30 22:26:09.708 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:09.709 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:09.709 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-30 22:26:09.710 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure terminateConnection is properly hooked up
,ok 199 called with right arguments
,# teardown
,ok 200 must be stopped
,# setup
,2016-03-30 22:26:14.904 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:14.904 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:14.905 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:14.906 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. make sure terminateListener is properly hooked up
,ok 201 called with right arguments
,# teardown
,ok 202 must be stopped
,# setup
,2016-03-30 22:26:24.970 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:24.970 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:24.970 ThaliTest[2518:4,627536] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:24.972 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 53. make sure we actually call kill connections properly
,2016-03-30 22:26:25.116 ThaliTest[2518:4627536] jxcore: killConnections
2016-03-30 22:26:25.117 ThaliTest[2518:4627536] jxcore: killConnections: badParam
,not ok 203 should not fail on iOS
  ---
,    operator: fail
,  ...
,# teardown
,ok 204 must be stopped
,# setup
,2016-03-30 22:26:25.403 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:25.404 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:25.404 ThaliTest[2518:4,627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:25.405 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56116
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":56115,"error":{}}
,2016-03-30 22:26:25.534 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
2016-03-30 22:26:25.535 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
2016-03-30 22:26:25.535 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-30 22:26:25.535 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:26:25.537 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,ok 205 failure reason is as expected
,ok 206 error description is as expected
,ok 207 must be stopped
,# teardown
,ok 208 must be stopped
,# setup
,2016-03-30 22:26:25.801 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-30 22:26:25.802 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-30 22:26:25.803 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:25.804 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 55. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56118
,ok 209 peerIdentifier matches
ok 210 error description matches
,# teardown
,2016-03-30 22:26:26.211 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening
,2016-03-30 22:26:26.211 ThaliTest[2518:4627536] THEMultipeerManager stopping peer
,2016-03-30 22:26:26.212 ThaliTest[2518:4627536] jxcore: stopAdvertisingAndListening: success
,2016-03-30 22:26:26.213 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-30 22:26:26.214 ThaliTest[2518:4627536] jxcore: stopListeningForAdvertisements: success
,ok 211 must be stopped
,# setup
,2016-03-30 22:26:26.437 ThaliTest[2518:4627536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-30 22:26:26.438 ThaliTest[2518:4627536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-30 22:26:26.438 ThaliTest[2518:4627536] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-30 22:26:26.439 ThaliTest[2518:4627536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 56. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56120
,2016-03-30 22:26:26.755 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements
2016-03-30 22:26:26.756 ThaliTest[2518:4627536] multipeer manager: start client restart timer: 0x165c2260
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,ok 212 discoveryActive matches
,ok 213 advertisingActive matches
,2016-03-30 22:26:26.762 ThaliTest[2518:4627380] client: found new peer: 10864D2D-6C65-445D-AFFE-A77AB0B7C823:9
2016-03-30 22:26:26.762 ThaliTest[2518:4627536] jxcore: startListeningForAdvertisements: success

```
